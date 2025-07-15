# TTR: Test-Time Reasoning for Robust CLIP Zero-Shot Classification

Welcome! This is the official implementation for our ICCV 2025 paper on enhancing robustness in CLIP-based zero-shot classification through Test-Time Reasoning (TTR).


---

## Installation

### Requirements

- Python 3.12
- PyTorch ([installation guide](https://pytorch.org/get-started/locally/))
- [OpenCLIP](https://github.com/mlfoundations/open_clip)
- Other Python dependencies specified in [requirements.txt](requirements.txt)

### Steps to Install

Clone the repository and install the required dependencies:

```bash
pip install -r requirements.txt
pip install open_clip_torch
```

## Reproducing Experiment
We provide Jupyter notebooks to ensure transparency and easy reproducibility. Each notebook directly corresponds to the specific experimental results presented in our paper.

### Variant of waterbirds dataset result

To reproduce the main results from Table 1, run the notebooks:

```
OV.ipynb
Core blk.ipynb
Core Wht.ipynb
```

Semantic identification recipe
```
cd Ablation Introduction
GDINO.ipynb
SAM+GDINO.ipynb
PCA+K-means.ipynb
```

Main results
```
Waterbirds_final.ipynb
CelebA-final.ipynb
Metashifts_final.ipynb
Urbancars_final.ipynb
```



