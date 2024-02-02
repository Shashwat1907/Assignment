# Analyzing Reviews and Converting to Parquet

This repository contains a Jupyter Notebook for analyzing a large dataset of restaurant reviews. The notebook uses Pandas and Numpy to perform various tasks, including identifying the least-rated and most-rated items and transforming the data. The final step involves saving the processed data into a Parquet file.

## Task Overview

1. **Dataset:**
   - The analysis is performed on a large dataset containing user reviews. The dataset includes columns such as `user_id`, `recipe_id`, `date`, `rating`, and `review`.

2. **Analysis Steps:**
   - The Jupyter Notebook performs the following key tasks:
     - Loading the dataset into a Pandas DataFrame.
     - Exploring the structure and content of the original DataFrame.
     - Transforming the date column to MM-DD-YYYY format.
     - Identifying the least-rated and most-rated items.
     - Extracting insights such as the item with the longest reviews.
     - Calculating average ratings for recipes.

3. **Saving to Parquet:**
   - The processed DataFrame is saved to a Parquet file for efficient storage and later use.

## Getting Started

1. **Clone the Repository:**
   - Clone this repository to your local machine using the following command:
     ```
     git clone https://github.com/your-username/your-repository.git
     ```

2. **Install Dependencies:**
   - Make sure you have Python, Jupyter Notebook, Pandas, and Numpy installed.
   - Install additional dependencies using:
     ```
     pip install pandas numpy
     ```

3. **Run the Jupyter Notebook:**
   - Open the Jupyter Notebook in your preferred environment.
   - Open the `Analysis.ipynb` notebook.
   - Run each cell in the notebook to perform the analysis step by step.

4. **Review Results:**
   - Check the notebook for insights generated during the analysis, such as least-rated, most-rated items, and other relevant information.

5. **Save to Parquet:**
   - The final DataFrame is saved to a Parquet file, providing a more efficient storage format compared to traditional CSV.

## Files and Directories

- **Analysis.ipynb:**
  - Jupyter Notebook containing the code for analyzing the reviews and saving to Parquet.

- **data/:**
  - Directory to store the original and processed datasets.

- **transformed_data.parquet:**
  - The Parquet file containing the processed data.


