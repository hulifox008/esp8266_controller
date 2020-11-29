# esp8266_controller

Checkout this repository **recursively**.

## Build xtensa-lx106 toolchain
```
cd crosstool-NG
./bootstrap
./configure --enable-local
make
./ct-ng xtensa-lx106-elf
./ct-ng build
```

The toolchain is generated in crosstool-NG/builds/xtensa-lx106-elf directory. Add it to the PATH environment variable.
