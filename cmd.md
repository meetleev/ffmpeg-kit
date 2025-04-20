### Prerequisites:
autoconf automake libtool pkg-config curl git nasm


* iOS

```bash
    ./ios.sh --lts --enable-gpl  --enable-ios-bzip2 --enable-ios-audiotoolbox --enable-ios-avfoundation --enable-ios-videotoolbox --enable-ios-zlib --enable-ios-libiconv --enable-libvidstab --enable-x264 --enable-x265 --enable-xvidcore   --xcframework --disable-arm64-mac-catalyst  --disable-x86-64-mac-catalyst
```


* Android

```bash
    ./android.sh --enable-gpl  -l --enable-android-media-codec   --enable-android-zlib --enable-libvidstab  --enable-x264  --enable-x265 --enable-xvidcore
```

* MacOS

```bash
```