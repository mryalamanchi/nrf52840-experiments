# Work in progress IEEE 802.15.4 for nRF52840

This is some experiments with using the nRF52840 radio in 802.14.5 mode. The
examples in this repository assumes that one of the nRF52840-DK or
nRF52840-MDK boards is used.
The host program has only been tested with Fedora 29 Linux.

The code is split into following parts.

## Parts

### nRF52840 crypto cell

`nrf52-cryptocell` is a crate for using the nRF52480 crypto cell for AES
crypto.

### nRF52840 utils

`nrf52-utils` is a small logging crate.

### Target

The target examples are found in the `nrf52840-dk` and `nrf52840-mdk`
directories.

### Host

The host tool, psila-host, is found in the psila repository.

## Usage

 1. Start the host application listening to the nrf52840 USB-to-serial device
 2. Start the target application on the nRF52840

## License

Licensed under the MIT license. See LICENSE.
