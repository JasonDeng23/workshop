## Nieves Response

Nieves et a. use the random forest machine learning method to predict what value globally? Describe in detail how random forest works. What is a dasymmetric population allocation? Which geospatial covariates proved to be the most important when predicting global values of where humans reside?

### Response

The random forest machine learning model was used by Nieves et al. to predict population densities and settlements globally. In Nieves' research, they combined two groups of large data sets: one of them was population census data, the other one was different layers of various covariates at a subdivision level. The 2nd data stack could include anything from nighttime lights to foliage. What they want the random forest model to do is to take these two data sets and combine them in a way that can generate a layered, weighted population grid-celled map that accurately shows population densities. The process that the initial data sets have to go through include creating what is called "trees", or regression data structure that allows for various predictions. Weak trees are combined and made into stronger trees, and processed with OOB data for estimating erorr, you receive the final, machine-learning generated product. 

Dasymmetric population allocation is a technique that is used to distribute census data in administrative units to grid cells using the population density. This helped the researches develop and improve on the weak trees in their model to become stronger trees and better predictors. 

Built environment cases were found to be the significantly more important than classified populated places. Additionally, waterways and other bodies of water showed to be important for countries in Africa, and other LMIC's. Naturally, this makes sense, as people will tend to be around these kinds of things. 
