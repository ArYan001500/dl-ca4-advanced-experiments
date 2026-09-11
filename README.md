# CA4 advanced experiments

This repository contains a separate working version of the flower-classification assignment. It is related to CA4, but it is not an exact file-content duplicate of the submitted CA4 folder.

## Contents

- `notebooks/flower_cnn_advanced_experiments.ipynb`: regularized CNN experiments, residual-style blocks, squeeze-and-excitation components, stochastic depth, MixUp, EfficientNetB0 transfer learning, and Keras Tuner runs.

## Results from the notebook

The notebook contains several experimental tracks. One EfficientNetB0 transfer-learning run reached about 93.73% validation accuracy during training. A later evaluation block in the same notebook is inconsistent with that high validation number, so I describe it as an experimental training observation rather than a final verified benchmark.

Generated tuner folders, checkpoints, local cache files, and the EfficientNet cache weight file were excluded.
