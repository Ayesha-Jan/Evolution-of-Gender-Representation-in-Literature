# 📚 The Evolution of Gender Representation in Literature

This project explores the evolution of gender representation in published books using Goodreads data. Through exploratory data analysis and visual storytelling, we examine how the balance between male and female authorship has shifted over the past centuries.

---

## Features

- **Historical Trends (720BC–2019AD)**: Charts comparing number of books by male vs. female authors.
- **Animated Explainer**: A short visual summary of the gender shift.
- **Statistical Analysis**: Mean, median, skewness, correlation, ANOVA, and regression.
- **Visualizations**: 10 well-labeled figures exploring genre, ratings, author gender, and time trends.

### Tools & Technologies

- Python, Pandas, NumPy
- Plotly, Seaborn, Matplotlib
- Jupyter Notebook
- Canva (for infographic/animation polish)

---

## Project Structure:

### 1. Jupyter Notebook: `Visualisation.ipynb`

**Purpose:**  
Explore gender representation in literature over time using Goodreads data.

**Contents:**
- Importing libraries (`pandas`, `plotly`, `matplotlib`, `seaborn`)
- Cleaning and preprocessing the Goodreads dataset (`good_reads_final.csv`)
- Creating statistical summaries (mean, median, skewness, ANOVA, correlation)
- Generating visualizations (line charts, bar plots, histograms, boxplots)

**Output:**  
Cleaned dataset, visual insights, and saved plots in the `images/` folder used in both the report and animation.

### 2. Final Report: `The Evolution of Gender Representation in Literature.pdf`

**Purpose:**  
A structured exploratory data analysis report that answers key research questions about gender trends in book publishing.

**Contents:**
- Abstract, Introduction, Methods, Results, Discussions and Conclusions, and References
- Answers these research questions:
  1. Is there a gender disparity in the number of books published by male and female authors? 
  2. Do male and female authors prefer different genres, and if so, which genres?
  3. How do gender, genre, and publication date influence the popularity of books?
- Includes interpretations, statistical evidence, and visualizations

**Output:**  
A 15 page data report.

### 3. Animation Video: `Gender Evolution in Literature.mp4`

**Purpose:**  
A short animated explainer visualizing the rise of female authors in literature, showing a pivotal shift in the 2010s.

**Contents:**
- Animated line chart showing book counts by gender (1900–2019)
- Narrative of historical gender shift in publishing

**Output:**  
An engaging visual summary of the project, suitable for presentations or bonus material.

### 4. Visualizations Folder: `images/`

**Purpose:**  
Contains all visualizations generated from analysis.

**Output:**  
High-quality PNG/GIF figures used throughout the project.

### 5. Dataset: `good_reads_final.csv`

**Purpose:**  
The original reliable Goodreads dataset used for statistical analysis and visualization generation.

---

## Getting started

### Prerequisites

- Python 3.x  
- Jupyter Notebook or JupyterLab  
- Libraries: pandas, seaborn, matplotlib.pyplot, numpy, plotly.express, plotly.graph_objects, dateutil, statsmodels, scipy.stats, re, os, imageio

### Installation

1. **Clone the Repository**
   
   ```bash
   git clone https://github.com/Ayesha-Jan/Evolution-of-Gender-Representation-in-Literature.git
   cd gender-evolution-literature

2. **Install Dependencies**

   ```bash
   pip install pandas seaborn matplotlib numpy plotly python-dateutil statsmodels scipy imageio

### Running the Project

Jupyter Notebook:
Open and run Visualisation.ipynb

---

## Data Source

This project uses Goodreads data compiled from Kaggle: https://www.kaggle.com/datasets/brosen255/goodreads-books

## Author

Developed by: Ayesha A. Jan  
Email: Ayesha.Jan@stud.srh-campus-berlin.de  
🎓 BST Statistics Project – 2025
