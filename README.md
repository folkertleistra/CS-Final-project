# CS-Final-project
Word Sense Disambiguation using GlossBERT on the PMB dataset

This project contains two directories: `jupyter` and `data`.

## jupyter
This directory contains all the Jupyter notebooks that were used to extract/inspect the data and build the models.

## data
This directory contains the data used in the project, divided into two folders:
- `only_sns` - contains the raw PMB data
- `processed` - contains the data in the Weak Supervision Context-Gloss pairs

The data in the ``only_sns`` folder was obtained by running the following command on the PMB 4.0.0 dataset:

`python3 src/extract_conll.py en data test_dir -j statuses.json -ls sns:g `

Running this command extracts the gold english data in combination with their annotated senses.

### Usage
We recommend running this project in Google Colab.

All required dependecies are installed in the notebooks.

### Contributors

- Folkert Leistra
- Milan van Wouden
- Xi Yu

