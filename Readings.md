# Readings

### compile time garbage collection
[ASAP: As Static As Possible memory management](http://www.cl.cam.ac.uk/techreports/UCAM-CL-TR-908.html)

### Data Flow Fusion
[Data Flow Fusion with Series Expressions in Haskell](http://repa.ouroborus.net/#DataFlowFusion)

### unified effectful and pure syntax
[Ben Lippmeier - An overview of the DDC compiler](https://www.youtube.com/watch?v=QShfhs7nToI)

### high-performance SIMD programming on the CPU 
[Efficiently coding for modern CPUs by Edward Kmett](https://www.youtube.com/watch?v=KzqNQMpRbac)

### existing ideas and implementations
- gpgpu languages / array languages:  futhark, repa
- multi-stage languages:              ber meta ocaml
- modern language design:             idris

languages to check
- ber meta ocaml
- idris (dependent type + partial evaluation + staged compilation + extendable syntax)
- futhark (it's written in haskell)
- [urweb](http://www.impredicative.com/ur/): - what happens with runtime polymorphismin the back-end?

[holyjit](https://github.com/nbp/holyjit): this is also some kind of partial evaluation thing and I don't really understand it

### Minimal use-case test comparisons
#### Low-level
- Obsidian
- Fcl
#### High-level
- Accelerate
- Futhark

### GHC simplifier
- [Compilation by transformation for non-strict functional languages](https://www.microsoft.com/en-us/research/publication/compilation-transformation-non-strict-functional-languages)


### Dependent Type implementation tutorials
- [Lambda Pi](https://www.andres-loeh.de/LambdaPi/)
- [Simple Easy!](http://strictlypositive.org/Easy.pdf)
