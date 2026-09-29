# Automated Titanic EDA with ydata-profiling

This repository demonstrates how to perform quick, automated Exploratory Data Analysis (EDA) using the `ydata-profiling` library. The script loads the classic Titanic dataset via Seaborn and automatically outputs an interactive, comprehensive HTML summary report.

## Features
* **Automated Data Profiling:** Replaces hours of manual matplotlib/seaborn plotting with a single line of code.
* **Comprehensive Metrics:** Generates data type checks, missing value alerts, descriptive statistics, quantile summaries, and high-correlation flags.
* **HTML Export:** Consolidates all metrics, distributions, and interactive heatmaps into a shareable standalone web report (`titanic.html`).

## Prerequisites & Installation
Ensure you are using Python 3.12+ (as verified in the provided conda environment). Install the necessary data analysis and profiling tools using pip:

```bash
pip install pandas numpy matplotlib seaborn ydata-profiling
```

## How to Run
1. Open the Jupyter Notebook environment.
2. Run the cells sequentially:
   * **Cell 1 & 2:** Install and import `ydata-profiling`, `pandas`, and `seaborn`.
   * **Cell 3:** Load the Seaborn-native Titanic dataframe.
   * **Cell 4:** Generate the `ProfileReport` and export the final output directly to a standalone webpage called `titanic.html` in your current working directory.
