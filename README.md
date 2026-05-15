<a id="readme-top"></a>

<div align="center">

# Cancer Type Prediction

![GitHub Repo Badge](https://img.shields.io/badge/github-repo-blue?logo=github)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)
[![Python 3.10+](https://img.shields.io/badge/python-3.10%2B-blue.svg?logo=python&logoColor=white)](https://www.python.org/)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)

This project aims to build a deep-learning model that predicts cancer types from gene-expression profiles using RNA-seq data from The Cancer Genome Atlas (TCGA). It is done within the scope of the Deep Learning course of the ZHAW ACLS Master.



</div>

## Table of Contents

- [Cancer Type Prediction](#cancer-type-prediction)
	- [Table of Contents](#table-of-contents)
	- [About](#about)
	- [Project Structure](#project-structure)
	- [Getting Started](#getting-started)
		- [Prerequisites](#prerequisites)
		- [Installation](#installation)
	- [Usage](#usage)
	- [Roadmap](#roadmap)
		- [Authors](#authors)
	- [License](#license)

## About

Gene-expression signatures capture the activity of thousands of genes simultaneously and different cancers exhibit distinct molecular patterns that can be learned by machine-learning models. Accurate cancer classification from expression data is clinically relevant because it can support the diagnosis, reveal the underlying biology and potentially guide treatment decisions.

This project's idea is to use neural networks for cancer classification, a well-established approach in the literature.

[Back to top](#readme-top)

## Goals

- Represent a TCGA sample as a high-dimensional vector of gene-expression values
- Exploratory data analysis for  understanding the structure of the dataset:
    - normalization
    - variance filtering
    - dimensionality reduction (PCA) 
- Design and experiment with feed-forward neural network (FNN)
- Evaluate performance

[Back to top](#readme-top)

## Project Structure


```text
.
├── documentation/    # Documentation for the application
├── src/              # Source code of the application
├── .gitignore        # Rules for excluding local, generated, and environment-specific files from Git
├── LICENSE           # License for this repository
└── README.md         # Project documentation, setup, and usage instructions
```

[Back to top](#readme-top)

## Getting Started

### Prerequisites

- Git
- Python 3.10+
- Jupyter Notebook

### Installation

```sh
git git@github.com:the-nerd-sloth/dl-cancer-prediction.git
cd dl-cancer-prediction
```

[Back to top](#readme-top)

## Usage

- Follow the Installation instructions.
- Run it.

[Back to top](#readme-top)

### Authors

- **Triantafyllia Giora**
	- GitHub: [@triantafylliagiora](https://github.com/triantafylliagiora)
- **Spyridon Margomenos**
	- Github: [@the-nerd-sloth](https://github.com/the-nerd-sloth)

[Back to top](#readme-top)

## License
Distributed under The MIT license.
For more information see `LICENSE`.

[Back to top](#readme-top)
