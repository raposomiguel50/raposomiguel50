# Miguel Raposo

## Miguel's Game Dev Lab

**Learning hardware through ports. Building native games from what I learn.**

I use practical game ports to study hardware, operating-system boundaries, rendering, input, audio, performance and release engineering. The results are documented publicly so each project can support both practical use and further technical learning.

The lab favours preservation, containment, focus, restoration and minimal intervention. Changes are selected according to project purpose, target-platform constraints and evidence.

[Open Miguel's Game Dev Lab](https://raposomiguel50.github.io/)  
[Development method and AI assistance](https://raposomiguel50.github.io/method/)  
[ModDB developer profile](https://www.moddb.com/company/miguels-game-dev-lab)

## Development method

The lab is human-directed and AI-assisted. I define the project goals, design, process, constraints, target hardware, acceptance criteria and final approval. ChatGPT provides substantial assistance with calculations, programming, automation, analysis, documentation and repetitive technical work.

I use explicit checkpoints, versioned handovers, hashes, clean-clone validation and real-hardware QA to preserve continuity and keep conclusions tied to evidence.

[Read the full development method](https://raposomiguel50.github.io/method/)

## Current projects

### System Shock - Android

An unofficial native Android/ARM64 adaptation based on [Shockolate](https://github.com/Interrupt/systemshock), developed with the Retroid Pocket 5 as the primary reference device.

The project includes handheld-focused controls, Android text input, audio integration, a preserved 4:3 no-stretch presentation, reproducible build documentation and an open engineering knowledge base. The Android IME keyboard shown during text entry is the only platform-specific visual addition to the original game presentation.

- [Project page](https://raposomiguel50.github.io/projects/system-shock-android/)
- [Public source](https://github.com/raposomiguel50/system-shock-android)
- [Build and reproduction guide](https://raposomiguel50.github.io/projects/system-shock-android/reproduce/)
- [Engineering knowledge base](https://raposomiguel50.github.io/projects/system-shock-android/knowledge/)
- [Development method](https://github.com/raposomiguel50/system-shock-android/blob/main/docs/DEVELOPMENT_METHOD.md)
- [Releases](https://github.com/raposomiguel50/system-shock-android/releases)
- [Feedback and testing](https://github.com/raposomiguel50/system-shock-android/issues/new/choose)
- [ModDB](https://www.moddb.com/mods/system-shock-android)

### The Minish Cap - RG34XX

An unofficial H700/Linux integration based on EstebanPdN's [Project Picori-derived port](https://github.com/EstebanPdN/zelda-tmc-3ds). The recorded target is the RG34XX with muOS; historical project records use the label RG34XX-H.

The published work contains [15 historical patches and a launcher](https://github.com/raposomiguel50/minish-cap-rg34xx/tree/90fd77a82d579de9460f2de1167a95ec264e57c3). Specific changes address AArch64 build/link configuration, menu hints, quit handling, conditional audio resampling and presentation scheduling. [Archived records](https://github.com/raposomiguel50/minish-cap-rg34xx/tree/e0f8c056bb94e8112a4b142b6addce78c9deb53b/docs/evidence/2026-09-07) document menu/exit checks, two timing captures and a later operator-accepted session.

Restoration and curation are the approved decision framework, not a claim that original GBA gameplay bugs have been corrected. The [technical report and supplement](https://github.com/raposomiguel50/minish-cap-rg34xx/blob/main/docs/TECHNICAL_REPORT.md) distinguish source changes, measurements and unresolved diagnostics. Measured energy savings and complete build reproducibility are not established. No ROM, extracted Nintendo assets or public V1 executable is included.

- [Project page](https://raposomiguel50.github.io/projects/minish-cap-rg34xx/)
- [Engineering knowledge](https://raposomiguel50.github.io/projects/minish-cap-rg34xx/knowledge/)
- [Reconstruction and reproducibility](https://raposomiguel50.github.io/projects/minish-cap-rg34xx/reproduce/)
- [Public source](https://github.com/raposomiguel50/minish-cap-rg34xx)
- [Project philosophy](https://github.com/raposomiguel50/minish-cap-rg34xx/blob/main/docs/PHILOSOPHY.md)
- [Patch history](https://github.com/raposomiguel50/minish-cap-rg34xx/blob/main/docs/PATCH_SERIES.md)
- [Validation](https://github.com/raposomiguel50/minish-cap-rg34xx/blob/main/docs/VALIDATION.md)
- [Pinned source foundation](https://github.com/EstebanPdN/zelda-tmc-3ds/tree/e72663ca4059dabf9dbf7f03c36fc791d90b8db5)
- [PortMaster status](https://github.com/raposomiguel50/minish-cap-rg34xx/blob/main/docs/PORTMASTER_STATUS.md)

## Development focus

- Native game ports and platform-specific development
- Preservation-led, incremental integration work
- Retro hardware and constrained systems
- Android/ARM64 and handheld gaming devices
- Rendering, controls, audio and platform integration
- Reproducible builds and evidence-based validation
- Open technical documentation and reusable engineering knowledge
- Human-directed, AI-assisted development with explicit attribution
- Applying porting knowledge to original native games

## Contact

- [Miguel's Game Dev Lab](https://raposomiguel50.github.io/)
- [Development method](https://raposomiguel50.github.io/method/)
- [ModDB developer profile](https://www.moddb.com/company/miguels-game-dev-lab)
- [LinkedIn](https://www.linkedin.com/in/miguel-raposo-7192a251/)
