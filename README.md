# Loan Default Prediction

Predicting the outcome of a loan as a means to maximize return for peer-to-peer lending investments.

![Loan](https://cdn.pixabay.com/photo/2015/02/07/07/39/analysis-626881_960_720.jpg?raw=true)

## Description

In this project, loan data for a peer-to-peer lending platform is obtained and analyzed with a goal of maximizing return for investors. Variables from the dataset are evaluated to determine if they can be used for prediction of the target variable, loan status. Each variable is then analyzed to describe its distribution and its association with whether or not a loan was paid in full. Following exploratory data analysis, preprocessing and predictive modeling is used to create a loan selection process that maximizes return on investment. This loan selection process is compared to using FICO scores and loan grade for selecting loans. Finally, ideas for further analysis and key learnings are provided.

## Data

[Kaggle Dataset](https://www.kaggle.com/wordsforthewise/lending-club)

## Contents

**Data**  
* Dataset web address.txt - Web address of dataset (too large to store in Github)
* LCDataDictionary - Variable descriptions

**Papers**  
* Proposal.pdf
* Expected Questions.pdf
* Report.pdf

**Notebooks and Visualizations** (main directory)
* Exploratory Data Analysis.ipynb - First step in the project; exploring and visualizing data
* Data Profile Report.html - Variable statistics, distributions, and relationships
* Predictive Modeling.ipynb - Last step in the project; fitting various predictive models and applying them to the business problem
* Excel Charts.xlsx - Visualizations used in the Report
* Presentation Deck.pdf - Recording of presentation can be found [here](https://drive.google.com/file/d/1zx4eGDptbJEnNaAMkbryTTjGmFDNgpyU/view?usp=sharing)

## Tools
* Python
* PyCaret
* SKLearn
* MatPlotLib
* Seaborn

## Author

Samuel Sears @ssears219

## Acknowledgments

* [Investopedia Article on Peer-to-Peer Lending Sites](https://www.investopedia.com/articles/investing/092315/7-best-peertopeer-lending-websites.asp)
* [Investopedia Article on Peer-to-Peer Lending](https://www.investopedia.com/terms/p/peer-to-peer-lending.asp)
* [The Ascent Article on LendingClub](https://www.fool.com/the-ascent/personal-loans/articles/lendingclub-ending-its-p2p-lending-platform-now-what/)
* [PyCaret](https://pycaret.org/compare=models/)
* [Article About Prepping LendingClub Data](https://www.dataquest.io/blog/machine-learning-preparing-data/)
* [Article on Confusion Matrix Visualization](https://medium.com/@dtuk81/confusion-matrix-visualization-fc31e3f30fea)
