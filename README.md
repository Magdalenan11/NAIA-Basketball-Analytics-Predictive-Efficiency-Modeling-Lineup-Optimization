Engineering Victory: Predictive NAIA Efficiency Indexing & Mathematical Optimization
This repository integrates advanced mathematical modeling with a robust data engineering pipeline to evaluate and predict athletic performance. This project was developed as a collaborative partnership to modernize performance management for NAIA women’s basketball, translating raw box scores into a structured, predictive framework.

Technical Details

Languages & Core Libraries: Python (Pandas, NumPy, Scikit-Learn, SciPy).

Data Wrangling: Performed end-to-end "ETL" by converting raw historical records into a structured format. Utilized Regular Expressions (re) to programmatically clean and standardize 12 unique datasets, resolving formatting inconsistencies across multiple seasons.

Exploratory Data Analysis (EDA): Leveraged Seaborn and Matplotlib to conduct visual analysis. Engineered Correlation Heat Maps to identify metrics with the strongest relationship to the Player Efficiency Index (PEI) for data-driven feature selection.

Modeling & Optimization: Developed Linear Regression models to forecast performance and implemented Linear Programming (via linprog) to solve for mathematically ideal lineups under a 200-minute game constraint.

What's in this Repository

Magdalena_Vicencio_Final_Project.ipynb: The primary Python notebook. It contains the data ingestion logic, automated cleaning scripts, the PEI_40 Player Performance Simulator, and the lineup optimization code.

FINAL_PROJECT.xlsx: The core data engine. This file contains the cleaned datasets and complex statistical formulas used to calculate efficiency metrics like eFG%, USG%, and STOCKS.

Math_In_Sports_Presentation.pptx: A full presentation detailing the statistical validation of the Player Efficiency Index and its correlation with national tournament success.

Data_Methodology_Presentation.pptx: A technical presentation focusing on the architecture of the data pipeline and the software foundation for real-time coaching strategy tools.

Usage Instructions

Environment Setup: Ensure Python and the required libraries (Pandas, Seaborn, Scikit-Learn, SciPy) are installed.

File Placement: Download the .ipynb and .xlsx files into the same directory.

Path Configuration: In the notebook, ensure EXCEL_FILE_PATH = 'FINAL PROJECT.xlsx' is set to the local relative path.

Execution: Run all cells to generate the visual heat maps and launch the interactive performance simulator.

