# Manifest for Sailfish OS for Samsung Galaxy S4 (International LTE)

This is the manifest for Sailfish OS for the Samsung Galaxy S4 (International LTE), also known as GT-i9505 and jfltexx.

## How to use
- Follow [HADK](https://sailfishos.org/develop/hadk/) chapter 5.1.
- Use `repo init -u git://github.com/mer-hybris/android.git -b hybris-11.0 --depth=10` to install Repo
- `mkdir $ANDROID_ROOT/.repo/local_manifests` and add `jflte.xml` from this repo to it
- Run `repo sync -c` from $ANDROID_ROOT to synchronize/download all repos
