# Awesome SNESdev [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of tools, libraries, documentation, and projects for
> Super Nintendo Entertainment System / Super Famicom homebrew development.

The SNES (Super Famicom) is a 65816-based console from 1990 with a capable PPU
and an SPC700 sound subsystem. This list collects the assemblers, C toolchains,
emulators, debuggers, graphics and audio tools, hardware references, example
projects, and communities for building real SNES software.

## Contents

- [Getting Started & References](#getting-started--references)
- [Assemblers & Toolchains](#assemblers--toolchains)
- [C & High-Level Toolchains & Libraries](#c--high-level-toolchains--libraries)
- [Emulators & Debuggers](#emulators--debuggers)
- [Graphics Tools](#graphics-tools)
- [Audio & Music Tools](#audio--music-tools)
- [Hardware Docs](#hardware-docs)
- [Example & Open-Source Games](#example--open-source-games)
- [Communities](#communities)
- [AI & ML on the SNES](#ai--ml-on-the-snes)
- [Contributing](#contributing)

## Getting Started & References

- [SNESdev Wiki](https://snes.nesdev.org/) - Community wiki covering SNES/Super Famicom hardware, registers, and development.
- [fullsnes](https://problemkaputt.de/fullsnes.htm) - nocash's exhaustive single-page SNES hardware specification (CPU, PPU, APU, DSP).
- [snesdev-notes](https://github.com/undisbeliever/snesdev-notes) - undisbeliever's practical notes on a range of SNES development topics.

## Assemblers & Toolchains

- [cc65 / ca65](https://github.com/cc65/cc65) - `ca65` supports the 65816, making the cc65 suite usable for SNES assembly projects.
- [WLA-DX](https://github.com/vhelin/wla-dx) - Multi-platform cross assembler with full 65816 and SPC700 support, widely used for SNES.
- [bass](https://github.com/ARM9/bass) - Maintained fork of byuu's `bass` multi-architecture assembler, common for 65816 SNES work.

## C & High-Level Toolchains & Libraries

- [PVSnesLib](https://github.com/alekmaul/pvsneslib) - The main open C development kit for the SNES, with a tcc-based toolchain, libraries, and examples.

## Emulators & Debuggers

- [bsnes](https://github.com/bsnes-emu/bsnes) - Accuracy-focused SNES emulator.
- [bsnes-plus](https://github.com/devinacker/bsnes-plus) - Debug-oriented fork of bsnes with a disassembler, breakpoints, and memory tools.
- [Snes9x](https://github.com/snes9xgit/snes9x) - Portable, long-standing SNES emulator.
- [Mesen2](https://github.com/SourMesen/Mesen2) - Multi-system emulator with a strong SNES debugger; the repository is archived but it remains a reference tool.

## Graphics Tools

- [SuperFamiconv](https://github.com/Optiroc/SuperFamiconv) - Flexible tile, palette, and map graphics converter supporting SNES (and other console) formats.

## Audio & Music Tools

- [Terrific Audio Driver](https://github.com/undisbeliever/terrific-audio-driver) - Modern homebrew SNES SPC700 audio driver with a GUI editor.
- [SNESMod](https://github.com/mukunda-/snesmod) - SPC700 music and sound driver that plays IT-format modules on the SNES.

## Hardware Docs

- [fullsnes](https://problemkaputt.de/fullsnes.htm) - In-depth coverage of the SPC700, PPU, and DSP registers (same nocash reference).

## Example & Open-Source Games

- [SNES Assembly Adventure](https://github.com/georgjz/snes-assembly-adventure-code) - Code accompanying a step-by-step 65816 SNES assembly tutorial series.
- [unnamed-snes-engine](https://github.com/undisbeliever/unnamed-snes-engine) - A single-screen top-down SNES game demo and engine.
- [snes-breakout](https://github.com/georgjz/snes-breakout) - A small, complete Breakout clone written in SNES assembly.
- [SNES_00](https://github.com/nesdoug/SNES_00) - nesdoug's SNES test and example code, part of a numbered example series.

## Communities

- [NESdev Forums (SNESdev section)](https://forums.nesdev.org/) - Hosts the primary SNES/Super Famicom development discussion boards.

## AI & ML on the SNES

- [elya-snes](https://github.com/Scottcjn/elya-snes) - A ternary transformer LLM on the SNES 65816, showing ternary beating int8 by 2.02x despite the hardware multiplier.

## Contributing

Contributions are welcome. Please read the [contributing guidelines](CONTRIBUTING.md) first, then open a pull request.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and
related or neighboring rights to this work.
