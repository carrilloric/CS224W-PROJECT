# Circuit Quest: Embarking on a GNN Adventure in Logic Synthesis
by Mini Rawat, Ricardo Alberto Carrillo Romero, Malik Hubbard as part of the Stanford CS224W course project.


## Overview

This project explores the application of Graph Neural Networks (GNNs) in the optimization of logic synthesis for very-large-scale integration (VLSI) circuits. We aim to develop a GNN model that can predict final synthesis metrics - such as area, delay, and node count - given an initial design and synthesis recipe. Our model's ( SynE and SynP ) insights could help circuit designers optimize synthesis paths by forecasting performance, allowing for efficient design-space exploration.




- [Pytorch](https://pytorch.org/get-started/locally/)
- [Torch-geometric](https://pytorch-geometric.readthedocs.io/en/latest/notes/installation.html)
- [Networkx](https://networkx.org/documentation/stable/install.html)

Make sure that that the cudatoolkit version in the gpu matches with the pytorch-geometric's (and dependencies) CUDA version.

## Organisation

### Dataset directory structure

	├── CS224W-PROJECT
	│   ├── datagen/utilities      # FUTURE: python Script to convert data from previous version to updated pytorch-geometric versions 
	│   ├── models			       # FUTURE: Models for regression tasks
	│   ├── sample_data 		   # Sample Files in 3 formats, original pt files, graphml files and converted pts files
