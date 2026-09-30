# PGMCR

This repository accompanies the manuscript **“PGMCR: Polarity-Guided Multimodal Consistency Regularization with Reliability Fusion for Multimodal Sentiment Analysis.”** The project studies multimodal sentiment analysis on CMU-MOSI and CMU-MOSEI.

**Repository:** [https://github.com/Guojy-julia/PGMCR](https://github.com/Guojy-julia/PGMCR)

## Data

The experiments use the pre-extracted, non-aligned visual and acoustic features and sentiment labels provided with CMU-MOSI and CMU-MOSEI. The benchmark datasets are maintained by their original providers. Download links for the files used in this project will be added here:

- **CMU-MOSI:** `https://drive.google.com/drive/folders/1i3q1NX9_c2lgdeZevtRs6K029B-CwowL?usp=drive_link`
- **CMU-MOSEI:** `https://drive.google.com/drive/folders/1pFH9osugmlZVXfyTEFgXfdgMb9pfUOeq?usp=drive_link`

## Dataset Files Used

These are the minimum files needed to run the current experiments:

```text
datasets/MOSI/train.pkl
datasets/MOSI/dev.pkl
datasets/MOSI/test.pkl
datasets/MOSEI/train.pkl
datasets/MOSEI/dev.pkl
datasets/MOSEI/test.pkl
```
- MOSI and MOSEI use the benchmark-provided train, development, and test splits.

## Code Status

The code is being organized for public release and will be added to this repository in a subsequent update. The current repository page provides the project and data-file documentation.

## Citation

Please cite the associated manuscript when using this project. Full bibliographic information will be added after publication.
