# MIT Surrey dwarf galaxy collab

Some tutorials and notes on how to get the GNN+Flow models running when I'm away :D

## Install:
This repo includes the `JeansGNN` library as a submodule. Make sure to clone with the `--recurse-submodules` flag.
In other words, run:
```
git clone --recurse-submodules https://github.com/trivnguyen/mit_surrey_collab.git
```

Then install the `JeansGNN` library by running:
```
cd JeansGNN
pip install .
```

## Notes:
The `JeansGNN` should include a detailed documentation and tutorial. Note that what you have here is the most updated version (`dev-unstable`). There are some fun experiments with `jax` and stochastic variation inference with `numpyro`, so feel free to explore and play around with it.