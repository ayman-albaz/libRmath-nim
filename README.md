libRmath-nim
============

This is the Rmath library from R, patched to use the [DSFMT](http://www.math.sci.hiroshima-u.ac.jp/~m-mat/MT/SFMT/) RNG in `src/runif.c` as part of the [Rmath-julia](https://github.com/JuliaLang/Rmath-julia) repository. The repository has been forked, to keep in sync with Nim-friendly wrappers. See [rmath](http://github.com/sdwfrost/rmath) for how to use this library from Nim.

Build instructions
------------------

libRmath-nim requires GNU Make (https://www.gnu.org/software/make). Just run `make` to compile the library.
