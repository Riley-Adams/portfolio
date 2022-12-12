# Portfolio
Please find below some examples of my past projects.

# Sentiment Analysis of UC Davis Professor Reviews

[Project Report](https://github.com/Riley-Adams/sta141b_project/blob/main/sta141B_final_report.pdf)

[Project Repository](https://github.com/Riley-Adams/sta141b_project)

In this project, which was a final project for a course at UC Davis called STA 141B: Data & Web Technologies for Data Analysis, we used Python to conduct a sentiment analysis of reviews from RateMyProfessors.com. We addressed the following research questions:

* How do departments differ in terms of student-perceived quality and difficulty of their professors?

* Given a professor’s review text, can we classify the reviewer’s sentiment as good or bad?

To obtain the data necessary for this project we scraped all professor names from the UC Davis RateMyProfessors page and then scraped data from all subsequent professors' pages. We conducted exploratory analysis, cleaned the data, then implemented natural language processing techniques to process review text. Then we built a logistic regression model to perform sentiment classification and assessed our results.

# Analysis of Movies

[Project Website](https://finalprojectgroup7.netlify.app/index.html)

[Project Repository](https://github.com/Riley-Adams/STA141AFinalProjectG7)

In this project, which was a final project for a course at UC Davis called STA 141A: Fundamentals of Statistical Data Science, 
we used R to conduct an analysis about on a large set of movie office data. We explored the following research questions: 

* What are the strongest predictors of IMDb score; that is, are there variables that strongly predict if a movie will be well received by audiences?

* How can we group movies together that contain similar attributes so that we can recommend similar movies to others?

To address the first question, we implemented a multiple regression linear model. 
For the second question, we implemented hierarchical clustering methods.

# Regression Model for Life Expectancy Data of Various Countries

[Project Report](https://github.com/Riley-Adams/sta108finalProject/blob/main/TermProjectFinal.pdf)

[Project Repository](https://github.com/Riley-Adams/sta108finalProject)

In this project, which was a final project for a course at UC Davis called STA 108: Applied Statistical Methods - Regression Analysis, I used R 
to find a parsimonious model which predicts life expectancy. In order to meed this goal I took the following steps:

1. Built a model with LifeExpectancy as the outcome, and all remaining variables as predictors.
2. Carried out a residual analysis to identify
    * Deviations from linearity in any of the predictors
    * Possible transformations of predictors
    * Possible transformations fo the outcome variable.
3. Assessed the potential for multicollinearity.
4. Identified which variables are predictors of LifeExpectancy using model selection algorithms.

# Analysis of Annual Temperature Anomalies

[Project Report](https://github.com/Riley-Adams/sta137finalProject/blob/main/STA137_Project.pdf)

[Project Repository](https://github.com/Riley-Adams/sta137finalProject)

In this project, which was a final project for a course at UC Davis called STA 137: Applied Time Series Analysis, we used R to analyze a data set on annual temperature anomalies in the Northern Hemisphere from 1850 - 2019. In doing so, we:

* Used graphical techniques to understand the nature of the variation in the data.
* Utilized the ACF and PACF plots to make preliminary identification of a time series model.
* Utilized AIC model selection criteria to fit an appropriate ARIMA model.
* Performed graphical diagnostics to determine whether the chosen ARIMA model was appropriate.
* Analyzed a plot of the spectral density and smoothed periodogram for the ARIMA fitted values.
* Assessed the models ability to forcast temperature anomalies.

# Curve Fitting for Life Expectancy Data

[Project Repository](https://github.com/Riley-Adams/mat167finalProject)

In this project, which was a final project for a course at UC Davis called MAT 167: Applied Linear Algebra, we used MATLAB to implement various algorithms which fit a curve to best describe the relationship between a country's average life expectancy and the average years of schooling for citizen's of that country. We compared the fit of linear, quadratic, cubic, and logarithmic curves using the 2-norm of the residuals vector. Curves were fit to the data by solving the least squares problem using the psuedoinverse, 3 different algorithms for QR decomposition (Classical Gram-Shmidt, Modified Gram-Schmidt, Householder Triangularization) and Singular Value Decomposition.

# Methicillin-resistant Staphylococcus *aureus* (MRSA) - Modeling, Evolution, and 3-dimensional Structure

This project was a term-long project for a course at UC Davis called MAT 124: Mathematical Biology. The project was completed in 3 distinct phases:

## Modeling

[Report](https://github.com/rjcampbe/MAT-124-MRSA-Project/blob/main/MAT_124_Project.pdf)

In this first phase, we examined a 2002 paper which proposes a dynamical model for the spread of MRSA among inmates at the LA County Jail. We used MATLAB to approximate solution curves for each compartment of the model using the Runge-Kutta method, splitting the data by male and female inmates. We also recreated an analysis for the basic reproduction number, using a matrix method as well as a weighted average approach. Lastly, in R, we simulated values for the basic reproduction number based on random samples of varying parameter values.

## Evolution

[Report](https://github.com/rjcampbe/MAT-124-MRSA-Project/blob/main/MRSA_Project_Main.html)

[Repository](https://github.com/rjcampbe/MAT-124-MRSA-Project)

In this second phase, we examined the genetic similarity and evolution of 224 isolates of hypervirulent ST-8 type Staphylococcus *aureus* in order to gain insight into the background and spread of MRSA. In R, we implement various packages to conduct multiple sequence alignment, phylogenetic tree analysis, and topological data analysis.

## 3d Structure / Summary Report

[Report](https://github.com/rjcampbe/MAT124_Final/blob/main/MRSAfinal.html)

[Repository](https://github.com/rjcampbe/MAT124_Final)

In the final phase, I wrote up my own summary report of the previous two reports, and included an additional section where I found the 3D structure of the MecI protein, the Methicillin Resistance Regulatory protein. This protein is significant because it plays an important role in inducing resistance to Methicillin (an antibiotic used to treat infection caused by this bacteria) in many strains which have developed this resistance. 

To obtain the data for the structure of the protein, I accessed the UniProt database and downloaded the FASTA file which codes for the amino acid sequence, translated from the MecI gene. The AlphaFold2 software tool was then used to simulate the structure of the protein. 
