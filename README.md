![FMI.jl Logo](https://github.com/ThummeTo/FMI.jl/blob/main/logo/dark/fmijl_logo_640_320.png "FMI.jl Logo")
# FMICore.jl

## What is FMICore.jl?
[*FMICore.jl*](https://github.com/ThummeTo/FMICore.jl) implements the low-level equivalents of the C-functions and C-data types of the FMI-standard ([fmi-standard.org](http://fmi-standard.org/)) for the Julia programming language. 
[*FMICore.jl*](https://github.com/ThummeTo/FMICore.jl) provides the foundation for the Julia packages [*FMIImport.jl*](https://github.com/ThummeTo/FMIImport.jl) and [*FMIExport.jl*](https://github.com/ThummeTo/FMIExport.jl).

[![CI Testing](https://github.com/ThummeTo/FMICore.jl/actions/workflows/Test.yml/badge.svg)](https://github.com/ThummeTo/FMICore.jl/actions)
[![Coverage](https://codecov.io/gh/ThummeTo/FMICore.jl/branch/main/graph/badge.svg)](https://codecov.io/gh/ThummeTo/FMICore.jl)

## How can I use FMICore.jl?
**Please note:** [*FMICore.jl*](https://github.com/ThummeTo/FMICore.jl) is not meant to be used as it is, but as part of [*FMI.jl*](https://github.com/ThummeTo/FMI.jl), [*FMIImport.jl*](https://github.com/ThummeTo/FMIImport.jl), [*FMIExport.jl*](https://github.com/ThummeTo/FMIExport.jl) and [*FMIFlux.jl*](https://github.com/ThummeTo/FMIFlux.jl). However you can install [*FMICore.jl*](https://github.com/ThummeTo/FMICore.jl) by following these steps.
1. open a Julia-Command-Window, activate your prefered environment
1. goto package manager using ```]```
1. type ```add FMICore```

## What FMI.jl-Library should I use?
![FMI.jl Family](https://github.com/ThummeTo/FMI.jl/blob/main/docs/src/assets/FMI_JL_family.png "FMI.jl Family")
To keep dependencies nice and clean, the original package [*FMI.jl*](https://github.com/ThummeTo/FMI.jl) had been split into new packages:
- [*FMI.jl*](https://github.com/ThummeTo/FMI.jl): High level loading, manipulating, saving or building entire FMUs from scratch
- [*FMIImport.jl*](https://github.com/ThummeTo/FMIImport.jl): Importing FMUs into Julia
- [*FMIExport.jl*](https://github.com/ThummeTo/FMIExport.jl): Exporting stand-alone FMUs from Julia Code
- [*FMICore.jl*](https://github.com/ThummeTo/FMICore.jl): C-code wrapper for the FMI-standard
- [*FMIBuild.jl*](https://github.com/ThummeTo/FMIBuild.jl): Compiler/Compilation dependencies for FMIExport.jl
- [*FMIFlux.jl*](https://github.com/ThummeTo/FMIFlux.jl): Machine Learning with FMUs (differentiation over FMUs)
- [*FMIZoo.jl*](https://github.com/ThummeTo/FMIZoo.jl): A collection of testing and example FMUs

## What Platforms are supported?
[*FMICore.jl*](https://github.com/ThummeTo/FMICore.jl) is tested (and testing) under Julia Versions *1.6.5 LTS* and *latest* on Windows *latest*, Ubuntu *latest* and MacOS *latest*. `x64` and `x86` architectures are tested.

## How to cite?
Tobias Thummerer, Lars Mikelsons and Josef Kircher. 2021. **NeuralFMU: towards structural integration of FMUs into neural networks.** Martin Sjölund, Lena Buffoni, Adrian Pop and Lennart Ochel (Ed.). Proceedings of 14th Modelica Conference 2021, Linköping, Sweden, September 20-24, 2021. Linköping University Electronic Press, Linköping (Linköping Electronic Conference Proceedings ; 181), 297-306. [DOI: 10.3384/ecp21181297](https://doi.org/10.3384/ecp21181297)

## Related publications
Tobias Thummerer, Johannes Tintenherr, Lars Mikelsons 2021 **Hybrid modeling of the human cardiovascular system using NeuralFMUs** Journal of Physics: Conference Series 2090, 1, 012155. [DOI: 10.1088/1742-6596/2090/1/012155](https://doi.org/10.1088/1742-6596/2090/1/012155)
