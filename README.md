# GB-GA
[Graph-based genetic algorithm](http://dx.doi.org/10.1039/C8SC05372C)
 
usage example: 'python GA_logP.py ZINC_first_1000.smi' or 'python GA_rediscovery.py Celecoxib_1000_100.smi'. The idea is that the py file serves as an input file.

# Changes by me
- Ran some .py files through [black](https://black.readthedocs.io/en/stable/) to get rid of the two-space indentations
- Implement calculators for IP/EA with GFN-XTB, see the [docs](https://xtb-docs.readthedocs.io/en/latest/sp.html?vertical-ionization-potentials-and-electron-affinities#vertical-ionization-potentials-and-electron-affinities)

## TODO
- Write GA_IPEA.py that implements GA for IP/EA targets
- Figure out the role of GaussianModifier, ThresholdedLinearModifier, whether to use these.