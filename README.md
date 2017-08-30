# mod2neuroml

The [`nmodl` language](https://www.neuron.yale.edu/neuron/static/papers/nc2000/nmodl.htm) is used to define new cell mechanisms (eg ionic currents) for the [NEURON simulator](http://neuron.yale.edu/neuron/). This project outlines some possible pipelines for expressing models defined using `mod` in [NeuroML2/LEMS](https://github.com/NeuroML/NeuroML2).

## pynmodl

The [pynmodl](https://github.com/borismarin/pynmodl/tree/master/pynmodl) repositry contains a (`python`-based) parser for `mod` files, providing infrastructure for building compilers from `mod` to other languages. It includes basic support for generating LEMS ([usage example](https://github.com/borismarin/pynmodl/blob/master/pynmodl/tests/compiling/lems/test_lemsgen.py)).
