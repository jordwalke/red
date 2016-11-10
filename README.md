# RED

Better UX for OCamlDebug. Works with Ocaml and [Reason](https://facebook.github.io/reason/) code.

### Features:

1. Zero config, just prepend your command with `red`
2. Time traveling (can step back in time)
3. Printing arbitrary values and structs
4. Adding and removing breakpoints
5. More to come. See TODO file

<hr>

### Usage:

1. Make sure your build target is `byte-code`, not `native`:

        ocamlbuild myapp.d.byte

2. Clone the repo and run RED:

        git clone https://github.com/frantic/red.git
        ./red/red.py /path/to/myapp.d.byte

3. Press `?` to see available options
