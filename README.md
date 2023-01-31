# H-1B Visa Application: Strategize for a better chance to be certified

This analysis was originally a project I (Monika Sembiring) did with my friend Bindu Rajanna in our 95885 - Data Science and Big Data class at Carnegie Mellon University. 

## Background and Motivation
In January 2022, Fern Hollow Bridge collapsed on the day President Biden visited Pittsburgh, the City of Bridges. Although no one died, we wonder: What are the factors associated with the risk level/condition of a bridge? The answer can help prevent potential bridge collapses in the future, thus preparing for better maintenance of the bridge and providing people with a safer living environment.

## Project Goals
* **[Classification]** Help government prioritize bridge inspection and maintenance for bridges with poor conditions beforehand; encourage better preservation to maintain the sustainability of bridges in excellent condition.
* **[Case Studies]** Recommend some bridges regarding maintenance efforts and costs on top of bridge conditions and other attributes to help government strategically allocate the bridge maintenance budget.

## Dataset
* PennDOT bridge dataset
* Allegheny county crash dataset
* Pennsylvania bridges dataset

## Machine Learning Technique Used
* K-Nearest Neighbor
* Gaussian Naive Bayes
* Support Vector Machine
* Random Forest
* Gradient Boosting

## Featured Notebooks/Analysis/Deliverables
* Best model for bridge condition classification is Random Forest, with an accuracy of 77.8% and a recall rate of 64.1%.
* The most important features in determining bridges' condition are Substructure Condition, Superstructure Condition, Reconstruction Age, Age, Deck Condition, and Rehab/Replace Eligibility.
* On top of the predicted condition result, maintenance prioritization will be evaluated with the availability of alternative routes, bridge size, traffic amount, and estimated maintenance cost.

*Notes:
Some visualization in the Notebook is generated using Altair, and it cannot be shown in [Github's notebook viewer because it does not execute any embedded Javascript code](https://stackoverflow.com/questions/71346406/why-are-my-altair-data-visualizations-not-showing-up-in-github). You can download the Notebook to open it in your local Jupyter Notebook or open it using Google Colab.* 
