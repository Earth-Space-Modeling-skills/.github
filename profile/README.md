# Earth-Space-Modeling-skills

Curated skill packages for Earth and space system models. Each repo is a self-contained, progressive-disclosure knowledge package: a `SKILL.md` routing hub plus `reference/` deep-dive docs covering install, compile, run, modify, debug, and contribute.

These repos are designed to be loaded as skills by AI coding agents (Claude Code, Codex, Cursor, etc.) and to serve as durable, human-readable references for researchers and developers.

**Status legend:** ✅ deep-dive complete. 🟡 scaffold (v0.1.0-scaffold), routing and source-grounded surface verified, operational depth being filled in.

## Models

### Earth-system / coupled
- ✅ [cam-skill](https://github.com/Earth-Space-Modeling-skills/cam-skill), Community Atmosphere Model (CAM)
- 🟡 [cesm-skill](https://github.com/Earth-Space-Modeling-skills/cesm-skill), Community Earth System Model (CESM) superproject
- ✅ [e3sm-skill](https://github.com/Earth-Space-Modeling-skills/e3sm-skill), Energy Exascale Earth System Model (E3SM)
- 🟡 [noresm-skill](https://github.com/Earth-Space-Modeling-skills/noresm-skill), Norwegian Earth System Model (NorESM)
- 🟡 [fms-skill](https://github.com/Earth-Space-Modeling-skills/fms-skill), GFDL Flexible Modeling System (FMS) framework

### Atmosphere
- ✅ [wrf-skill](https://github.com/Earth-Space-Modeling-skills/wrf-skill), Weather Research and Forecasting (WRF)
- 🟡 [waccm-skill](https://github.com/Earth-Space-Modeling-skills/waccm-skill), Whole Atmosphere Community Climate Model (WACCM)
- 🟡 [waccmx-skill](https://github.com/Earth-Space-Modeling-skills/waccmx-skill), extended WACCM (ionosphere/thermosphere)
- 🟡 [gfdl-fv3-skill](https://github.com/Earth-Space-Modeling-skills/gfdl-fv3-skill), GFDL FV3 cubed-sphere dynamical core
- 🟡 [openifs-skill](https://github.com/Earth-Space-Modeling-skills/openifs-skill), ECMWF OpenIFS (research/education)
- 🟡 [regcm-skill](https://github.com/Earth-Space-Modeling-skills/regcm-skill), ICTP Regional Climate Model
- 🟡 [geos-chem-skill](https://github.com/Earth-Space-Modeling-skills/geos-chem-skill), GEOS-Chem atmospheric chemistry

### Land surface and hydrology
- ✅ [noahmp-skill](https://github.com/Earth-Space-Modeling-skills/noahmp-skill), Noah-MP land surface model and HRLDAS
- ✅ [ctsm-skill](https://github.com/Earth-Space-Modeling-skills/ctsm-skill), Community Terrestrial Systems Model (CTSM/CLM)
- ✅ [jules-skill](https://github.com/Earth-Space-Modeling-skills/jules-skill), Joint UK Land Environment Simulator (JULES)
- ✅ [summa-skill](https://github.com/Earth-Space-Modeling-skills/summa-skill), Structure for Unifying Multiple Modeling Alternatives (SUMMA)
- ✅ [vic-skill](https://github.com/Earth-Space-Modeling-skills/vic-skill), Variable Infiltration Capacity (VIC) macroscale hydrologic model
- ✅ [parflow-skill](https://github.com/Earth-Space-Modeling-skills/parflow-skill), ParFlow parallel watershed flow model

### Ocean
- ✅ [mom6-skill](https://github.com/Earth-Space-Modeling-skills/mom6-skill), Modular Ocean Model 6 (MOM6)
- 🟡 [mitgcm-skill](https://github.com/Earth-Space-Modeling-skills/mitgcm-skill), MIT General Circulation Model (MITgcm)
- 🟡 [fesom2-skill](https://github.com/Earth-Space-Modeling-skills/fesom2-skill), FESOM2 unstructured-mesh ocean
- 🟡 [roms-skill](https://github.com/Earth-Space-Modeling-skills/roms-skill), Regional Ocean Modeling System (ROMS)

### Sea ice
- 🟡 [cice-skill](https://github.com/Earth-Space-Modeling-skills/cice-skill), CICE Consortium sea-ice model

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
