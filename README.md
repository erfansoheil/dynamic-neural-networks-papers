# dynamic-neural-networks-papers

## Goal
This repository aims to organize research on dynamic neural network adaptation methods, including pruning, growing, topology adaptation, and adaptive computation.

## Categories
- [Pruning](./pruning/): Pruning methods remove unnecessary parameters, neurons, channels, layers, or connections to obtain smaller, more efficient, or more interpretable models.
   In this repository, a paper belongs to this section when the main architectural change is the structural removal of components during training, without explicitly adding new components.
- [Growing](./growing/): Growing methods add new neurons, layers, channels, branches, or other architectural components when the current model is not expressive enough. In this repository, a paper belongs to this section when the main architectural change is structural expansion during training, without explicitly pruning existing components.
- [Growing + Pruning](./growing-and-pruning/): These methods combine growth and pruning mechanisms, allowing the model to add capacity when needed and remove unnecessary structure when it becomes redundant. In this repository, a paper belongs to this section when both structural growth and structural pruning are central parts of the method.
- [Adaptive Computation](./adaptive-computation/): Adaptive computation methods may change routing, execution paths, attention, convolutional kernels, activation functions, or ... In this repository, a paper belongs to this section when the model adapts how it computes, but the main contribution is not structural growing or pruning.

## Paper Format
Each paper includes:
- Title
- Year
- Paper link
- GitHub repository (if available)
- Keywords

## Number of Papers: 20
- Pruning: 6
- Growing: 8
- Growing and Pruning: 4 
- Adaptive Computation: 3

  
Last updated: 2 June 2026
