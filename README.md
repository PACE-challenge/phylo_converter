# phylo_converter
convert multiple-sequence-alignments to character-state intersection graphs 

This code converts a multiple alignments, given in fasta format (one line per species) to the corresponding
character-state intersection graph.

build requirements:
- cmake
- boost
- gcc

runtime requirements:
- boost

compile:
1. `cmake .`  
  (optionally, compile with debug support: `cmake -DDEBUG=x` where x is the debug level (0 ... 5, where 0 means no debugging output))
2. `make`

install:
`make install`

usage:
`ma_to_cc <input-file> [output-file]`
see also
`ma_to_cc --help`
