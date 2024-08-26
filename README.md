# Customer Segmentation using K-Means Clustering

## Overview
Customer segmentation is a powerful technique that allows businesses to divide their customer base into distinct groups based on various characteristics and behaviors. This project leverages K-Means clustering, a popular unsupervised machine learning algorithm, to segment customers and uncover actionable insights that can help in crafting targeted marketing strategies.

## Table of Contents
- [Project Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

## Dataset
The dataset contains various features that describe customer preferences, behaviors, and demographics, including:

- **yummy**: Indicates if the product is perceived as yummy (Yes/No).
- **convenient**: Indicates if the product is perceived as convenient (Yes/No).
- **spicy**: Indicates if the product is perceived as spicy (Yes/No).
- **fattening**: Indicates if the product is perceived as fattening (Yes/No).
- **greasy**: Indicates if the product is perceived as greasy (Yes/No).
- **fast**: Indicates if the product is perceived as fast (Yes/No).
- **cheap**: Indicates if the product is perceived as cheap (Yes/No).
- **tasty**: Indicates if the product is perceived as tasty (Yes/No).
- **expensive**: Indicates if the product is perceived as expensive (Yes/No).
- **healthy**: Indicates if the product is perceived as healthy (Yes/No).
- **disgusting**: Indicates if the product is perceived as disgusting (Yes/No).
- **Like**: A numeric rating of the product on a scale from negative to positive.
- **Age**: The age of the customer.
- **VisitFrequency**: The frequency with which the customer visits or uses the product/service.
- **Gender**: The gender of the customer (Male/Female).

## Installation
To get started with this project, clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/chandkund/customer-segmentation.git
cd customer-segmentation
pip install -r requirements.txt
```

Ensure you have Python 3.x and all the required libraries installed.

## Usage
You can run the segmentation analysis by executing the main Python script:

```bash
python customer_segmentation.py
```

This will load the dataset, perform data preprocessing, apply K-Means clustering, and output the results.

### Key Features
- **Data Preprocessing**: Cleans and prepares the data for analysis.
- **K-Means Clustering**: Segments the customer base into distinct groups.
- **Visualization**: Provides visual representations of the clusters.

## Results
The project outputs various insights, including:
- Identification of key customer segments.
- Visualization of clusters based on different customer characteristics.
- Recommendations for targeted marketing strategies based on segment analysis.

Example visualizations and detailed findings are available in the `results/` directory.

.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
