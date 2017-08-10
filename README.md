## R Walkthroughs

### Introduction to R
- [Installing R](basics/installing_R.html): installing R and RStudio.  
- [Some R educational resources](basics/resources.html): installing R and RStudio.
- [Installing a library](basics/installing_library.html): installing the mosaic library from within RStudio.  

### Baby steps with R
We will learn R by doing and through exercises. The following are a bunch of hopefully useful tutorials/exercises to get you started. Feel free to peruse the internet, there are plenty of these sorts of things.

1. To learn the basics, open the 1_RBasics.Rmd file in the directory 'tutorials' and follow the instructions. 
2. Dataframe is to R as spreadsheet is to Excel. Open the 2_dataframes.Rmd file in the directory 'tutorials' and follow the instructions to learn more. 

### Exploratory data analysis
- [Survival on the Titanic](titanic/titanic.md): basics of contingency tables.  
- [Temperatures in San Diego and Rapid City](citytemps/citytemps.md): measuring and visualizing dispersion; changing default plots in R.
- [SAT scores and GPA at UT-Austin](sat/sat.md): boxplots, between-group and within-group variation, sample correlation, scatter plots, pairs plots, and lattice plots.    

### Fitting equations to data
- [Asking prices of pickup trucks on Craigslist](pickup/pickup.md): simple linear regression via ordinary least squares; residual summaries   
- [Utility bills versus temperature](utilities/utilities.md): adding polynomial terms to fit nonlinear curves  
- [Infant mortality and GDP](infmort/infmort.md): using log transformations to fit power laws via linear least squares      

### Predictable and unpredictable variation  
- [Kidney function and aging](creatinine/creatinine.md): naive prediction intervals; R^2 and the decomposition of variance     

### Grouping variables in regression    
- [Reaction time in video games](rxntime/rxntime.md): modeling numerical outcomes with more than one categorical predictor; dummy variables and interaction terms; analysis of variance.  
- [House prices](house/house.md): regression with one numerical and multiple categorical predictors; dummy variables and interactions in simple regression models.  


### Quantifying uncertainty via the bootstrap 
- [Gone fishing](gonefishing/gonefishing.md): using the Monte Carlo method to simulate the sampling distributions of the sample mean and of the least-squares estimator  
- [Kidney function and aging, revisited](creatinine/creatinine_bootstrap.md): bootstrapping the sample mean and the OLS estimator; computing confidence intervals from bootstrapped samples.  
- [Newspapers](newspapers/newspapers.md): using the normal linear regression model to quantify uncertainty about parameters and predictions.    

### Multiple regression: basics  
- [The wage gap](salary/salary.md): an introduction to multiple regression  
- [Current population survey](cps/cps.md): the affect of collinearity on the estimated coefficients and ANOVA table in a multiple regression model.  

### Hypothesis testing
- [The Patriots and the coin toss](hyptest/hyptest.md): testing a simple hypothesis by Monte Carlo simulation.  
- [Titanic, revisited](titanic/titanic_permtest.md): relative risk, odds ratios, and permutation tests in 2x2 contingency tables.  


### Building a predictive model 
- [Google flu trends](flu/flu.md): Building and checking a predictive model using stepwise selection  


### Generalized linear models  
- [Basketball point spreads](bballbets/bballbets.md): Logistic regression.  

### Time series  
- [Atmospheric CO2](maunaloa/maunaloa.md): Trends and seasonal variation in time-series models.  


### Monte Carlo simulation  
- [Introduction to Monte Carlo](montecarlo/montecarlo_intro.md) in the context of a simplified investment problem.  


### Miscellaneous  
- [Optimization](optimize/optimize.md): defining and optimizing your own functions in R.  