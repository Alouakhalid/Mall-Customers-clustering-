# Customer Segmentation Project

This project performs customer segmentation using various clustering algorithms on the Mall Customers dataset.

## Project Structure

- `main.ipynb`: Jupyter notebook containing the code for data analysis and clustering.
- `Mall_Customers.csv`: Dataset containing customer information.

## Dependencies

- pandas
- numpy
- seaborn
- scikit-learn
- matplotlib

## Usage

1. Install the required dependencies:
    ```sh
    pip install pandas numpy seaborn scikit-learn matplotlib
    ```

2. Open `main.ipynb` in Jupyter Notebook or Jupyter Lab.

3. Run the cells in the notebook to perform data analysis and clustering.

## Dataset

The dataset contains the following columns:
- `CustomerID`: Unique ID for each customer
- `Gender`: Gender of the customer
- `Age`: Age of the customer
- `Annual Income (k$)`: Annual income of the customer in thousands of dollars
- `Spending Score (1-100)`: Spending score assigned to the customer based on their behavior and spending nature

## Clustering Algorithms Used

- KMeans
- Agglomerative Clustering
- DBSCAN
- Gaussian Mixture
- MeanShift
- Spectral Clustering
- OPTICS
- Birch
- AffinityPropagation

## Visualization

The project includes visualizations such as box plots, count plots, and scatter plots to analyze the clustering results.

## Example

Example of a box plot showing annual income by cluster:
```python
sns.boxplot(x=data.Kmeans, y=data['Annual Income (k$)'], palette="Set2")
plt.title('Annual Income by Cluster')
plt.show()
