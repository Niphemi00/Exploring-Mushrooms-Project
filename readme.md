# Mushroom Data Visualization & Profiling

This project performs **exploratory data analysis (EDA)** and **data profiling** on a dataset of mushrooms. It uses visualization tools like **Matplotlib** and **Seaborn** to generate charts, along with **Pandas Profiling**  for automated insights. The dataset includes categorical features describing various physical traits of mushrooms and whether they are edible or poisonous.

---

##  Project Structure

mushroom-analysis/
│
├── Exploring Mushrooms.ipynb 
├── nifeplot.png # Example visualization output (23 subplots)
├── mushroom_data.csv # Mushroom dataset (UCI format)
├── requirements.txt 
└── README.md 


---

##  Dataset Overview

The dataset includes over 8,000 samples of mushrooms with the following features:

- **class, edible or poisonous**
- **cap-shape, cap-surface, cap-color**
- **bruises, odor, gill-attachment, gill-spacing, gill-size, gill-color**
- **stalk-shape, stalk-root, stalk-surface-above/below-ring, stalk-color-above/below-ring**
- **veil-type, veil-color**
- **ring-number, ring-type**
- **spore-print-color**
- **population, habitat**

---
## install required packages
pip install -r requirements.txt


## How to Run the Project
You can run the visualizations and profiling in one of two ways:

Option 1: Interactive Notebook
    Open mushroom_profiling.ipynb and run all cells to:

    Generate 23 subplots (bar or pie depending on category count)

    Create an automatic profiling report

    Save/export findings

Option 2: Python Script (Fast)
    Run the script to generate and display plots:
    "python mushroom_visualization.py"


## Features

1. 23 bar charts or pie charts depending on category count

2. Consistent and colorful 5x5 subplot grid for space efficiency

3. Automated profiling report with warnings, duplicates, distributions

4. Easy to customize colors with Seaborn palettes

5. Ideal for discovering trends in mushroom morphology


## 🔧 Setup Instructions

1. **Clone the Repository**

```bash
git clone https://github.com/Niphemi00/Exploring-Mushrooms-Project.git
cd mushroom-analysis
```
## Useful Resources

Seaborn Docs: https://seaborn.pydata.org

Pandas Profiling: https://github.com/ydataai/ydata-profiling

👩🏽‍💻 Author
Joshua Ikem – Data Enthusiast, Developer, or Researcher
Email: niphemijoshua@gmail.com
GitHub: @Niphemi00