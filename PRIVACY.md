# Privacy / sanitization

This repository is intended to be publishable without personal data.

## What is included

- Anonymized field measurements (compressor starts, outdoor temperature means, electric energy estimates)
- Generic Home Assistant YAML examples with placeholder entity IDs
- SVG charts derived from the sanitized CSVs

## What must not be committed

- Real names, street addresses, GPS, or site photos that identify a building
- Home Assistant tokens, EMS-ESP passwords, Wi‑Fi credentials, UniFi / FritzBox details
- Production `secrets.yaml`, `.storage` dumps, or full entity registries
- Hostnames / public IPs of the home network
- Unredacted dashboard screenshots that show personal room names tied to an address

## Entity naming in examples

Examples use neutral names (`living_room`, `thermostat_hc1_offsettemp`, …). Adapt them locally; do not replace examples with your production dump when contributing.

## Data provenance

Daily aggregates in `data/` come from a single residential Bosch heat-pump installation in Central Europe (Nov 2026). Exact location is omitted on purpose.
