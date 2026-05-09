# Earth-Space-Modeling-skills

Curated skill packages for Earth and space system models. Each repo is a self-contained, progressive-disclosure knowledge package: a `SKILL.md` routing hub plus `reference/` deep-dive docs covering install, compile, run, modify, debug, and contribute.

These repos are designed to be loaded as skills by AI coding agents (Claude Code, Codex, Cursor, etc.) and to serve as durable, human-readable references for researchers and developers.

## Models

### Atmosphere
- [cam-skill](https://github.com/Earth-Space-Modeling-skills/cam-skill) — Community Atmosphere Model (CAM)
- [wrf-skill](https://github.com/Earth-Space-Modeling-skills/wrf-skill) — Weather Research and Forecasting (WRF), including ARW, WRF-Chem, WPS, WRF-Hydro

### Land surface and hydrology
- [noahmp-skill](https://github.com/Earth-Space-Modeling-skills/noahmp-skill) — Noah-MP land surface model and HRLDAS offline driver
- [ctsm-skill](https://github.com/Earth-Space-Modeling-skills/ctsm-skill) — Community Terrestrial Systems Model (CTSM/CLM), with LILAC coupling
- [jules-skill](https://github.com/Earth-Space-Modeling-skills/jules-skill) — Joint UK Land Environment Simulator (JULES), Rose suite execution
- [summa-skill](https://github.com/Earth-Space-Modeling-skills/summa-skill) — Structure for Unifying Multiple Modeling Alternatives (SUMMA)
- [vic-skill](https://github.com/Earth-Space-Modeling-skills/vic-skill) — Variable Infiltration Capacity (VIC) macroscale hydrologic model
- [parflow-skill](https://github.com/Earth-Space-Modeling-skills/parflow-skill) — ParFlow parallel watershed flow model, with CLM coupling and GPU notes

### Ocean
- [mom6-skill](https://github.com/Earth-Space-Modeling-skills/mom6-skill) — Modular Ocean Model 6 (MOM6)

### Earth system
- [e3sm-skill](https://github.com/Earth-Space-Modeling-skills/e3sm-skill) — Energy Exascale Earth System Model (E3SM), EAM atmosphere and MPAS ocean/sea ice

## Layout of a skill repo

```
<model>-skill/
├── SKILL.md              # Routing hub: when to use, where to look
├── reference/            # Deep-dive docs by topic
│   ├── architecture.md
│   ├── physics.md
│   ├── workflow.md
│   ├── debugging.md
│   └── ...
└── README.md
```

## Contributing

Contributions are welcome. Open an issue or PR on the relevant repo. For new model coverage that fits the scope (Earth, ocean, atmosphere, land, ice, space weather, planetary), open an issue to discuss before starting a new repo.

## License

Each repo carries its own license file. See the individual repo for details.
