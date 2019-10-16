# press-freedom
An index to monitor press freedom emergencies

## Research phase
- Select projects to use as a model
- Literature review
- Define list of models, basic requirements and data sources
- Elaborate workflow for basic prototype

## Workflow (draft)
- Select basic datasets for testing:
-- AI
-- USSD
-- Freedom House
-- CPJ
-- Early Warning Project
-- Netblocks?
--Data from the Special Rapporteur on Human Rights Defenders between 2014 and 2019.
- Estimate a set of random forests to assess each covariate's predictive power. 
- Use cross-validation to examine the out-of-sample predictive power (10 folds?)
- Test several interpretable algorithms for classification [select classification method for state repression: Most of the empirical research on repression uses ei- ther the indicator used by Poe and Tate (1994), known as the “Political Terror Scale” (PTS) (Gibney, Cornett and Wood, 2009), or an indicator knownas the “Physical Integrity Index” from the Cingranelli-Richards (CIRI) human rights project, Cingranelly and Richards, 2010). Source: An empirical evaluation for state repression, 2014: In addition to CIRI and PTS we employ a new measure from Fariss (2014), which is created using a Bayesian measurement model. 


## Notes on literature review

### An Empirical Evaluation of Explanations for State Repression, 2014
- Cross-validation analysis and random forests, or ensembles of decision trees, might be needed to  carefully select variables for a model, instead of measuring null hyphotesis tests of statistical significance, to predict the outcome of interest and avoid potential overfitting by routinely using all data to fit the model thus not being able to know if the patterns uncovered are the result of the pecualirities of a particular dataset or whether they are more general. 
- Historical context: Cross-national, quantitative research on government repression began in earnest in the mid-1980s. Data collection efforts such as reports on human rights conditions by Freedom House, Amnesty International (AI), the US State Department (USSD), or previous ones such as the World Handbook of Political and Social Indicators facilitated research on state repression. Data reported from AI and USSD have become the most commonly used in the literature. 
- Poe and Tate (1994) presented the first analysis using data covering a relatively large time span and a relatively large number of countries. 
- Empirical studies have so consistently found a relationship between dissent and repression8 that this constitutes one ofthe literature’s principal findings, and the reciprocal relationship between the two has be- come incorporated into more recent, formal, strategic models as an assumption
- Goal of this research is to determine which of the many posited causes of repression receive the strongest support in the available data. To make this determination we examine whether (1) the statistical relationships discovered by this broad literature are generalizable beyond the particular datasets which produced these relationships, and (2) indicators of the concepts identified as important determinants of state repression improve the predictive power of statistical models of state repression.
- Important: Recent work on civil war has shown that statistical significance and predictive validity can actually be at odds with one another, i.e., covariates with statistically significant coefficients can actually impair a model’s predictive performance (Ward, Greenhill, and Bakke 2010). This means that attention to statistical significance alone is misleading researchers about what are, and what are not, important determinants of state repression.
- ** This means that attention to statistical significance alone is misleading researchers about what are, and what are not, important determinants of state repression.22 Rather than evaluating statistical signifi- cance alone, researchers should evaluate the fit of their model to the data.**
