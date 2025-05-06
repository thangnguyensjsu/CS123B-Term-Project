# CS123B-Term-Project

## 🌟 Project Overview:

This project is a ML tool that uses linear regression to predict the behaviorial/cognitive performance of test subject mice after being exposed to simulated radiation resenbling spaceflight conditions in order to studying the impact of spaceflight extreme environmental conditions, such as microgravity and radiation, on astronauts' well-being. 

Here are the main points of this Readme file:

- Data Source
- Methods
- Instructions to Use this Notebook
- Results
- Further Readings


## ℹ️ Data Source:

The project utilizes data from OSDR database, which include the following sources:

**Flow Cytometry Data:** LSDS-122 (Assay No.1) and LSDS-125 (Assay No.2 - Microglia). These flow cytometry datasets are used to analyze white blood cell counts and percentages.
**Behavior Assay Data:** LSDS-121 EPM data provides information on the time spent in the open and center areas of the elevated plus maze.
**Metadata:** OSD-776, OSD-777, OSD-479: Associated metadata files provide details about the samples, including radiation exposure levels, sex, and source names.


## Methods:

The project employs the following methods:
1.  **Data Acquisition:** Data is imported from the OSDR using custom functions defined in the `TermProject Methods` notebook.
2.  **Data Processing:** The data undergoes cleaning, filtering, and merging to create a unified dataset for analysis.
3.  **Data Visualization:** Numerical features and target variables are visualized to understand their distributions and relationships.
4.  **Machine Learning:** Linear regression and other supervised learning algorithms are used to predict cognitive performance based on flow cytometry data.
5.  **Model Evaluation:** The performance of the machine learning models is evaluated using metrics such as accuracy and visualized using ROC curves and confusion matrices.

## Instructions to Use the Notebook:

To run the project:

1. Ensure you have a Google Colab account and environment set up.
2. Upload the project files (`TermProject.ipynb` and `TermProject_Methods.ipynb`) to your Google Drive with the directory: MyDrive/Colab Notebooks.
3. Open `TermProject.ipynb` in Google Colab.
4. Run the cells in the notebook sequentially to execute the analysis.

## Results:

The results of the project will be displayed in the notebook. The project aims to identify correlations between radiation exposure and cognitive performance in male astronauts and potentially predict cognitive response using flow cytometry data.

## 📖 Further reading:
- https://www.science.org/doi/10.1126/sciadv.abg6702