# Invoice Classification from Scanned Documents

This project uses Convolutional Neural Networks (CNNs) with PyTorch to classify scanned business and financial documents. It supports open-set classification to reject non-relevant document types using Entropic Open-set Loss. The model is trained on a modified version of the RVL-CDIP dataset.

---

## Features

- Handles 12 financial/business document types 
- Rejects unknown or irrelevant documents
- Custom CNN with residual blocks
- Open-set loss function to manage out-of-distribution data

---
## Installation

```bash
git clone https://github.com/SherifHamed1/Invoice-Classification-From-Scanned-Documents.git
```

---

## Download Dataset  

The project uses the [RVL-CDIP dataset](https://huggingface.co/datasets/aharley/rvl_cdip). The dataset will be downloaded automatically by running the first block of the notebook. Please note that the dataset is quite large at 38 GB and additional disk space will be required during preprocessing due to caching.

---

## Requirements

- jupyterlab
- notebook
- PyTorch
- torchvision
- torchsummary
- scikit-learn
- datasets (Hugging Face)
- matplotlib
- numpy
- Pillow

Most dependencies can be installed via:

```bash
pip install -r requirements.txt
```

For downloading torch, please check [here](https://pytorch.org/get-started/locally/) to install the version suitable for your os. This notebook requires Python 3.8+ and PyTorch 1.18+, CUDA support is highly recommended.

---

## License

This project is released under the MIT License.