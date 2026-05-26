# Cognify Restaurant Data Analysis

This project analyzes a restaurant dataset using Python, Pandas, and Matplotlib. The notebook explores cuisine popularity, restaurant distribution by city, and city-level aggregate ratings.

## Project Files

- `cognify.ipynb` - Jupyter Notebook containing the data analysis code.
- `Dataset .csv` - Restaurant dataset used by the notebook.

## Analysis Covered

The notebook currently performs the following tasks:

- Loads the restaurant dataset from `Dataset .csv`.
- Displays the first few records for inspection.
- Splits multi-cuisine entries and identifies the top 10 cuisines.
- Visualizes the top 10 cuisines using a bar chart.
- Calculates each top cuisine's percentage share.
- Counts restaurants by city.
- Finds the city with the highest number of restaurants.
- Calculates average aggregate rating by city.

## Requirements

Install the required Python packages:

```bash
pip install pandas matplotlib jupyter
```

## How to Run

1. Open the project folder.
2. Start Jupyter Notebook:

```bash
jupyter notebook
```

3. Open `cognify.ipynb`.
4. Run the notebook cells from top to bottom.

Make sure `Dataset .csv` remains in the same folder as `cognify.ipynb`, because the notebook reads it using this relative path:

```python
pd.read_csv("Dataset .csv")
```

## Dataset Columns

The dataset includes restaurant details such as:

- Restaurant name
- City and locality
- Cuisines
- Average cost for two
- Currency
- Table booking availability
- Online delivery availability
- Price range
- Aggregate rating
- Rating text
- Votes

## Output

The notebook prints summary tables and generates a bar chart showing the most common cuisines in the dataset.
