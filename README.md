# nrf52-fixed-passkey-bonding-with-display

Device with Display to do the fixed Passkey Bonding (MITM)

This example is to show the device with display (IO capacitivity) and have the fixed 6 digits passkey (MITM - Man In The MIddle).  During the bonding with phone, the phone needs to entry such known sequence digits.

## Requirement

* nRF52810 DK / nRF52840 DK
* Nordic SDK 15.3
* Softdevice S112v6.1 or S140v6.1.1
* Segger Embedded Studio 4.12 or later

This example can easily port to any other nRF52 series chipset.  The folder can be placed inside the SDK15.3\examples.
