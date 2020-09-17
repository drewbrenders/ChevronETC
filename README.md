# Jets.jl

| **Documentation** | **Action Statuses** |
|:---:|:---:|
| [![][docs-dev-img]][docs-dev-url] [![][docs-stable-img]][docs-stable-url] | [![][doc-build-status-img]][doc-build-status-url] [![][build-status-img]][build-status-url] [![][code-coverage-img]][code-coverage-results] |

Jets is a Julia library for matrix-free linear algebra and nonlinear optimization.

Some related Julia packages include:
- JOLI https://github.com/slimgroup/JOLI.jl 
- LinearMap https://github.com/Jutho/LinearMaps.jl 
- BlockArrays https://github.com/JuliaArrays/BlockArrays.jl 
- FunctionalOperators https://github.com/hakkelt/FunctionOperators.jl 
- AbstractOperators https://github.com/kul-forbes/AbstractOperators.jl 

The purpose of Jets is to provide familiar matrix-vector syntax without forming matrices. Instead, the action of the matrix and its adjoint applied to vectors is specified using Julia methods. In addition, Jets provides a framework for nonlinear functions and their linearization. The main construct in this package is a `jet` and is loosely based on its mathematical namesake (https://en.wikipedia.org/wiki/Jet_(mathematics)). In particular,  a `jet` describes a function and its linearization at some point in its domain.

For more information please see: [link to docs index.md]

## Companion packages in the COFII framework
- DistributedJets - https://github.com/ChevronETC/DistributedJets.jl
- JetPack - https://github.com/ChevronETC/JetPack.jl
- JetPackDSP - https://github.com/ChevronETC/JetPackDSP.jl
- JetPackWave - https://github.com/ChevronETC/JetPackWave.jl
- JetPackTransforms - https://github.com/ChevronETC/JetPackTransforms.jl

[![](https://img.shields.io/badge/docs-stable-green.svg)](https://chevronetc.github.io/Jets.jl/stable/)
[![](https://img.shields.io/badge/docs-dev-blue.svg)](https://chevronetc.github.io/Jets.jl/dev/)


[docs-dev-img]: https://img.shields.io/badge/docs-dev-blue.svg
[docs-dev-url]: https://chevronetc.github.io/Jets.jl/dev/

[docs-stable-img]: https://img.shields.io/badge/docs-stable-blue.svg
[docs-stable-url]: https://ChevronETC.github.io/Jets.jl/stable

[doc-build-status-img]: https://github.com/ChevronETC/Jets.jl/workflows/Documentation/badge.svg
[doc-build-status-url]: https://github.com/ChevronETC/Jets.jl/actions?query=workflow%3ADocumentation

[build-status-img]: https://github.com/ChevronETC/Jets.jl/workflows/Tests/badge.svg
[build-status-url]: https://github.com/ChevronETC/Jets.jl/actions?query=workflow%3A"Tests"

[code-coverage-img]: https://codecov.io/gh/ChevronETC/Jets.jl/branch/master/graph/badge.svg
[code-coverage-results]: https://codecov.io/gh/ChevronETC/Jets.jl