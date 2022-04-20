# RISC-V Reference Card

[![Build Status](https://travis-ci.com/jameslzhu/riscv-card.svg?branch=master)](https://travis-ci.com/jameslzhu/riscv-card)

An unofficial reference sheet for RISC-V, the free and libre ISA from Berkeley. ([**PDF**][pdf]).

## What's inside?

- The base ISA (RV32I), with opcode values and C-like descriptions
- Standard ISA extensions (most but not all yet)
- Register aliases and calling conventions
- Pseudoinstructions

Other information from the more official reference cards not specific to the ISA,
like the stack/heap memory layout, IEEE 754 floating-point layout, and size prefixes,
have been omitted.

## Why?

In RISC tradition, the assembly reference for [MIPS][mips-green-sheet]
and [RISC-V][riscv-card] fits onto a single double-sided 'Green Sheet'.

When I took [CS 61C][cs61c] at UC Berkeley in 2017, we were the first semester taught
using RISC-V, and our reference card scans from our [RISC-V textbook][patterson-hennessy]
were low-quality. I wanted a card I didn't have to squint at, so I typeset it in LaTeX.

The latest [Berkeley course reference card][cs61c-sp22] is also available.

This little reference has grown well past a double-sided page, but if you still want
the original you can print the first and last pages for the asm opcodes and calling convention.

## Contributing

This repository is not actively developed, but pull requests are accepted for
fixes, new ISA standard extensions, style improvements, or other such changes.
Please include a rebuilt PDF binary in your pull request.

Print-friendly format is preferred, when possible: legible font sizes, clean
page breaks and full letter page width usage.
(A4 support may be a good thing to check.)

Some ideas if you are truly motivated:
- Multiple outputs (pdfs) for different domains / ISA extension sets, or for 32
  / 64-bit support
- Directly parsing the spec, banishing typos forever
- Build system to select binary or hex instruction opcodes
- Other ISA support? (probably only feasible for RISC ISAs)

## Licensing

This work is licensed under the Creative Commons [CC-BY-4.0][CC] license.
(See LICENSE for the full text.)

In brief, feel free to use this for your own purposes, as long as you credit
me, and don't restrict others. (Again, read the license for the specifics.)

This work is adapted from the RISC-V Instruction Set Manual, available at
[https://riscv.org/specifications/][RV] and licensed
under the Creative Commons [CC-BY-4.0][CC] license.

[pdf]: https://github.com/jameslzhu/riscv-card/blob/master/riscv-card.pdf
[RV]: https://riscv.org/specifications "RISC-V spec"
[CC]: https://creativecommons.org/licenses/by/4.0/ "CC-BY-4.0"
[cs61c]: https://cs61c.org/
[patterson-hennessy]: https://www.elsevier.com/books/catalog/isbn/9780128203316
[riscv-card]: https://inst.eecs.berkeley.edu/~cs61c/resources/RISCV_Green_Sheet.pdf
[mips-green-sheet]: https://inst.eecs.berkeley.edu/~cs61c/resources/MIPS_Green_Sheet.pdf
[cs61c-sp22]: https://cs61c.org/sp22/pdfs/resources/reference-card.pdf
