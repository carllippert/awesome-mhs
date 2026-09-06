# Awesome MHS [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Anthropic's Model Hardware Standard for connecting AI models to hardware.

This list curates technical implementations: specs, SDKs, drivers, harnesses, wrappers, and protocol tooling.

FastMHS is an independent directory and wrapper effort, not affiliated with Anthropic.

## Contents

- [Official](#official)
- [Directories & Discovery](#directories--discovery)
- [Packages & Wrappers](#packages--wrappers)
- [Unofficial / Inspired-by](#unofficial--inspired-by)
- [Related Ecosystems](#related-ecosystems)

## Official

- [Anthropic Model Hardware Standard](https://www.modelhardwarestandard.com/) - Apply-only as of August 2026. No public GitHub organization repositories yet (github.com/modelhardwarestandard exists with 0 public repos).

## Directories & Discovery

- [FastMHS Directory](https://gofastmhs.com/) - Independent partner/catalog directory for MHS-compatible devices and services.

## Packages & Wrappers

- [FastMHS](https://github.com/carllippert/fastmhs#readme) - Python name-holder package (`pip install fastmhs`). Wraps devices and will expose MHS+MCP+CLI when released. Updates at gofastmhs.com. **Note: Not a released SDK yet.**
- [quilt-mhs](https://github.com/SuperInstance/quilt-mhs#readme) - Community/unofficial inspired-by work. **Not affiliated with or endorsed by Anthropic.**

## Unofficial / Inspired-by

Projects exploring MHS concepts independently. **Not affiliated with or endorsed by Anthropic.**

- [tongriyaotxt/open-mhs](https://github.com/tongriyaotxt/open-mhs#readme) - Community exploration of MHS concepts.
- [SCUT-ESA/open-mhs](https://github.com/SCUT-ESA/open-mhs#readme) - Independent MHS-inspired implementation.
- [Open-MHS](https://github.com/Abenor-Labs/Open-MHS#readme) - Unofficial vendor-neutral driver spec positioned as an open alternative to Anthropic MHS.
- [mhs-demo](https://github.com/sidman76/mhs-demo#readme) - Demo agent for an MHS-style read/write pattern against simulated lab hardware over MCP.
- [OpenMHS](https://github.com/Pratyush-exe/OpenMHS#readme) - Unofficial shared spec sketch for language models to discover and operate hardware.
- [mhs-ics-skills](https://github.com/Ashigo-Research/mhs-ics-skills#readme) - Open Claude agent skills for ICS/OT (ladder logic, Modbus, OPC UA); MHS integration described as in progress.
- [hardmesh](https://github.com/huzjie/hardmesh#readme) - Unofficial MHS-inspired AI hardware control mesh / lab automation platform (device abstraction, multi-protocol drivers, calibration, safety guardrails, LLM agent control). Apache-2.0. **Not affiliated with or endorsed by Anthropic.**
- [edge-mhs](https://github.com/fastly/edge-mhs#readme) - Fastly Compute edge security gateway for MHS-over-MCP (safety limits, quotas, audit). **Not affiliated with or endorsed by Anthropic.**
- [LabBench / Open_Model_Hardware_Standard](https://github.com/Jayasuryamahadevan/Open_Model_Hardware_Standard#readme) - Unofficial LabBench capability model + safety kernel + provenance ledger for lab instruments. **Not affiliated with or endorsed by Anthropic.**

## Related Ecosystems

Adjacent projects with MHS interest or compatibility efforts:

- [Hugging Face LeRobot](https://github.com/huggingface/lerobot#readme) - Robotics framework that has announced MHS interest. No MHS implementation merged as of late August 2026.
- [Strands Labs robots](https://github.com/strands-labs/robots#readme) - Public robot drivers. MHS support was preview-gated; full in-repo implementation status pending verification.

## Contributing

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.
