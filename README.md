# Red Panda C++ Generic Linux Packages

Download: [releases page](https://github.com/cyano-linux/redpanda-cpp/releases).

## Available Editions

* AppImage
  * x86-64 and AArch64.
    * x86-64 is built on CentOS 7, and should work on glibc-based Linux distributions since 2014.
    * AArch64 is built on Ubuntu 18.04, and should work on glibc-based Linux distributions since 2018.
  * [Alacritty](https://github.com/alacritty/alacritty) 0.11.0 bundled. Red Panda IDE will search [preferred system terminals](https://github.com/royqh1979/RedPanda-CPP/blob/2.18/RedPandaIDE/settings.cpp#L3377) and then fallback to Alacritty.
  * The configuration path depends on the filename of the AppImage file, so DO NOT rename it.
  * How to build: [upstream build instruction](https://github.com/royqh1979/RedPanda-CPP/blob/master/BUILD.md).
