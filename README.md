# multiarch-gdbinit

Some gdbinit files for MIPS and ARM used for remotely debugging devices using gdb.

Inspired by and partially stolen from mammon's excellent x86 gdbinit file

Use at your own risk

## Aliases / Commands Provided

* bp
* bpc 
* bpe
* bpd
* bpt
* bpm
* argv
* lib
* sig
* dis
* ascii_char
* hex_quad
* hexdump
* context
* context-on
* context-off
* n
* pret
* init
* start
* main
* regs
* sopath
* go
* plop

You may need to rename `go` on newer versions of gdb. Don't forget to rename the documentation name as well.

## License - GPLv3 - See LICENSE.md

copyright -at- mzpqnxow -dot- com
