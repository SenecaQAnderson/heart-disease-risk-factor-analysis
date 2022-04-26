# heart-disease-risk-factor-analysis
This is the final project completed for COMP.4600/5300: Special Topics (Computing for Health and Medicine) at UMass Lowell. Its purpose is to analyze a dataset of heart disease risk factors and determine (via Shapley values) which ones have the most impact on classifier decisions.

The Google Colab version of the code is in Heart_Disease_Risk_Factor_Analysis_Colab_Version.ipynb. A PDF version of the output is available in Heart_Disease_Risk_Factor_Analysis.pdf.


# Running the Project
In order to run this project, perform the following steps:

1) Open the Heart_Disease_Risk_Factor_Analysis_Colab_Version.ipynb file in GitHub. Make sure it is the _Colab version_, and not the non-Colab version available in the notebook folder.

2) Click on the Colab button to open the file in Colab. If the file takes too long to render and fails to display this button, click the Download button instead to get the raw file data. Save the raw file data to your computer and open it in Google Colab.

3) Run the project. It is very important to run the cells _in order_. If you don't run the cells in order, some of them may not work. Additionally, please note that this project takes a significant amount of computational time, so if a cell takes a long time to execute, this doesn't indicate a problem.

# Description of Code

The project is divided into five main sections, which must be executed in order. Each section has a title and brief description in the .ipynb file. Here is a summary of the sections:

1) Data Pre-Processing

2) Correlation Analysis -- generating heat maps for the Pearson and Spearman correlation coefficients to find the degree of correlation between features

3) Classification -- training and evaluating various classification models in order to determine the best ones for Shapley value analysis

4) Shapley Value Calculation -- calculating the Shapley values for three chosen models

5) Final Analysis & Data Visualizations -- use the SHAP library to generate visualizations to be used while analyzing the data