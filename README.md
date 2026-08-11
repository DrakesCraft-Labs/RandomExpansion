<p align="center"><img src="docs/banner.svg" alt="RandomExpansion banner" width="100%"></p>

# RandomExpansion

A compact collection of machines, creature resources and equipment that extends Slimefun's
mid-game without introducing a separate progression core.

## DrakesCraft edition

- Targets Java 21 and Paper/Purpur 1.21.11.
- Registers nine gameplay items against `Slimefun4-Drake`.
- Preserves original IDs and package names for world compatibility.
- Replaces retired build repositories with maintained dependencies.

## Building

```bash
mvn -B -ntp clean package
```

Deploy the artifact from `target/` alongside
[`Slimefun4-Drake`](https://github.com/DrakesCraft-Labs/Slimefun4-Drake).

## Provenance

Integrated from [SlimefunGuguProject/RandomExpansion](https://github.com/SlimefunGuguProject/RandomExpansion).
Original authorship and the MIT license are preserved.
