---
title: "BE Webinar 2025"
author: "Tucker S. McElroy"
date: "1/8/2025"
output:
  html_document:
    df_print: paged
---
 
##  **Time Series: A First Course with Bootstrap Starter**

### Abstract: 
The proposed course will cover the content of the book *Time Series: A First Course with Bootstrap Starter* in three parts, each covering four chapters. 
The course will be sponsored by the Business and Economics Statistics section. The intended audience includes statisticians with little or no knowledge 
of time series, but a general knowledge of statistics. Prerequisites include a course on linear models, a course on mathematical statistics 
(such concepts as bias, variance, and the Gaussian distribution), and a familiarity with linear algebra (the transpose, inverse, and eigen-values of 
a matrix). The aim is to cover basic concepts of time series analysis at a level suitable for those with a bachelor's or master's degree in statistics, 
while including a few non-standard concepts such as entropy, volatility filtering, and time series bootstraps. A second aim is to incorporate coding 
in R of all concepts, methods, and examples.

## Instructor: Tucker S. McElroy

### Contact
 Research and Methodology Directorate, U.S. Census Bureau  
 4600 Silver Hill Road, Washington, D.C. 20233-9100  
 tucker.s.mcelroy@census.gov   
 Phone: 240-695-3610  

### Biography 
Tucker S. McElroy is Senior Time Series Mathematical Statistician at the U.S. Census Bureau, where he has contributed to developing time series research 
and software for the last 21 years. He has published more than 100 papers and is a recipient of the Arthur S. Flemming award (2011).
 
## Outline

The course will emphasize the methodological and computational aspects of the book's material. While the course will not include proofs, some 
important theoretical results will be discussed. The following outline provides the main topics; in *italics* are topics not typically covered in a time series course.
 
1. **Introduction:** time series data, cycles, regression, and autoregression
2. **Stochastic Processes:** stationarity, autocovariance, moving averages, white noise, and integrated processes
3. **Filtering:** linear filters, trends, and *seasonality*
4. **Forecasting:** prediction, normal equations, and iterative forecasting
5. **ARMA:** ARMA recursion, difference equations, and autocovariance generating functions
6. **Frequency Domain:** spectral density, *frequency response functions*, *inverse autocovariances*, and partial autocorrelations
7. **Frequency Domain:** discrete Fourier Transform, *optimal filtering*, Wold decomposition, and *cepstrum*
8. **Model Identification:** *maximum entropy*, *time series entropy*, and *Kullback-Leibler discrepancy*
9. **Statistical Estimation:** sample mean, sample autocovariance, *spectral mean*, and periodogram 
10. **Model Fitting:** Gaussian likelihood, fitting AR and MA models, model assessment, and AIC
11. **Nonlinear Time Series:** GARCH processes, *bi-spectral density*, and *volatility filtering*
12. **The Bootstrap:** Monte Carlo, *plug-in principle*, *model-based bootstrap*, *sieve bootstraps*, *subsampling*, *block bootstrap,* *stationary bootstrap*, and *model-free bootstrap*
 
 
## Format

The teaching format is live and virtual. Webinars will be held weekly for one hour, with instruction being offered in real-time. 
The course will utilize R notebooks associated with the textbook. Each notebook corresponds to a lesson, covering a few examples or one concept, 
and occupying 10-15 minutes of time. Each one-hour webinar will cover 4-7 notebooks. The teacher will review that material in the lesson, 
explaining the main concepts. Students can execute the code on their own laptop, and then during instruction the instructor may modify the code; 
students can follow along and modify the code, or rewrite it, and in real-time see the new results. The notebooks are freely available on the Github site.
    
 
## List of Lessons

### Webinar 1

1. Time Series Data
2. Cycles
3. Windows and Transforms 
4. Regression and Autoregression

### Webinar 2

1. Random Vectors
2. Stochastic Processes
3. Stationarity
4. Autocovariance
5. Autoregression and Moving Average
6. White Noise Processes

### Webinar 3

1. Nonparametric Smoothing
2. *Linear Filters*
3. Examples of Filters
4. Trends
5. *Seasonality*
6. *Trend and Seasonality*
7. Integrated Processes

### Webinar 4

1. Vector Space Geometry
2. The L2 Space
3. Projection in Hilbert Space
4. Time Series Prediction
5. Linear Prediction
6. Orthonormal Sets
7. *Projection of Signals*

### Webinar 5

1. ARMA Recursion
2. Difference Equations
3. Causality of AR(1)
4. Causality of ARMA
5. Invertibility of ARMA
6. Autocovariance Generating Function
7. MA Representation
8. Recursive Computation of Autocovariance

### Webinar 6

1. Spectral Density
2. *Filtering in Frequency Domain*
3. *Inverse Autocovariance*
4. Toeplitz Matrices
5. Partial Autocorrelation
6. AR and MA Identification

### Webinar 7

1. Herglotz Theorem
2. Discrete Fourier Transform
3. *Spectral Representation*
4. *Optimal Filtering*
5. Kolmogorov's Formula
6. Wold Decomposition
7. *Cepstrum*

### Webinar 8

1. *Introduction to Entropy*
2. *Entropy Mixing*
3. Maximum Entropy
4. *Time Series Entropy*
5. Markov Time Series
6. *Modeling via Entropy*
7. *Kullback-Leibler Discrepancy*

### Webinar 9

1. Weak Dependence
2. Sample Mean
3. Serial Correlation
4. Sample Autocovariance
5. *Spectral Means*
6. Periodogram
7. Spectral Density Estimation
8. Spectral Analysis

### Webinar 10

1. MA Identification
2. AR Identification
3. Optimal Prediction Estimators
4. *Relative Entropy Minimization*
5. *Computation of Optimal Predictors*
6. The Gaussian Likelihood
7. Model Assessment
8. Information Criteria
9. Model Comparisons
10. *Iterative Forecasting*
11. *Imputation and Signal Extraction*

### Webinar 11

1. *Nonlinear Processes*
2. ARCH Process
3. GARCH Process
4. *Bi-spectral Density*
5. *Volatility Filtering*

### Webinar 12

1. Sampling Distributions
2. Monte Carlo
3. *The Plug-in Principle and the Bootstrap*
4. *Model-based Bootstrap*
5. *Sieve Bootstraps*
6. *Time Frequency Toggle Bootstrap*
7. *Subsampling*
8. *Block Bootstrap*

 
## Learning Outcomes

### Performance Objectives 

Students will obtain a basic knowledge of time series theory and methodology. They will be able to analyze time series data by
exploratory analysis, by model identification and fitting, and by making applications such as forecasting. Students will know 
how to use R to perform these tasks: not only to apply common time series functions appropriately, but also to write R scripts 
that capture time series methodology. In addition to learning basic time series topics, including ARMA modeling, students will 
learn how to use entropy, frequency domain methods, and time series bootstraps.
 
### Content and Instructional Methods

The course will be drawn from the textbook's material, but presentations will be primarily rendered through R Notebooks. 
The instructional strategy will be to briefly discuss a new topic, and then demonstrate through R code the computational and
empirical facets of the topic. Short exercises can then be given, where the teacher asks the students to modify the R code to 
generate a different result. Through the technology of the virtual format, the instruction can be paused to address student questions.
 
 
 
 
