# odinjar

Merges files and libraries into a single jar. Will attempt to find an entry point automatically, unless specified through the main class argument.

`usage: odinjar [-h] [-o OUT] [-e ENTRY] [-l] files [files ...]`

`-e, --entry`: Java class containing entry point (main class)

`-o, --out`: jar output filename (default: out)

`-l, --inclib`: include libraries when finding entry point
