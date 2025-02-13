# CustomerSegmentationAnalyzer

## Description
This project utilizes clustering techniques to create a machine learning model that segments customers into different groups to develop marketing strategies. The dataset includes customer IDs, annual income, spending scores, age, and preferred product categories. The goal is to identify distinct customer segments and analyze their characteristics to optimize marketing campaigns.

## Features
- Analyzes customer data, including age, income, and spending scores.
- Utilizes clustering techniques such as K-Means and hierarchical clustering.
- Reduces dimensionality using Principal Component Analysis (PCA) and Singular Value Decomposition (SVD) for visualization.
- Visualizes clusters with scatter plots and dendrograms.
- Provides statistical insights for each cluster to guide marketing strategies.

## Getting Started

### Prerequisites
Ensure you have the following software installed:
- Python 3.x
- Required Python libraries:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn
  - scipy
- Jupyter Notebook 7.x

## Data
The project uses a CSV file named customer_data.csv, which should be located in the same folder as the Jupyter notebook. The file contains the following columns:

- Customer ID: Unique identifier for each customer.
- Age: Customer’s age.
- Annual Income (k$): Customer’s yearly income in thousands of dollars.
- Spending Score (1-100): Score assigned based on purchasing behavior (higher score means higher spending tendency).
- Preferred Product Category: The product category most frequently purchased by the customer.

## Usage

1. Clone the repository or download the necessary files.
2. Ensure that the customer_data.csv file is in the same directory as the Jupyter notebook.
3. Open the Jupyter notebook and run the cells in order.
4. The code will perform the following actions:
   - Load the data from the CSV file.
   - Normalize the data using MinMaxScaler.
   - Apply PCA and SVD to reduce dimensions and visualize patterns.
   - Cluster the data using K-Means and hierarchical clustering.
   - Generate visualizations, including scatter plots and dendrograms.
   - Provide insights into customer segments with statistical summaries.

## Example
An example of how to run the analysis is available in the Jupyter notebook. Simply execute the cells one by one to see the results.

## Contributing
Contributions are welcome. If you would like to improve the project, please open an issue or a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for more information.

## Feel Free to Customize
You can further customize this README as needed. If there are specific steps you want to include in the Usage section.

## Acknowledgments
Thank you Fede.
