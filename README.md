# Netflix Movie Duration Analysis

A data analysis project exploring Netflix movie durations and trends using Python, pandas, and matplotlib.

## Overview

This project investigates whether movie durations on Netflix have been decreasing over time. The analysis uses Netflix's dataset to explore trends in movie lengths from 2011-2020, filtering and visualizing the data to understand patterns in content duration.

## Dataset

The project uses two CSV files located in the `datasets/` directory:

- **netflix_data.csv**: Contains information about Netflix shows and movies including:
  - `show_id`: Unique identifier
  - `type`: Movie or TV Show
  - `title`: Title of the content
  - `director`: Director name
  - `cast`: Cast members
  - `country`: Country of origin
  - `date_added`: Date added to Netflix
  - `release_year`: Year of release
  - `duration`: Duration (minutes for movies, seasons for TV shows)
  - `description`: Content description
  - `genre`: Genre classification

- **color_data.csv**: Supporting data for visualization

## Analysis Steps

The notebook follows a structured data analysis workflow:

1. **Loading Data into a Dictionary**: Initial data exploration using Python dictionaries
2. **Creating a DataFrame**: Converting data to pandas DataFrame for easier manipulation
3. **Visual Inspection**: Creating line plots to visualize trends over time
4. **Loading Full Dataset**: Reading the complete Netflix dataset from CSV
5. **Filtering for Movies**: Subsetting data to focus only on movies (excluding TV shows)
6. **Creating Scatter Plots**: Visualizing movie durations across years
7. **Deeper Analysis**: Investigating patterns and outliers in the data
8. **Marking Non-Feature Films**: Identifying and categorizing different types of content
9. **Color-Coded Visualization**: Creating enhanced plots with genre-based color coding
10. **Conclusions**: Summarizing findings about movie duration trends

## Key Technologies

- **Python 3**: Primary programming language
- **pandas**: Data manipulation and analysis
- **matplotlib**: Data visualization and plotting

## Getting Started

### Prerequisites

```bash
pip install pandas matplotlib jupyter
```

### Running the Analysis

1. Clone this repository:
```bash
git clone https://github.com/C-Thayer/Netflix_DataCamp.git
cd Netflix_DataCamp
```

2. Launch Jupyter Notebook:
```bash
jupyter notebook notebook.ipynb
```

3. Run all cells sequentially to reproduce the analysis

## Key Findings

The analysis explores whether movies are getting shorter on Netflix. The conclusion indicates that while there are observable patterns, the trend is not uniformly consistent across the years analyzed (2011-2020), making it difficult to make a definitive statement about decreasing movie lengths.

## Project Structure

```
Netflix_DataCamp/
├── notebook.ipynb          # Main Jupyter notebook with analysis
├── datasets/
│   ├── netflix_data.csv    # Netflix content dataset
│   └── color_data.csv      # Visualization support data
└── README.md               # This file
```

## Contributing

This is a DataCamp project for educational purposes. Feel free to fork and extend the analysis with your own insights!

## Acknowledgments

- Dataset provided by DataCamp
- Netflix for making their catalog data available for analysis
