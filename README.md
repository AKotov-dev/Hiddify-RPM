# Hiddify-RPM
RPM package of [Hiddify Client](https://github.com/hiddify/hiddify-app), repackaged from the original [Debian package](https://github.com/hiddify/hiddify-app/releases/tag/v4.1.1).
 
+ configurations: ~/.local/share/app.hiddify.com
+ autostart mode: ~/.config/autostart/hiddify.desktop 
+ icons: ~/.local/share/icons/hicolor/{128x128,256x256}/apps/hiddify.png

**12334** - Local mixed port (SOCKS5 / HTTP)

**Modes:** Proxy, System Proxy, VPN and Protection via WARP

![](https://github.com/AKotov-dev/Hiddify-RPM/blob/main/Screenshot1.png)

## Motivation for building a package
RPM package is missing, AppImage does not start with error:
```
./Hiddify-Linux-x64-AppImage.AppImage
./hiddify: usr/lib/libcrypto.so.3: version `OPENSSL_3.2.0' not found (required by /lib64/libcryptsetup.so.12)
```
Build and scripts adaptation were carried out using [RPMCreator-v2.9](https://github.com/AKotov-dev/RPMCreator/releases/tag/v2.9), the project is [here](https://github.com/AKotov-dev/Hiddify-RPM/blob/main/hiddify.prj).
