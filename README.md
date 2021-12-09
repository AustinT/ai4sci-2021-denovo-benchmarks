# Code for "A Fresh Look at De Novo Molecular Design Benchmarks"

This is the code for the [workshop paper](https://openreview.net/forum?id=gS3XMun4cl_) presented at NeurIPS 2021 AI for Science: Mind the Gaps workshop.
The code is fairly rough as it was originally part of a code base for another project.
I have tried to extract out just the parts for this workshop paper.
If you are unable to get the code to run, feel free to contact us.

## Data

All datasets are included in the repo.

## Python environment

The basic requirements are:

- python 3.7+ (tested on 3.7)
- scipy
- numpy
- pandas
- rdkit
- scikit-learn
- joblib
- gpytorch and botorch (for Gaussian process regression and BO)
- matplotlib (for plotting)

## Reproducing experiments

To reproduce the experiments, simply activate the conda environment, and run the scripts in the `experiments/ai4sci-sep2021` directory.
For example: `bash experiments/ai4sci-sep2021/graph_ga_v1.sh`

## Citation

If you use this code or find our paper useful, we would appreciate a citation! Here is a sample Bibtex file that you could use:

```bibtex
@inproceedings{
tripp2021a,
title={A Fresh Look at De Novo Molecular Design Benchmarks},
author={Austin Tripp and Gregor N. C. Simm and Jos{\'e} Miguel Hern{\'a}ndez-Lobato},
booktitle={NeurIPS 2021 AI for Science Workshop},
year={2021},
url={https://openreview.net/forum?id=gS3XMun4cl_}
}
```
