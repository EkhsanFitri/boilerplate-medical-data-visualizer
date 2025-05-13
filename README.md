# Medical Data Visualizer

This project is part of the freeCodeCamp Data Analysis with Python curriculum.

## Project Description

You will visualize and make calculations from medical examination data using `matplotlib`, `seaborn`, and `pandas`. The dataset contains information collected during medical examinations, such as body measurements, blood test results, and lifestyle choices. The goal is to explore the relationship between cardiovascular disease and various health/lifestyle factors.

## Features

- **BMI Calculation:** Adds an `overweight` column based on BMI.
- **Data Normalization:** Cholesterol and glucose values are normalized to binary (0 = good, 1 = bad).
- **Categorical Plot:** Visualizes counts of good/bad outcomes for several features, split by cardiovascular disease status.
- **Heatmap:** Shows the correlation matrix of the cleaned dataset.

## Files

- `medical_examination.csv` - The dataset.
- `medical_data_visualizer.py` - Main code for data processing and visualization.
- `main.py` - Entrypoint for running the visualizations and tests.
- `test_module.py` - Unit tests for the project.

## Usage

1. Install dependencies:
    ```
    pip install pandas matplotlib seaborn
    ```
2. Run the main script to generate plots and run tests:
    ```
    python [main.py](http://_vscodecontentref_/0)
    ```
3. The following files will be generated:
    - `catplot.png`
    - `heatmap.png`

## Testing

Unit tests are provided in `test_module.py` and are run automatically by `main.py`.

## Resources

- [Project Instructions](https://www.freecodecamp.org/learn/data-analysis-with-python/data-analysis-with-python-projects/medical-data-visualizer)
- [Python for Everybody Video Course](https://www.youtube.com/watch?v=8DvywoWv6fI)
- [How to Analyze Data with Python Pandas](https://www.youtube.com/watch?v=vmEHCJofslg)

---
This project is part of the freeCodeCamp Data Analysis with Python certification.
