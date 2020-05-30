# Analyze AB Test Results
Within the framework of this project, I tried to assess whether the company should implement a new page or keep the old page with following approaches:

- Probability based approach
- A/B test
- Regression approach

**Requirements**
- Python 3.6 (or higher)
- matplotlib 2.1 (or higher)
- numpy 1.10 (or higher)
- pandas 0.20 (or higher) 
- statsmodels 0.8.0

**Probability based approach:**
- Calculate probability of an individual receiving the new page or an old page and what are the chances of those.

**A/B test:**
- Set up hypothesis to test if new page results in better conversions or not
- Simulate user groups with respect to conversions
- Calculate the p_value
- Use an alternative approach to validate / double check our results and decide whether to reject the null hypothesis

**Regression Approach:**
- Explore two possible outcomes (Whether new page is better or not)
- Include geographic location of the users as well, to find if any specific country had an impact on conversion
