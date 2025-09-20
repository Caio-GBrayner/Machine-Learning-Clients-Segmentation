<div align="center">

<h1 align="center">Client Segmentation with K-Means Clustering</h1>

<p align="center">
    <strong>Technology study using scikit-learn</strong>
</p>

[![en](https://img.shields.io/badge/lang-en-red.svg)](./README.md)

</div>

## Table of Contents

- [Project Description](#table-of-contents)
- [About](#about)
- [Installation](#installation)
- [Technologies Used](#technologies-used)
- [License](#license)
- [Contact](#contributing)

## Project Description

This project utilizes unsupervised machine learning, specifically the K-Means clustering algorithm, to perform customer segmentation. The goal is to identify and group customers with similar purchasing behaviors, demographics, or other attributes into distinct clusters. This segmentation provides valuable insights for targeted marketing strategies, personalized product recommendations, and improved customer relationship management.

## About

1. **Data Loading and Exploration:** The initial phase involves loading the client data and performing an exploratory data analysis to understand its structure, identify missing values, and check for outliers.
2. **Data Preprocessing:** The data is prepared for the clustering algorithm by handling categorical variables and scaling numerical features to ensure that each feature contributes equally to the clustering process. The `StandardScaler` from scikit-learn is used for this step.
3. **K-Means Clustering:** The K-Means algorithm is applied to the preprocessed data. The optimal number of clusters (`k`) is determined using a technique like the Elbow Method to achieve the best segmentation.
4. **Analysis and Interpretation:** The resulting clusters are analyzed to understand the unique characteristics of each customer segment. This includes examining the average values of key features within each cluster to create a profile for each segment.


## Installation

To run this project, you need to have Python installed. The required libraries can be installed using `pip`. It is recommended to create a virtual environment first.

1. Clone the repository

```bash
git clone https://github.com/Caio-GBrayner/https://github.com/Caio-GBrayner/Machine-Learning-Clients-Segmentation
```

2. Create and activate a virtual environment (recommended):

```bash
python -m venv venv
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

## Usage

- To run the notebook:

```bash
jupyter notebook
```
(Or `jupyterLab` if applicable)

- Navigate to the main notebook (e.g., **altair.ipynb**) and execute the cells to see the code and visualizations.

## Technologies Used

- **Python:** The core programming language used for the project.

- **pandas:** For efficient data manipulation and analysis, primarily using `DataFrame` objects.

- **numpy:** For numerical operations and array handling.

- **scikit-learn:** A robust machine learning library that provides the `KMeans` clustering algorithm and the `StandardScaler` for data preprocessing.

## License

This project is licensed under the MIT [License](LICENSE). See the LICENSE file for more details.

## Contact

- Caio Gomes Brayner
- Caio Brayner [LinkedIn](https://www.linkedin.com/in/caiogomesbrayner).
- E-mail: caiogomesbrayner@outlook.com