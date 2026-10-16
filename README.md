# Enterprise Campus Network Design

> A complete network for three floors of BINUS Kampus Anggrek.

## Overview

- Computer Networks project by a 6-person team.
- Covers zones such as a library, admissions office, food-court tenants and support offices.

## Data / Scope

- Scope: 3 campus floors, with a 67-page proposal and a working simulation.

## Workflow

- Used VLSM to give each room or department the right-sized address range.
- Used VLANs to isolate areas like Admissions and Library on shared switches.
- Chose MikroTik and UniFi gear and mapped cabling onto the floor plans.

## Results

- 67-page proposal covering equipment, IP addressing, routing and services.
- Packet Tracer tests confirmed ping between floors and subnets.
- Web, FTP and email servers working in simulation.

## Tech Stack

VLSM, VLAN, Cisco Packet Tracer, MikroTik, UniFi

## Repository Structure

```
packet-tracer/      Cisco Packet Tracer simulation (.pkt)
docs/               67-page network design proposal (PDF)
```

## How to Run

Open `packet-tracer/Gabungan_Final_AOL_Kelompok1.pkt` with Cisco Packet Tracer (free with a Cisco NetAcad account) and read `docs/Computer_Network_Proposal.pdf` for the IP plan, VLANs and floor-by-floor design.

## Team

Computer Network course project (Group 1), 6 members.

## Notes

- Floor plans, IP plan and equipment list are inside the proposal PDF.

## Author

Nadya Angelie Lislie, BINUS University (Computer Science and Statistics). [LinkedIn](https://www.linkedin.com/in/nadya-angelie-lislie/) | [GitHub](https://github.com/Nadya-AngelieLislie)

## Continuous Integration

GitHub Actions (`.github/workflows/ci.yml`) runs `ruff` and `pytest` repository-health checks on every push; run them locally with `make lint test`.
