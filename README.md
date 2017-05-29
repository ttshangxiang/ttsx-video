# ttsx-video

## 安装
npm install & npm start

## 运行前

Basically all you need to ship is `mpvjs.node` and mpv library. Make sure they both and also Electron/NW.js distribution have the same bitness!

### Windows

You may use [lachs0r builds](https://mpv.srsfckn.biz/mpv-dev-latest.7z). Copy `mpv-1.dll` to the directory with `mpvjs.node` and you are done.

### macOS

[Homebrew](https://brew.sh/) can compile `libmpv.1.dylib` and all its dependencies. To find dylibs that need to be packaged and fix install names you may use [collect-dylib-deps](scripts/collect-dylib-deps.sh) script.

### Linux

Two options are normally acceptable:

1. Ask your users to install `libmpv1` with package manager or simply depend on it if you build package.
2. Compile static `libmpv.so` with e.g. [mpv-build](https://github.com/mpv-player/mpv-build).

##感谢  
[mpv](https://github.com/mpv-player/mpv)  
[mpv.js](https://github.com/Kagami/mpv.js)  

