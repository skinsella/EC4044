# EC4044 Applied Economic Analysis

# Introduction 

> The formulation of a problem is often more essential than its solution which may be merely a matter of mathematical or experimental skill. 
--Albert Einstein



> Routine, in an intelligent man, is a sign of ambition. 
—WH Auden


# Welcome to this module

* This is a *brand new* module, EC4044. 
* This is the first time it has been taught. So please, bear with me. 
* Slides will be added to this master version as I get the chance to build them out. 
* In addition to being a pedagogical experiment, this is also technical experiment. 
* We'll be using some open-source tools, your feedback will be crucial as we develop the material. 

# Brief note on the slides

- The slides and the code that generates them are a part of the course. They will be added to incrementally, so you should expect to see longer and longer slide decks being created. 
- That is, I won't be giving out individual slides per lecture. You will see why in a moment.

# Learning outcomes for this module

0. Understand principles of data science;
1. Understand where economic data come from;
2. Understand the *politics* of economic data collection and dissemination;
3. Estimate simple economic models
4. Understand the merits of qualitative as well as quantitative economic analysis. Economics is not all ones and zeroes. You do have to talk to real people from time to time. 

# How you'll learn

0. Hands-on, with your laptops or tablets in class. Laptops are better, but whatever works for you. 
1. The idea is to make this module, as far as possible, one 36 hour-long lab. 
2. You'll become familiar with a cutting edge statistical language and gain the ability to produce really nice reports, slides, and data analysis using this software. You'll also learn how to interview individuals and groups. 
3. Importantly, your work will be open for everyone to view. You'll gain an appreciation of the kind of work that gets social scientists interested in things. 

# Key Resources

- David Freedman, [*Statistical Models, Theory and Practice*](https://www.amazon.com/Statistical-Models-Practice-David-Freedman/dp/0521743850), Cambridge University Press, 2009. This is the best book on statistics I have ever read. 
- Garrett Grolemund and Hadley Wickham, [R for data science](http://r4ds.had.co.nz), O'Reilly, 2016.
- Gary Koop, *Analysis of Economic Data*, Wiley, 2013. This book is a classic and fun to read. 
- *Lots* of online resources with R, especially [Datacamp](http://www.datacamp.com)

# Key Software resources

- R and Rstudio. 
- Github, where all the notes, code, and other elements for the course will be. 
- Datacamp.com, for the introductions to R. 
- SULIS contains the readings.
- Turnitin, for the final data project. 

# Why R?

- This is not an econometrics class, or a basic statistics class--you are taking one of those. 
- This is about using the theories you've learned over the last 3 semesters and learning how to go about investigating the real world and their applicability to that world. 
- So you need a tool, but one that can't be too complicated. R allows you enough power (for free) to analyse 50 million datapoints at the same time, but you don't need to know everything about what's going on under the hood to do useful work. 
- That is, I want you to be able to drive a car, not tinker with its engine or repair it 
- This means we'll be skipping over a lot of detail to get to the important points.


# Lecture 1: Basics and Data handling

- Types of economic data: micro and macro
- Observation studies and experiments
- Statisitical inference, probabilit distributions, fitting a model.
- Graphical methods
- Descriptive statistics
- Expected Values and Variances
- Example: Hall and Jones, Growth Accounting, 1999. 
- Reading: Koop, Chapter 2, Freedman, Chapter 1

# Lab 1: Introduction to R (Teetor, Chapters 1 and 2)

- Installing R + Rstudio
- Getting Github, Quandl, and FRED accounts
- Working through [Twotorials](http://twotorials.com)

# Lecture 2: Modeling (Freedman Chapter 1, Koop Chapter 4 )

- Understanding correlation
- Why are variables correlated
- Staring at XY plots
- Complexities
- Example: Wage/Salary data from 1985.

# Lab 2: Working with data in R (Teetor, Chapter 3)

- Getting data into R
- Simple manipulation
- Your first graphs
- Interpreting your first graphs.

# Lecture 3: Introduction to Simple Regression (Koop, Chapter 4, Freedman, Chapter 3)

- Best fitting line
- Interpreting OLS estimates
- Measuring the fit of a regression model 
- Nonlinearity in Regression 
- Factors affecting $\beta$
- Calculating confidence intervals for $\beta$
- Example: regression by hand, roll your own betas using R.

# Lab 3: Matrix algebra FTW (Freedman Chapter 4)

- Concepts you need to know to get the most out of the rest of the course. 
- What is a matrix
- Determinants & Inverses
- Random vectors
- Positive definite matrices


# Lecture 4: Multiple Regression  (Freedman, Chapter 5)

- Explaining variance in multiple regression 
- Statistical aspects
- Interpreting multiple regression 
- Biases: multicollinearity/heteroskedasticity/autocorrelation 
- Example: education spending and educational attainment

# Lab 4: Working with complex data sets in R

- Cleaning and working with data
- Running regressions, outputting tables, interpreting results
- Mashing data sets together
- Writing reports & making slides with Rmarkdown. 

# Lecture 5: Multiple regression 2 (Freedman, Chapter 5)

- Multiple regression with dummy variables
- Distributed lag models
- Applying theory to data
- Example: Gender pay disparities.

# Lab 5: Working with complex data sets in R, part deux

- Cleaning and working with data
- Running regressions, outputting tables, interpreting results
- Example: Mashing HUGE data sets together

# Lecture 6: Time series analysis (Wickham, )

- Autocorrelation and $AR(1)$ processes
- Stationarity and Unit roots
- Example: Volatility in asset prices
- Example (gapminder): How does life expectancy change over time  for each country?

# Lab 6: Time series data in R

# Lecture 7: Machine learning

- Introduction to machine learning 
- Classification and maximum likelihood
- Neural networks
- Example: zip code recognition problems

# Lab 7: Your first neural network


# Lecture 8: Machine learning 2

- Discovering meaningful patterns in massive data
- Designing models with hidden and observed variables. 
- Statistical learning, criticising the model. 

# Lab 8: More ML

# Lecture 9: Big data and public policy

- Big data, what it is, and what it isn't. 
- Machine learning and public policy
- Manski vs Minsky

# Lab 9: Working on your data-project


# Lecture 10: Interviewing & qualitative analysis

- Applied economic analysis is not just thinking about data and numbers. It is also about finding things out about by simply asking people. 
- *Why Wages Don't Fall during a Recession*, Truman F. Bewley.
- Structured vs Unstructured interview techniques


# Lab 10: Working on your data project

# Lecture 11: Interviewing & qualitative analysis

- Survey data vs interview data
- Example: coding and thematic analysis [Burnard et al, 2008](http://www.nature.com/bdj/journal/v204/n8/full/sj.bdj.2008.292.html) 
- Exercises in interviewing & transcription. 

# Lecture 12: Recap

# Assessment

- 2 Datacamp courses, 'introducing you to R', worth 5% and 'correlation and regression' in R, worth 10%. These are both due by the end of week 6, but you should aim to have the introduction course sorted by week 3 at the latest. 
- 1 *optional* Datacamp course, which you choose, worth 10%. Peruse the course catalogue and let us know which one you want. Guide your own learning. You have access to the entire suite of modules for the entire semester. This would cost you 30 euros every month to learn, and you can add the certifications to you linkedin profiles etc for signalling purposes. 
- 1 end of term project, due week 13. Details of this will be given in the tutorials, it is worth 75%-85%, depending.  
- The objective is not to over-assess you. Rather, there are some basics you need to know to progress in this module, and then to let you play with the data and the tools we give you for 6-8 weeks. The more you use R for economic analysis, the better you'll be at it. 

# Lecture 1: Movitation, statistical basics and data handling

- Types of economic data: micro and macro
- Observation studies and experiments
- Statisitical inference, probabilit distributions, fitting a model.
- Graphical methods
- Descriptive statistics
- Expected Values and Variances
- Example: Hall and Jones, Growth Accounting, 1999. 
- Reading: Koop, Chapter 2, Freedman, Chapter 1

# Lab 1: Introduction to R (Teetor, Chapters 1 and 2)

- Installing R + Rstudio
- Getting Github, Quandl, and FRED accounts
- Working through [Twotorials](http://twotorials.com)

# Lecture 2: Modeling using simple regression (Freedman Chapter 1, Koop Chapter 4 )

- Understanding correlation
- Why are variables correlated
- Staring at XY plots
- Complexities
- Example: Wage/Salary data from 1985.

# Lab 2: Working with data in R (Teetor, Chapter 3)

- Getting data into R
- Simple manipulation
- Your first graphs
- Interpreting your first graphs.

# Lecture 3: More on Simple Regression (Koop, Chapter 4, Freedman, Chapter 3)

- Best fitting line
- Interpreting OLS estimates
- Measuring the fit of a regression model 
- Nonlinearity in Regression 
- Factors affecting $\beta$
- Calculating confidence intervals for $\beta$
- Example: regression by hand, roll your own betas using R.

# Lab 3: Matrix algebra FTW (Freedman Chapter 4)

- Concepts you need to know to get the most out of the rest of the course. 
- What is a matrix
- Determinants & Inverses
- Random vectors
- Positive definite matrices


# Lecture 4: Multiple Regression  (Freedman, Chapter 5)

- Explaining variance in multiple regression 
- Statistical aspects
- Interpreting multiple regression 
- Biases: multicollinearity/heteroskedasticity/autocorrelation 
- Example: education spending and educational attainment

# Lab 4: Working with complex data sets in R

- Cleaning and working with data
- Running regressions, outputting tables, interpreting results
- Mashing data sets together
- Writing reports & making slides with Rmarkdown. 

# Lecture 5: Multiple regression 2 (Freedman, Chapter 5)

- Multiple regression with dummy variables
- Distributed lag models
- Applying theory to data
- Example: Gender pay disparities & producer theory. 

# Lab 5: Working with complex data sets in R, part deux

- Cleaning and working with data
- Running regressions, outputting tables, interpreting results
- Example: Mashing HUGE data sets together

# Lecture 6: Time series analysis (Wickham, )

- Autocorrelation and $AR(1)$ processes
- Stationarity and Unit roots
- Example: Volatility in asset prices
- Example (gapminder): How does life expectancy change over time  for each country?

# Lab 6: Time series data in R

# Lecture 7: Machine learning

- Introduction to machine learning 
- Classification and maximum likelihood
- Neural networks
- Example: zip code recognition problems

# Lab 7: Your first neural network


# Lecture 8: Machine learning 2

- Discovering meaningful patterns in massive data
- Designing models with hidden and observed variables. 
- Statistical learning, criticising the model. 

# Lab 8: More ML

# Lecture 9: Big data and public policy

- Big data, what it is, and what it isn't. 
- Machine learning and public policy
- Manski vs Minsky

# Lab 9: Working on your data-project


# Lecture 10: Interviewing & qualitative analysis

- Applied economic analysis is not just thinking about data and numbers. It is also about finding things out about by simply asking people. 
- *Why Wages Don't Fall during a Recession*, Truman F. Bewley.
- Structured vs Unstructured interview techniques


# Lab 10: Working on your data project

# Lecture 11: Interviewing & qualitative analysis

- Survey data vs interview data
- Example: coding and thematic analysis [Burnard et al, 2008](http://www.nature.com/bdj/journal/v204/n8/full/sj.bdj.2008.292.html) 
- Exercises in interviewing & transcription. 

# Lecture 12: Recap

# Why it is useful to learn these skills in this way and in this order.

My overarcing goal is to help you work as economists. 

1. Most problems you'll face that need serious analysis require you to 1. talk to people and figure out what's going on and 2. get data of some kind and see what's going on. 
2. Once you have data on your problem, you need to start thinking about cleaning it, visualising it, summarising it, transforming it, and modeling it. 
3. Finally, you need to be able to write about it, present it, and more and more, reproduce it so that people can check your work. 


R can help you do all of these things.

