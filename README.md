# Simplicial Complex Neural Networks for Deterministic and Uncertain Knowledge Graph Embedding

This repository provides the official PyTorch implementation of the research paper **Simplicial Complex Neural Networks for Deterministic and Uncertain Knowledge Graph Embedding**. If the paper is officially published, we will release all the experimental codes. It will update soon. Thanks for your attention.

### Requirements

- python >= 3.6
- pytorch == 1.8.1
- torch-geometric == 2.0.3
- torch-scatter == 2.0.6
- torch-sparse == 0.6.12
- torchsummary == 1.5.1
- tqdm == 4.63.0
- simcse == 0.4
- scikit-learn == 0.21.1
- numpy == 1.19.5

### How to run

SCKGE:

```shell
python run.py -use_scnn -edge_sample_scale 8000 -lr 0.001 -data WN18RR -model SCKGE -score_func conve
```

SCUKGE:

```shell
python run.py -use_scnn -edge_sample_scale 10000 -lr 0.001 -data cn15k -model SCKGE -score_func conve
```

