# Transfer Learning Demo

This repo contains a demo of transfer-learning using Inception v3 and TensorFlow in a Jupyter notebook.

Much of the material is based on Google's Codelab [TensorFlow for Poets](https://codelabs.developers.google.com/codelabs/tensorflow-for-poets)

## Setup

Clone this repo via

```bash
git clone --recursive git://github.com/foo/bar.git
```

or if you've already downloaded it, you *need* to init submodules manually:

```bash
cd <repo>
git submodule update --init --recursive
```

### Python distribution

Install the [Miniconda](https://conda.io/miniconda.html) (or [Anaconda](https://www.anaconda.com/download/#macos)) Python distribution.
The code has been tested on Python 2.

Set up conda environment via `conda env create -n transfer-learning -f environment.yml`

### Dataset

The dataset-folder contains two folders:
"Train" should contain subfolders named after the class of images they contain;
"Test" should contain test images from multiple classes (not present in the training data".



You will need to build your dataset;

I just used [Fatkun Batch Download Image](https://chrome.google.com/webstore/detail/fatkun-batch-download-ima/nnjjahlikiabnchcpehcpkdeckfgnohf?hl=en) to handle batch downloading from Google image search results.

## Run 

Run the notebook:

```bash
# Activate our Python environment
source activate transfer-learning

# Start Jupyter and open the notebook
jupyter notebook
```

