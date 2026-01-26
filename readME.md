# Laboratory Activities for Statistics with Python

A collection of hands-on laboratory activities designed to teach Statistics using Python through practical, real-world data analysis.

This repository is built for students who want to actually understand statistics and the coding fundamentals behind them, not just memorize formulas.

---

## Repository Structure

### The Labs
The activities follow a progression from Python basics to statistical application:

| Lab | File Name | Key Concepts |
| :--- | :--- | :--- |
| **01** | `Lab-1-lists-and-tuples.ipynb` | **Python Basics:** Handling data structures, list manipulation, and tuple immutability. |
| **02** | `Lab-2-for-Loop.ipynb` | **Control Flow:** Iterating through data sequences and automating calculations. |
| **03** | `Lab-3-numpy-basics.ipynb` | **Numerical Computing:** Introduction to NumPy arrays, broadcasting, and vectorization. |
| **04** | `Lab-4-pandas-basics.ipynb` | **Data Manipulation:** Loading CSVs, DataFrames, cleaning data, and basic exploratory analysis. |
| **05** | `Lab-5-correlation.ipynb` | **Statistical Relationships:** Measuring the strength of relationships between variables (Pearson/Spearman). |
| **06** | `Lab-6-standard-normal-distribution.ipynb` | **Probability:** Understanding the Bell Curve, Z-scores, and probability density. |

### The Datasets
Located in the `dataset/` directory, these real-world CSV files are used throughout the labs:

* **Environmental:** `air-quality.csv`
* **Energy:** `current-power.csv`, `current-test.csv`, `transformer-voltage.csv`
* **Retail/Inventory:** `shoe-inventory.csv`

---

## Tech Stack

* **Python 3.9+**
* **Jupyter Notebook**
* **Core Libraries:**
    * `numpy` (Math & Arrays)
    * `pandas` (Data Handling)
    * `matplotlib` & `seaborn` (Visualization)
    * `scipy` (Scientific Computing)

---

## Getting Started

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/12valor/Statistics.git](https://github.com/12valor/Statistics.git)
    cd Statistics
    ```

2.  **Install dependencies**
    ```bash
    pip install numpy pandas matplotlib scipy seaborn jupyter
    ```

3.  **Launch Jupyter Notebook**
    ```bash
    jupyter notebook
    ```