# SARCropPhenoData

This repository provides the dataset preview and release information for **LoRA-RCB**.

The dataset is designed for **unsupervised SAR crop phenology discovery** from multi-temporal SAR image time series. The goal is to discover crop-related phenological prototypes from unlabeled SAR observations. Reference crop labels are used only for evaluation after clustering.

## Release Status

At the current review stage, this repository provides **VV-band SAR PNG quicklooks** for two regional datasets:

- `US_Illinois`
- `CA_Manitoba`

The complete processed dataset used in the experiments, including SAR feature tensors, valid-observation masks, reference labels, metadata files, VH quicklooks, and label quicklooks, will be released after the review process.

## Current Preview Release

The current repository contains:

```text
SARCropPhenoData/
├── README.md
├── US_Illinois/
│   └── png/
│       ├── US_Illinois_20210401_VV.png
│       ├── US_Illinois_20210416_VV.png
│       ├── ...
│       └── US_Illinois_20211028_VV.png
└── CA_Manitoba/
    └── png/
        ├── CA_Manitoba_20210401_VV.png
        ├── CA_Manitoba_20210416_VV.png
        ├── ...
        └── CA_Manitoba_20211013_VV.png
