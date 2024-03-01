# Vextra - Vehicle Extras

Vextra is an extensible system of vehicle (car, bicycle, motorbike, etc.) extras, including position tracking, smart accessories, and more.

## Repository Structure

- `api` - Vextra data access / API server
- `db` - Vextra database interface (support for Timescale DB and a debugging/testing stub)
- `firmware` - Vextra Device firmware (for ESP32-C6)
- `hardware` - Vextra Device schematic, PCB, and additional hardware design
- `ingest` - Vextra data ingest server (over UDP and HTTPS)
- `proto` - Vextra protocols
- `web` - Vextra website front-end

## Licenses

Vextra software (`api`, `db`, `firmware`, `ingest`, `proto`, and `web`) is licensed under the GNU AGPL v3 or later ([`AGPL-3.0-or-later`](https://spdx.org/licenses/AGPL-3.0-or-later.html)).
You can find the full license text in the `LICENSE-AGPL` file.

Vextra hardware (`hardware`) is **partially** licensed under the CERN Open Hardware Licence - Strongly Reciprocal Version 2 or later ([`CERN-OHL-S-2.0+`](https://ohwr.org/cern_ohl_s_v2.txt)).
See `hardware/README.md` for details, and the `LICENSE-OHL` file for the full text of the CERN OHL.
