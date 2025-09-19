# Traffic Accident Analysis Project

## 📖 Overview

This project involves an in-depth exploratory data analysis (EDA) of a traffic accident dataset. The primary goal is to uncover patterns, identify key contributing factors to accidents, and visualize these findings to make them understandable. This analysis serves as a foundational step for further investigation and predictive modeling.

This notebook is ideal for data science students and enthusiasts looking for a practical example of data cleaning, feature engineering, and visualization using popular Python libraries.

---

## 📊 Dataset

The dataset used in this analysis is `traffic accident.csv`, which contains detailed records of traffic incidents. Each row represents a single accident and includes a variety of features, such as:

* **Date and Time:** `crash_date`, `crash_hour`, `crash_day_of_week`
* **Conditions:** `weather_condition`, `lighting_condition`, `roadway_surface_cond`
* **Accident Details:** `first_crash_type`, `prim_contributory_cause`
* **Outcome:** `most_severe_injury`, `injuries_total`, `damage`

---

## 🔬 Analysis Workflow

The analysis in the Jupyter Notebook (`Untitled.ipynb`) follows a structured data science workflow:

1.  **Project Setup**: Importing essential libraries including Pandas, NumPy, Matplotlib, and Seaborn.
2.  **Data Loading & Inspection**: Loading the dataset and performing an initial review using `.head()`, `.info()`, and `.describe()` to understand its structure and identify missing values.
3.  **Data Cleaning & Preprocessing**:
    * Converting the `crash_date` column from a string to a proper `datetime` object.
    * **Feature Engineering**: Extracting valuable information like `crash_month`, `crash_day_of_week`, and `crash_hour` from the `crash_date`.
4.  **Exploratory Data Analysis (EDA)**:
    * **Univariate Analysis**: Creating bar charts and histograms to visualize the distribution of key variables like weather conditions, lighting conditions, and the hour of the day.
    * **Bivariate Analysis**: Using heatmaps to explore the relationship between two variables, such as the number of accidents by the day of the week and the hour.
    * **Multivariate Analysis**: Generating a correlation matrix to understand the linear relationships between all numerical features in the dataset.

---

## ✨ Key Visualizations & Insights

This notebook generates several key visualizations to uncover insights from the data:

* **Distribution Plots**: Bar charts showing the most common weather and lighting conditions during accidents.
* **Hourly Accident Trends**: A histogram revealing the peak hours for traffic accidents during a typical day.
* **Weekly Heatmap**: A heatmap that clearly illustrates the riskiest times, pinpointing specific days and hours with high accident frequencies.
* **Correlation Matrix**: A heatmap that displays the correlation coefficients between numerical variables, helping to identify which factors are statistically related.

---

## 🛠️ Technologies Used

* **Python 3**
* **Pandas**: For data manipulation and analysis.
* **NumPy**: For numerical operations.
* **Matplotlib**: For creating foundational plots and charts.
* **Seaborn**: For advanced statistical data visualization.
* **Jupyter Notebook**: For interactive coding and analysis.

---

## 🚀 How to Use

To run this analysis on your own machine, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone <your-repository-url>
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd <your-project-directory>
    ```
3.  **Install the required libraries:**
    ```bash
    pip install pandas numpy matplotlib seaborn jupyter
    ```
4.  **Launch Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
5.  Open the `Untitled.ipynb` file and run the cells.

**Note:** Ensure the `traffic accident.csv` file is in the same directory as the notebook.

---

## 📫 Contact

Created by **Vineet Kumar Chaudhary** - feel free to reach out!

* **📧Email**: [chaudharyvineet730@gmail.com](mailto:chaudharyvineet730@gmail.com)
* **🚀GitHub**: `https://github.com/curiouschaudhary` 

If you have any questions, find a bug, or would like to collaborate on a project, please don't hesitate to get in touch.
