## R Walkthroughs

### Introduction to R
- [Installing R](basics/installing_R.html): installing R and RStudio.  
- [Some R educational resources](basics/resources.html): installing R and RStudio.
- [Installing a library](basics/installing_library.html): installing the mosaic library from within RStudio.  

### Baby steps with R
We will learn R by doing and through exercises. The following are a bunch of hopefully useful tutorials/exercises to get you started. Feel free to peruse the internet, there are plenty of these sorts of things.

1. To learn the basics, open the 1_RBasics.Rmd file in the directory 'tutorials' and follow the instructions. 
2. Dataframe is to R as spreadsheet is to Excel. Open the 2_dataframes.Rmd file in the directory 'tutorials' and follow the instructions to learn more. 

### Getting your hands dirty with dplyr
Now that you've learned the basics, its time to learn how to manipulate data. The tools that we will use to manipulate, munge and clean data will come from the package `dplyr`

There are many many online resources to learn about dplyr. I'd recommend:

1. [This book chapter](https://ismayc.github.io/moderndiver-book/5-wrangling.html)
2. [This book chapter](http://r4ds.had.co.nz/transform.html), which has a more extensive review of this subject
3. [This video](https://www.youtube.com/watch?v=8SGif63VW6E) by the creator of dplyr, Hadley Wickham. If you want a shorter one, the first half of [this one](https://www.youtube.com/watch?v=40tyOFMZUSM&t=37s) is pretty good. [This](https://www.youtube.com/watch?v=aywFompr1F4) is a shorter one by Roger Peng who is a statistician at Hopkins and is also pretty good. 
4. [This](https://www.rstudio.com/wp-content/uploads/2015/02/data-wrangling-cheatsheet.pdf) is a useful cheatsheet (Rstudio makes a bunch of these)

### Making plots with, the ggplot2 way
Plotting is fun. Its the way to start looking at all your data, whats in there, what correlates with what. I recommend the ggplot2 package for making plots in R. It has an intuitive (once you get it) logic and it has tons and tons of add-on packages that enhance its functionality. The gg in ggplot2 stands for 'grammer of graphics' which is based on the idea that just like a language has rules, logic, verbs/adjectives/nouns, plots also have a fundamental vocabulary. The following are good resources for learning how to use ggplot2.

1. [This book chapter](https://ismayc.github.io/moderndiver-book/3-viz.html#grammarofgraphics)
2. [This book chapter](http://r4ds.had.co.nz/data-visualisation.html), which has a more extensive review of this subject
3. [This video](https://www.youtube.com/watch?v=TaxJwC_MP9Q&t=4s) by the creator of ggplot2, Hadley Wickham. [This one](https://www.youtube.com/watch?v=n8kYa9vu1l8) is by Roger Peng.
4. [This](https://www.rstudio.com/wp-content/uploads/2015/03/ggplot2-cheatsheet.pdf) is a useful cheatsheet (Rstudio makes a bunch of these)

## Starting here are a bunch of lessons from the original repo. 
Feel free to peruse, but we'll probably go our own way.

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