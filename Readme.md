# uf2conf

uf2conf, a tool for convert binary to uf2 format. If already in BOOT mode, audo copy new .uf2 to BOOT disk to upgrade.

Version 0.2.1

usage:
    uf2conv.exe [-s 2000|4000] -i flash.bin [-o flash.uf2]

Options:
-    -s --start 2000|4000    Starting address in hex for binary file (default: 2000)
-    -i --input flash.bin    Set the input file name to be convert, mandory
-    -o --output flash.uf2   Set the output file name, default: flash.uf2
-    -h --help               Display help information
-    -v --version            Show the program version
