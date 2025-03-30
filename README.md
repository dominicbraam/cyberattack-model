# ml-proj-model-development

This repo contains all notebooks and files related to model development, including but not limited to data exploration, data cleaning, feature extraction, and model training.

## Setup

1. Create a virtual environment `conda env create -f environment.yml`. If changes were made in the environment.yml, you can update your local environment `conda env update --file environment.yml --prune`.
2. Run jupyter notebook with `jupyter notebook`.

## External Datasets

There are 3 external datasets that the notebooks expect. Please add them to the `data/` directory:

- [ip-to-country-lite](https://db-ip.com/db/download/ip-to-country-lite)
- [ip-to-asn-lite](https://db-ip.com/db/download/ip-to-asn-lite)
- `top-30000-most-popular-tcp-ports-nmap-sorted.csv` from the github repo: [https://github.com/HeckerBirb/top-nmap-ports-csv](https://github.com/HeckerBirb/top-nmap-ports-csv)
