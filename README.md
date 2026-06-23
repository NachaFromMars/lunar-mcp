# lunar-mcp — Chinese lunar calendar + BaZi MCP server

> An MCP server for lunar calendar operations and BaZi calculations. Solar↔lunar conversion, auspicious day guidance, 24 Solar Terms, Five Elements analysis — all accessible to any MCP-compatible agent.

[![OpenClaw Skill](https://img.shields.io/badge/OpenClaw-Skill-blueviolet)](https://github.com/NachaFromMars)

## Overview
lunar-mcp is a Model Context Protocol server that exposes Chinese lunar calendar and BaZi (Four Pillars) tools to AI agents. It handles solar-to-lunar and lunar-to-solar date conversion, generates Huang Li (auspicious day) guidance, calculates BaZi charts, tracks the 24 Solar Terms (節氣), and analyzes Five Elements composition. Based on [AlbertHuangKSFO/lunar_mcp_server](https://github.com/AlbertHuangKSFO/lunar_mcp_server) (MIT).

## Features
- **BaZi calculation** — Four Pillars from birth date
- **Date conversion** — solar ↔ lunar calendar
- **Huang Li** — auspicious and inauspicious day guidance
- **Daily fortune** — daily luck overview
- **24 Solar Terms** — 節氣 tracking
- **Five Elements** — Ngũ Hành composition analysis
- **MCP protocol** — works with any MCP-compatible agent

## Usage / Quick Start
```bash
pip install lunar-python
# then connect via MCP protocol
```

## Trigger Keywords (OpenClaw)
lịch âm, âm lịch, lunar calendar, hoàng lịch, tiết khí, solar terms, ngũ hành, five elements, bazi calculation, 农历, 黄历

## Related Skills
- [destiny-engine](https://github.com/NachaFromMars/destiny-engine) — full BaZi + Western astrology analysis

---
Part of the [NachaFromMars](https://github.com/NachaFromMars) OpenClaw skill ecosystem.
