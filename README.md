SAS Analytics Portfolio: Statistical Modeling & Business Case Analysis
Overview
This repository contains the SAS code, presentation materials, and technical methodologies for a comprehensive data analytics group project. The project applies statistical testing, regression modeling, and risk analysis to solve four distinct business cases across the retail, real estate, insurance, and financial sectors.

Business Cases
1. Cosmetics Sales Training ROI

Objective: Evaluate the financial impact of a new sales training course on employee performance.
Methodology: Assessed the normality of the sales differences using histograms and Q-Q plots. Applied paired T-tests (parametric) and Wilcoxon Signed-Rank tests (non-parametric) to determine if the post-training sales receipts were statistically significant.
Outcome: Provided actionable recommendations to management by weighing training costs against the marginal increase in sales.

2. Commercial Real Estate Valuation
Objective: Predict the value of commercial pub and restaurant properties to advise on maximum investment prices (specifically for a property named "The Good King James").
Methodology: * Built multiple linear regression models.
Conducted deep multicollinearity checks using correlation heatmaps and Variance Inflation Factor (VIF) tables.
Automated variable selection using Forward Selection, Backward Elimination, and Mallow’s Cp analysis to isolate the strongest predictors (Ratevalue, Employ, Garden).
Performed rigorous residual and influence diagnostics tracking DFFITS, Cook's D, CovRatio, and Studentized Residuals to identify extreme observations.


3. Insurance Claim Modeling
Objective: Model and predict insurance claim amounts based on client age.
Methodology: Initially fit a simple linear regression model but identified a misspecified U-shaped pattern in the Studentized residuals versus fitted values plot . Corrected the model specification by engineering a log-linear transformation (LnClaim) . Verified the new model's adequacy using normal probability (QQ) plots and histograms.
4. Loan Default Risk Analysis
Objective: Analyze the relationship between specific client groups and late loan repayments .
Methodology: Utilized frequency distributions and cross-tabulations. Applied Chi-Square tests and calculated risk differences to find the statistical variance in default rates between the test groups.
Technical Stack & SAS Procedures
Language: SAS Enterprise
Statistical Procedures: PROC TTEST, PROC UNIVARIATE, PROC REG, PROC FREQ, PROC CORR, PROC MEANS.
Data Visualization: PROC SGPLOT (Scatterplots, Histograms, Heatmaps, Fitted Regression Lines).

Repository Structure
SAS_CODE_FINAL.sas: The complete SAS script containing all data steps, procedures, and macro variables used for the analysis.
Presentation.pptx: The slide deck summarizing the methodology, visual diagnostics, and final business recommendations.
Data/: (If applicable, add a note here about your datasets or state that data was provided via the perm library ).

Team Members
This project was completed collaboratively by Group 27:
Sandhya Rani Arepalli 
Taizeem Ahmad Syed 
Varun Kumar Reddy Mallu 
Hruday Abothu 
Mandar Dnyaneshwar Satpute
