The source codes of S5P6818 drivers are all copied from https://github.com/rafaello7/linux-nanopi-m3.It is able to run but has bugs.  
In development.

### compilation

    make ARCH=arm64 nanopim3_defconfig
    make ARCH=arm64 CROSS_COMPILE=aarch64-linux-gnu- Image dtbs

