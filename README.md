java c
Financial Econometrics (ECOM40004/ECOM90011)
Assignment 2
Summary
• The assignment is marked out of 20. It is comprised of 2 parts.
• Each student has to hand in a SEPARATE WRITTEN report.
• Submission is electronic through LMS or via e-mail to: vietn@unimelb.edu.au
• Due date is 7pm Friday 13 September 2024. Late assignments will loose 2 marks per day.
Part 1 (4 marks)
• Consider the following VAR(1) for three stationary variables y1t, y2t, and y3t

where

• Equation (1) can be written compactly as follows:

• Equation (2) can be transformed using Wold representation theorem as follows:

1. Write the values of Θ1 and Θ2 in Equation (3) using the parameters of Equation (1) (i.e. in ϕij and σij with i, j = 1, 2, 3). (1 mark)
2. Write generalised impulse response of y1t to a shock of one-standard deviation to u2t at time t + 1 using the parameters of Equation (1) (i.e. in ϕij , σij with i, j = 1, 2, 3 and Σu). (1 mark)
3. Write generalised impulse response of y3t to a shock of one-standard deviation to u2t at time t + 2 using the parameters of Equation (1) (i.e. in ϕij , σij with i, j = 1, 2, 3 and Σu). (2 marks)
Part 2 (16 marks)
• The Excel file ‘Assignment1 S2 2023.xlsx’ contains daily changes (in basis points) of the sim-ulated sovereign Credit Default Swap spreads (CDSs) for 18 European countries between 2006-2012.
1. Specify a VAR model to study the interactions among the 18 sovereign CDSs; report the lag order selection test and indicate the optimal lag order of your specified VAR model based on the Schwarz information criterion (SC). (1 mark)
2. Estimate a VAR(1) model for the provided daily changes of 18 sovereign CDSs; report the stability condition of your estimated VAR(1) model.(1 mark)
3. Construct a network among the 18 sovereign CDSs, based on full-sample estimation of the VAR(1) model, using Forecast Error Variance Decomposition (based on Cholesky factorization of the variance-covariance matrix with the ordering provided, i.e. 1 to 18). Report the network at 10-day-ahead forecast horizon and repor代 写Financial Econometrics (ECOM40004/ECOM90011) Assignment 2Matlab
代做程序编程语言t the Dielbold-Yilmaz (DY) Spillover Index of the network at this selected forecast horizon. (2 marks)
4. Re-construct the FEVD-based network at 10-day-ahead forecast horizon (based on Cholesky factorization with the ordering provided) at two specified sample periods below:
– Before the Global Financial Crisis (GFC) network: based on observations from 17-April 2006 to 30-March 2007,
– During the Global Financial Crisis network: based on observations from 3-March-2008 to 13-February-2009,
a. Report the values of the DY Spillover Index at the above two sample periods, (2 marks)
b. Plot histograms of the network’s spillovers and its estimated kernel densities (based on Gaussian kernel with optimal bandwidth) at the above two sample periods, (2 marks)
c. Using the values of the DY Spillover Index and the two estimated kernel densities of the network, describe major changes in the shape of the network before and during the GFC. (1 mark)
5. Estimate a VAR(1) on a rolling-window basis with a window length of 250 days, to study the time-varying interactions among the 18 sovereign CDSs. Re-construct the 10-day-ahead network at each rolling sample using Generalised Forecast Error Variance Decomposition.
a. Compute and plot the time-varying DY Spillover Index of the network. (2 marks)
b. Estimate the spillover density (using Gaussian kernel with optimal bandwidth, 1024 grid points) of the constructed network at each rolling sample; compute the Kullback-Leibler Information Criterion (KLIC) by comparing the spillover density at each rolling sample, Sr, against the spillover density of the first rolling sample, denoted S0. Plot the time-varying KLIC series. (2 marks)
6. Construct a network among the 18 sovereign CDSs, based on full-sample estimation of the VAR(1) model, using accumulated Generalised Impulse Response Functions to shocks of 10 basis points to 18 sovereign CDSs. Report the network at 10-day-ahead horizon and report the estimated spillover density for this constructed network. (3 marks)







         
加QQ：99515681  WX：codinghelp
