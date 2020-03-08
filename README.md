# Build

Download/install a suitable toolchain e.g. gcc-arm-none-eabi-9-2019-q4-major-linux.tar.bz2 from:

https://developer.arm.com/tools-and-software/open-source-software/developer-tools/gnu-toolchain/gnu-rm/downloads

Setup env:

export ARCH=arm
export CROSS_COMPILE=/opt/gcc-arm-none-eabi-9-2019-q4-major/bin/arm-none-eabi-
export PATH=$PATH:/opt/gcc-arm-none-eabi-9-2019-q4-major/bin


./compile-scfw
