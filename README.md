# Linear Regression Model of Traffic Collisions in Toronto Neighbourhoods

**Author:** Yutong Lu 

**Date:** 12/17/2021

## Introduction

- Investigates the relationship between road, demographic, and economic characteristics in Toronto neighbourhoods and traffic collisions.
- Aims to build a descriptive linear regression model to aid urban and transportation planning.

## Methods

- The study used traffic collision data as the response variable.
- Training and test sets were split equally for analysis.
- Initial model included all potential predictors; transformations applied as needed.
- Linear regression assumptions assessed using standardized residual plots and Normal Q-Q plots.
- Reduced models created by removing insignificant predictors.
- Models assessed for multicollinearity, and problematic observations identified using Cook’s distance and DFBETAs.

## Results

- The dataset was cleaned, removing neighbourhoods with zero road volume and kilometers.
- Key findings from the training set include potential linear relationships between traffic collisions and predictors.
- The final model was selected based on adjusted R², multicollinearity, and minimal problematic observations.
- The final model included predictors such as labour force, business per area, population density, road volume, and TTC overcrowded routes.
- The model was tested for validation on a separate test set.

## Discussion

- Interpretation of the model suggests an increase in labour force and business per area leads to more traffic collisions, whereas higher population density and overcrowded TTC routes may reduce collisions.
- The final model provides insights into factors related to traffic collisions, emphasizing public transportation and road volume management.
- Limitations include potential biases due to removed observations and multicollinearity. The model showed weaker predictive ability on unseen data.

## Conclusion

- The study presents a comprehensive analysis of factors influencing traffic collisions in Toronto.
- Findings are critical for city planning, with recommendations for enhancing public transport and managing roads with high traffic volume.
