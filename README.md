# Red Panda C++ Generic Linux Packages

Download: [releases page](https://github.com/cyano-linux/redpanda-cpp/releases).

## Available Editions

* AppImage
  * x86-64, AArch64 and RISC-V RV64GC (riscv64).
    * x86-64 is built on CentOS 7, and should work on glibc-based Linux distributions since 2014.
    * AArch64 is built on Oracle Linux 7, and should work on glibc-based Linux distributions since 2014.
    * RISC-V RV64GC is built on Ubuntu 20.04, and should work on glibc-based Linux distributions since 2020.
  * [Alacritty](https://github.com/alacritty/alacritty) 0.12.2 bundled. Red Panda IDE will search [preferred system terminals](https://github.com/royqh1979/RedPanda-CPP/blob/2.18/RedPandaIDE/settings.cpp#L3377) and then fallback to bundled Alacritty.
  * How to build: [upstream build instruction](https://github.com/royqh1979/RedPanda-CPP/blob/master/BUILD.md).
