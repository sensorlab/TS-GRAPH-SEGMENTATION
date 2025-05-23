## GNN-based Time Series Segmentation

This project implements a graph-based approach to time series segmentation (TSS) using Graph Neural Networks (GNNs). It leverages synthetic and real-world datasets from the Time Series Segmentation Benchmark (TSSB) (https://github.com/ermshaua/time-series-segmentation-benchmark/blob/main/README.md) to train a multi-layer Graph Attention Network (GAT). The repository includes both a Jupyter Notebook that demonstrates the full segmentation pipeline — from data loading and graph construction to model training and evaluation — and an environment.yml file for easy environment setup. The enviroment.yml file includes also the dataset package doirect


## Envrionment Setup

1. Use mamba (conda) to build the environment from the provided environment.yml : 
  mamba env create -f environment.yml

2. Activate the environment:
  conda activate TSSB

3. Install ipykernel and add the environment as a Jupyter kernel:
  pip install ipykernel
  python -m ipykernel install --user --name TSSB --display-name "Python (TSSB)"

4. Launch Jupyter Notebook and select the Python (TSSB) kernel

## Citation

## License

## Acknowledgement

This work was supported by the Slovenian Research Agency (P2-0016) and the European Commission NANCY project (No.101096456).
