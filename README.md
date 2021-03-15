# cogs-182

The repository consists of two Jupyter notebooks to run.

`Environment_tests.ipynb` runs the sanity checks to make sure the state transitions work as expected for the simplified Pokemon setup.

`Agents.ipynb` contains both the environment code as well as the code for the Monte Carlo and TD(0) agents. The code to generate the graphs in the paper can be run by following the cells top to bottom.

In particular:

Cells 2, 3, and 4 have the code to train and test the MC Agent across the 3 environment variations.

Cells 7, 8, and 9 have the code to train and test the TD(0) Agent across the 3 environment variations.