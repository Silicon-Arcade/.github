# Silicon Arcade

Silicon Arcade is where the machines of the eighties get taken apart and
rebuilt as software. It is the home of **6502 Construction Set**, a two-volume
build-along in Rust: the first volume builds a cycle-accurate 6502 processor
from the datasheet up, and the second builds a machine compatible with the BBC
Model B on top of it. Thirty builds, starting at `LDA #$48` and culminating in
a game of chess.

This org holds the code that supports the books, not the books themselves.
Repositories appear here as the material they belong to is published, so expect
it to be sparse for now and to fill out as the volumes land. 

The first is
[**build-01-start**](https://github.com/Silicon-Arcade/build-01-start) — the
scaffold Build 1 begins from, so that anyone reading the free chapters can run
the code rather than only read it. Five opcodes, a 64 KB bus, a memory-mapped
output port, four unit tests, and no dependencies.

Three chapters and an essay are free to read in full at
[**silicon-arcade.com**](https://silicon-arcade.com), alongside an animated
episode that steps a 6502 through its first program one instruction at a time,
with the registers and memory changing as it goes.

