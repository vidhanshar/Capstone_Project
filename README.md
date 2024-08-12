# LSE_Capstone_Project
The repository contains raw files and R code that facilitated the analysis for the captsone project, titled: "Navigating Funding Landscape: The Role of Competition, Network Dynamics, and Patents in Fundraising Success of Indian Startups"

The .rmd file contains multiple code chunks containing the modular functions used to quanitfy certain features and aggregate the feature set, as input for the ensemble ML (XGBoost) model predicting the fundraising success of Indian startups in the next two years. 

The code broadly covers extraction of details of relevant organizations (Indian startups founded between 2013-Jun'24, and have had raised atleast a single rounf of funfing), extraction of entity specific funding details, identifying competitors using sentence embeddings to find semantic similarity between startup's text descriptions, forming a bi-partite network of startups and investors to arrive at one-mode projected netowrk of investor syndications, to cpature investor's network characteristics, finding startups with successful labels based on their fundrasing patterns, etc. 

The 'data' folder contains some of the figures/images used in the research paper. 
