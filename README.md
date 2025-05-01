# MO-TSPTW Dataset

This repository provides data files for the **Multi-Objective Traveling Salesman Problem with Time Windows (MO-TSPTW)**. It is associated with the paper submission:

> **Pareto-NRPA: A Novel Monte-Carlo Algorithm for Multi-Objective Optimization**

## Description

The dataset consists of 31 benchmark instances for the MO-TSPTW problem. Each instance includes:

- **City coordinates**: Stored in `coordinates.pickle`, containing the 2D positions of cities for all instances.
- **Cost matrices**: Stored as `.npy` files, each encoding the pairwise Euclidean distance matrix for a corresponding instance.

These files are intended to support reproducibility and further research in multi-objective combinatorial optimization, particularly for evaluating Monte Carlo planning algorithms.

## Citation

If you use this dataset in your research, please cite the associated paper:

> _Pareto-NRPA: A Novel Monte-Carlo Algorithm for Multi-Objective Optimization_

## License

This project is licensed under the [MIT License](LICENSE).
