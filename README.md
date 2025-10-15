# PySpark-Movielens-Data-Analysis

## Project Overview
This project analyzes the MovieLens dataset using PySpark to extract meaningful insights about movie ratings and user behavior. The analysis is implemented in a Jupyter notebook and utilizes PySpark for distributed data processing.

## Dataset
- **Source**: [MovieLens Dataset](https://grouplens.org/datasets/movielens/)
- **Description**: The dataset contains movie ratings and tagging data from the MovieLens website. It includes:
  - `ratings.csv`: User ratings for movies
  - `movies.csv`: Movie information including titles and genres
  - `tags.csv`: User-generated tags for movies

## Setup Instructions

### Prerequisites
- Python 3.7+
- Java 8 or later (required for PySpark)
- Jupyter Notebook or JupyterLab
- pip (Python package manager)

### Installation
1. Clone the repository:
   ```bash
   git clone [<repository-url>](https://github.com/Ruudra1/PySpark-Movielens-Data-Analysis.git)
   cd PySpark-Movielens-Data-Analysis
   ```

2. Create and activate a virtual environment (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install the required packages:
   ```bash
   pip install pyspark pandas matplotlib seaborn jupyter
   ```

4. Download the MovieLens dataset and place it in the project directory.

## Running the Analysis

1. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

2. Open `MovieLens_Data_Analysis_PySpark.ipynb` in your browser.

3. Run the notebook cells sequentially to execute the analysis.

## Project Insights

The analysis provides the following key insights:

### 1. Genre Popularity Analysis
- **Objective**: Identify the most popular movie genres based on user ratings
- **Method**: Analyze the distribution of ratings across different genres
- **Business Value**: Helps in understanding viewer preferences and can inform content recommendation and production decisions

### 2. Rating Trends Over Time
- **Objective**: Examine how user ratings have changed over time
- **Method**: Analyze the number and distribution of ratings across different years
- **Business Value**: Reveals temporal patterns in user engagement and can help identify trends in movie quality or user behavior

### 3. User Rating Patterns
- **Objective**: Understand how users rate movies (rating distribution)
- **Method**: Analyze the frequency of different rating scores
- **Business Value**: Provides insights into user rating behavior and can help identify potential biases in the rating system

## Output Files
The notebook generates the following output files:
- `insight1_genre_ratings.png`: Visualization of genre popularity
- `insight2_ratings_trend.png`: Visualization of rating trends over time
- `insight3_rating_distribution.png`: Visualization of rating distribution

## Dependencies
- PySpark 3.5.0
- pandas
- matplotlib
- seaborn
- jupyter

## Author
Ruudra Patel

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
