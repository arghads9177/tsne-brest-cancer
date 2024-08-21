# t-SNE of Breast Cancer Data

## About the Dataset

This project uses the GSE45827 dataset from the Curated Microarray Database (CuMiDa), which contains breast cancer gene expression data. The dataset includes:

- **6 Classes**: Different types of breast cancer and healthy tissue.
- **54,676 Genes**: Gene expression levels measured across samples.
- **151 Samples**: Each row represents a sample, and each column represents a gene.

### Dataset Source

CuMiDa is a carefully curated repository containing 78 cancer microarray datasets specifically designed for machine learning research. These datasets have been selected from over 30,000 studies in the Gene Expression Omnibus (GEO) and have undergone extensive biological preprocessing, including background correction and normalization, to ensure data reliability.

The GSE45827 dataset, like others in CuMiDa, is intended to serve as a reliable source for computational research, providing preprocessed data along with benchmark results for machine learning studies in cancer research. The dataset is available in various formats, including CSV, TAB, and ARFF, and also includes PCA and t-SNE results.

More details and the dataset are available at the official CuMiDa website under the ID GSE45827: [CuMiDa - GSE45827](http://sbcb.inf.ufrgs.br/cumida).

## Project Overview

This project focuses on applying t-SNE (t-distributed Stochastic Neighbor Embedding), a machine learning technique for dimensionality reduction, to visualize the gene expression data from the GSE45827 dataset. The goal is to represent the high-dimensional gene expression data in a 2D space, making it easier to observe patterns and similarities between different types of breast cancer.

## Project Structure

The project is organized as follows:

- `data/`: Contains the GSE45827 dataset in CSV format.
- `notebooks/`: Jupyter notebooks for data exploration, t-SNE application, and visualization.
- `visualizations/`: Contains the t-SNE visualizations of the gene expression data.
- `README.md`: Project overview and documentation.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/breast-cancer-tsne.git

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Contact

For any questions or inquiries, please contact **Argha Dey Sarkar** at `email2argha@gamail.com`.
