# Cyber Attack Classification - Model

This repo contains all notebooks related to model training for predicting the type of cyber attack.

## Model

The exported file contains a wrapper object with an attached scikit-learn pipeline model. This wrapper also stores information about the base features and their expected values, which were used to generate the derived features during training. This feature information aids external users in understanding the model, especially in cases where derived features may be unclear without insights into the training process.

For an example project utilizing this model, visit the [cyberattack-app](https://github.com/dominicbraam/cyberattack-app) project.

## Setup

1. Create a virtual environment for this project with `conda env create -f environment.yml`. If you make changes in the environment.yml, you can update your local environment with `conda env update --file environment.yml --prune`.
2. Run the jupyter notebook with `jupyter notebook`.

## Datasets

There are 4 datasets expected. Place them in the `data/` directory:

- [Cyber Security Attacks](https://www.kaggle.com/datasets/teamincribo/cyber-security-attacks)
- [ip-to-country-lite](https://db-ip.com/db/download/ip-to-country-lite)
- [ip-to-asn-lite](https://db-ip.com/db/download/ip-to-asn-lite)
- `top-30000-most-popular-tcp-ports-nmap-sorted.csv` from the github repo: [https://github.com/HeckerBirb/top-nmap-ports-csv](https://github.com/HeckerBirb/top-nmap-ports-csv)
