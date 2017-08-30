# mod2neuroml

The [`nmodl` language](https://www.neuron.yale.edu/neuron/static/papers/nc2000/nmodl.htm) is used to define new cell mechanisms (eg ionic currents) for the [NEURON simulator](http://neuron.yale.edu/neuron/). This project outlines some possible pipelines for expressing models defined using `mod` in [NeuroML2/LEMS](https://github.com/NeuroML/NeuroML2).

![mod2neuroml](https://docs.google.com/drawings/d/e/2PACX-1vSFxphfnUs0iPFj7_RB5jqJnhdOUSzmOryhRa2P7EYJ3VFy_nBlFycXDz-alX9Cz41Rupi2syZs_6uC/pub?w=1189&h=844)

## pynmodl

The [pynmodl](https://github.com/borismarin/pynmodl/tree/master/pynmodl) repositry contains a (`python`-based) parser for `mod` files, providing infrastructure for building compilers from `mod` to other languages. It includes basic support for generating LEMS ([usage example](https://github.com/borismarin/pynmodl/blob/master/pynmodl/tests/compiling/lems/test_lemsgen.py)).

## pynml-channelanalysis + pynml-modchananalysis

See http://www.opensourcebrain.org/docs#Converting_To_NeuroML2

## pyNeuroML

See https://github.com/NeuroML/pyNeuroML

## ICG mod files

See https://github.com/icgenealogy/icg-channels-K/


