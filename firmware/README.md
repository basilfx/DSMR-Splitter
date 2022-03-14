# Firmware

## Introduction
Support for DSMR is not added to RIOT-OS (yet). It lives in a separate branch
that can be found [here](https://github.com/basilfx/RIOT/tree/feature/dsmr).

To compile, navigate to the `examples/dsmr_splitter` folder, and run:

```
BOARD=dsmr_splitter make flash
```

This will compile the firmware, and flash it to the board using J-Link.

## Features
The firmware is quite extensive: it reads telegrams at a rate of 1 telegram
per second from the DSMR. It then copies the telegram to the next available
buffer of all three output ports.

This means that every output port has its own set of buffers. A buffer is
locked for reading when data is requested, but the next buffer will be written
to when a new telegram is recevied by the receiver thread.

The status LED will blink for every received telegram, but also for every
requested telegram.
