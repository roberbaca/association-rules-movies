# Movie Recommendation with Association Rules (Netflix)

This repository contains a movie recommendation model based on association rules, implemented in R using the MovieLens dataset.

## Project Overview

This project applies association rules to build a personalized movie recommendation system based on user behavior. Using the MovieLens (ml-latest-small) dataset, which includes user ratings for thousands of movies, the Apriori algorithm is applied to identify frequent co-viewing patterns.

The model filters movies rated 4 stars or higher and generates recommendations of up to 5 new titles per user without relying on demographic data, solely based on rating patterns.

The workflow covers:

- Data extraction, transformation, and loading (ETL)  
- Filtering and preparation of transactions  
- Generation of association rules using Apriori  
- Visualization of rules (graph and support-confidence plots)  
- Movie recommendation function based on user watched movies  

## Technologies and Libraries Used

- R  
- tidyverse  
- arules  
- arulesViz  

## How to Run

1. Clone the repository  
2. Open the RMarkdown file  
3. Run the notebook to reproduce the analysis and generate recommendations  

## Links

- [Kaggle Notebook](https://www.kaggle.com/code/robertonicolsbaca/association-rules-movie-recommendation-model-r)

---
© 2025 Roberto Baca
