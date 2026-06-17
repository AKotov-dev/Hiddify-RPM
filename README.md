# Hiddify-RPM
RPM package of [Hiddify Client](https://github.com/hiddify/hiddify-app), repackaged from the original [Debian package](https://github.com/hiddify/hiddify-app/releases/tag/v4.1.1).
![](https://github.com/AKotov-dev/Hiddify-RPM/blob/main/Screenshot1.png)

### Build Motivation
RPM package is missing, AppImage does not start with error:
```
./Hiddify-Linux-x64-AppImage.AppImage
./hiddify: usr/lib/libcrypto.so.3: version `OPENSSL_3.2.0' not found (required by /lib64/libcryptsetup.so.12)
```
Build and scripts adaptation were carried out using [RPMCreator-v2.9](https://github.com/AKotov-dev/RPMCreator), the project is [here](https://github.com/AKotov-dev/Hiddify-RPM/blob/main/hiddify.prj).
