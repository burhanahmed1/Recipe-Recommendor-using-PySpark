# Recipe Recommendation System

This repository contains a recipe recommendation system that utilizes machine learning techniques to suggest recipes based on ingredient similarities. The system is built using a Jupyter notebook and a dataset of recipes.

## Repository Structure

- **Recommendor.ipynb**: Jupyter notebook containing the code for the recipe recommendation system. This notebook includes:
  - Data loading and preprocessing.
  - Feature extraction using ingredient lists.
  - Calculation of cosine similarities between recipes to generate recommendations.

- **recipes_combined_dataset.csv**: Dataset containing 9,999 recipes with their ingredients. The columns in this dataset include:
  - `recipeNames`: Names of the recipes.
  - `ingredients`: Ingredients for each recipe.
  - `all_ingredients`: A consolidated list of all ingredients for each recipe.
  - Several unnamed columns with additional ingredient information.

## Installation

To run the Jupyter notebook and explore the recommendation system, you will need the following dependencies:

- Python
- Jupyter Notebook
- pandas
- numpy
- scikit-learn
- nltk

## Usage
1. Clone the repository:
```bash
git clone https://github.com/burhanahmed1/Recipe-Recommendor-using-PySpark.git
cd recipe-recommendation-system
```
2. Open the Jupyter notebook:
```bash
jupyter notebook Recommendor.ipynb
```
3. Run the cells in the notebook to load the dataset, preprocess the data, and generate recipe recommendations.


## Dataset
The dataset used in this project is a collection of recipes with their ingredients. It contains 9,999 entries with the following columns:

+ `recipeNames:` The name of the recipe.
+ `ingredients:` A list of ingredients for the recipe.
+ `all_ingredients:` A concatenated string of all ingredients for easier processing.
Several unnamed columns with additional ingredient information.

## Project Overview
The main goal of this project is to develop a recommendation system that can suggest recipes based on ingredient similarities. By calculating cosine similarities between recipes, the system can identify and recommend recipes with similar ingredient profiles.

## License
This project is licensed under the MIT License.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue if you have any suggestions or improvements.

## Acknowledgments
Special thanks to the dataset providers and the open-source community for their valuable resources and tools.

