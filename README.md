# Earthquake Data Analysis

## Description

This project involves analyzing earthquake data from a CSV file. The data includes information such as latitude, longitude, type of earthquake, depth, magnitude, and date/time of occurrence.

## Installation

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/your_username/earthquake-data-analysis.git
    ```

2. Install the required Python packages:

    ```bash
    pip install pandas matplotlib numpy
    ```

## Usage

1. Ensure you have Python installed on your system.
2. Navigate to the project directory.
3. Run the Python script `earthquake_analysis.py`:

    ```bash
    python earthquake_analysis.py
    ```

4. The script will load the earthquake data from the CSV file, perform various analyses, and generate visualizations.

## Data Preprocessing

- The script reads the earthquake data from the CSV file using Pandas.
- Date and time columns are converted to datetime objects and combined into a single column.
- Depth values are categorized into depth categories (e.g., Very Shallow, Shallow, Deep, etc.).

## Data Analysis

- Various analyses are performed on the earthquake data, including descriptive statistics and visualization.
- Analyses include generating line charts, bar charts, scatter plots, and histograms to visualize relationships and distributions within the data.

## Conclusion

This project provides insights into earthquake occurrences based on the provided dataset. Further analyses and visualizations can be performed as needed.
