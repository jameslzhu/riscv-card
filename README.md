# RISC-V Green Card
An unofficial reference card for RISC-V, the free and libre ISA from Berkeley.

## Why?

I wanted a better assembly reference card for my [CS 61C][CS61C] course at UC
Berkeley that I didn't have to squint at. The original intent was to print the
full base ISA and register calling convention on a single double-sided page.
This is still possible by printing the first and last pages.

The provided [green card][CS61C-card] from our
[RISC-V textbook][patterson-hennessy] is (now) available in high-resolution pdf
scans, but is not text-friendly. Information not specific to RISC-V
architectures, like the stack/heap memory layout, IEEE 754 floating-point
layout, and size prefixes, is omitted.

## Contributing

This repository is not actively developed, but pull requests are accepted, for
fixes, new ISA standard extensions, style improvements, or other such changes.
Please include a rebuilt PDF binary in your pull request.

Print-friendly format is preferred, when possible: legible font sizes, clean
page breaks and letter page width utilization.
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

[RV]: https://riscv.org/specifications "RISC-V spec"
[CC]: https://creativecommons.org/licenses/by/4.0/ "CC-BY-4.0"
[CS61C]:https://cs61c.org/
[patterson-hennessy]: https://www.elsevier.com/books/catalog/isbn/9780128203316
[CS61C-card]: https://cs61c.org/resources/pdf?file=riscvcard_large.pdf
