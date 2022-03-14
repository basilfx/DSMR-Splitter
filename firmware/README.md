# Firmware

## Introduction
Support for DSMR is not added to RIOT-OS (yet). It lives in a separate branch
that can be found [here](https://github.com/basilfx/RIOT/tree/feature/dsmr).

To compile, navigate to the `examples/dsmr_splitter` folder, and run:

```
BOARD=dsmr_splitter make flash
```

This will compile the firmware, and flash it to the board using J-Link.
