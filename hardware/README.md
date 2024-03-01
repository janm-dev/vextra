# Vextra Device Hardware

Vextra hardware, including the device's schematic, PCB layout, and additional external hardware.

## Main Device Components

- MCU - ESP32-C6-WROOM-1(U)
- GNSS receiver - ST Teseo-VIC3DA or other pin-compatible modules (e.g. u-blox NEO series)
- Mobile transceiver - Waveshare SimCom SIM7600 module
- Battery - Li-Ion / Li-Po
- Battery Charger - TP4054
- Power supply - TPS54260 and HE9073
- Antennas - 2 x L1 or L1/L5 GNSS, 2 x 4G/3G/2G cellular, 1 x 2.4 GHz WiFi/BLE

## Device PCB

The PCB is split into three sections with slots between them: the power supply on the left, the MCU/GNSS section in the middle, and the cellular section on the right.

These sections are designed to be reusable for other purposes, e.g. the power supply section can act as a USB power supply or Li-Ion/Li-Po battery charger when removed from the rest of the board.
As such, not all components need to be installed for full operation for a specific purpose, e.g. the LEDs when low power consumption is needed or Q5 and Q6 when the USB port is not used as a power source for other USB devices.

## Additional Hardware

A case with mounting hardware for the Vextra Device is available as STEP files in `case` or [on Onshape](https://cad.onshape.com/documents/913efcab07442fbc03a0e56f/).

## Licenses

The schematic(s) and PCB(s) (KiCad files in this directory) are licensed under the CERN Open Hardware Licence - Strongly Reciprocal Version 2 or later ([`CERN-OHL-S-2.0+`](https://ohwr.org/cern_ohl_s_v2.txt)).

Additional external hardware (STEP files and associated documentation in subdirectories of this directory; e.g. the device's case and mounting hardware) are made available under the confusing and *iiuc* self-contradictory Onshape Free license (<https://www.onshape.com/en/legal/terms-of-use>, quoted below).
Commercial use might be - but probably isn't - allowed; use at your own risk and ask a lawyer.

> Onshape Free is a fully featured CAD and PDM platform perfect for **open-source** projects, makers, hobbyists and those learning to use modern CAD. This no-cost plan is meant for creating **non-commercial** product designs that are **open-source** publicly online.

*From <https://www.onshape.com/en/products/free> with added emphasis*

> \[...\] Customer grants a worldwide, royaltyfree and non-exclusive license to any End User or third party accessing the Public Document to use the intellectual property contained in Customer's Public Document without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Document, and to permit persons to whom the Document is made available to do the same.
> \[...\]
> Free versions of the Service are intended to support (a) creating and editing intellectual property for non-commercial purposes \[...\]

*From <https://www.onshape.com/en/legal/terms-of-use>*
