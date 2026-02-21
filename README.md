# Engineering Victory: Predictive NAIA Efficiency Indexing & Mathematical Optimization
This repository integrates advanced mathematical modeling with a robust data engineering pipeline to evaluate and predict athletic performance. The project focused on translating raw NAIA box scores into a structured, predictive framework to assist coaching staffs in real-time decision-making.

# Technical Details

  •  **Language & Libraries:** Python (Pandas, NumPy, Scikit-Learn, SciPy).

  •  **Data Wrangling:** Performed end-to-end "ETL" to convert raw records into a         structured format. Utilized Regular Expressions (re) to programmatically clean       and standardize 12 unique datasets, ensuring data integrity across inconsistent      seasonal formats.

  •  **Exploratory Data Analysis (EDA):** Leveraged Seaborn and Matplotlib to             conduct visual analysis. Engineered Correlation Heat Maps to identify metrics        with the strongest relationship to the Player Efficiency Index (PEI) for data-       driven feature selection.

  •  **Key Skills:** Linear Regression Modeling, Constrained Optimization (linprog), Feature Engineering, and Interactive Data Visualization.

# What's in this Repository

  •  'Magdalena_Vicencio_Final_Project.ipynb': This is the main file. It contains          the data ingestion logic, automated cleaning scripts, the PEI_40 Player             Performance Simulator, and the lineup optimization code.

  •  'FINAL_PROJECT.xlsx': The core data engine containing the cleaned datasets and        complex statistical formulas used to calculate efficiency metrics like eFG%,         USG%, and STOCKS.

  •  'Math_In_Sports_Presentation.pptx': A presentation detailing the statistical         validation of the Player Efficiency Index and its correlation with national          tournament success.

  •  'Data_Methodology_Presentation.pptx': A technical presentation focusing on the      architecture of the data pipeline and the software foundation for coaching          strategy tools.


-------------------------------------------------------------------------------------

# Usage Instructions

1. **File Placement:** Download the '.ipynb' and '.xlsx' files into the same            directory.

2. **Path Configuration:** In the notebook, ensure 'EXCEL_FILE_PATH = 'FINAL             PROJECT.xlsx'' is set to the local relative path.

3. **Execution:** Run all cells to generate the visual heat maps and launch the interactive performance simulator.

> **Note:** This project was developed to modernize performance management for NAIA women’s basketball. No private student-athlete data is included.
