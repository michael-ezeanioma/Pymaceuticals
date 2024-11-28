# Overview

This project analyzes a clinical study conducted by Pymaceuticals, Inc., a pharmaceutical company specializing in anti-cancer medications. The study investigated the effectiveness of several drug regimens, including Capomulin, on squamous cell carcinoma (SCC), a common form of skin cancer. The dataset includes tumor volume observations for 249 mice over 45 days. The analysis generates tables, charts, and statistical insights to support a technical report for the executive team.

# Objectives

__1. Prepare the Data:__
Merge mouse metadata and study results into a single dataset.
Identify and remove duplicate entries to ensure data integrity.
Verify the number of unique mice IDs in the cleaned dataset.
__2. Generate Summary Statistics:__
Calculate key metrics (mean, median, variance, standard deviation, SEM) for tumor volume under each drug regimen.
__3. Create Visualizations:__
Bar charts to represent the total timepoints for each drug regimen.
Pie charts to visualize the gender distribution of mice in the study.
__4. Perform Statistical Analysis:__
Calculate quartiles, interquartile ranges (IQR), and identify outliers in tumor volumes for selected drug regimens.
Create a box plot to display the distribution of final tumor volumes.
__5. Explore Treatment Trends:__
Line plot of tumor volume vs. time for a single mouse treated with Capomulin.
Scatter plot of average tumor volume vs. mouse weight for the Capomulin regimen.
__6. Analyze Correlation and Regression:__
Compute the correlation coefficient between mouse weight and tumor volume.
Fit a linear regression model to the scatter plot data.

# Files

pymaceuticals_starter.ipynb: The Jupyter Notebook containing the analysis code.
Mouse Metadata: Dataset with mouse details.
Study Results: Dataset with tumor volume observations.
## Analysis Workflow

__1. Data Preparation:__
Import required libraries and datasets.
Merge datasets and clean duplicates for accurate analysis.
__2. Summary Statistics:__
Group data by drug regimen to calculate statistics and create a summary DataFrame.
__3. Visualization:__
Bar and pie charts for drug regimens and gender distributions using both Pandas and Matplotlib.
__4. Outlier Detection:__
Group data by mouse ID to isolate the last timepoint.
Analyze tumor volume distributions for Capomulin, Ramicane, Infubinol, and Ceftamin.
Highlight outliers in a box plot.
__5. Treatment-Specific Trends:__
Generate a line plot for tumor volume changes over time for a specific mouse on Capomulin.
Create a scatter plot to explore relationships between mouse weight and tumor volume under Capomulin.
__6. Correlation and Regression Analysis:__
Calculate and interpret the correlation coefficient.
Overlay a linear regression line on the scatter plot for Capomulin data.

# Tools and Libraries
Pandas: For data manipulation and summarization.
Matplotlib: For creating visualizations.
SciPy Stats: For statistical calculations.
NumPy: For numerical operations.

## Results

Comprehensive summary statistics for tumor volume across drug regimens.
Visual insights into gender distribution and drug regimen performance.
Identification of promising treatments (e.g., Capomulin and Ramicane).
Evidence of correlation between mouse weight and tumor volume.

## How to Use
1. Open the pymaceuticals_starter.ipynb notebook in JupyterLab or any compatible environment.
2. Run the cells sequentially to execute the analysis.
3. Review outputs, including visualizations and statistical summaries.

<!--Mod 5-->
