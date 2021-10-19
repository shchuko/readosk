# readosk - an utility to retrieve OSK key requred for QEMU-AppleSMC

Build & install:

```bash
./configure
make
make install
```

Usage:

```bash
qemu-system-x86_64 -device "isa-applesmc,osk=$(readosk)"
```
