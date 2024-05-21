# Insectmamba: Insect Pest Classification with State Space Model

This repository contains the code for the paper [Insectmamba: Insect pest classification with state space model](https://arxiv.org/pdf/2404.03611) by Qianning Wang, Chenglin Wang, Zhixin Lai, and Yucheng Zhou.

## Overview

Insectmamba is a state-of-the-art framework for classifying insect pests using a state space model. This repository provides the implementation details and the necessary scripts to reproduce the results presented in the paper.

## Installation

To install the necessary dependencies, please use the following command:

```bash
pip install -r requirements.txt
```

## Demo

To run the model, use the following command:

```bash
python simple_insectmamba.py
```

## Dataset

The dataset used for training and evaluation is provided in [Huggingface](https://huggingface.co/datasets/MambaHub/InsectMambaData).


## Citation

If you find this code useful, please consider citing our work:

```bibtex
@article{wang2024insectmamba,
  title={Insectmamba: Insect pest classification with state space model},
  author={Wang, Qianning and Wang, Chenglin and Lai, Zhixin and Zhou, Yucheng},
  journal={arXiv preprint arXiv:2404.03611},
  year={2024}
}
```

## Acknowledgments

[VMamba](https://github.com/MzeroMiko/VMamba): the codebase we built upon. We would like to thank all contributors and the research community for their invaluable feedback and support.