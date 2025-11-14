# Installation Instructions

### Install conda environment
```cd src```
```conda env create -f environment.yaml```
```conda activate gnn_layout```

# Generate Synthetic Data
Configure the parameters in `configs/synthetic.yaml` as needed, then run:
```python synthetic_data_gen/generate.py --dry-run --config synthetic_data_gen/configs/synthetic.yaml```