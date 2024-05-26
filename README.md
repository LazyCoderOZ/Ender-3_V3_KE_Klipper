Welcome to the Creality Ender-3_V3_KE Klipper project!

This is clone from https://github.com/Klipper3d/klipper/

[![Klipper](docs/img/klipper-logo-small.png)](https://www.klipper3d.org/)

https://www.klipper3d.org/

Used on Creality Ender-3_V3_KE devices

We are https://github.com/Klipper3d/klipper/ Updated relevant functions on the basis

This fork is to add in the source files necessary to compile Klipper on a Raspberry Pi to use instead of the Nebula Pad.
Use Kiauh to install Klipper (https://github.com/dw-0/kiauh.git), then compile the printer firmware using the make menuconfig etc...
You need to downgrade to
http://http.us.debian.org/debian/pool/main/g/gcc-arm-none-eabi/gcc-arm-none-eabi_8-2019-q3-1+b1_arm64.deb
to get Klipper bin file to compile.