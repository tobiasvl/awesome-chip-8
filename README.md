# Awesome CHIP-8 [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

[<img src="c8.png" align="right" width="100">](https://chip-8.github.io)

> Virtual computer game machine from the 70s 

A curated list of awesome CHIP-8 resources, tools, documentation, related projects and open source ROMs.

Created in 1977, [CHIP-8](https://en.wikipedia.org/wiki/CHIP-8) is the original fantasy console. Initially designed to ease game development for the COSMAC VIP kit computer, it has enjoyed several revivals over the decades for new and exciting platforms. Today, creating a CHIP-8 implementation is a rite of passage for anyone interested in learning about emulation.

To add something to this list, please see the [contribution guidelines](CONTRIBUTING.md).

## Contents

* [Community](#community)
* [Documentation](#documentation)
* [Emulator/interpreter development](#emulatorinterpreter-development)
  * [Testing](#testing)
* [Emulators/interpreters](#emulatorsinterpreters)
* [Software development](#software-development)
  * [Tools](#tools)
  * [Guides and snippets](#guides-and-snippets)
  * [Postmortems](#postmortems)
* [Games](#games)

## Community

* [COSMAC Elf Group](https://groups.io/g/cosmacelf) - Group for discussion of the COSMAC Elf, as well as anything else RCA 1802-related, including COSMAC VIP and CHIP-8.
* [#chip8 channel on the Emulation Development Discord server](https://discordapp.com/invite/Gf7cP3w) - Chat for discussing development of CHIP-8 emulators/interpreters.
* [OctoJam](http://octojam.com/) - An Octo-centric game jam held every October.

## Documentation

* [Mastering CHIP-8](https://github.com/mattmikolay/chip-8/wiki/Mastering-CHIP%E2%80%908) - In-depth overview of the CHIP-8 instruction set.
* [CHIP-8 Instruction Set](http://johnearnest.github.io/Octo/docs/chip8ref.pdf) - Quick cheat sheet for CHIP-8 instructions.
* [CHIP-8 Instruction Set](https://github.com/mattmikolay/chip-8/wiki/CHIP%E2%80%908-Instruction-Set) - A comprehensive instruction/opcode table.
* [CHIP-8 Technical Reference](https://github.com/mattmikolay/chip-8/wiki/CHIP%E2%80%908-Technical-Reference) - Overview of how the CHIP-8 interpreter works.
* [CHIP-8 Extensions Reference](https://github.com/mattmikolay/chip-8/wiki/CHIP%E2%80%908-Extensions-Reference) - A list of CHIP-8 variants and extensions.
* [Chip-8 on the COSMAC VIP](https://laurencescotford.com/chip-8-on-the-cosmac-vip-index/) - An in-depth disassembly and analysis of the original CHIP-8 interpreter on the COSMAC VIP.
* [HP48-Superchip](https://github.com/Chromatophore/HP48-Superchip) - An in-depth look at CHIP48 and Super-CHIP for the HP48 calculators, and modifications to make them CHIP-8 compatible.
* [Octo Extensions](http://johnearnest.github.io/Octo/docs/XO-ChipSpecification.html) - Specification for Octo's XO-CHIP extension.

## Emulator/interpreter development

* [How to write an emulator (CHIP-8 interpreter)](http://www.multigesture.net/articles/how-to-write-an-emulator-chip-8-interpreter/) - A guide to developing a CHIP-8 interpreter in C/C++.
* [Emulator 101: CHIP-8](http://www.emulator101.com/introduction-to-chip-8.html) - A guide to developing a CHIP-8 disassembler and interpreter in C.
* [Chip 8 Instruction Scheduling and Frequency](https://jackson-s.me/2019/07/13/Chip-8-Instruction-Scheduling-and-Frequency.html) - Timing of CHIP-8 instructions on the COSMAC VIP.
* [High-level guide to making a CHIP-8 emulator](https://tobiasvl.github.io/blog/write-a-chip-8-emulator/) - A guide for developing a CHIP-8 interpreter, without code.

### Testing

* [chip8-test-rom](https://github.com/corax89/chip8-test-rom) - corax89's CHIP-8 test program, which tests most instructions for correct (Super-CHIP compliant) behavior.
* [CHIP-8 test suite](https://github.com/Timendus/chip8-test-suite) - Timendus' collection of tests, including an improved version of corax89's test rom, a test for the behaviour of the flags and a CHIP-8 / Super-CHIP / XO-CHIP quirks test.
* [Delay timer test](https://github.com/mattmikolay/chip-8/tree/master/delaytimer) - Test program that checks the delay timer's behavior.
* [Random number test](https://github.com/mattmikolay/chip-8/tree/master/randomnumber) - Test program that checks the spread and mask for random number generation.

## Emulators/interpreters

* [Octo](http://johnearnest.github.io/Octo/) - An IDE for development of CHIP-8, Super-CHIP and XO-Chip games.
* [Emma02](https://www.emma02.hobby-site.com/) - An emulator for many old microcomputers, including COSMAC VIP, Telmac 1800 and ETI 660, which ran early CHIP-8 interpreters (which are included in the emulator).
* [Super-Chip8x](https://github.com/Ersanio/Super-Chip8x) - CHIP-8 emulator for the SNES.
* [CHIP-8 console on FPGA](https://github.com/pwmarcz/fpga-chip8) - A CHIP-8 emulator for the TinyFPGA BX chip.
* [Vinegar](http://benryves.com/bin/vinegar/) - CHIP-8/Super-CHIP interpreter for TI-83 (Plus) calculators.
* [LowResNX](https://lowresnx.inutilis.com/topic.php?id=1648) - CHIP-8 interpreter and debugger programmed in BASIC inside another retro fantasy console.

## Software development

### Tools

* [Octo](http://github.com/johnearnest/Octo/) - A high-level assembler for CHIP-8, Super-CHIP and XO-CHIP, complete with an environment for testing programs, and tools for sharing your creations.
* [wernsey chip8](https://github.com/wernsey/chip8) - A CHIP-8 assembler/disassembler.
* [EZ-Bake Animator](http://beyondloom.com/tools/ezbake.html) - A graphics preparation tool that creates XOR-ed animations.
* [EZ-Writer](http://beyondloom.com/tools/ezwriter.html) - A tool for converting text into CHIP-8 sprites.
* [EZ-Pack](http://beyondloom.com/tools/ezpack.html) - An image slicing/repaletting tool.
* [Chipify](http://johnearnest.github.io/Octo/tools/Chipify/) - A script that filters and encodes mono-channel WAV audio to XO-CHIP audio.
* [octofont](https://github.com/jdeeny/octofont/) - Convert TrueType (ttf) fonts to Octo code for CHIP-8.

### Guides and snippets

* [Octo manual](https://johnearnest.github.io/Octo/docs/Manual.html) - The manual for Octo.
* [A Beginner's Guide to Programming with Chip8](http://johnearnest.github.io/Octo/docs/BeginnersGuide.html) - An introductory guide to CHIP-8 programming in Octo.
* [An Intermediate Guide to Game Development with Chip8](http://johnearnest.github.io/Octo/docs/IntermediateGuide.html) - Remaking the Atari 2600 game "Outlaw" for CHIP-8 in Octo.
* [Chip8 Programming Techniques](http://johnearnest.github.io/Octo/docs/Chip8%20Programming.html) - Many different programming tips for CHIP-8.
* [Octo Metaprogramming Cookbook](http://johnearnest.github.io/Octo/docs/MetaProgramming.html) - How to use Octo's assembly directives for meta-programming.
* [Mastering SuperChip](http://johnearnest.github.io/Octo/docs/SuperChip.html) - How to make games compatible with CHIP-8 and Super-CHIP, as well as some Super-CHIP specific techniques.
* [Adventures in Sorting](https://johnearnest.github.io/Octo/docs/Sorting.html) - Implementing efficient sorting algorithms in Octo for CHIP-8.
* [chip8-multiply](https://github.com/jdeeny/chip8-multiply) - Multiplication routines for CHIP-8, written in Octo.

### Postmortems

Postmortems detailing the development of specific games, written by the developers.

* [Inside Eaty the Alien](http://johnearnest.github.io/Octo/docs/EatyTheAlien.html)
* [Octopeg Post Mortem](http://www.awfuljams.com/octojam-ii/games/octopeg)
* [CosmacCalc: The COSMAC VIP's place in Spreadsheet History](https://abitoutofplace.wordpress.com/2015/05/02/cosmaccalc-the-cosmac-vip-s-place-in-spreadsheet-history/)
* [Inside Cave Explorer](http://johnearnest.github.io/Octo/docs/CaveExplorer.html)
* [Inside Black Rainbow](http://johnearnest.github.io/Octo/docs/BlackRainbow.html)
* [Postmortem: Mini Lights Out](https://tobiasvl.itch.io/mini-lights-out/devlog/102679/postmortem-mini-lights-out)

## Games

* [CHIP-8 Archive](https://johnearnest.github.io/chip8Archive/) - A collection of public domain (CC0) games, all playable online.
* [A collection of CHIP-8 programs and documentation](https://github.com/mattmikolay/chip-8) - Matt Mikolay's games, programs and documentation.
