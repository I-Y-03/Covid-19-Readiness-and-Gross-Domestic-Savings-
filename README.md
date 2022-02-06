# Cross Country Analysis: Gross Domestic Savings on COVID-19 Cases
<!-- Output copied to clipboard! -->

<!-----

Yay, no errors, warnings, or alerts!

Conversion time: 0.353 seconds.


Using this Markdown file:

1. Paste this output into your source file.
2. See the notes and action items below regarding this conversion run.
3. Check the rendered output (headings, lists, code blocks, tables) for proper
   formatting and use a linkchecker before you publish this page.

Conversion notes:

* Docs to Markdown version 1.0β33
* Sat Feb 05 2022 19:47:51 GMT-0800 (PST)
* Source doc: Untitled document
----->


## What is it? 

This is a final research project for my Econometrics course. The paper examines the impact of Gross Domestic Savings on accumulative COVID-19 cases on a country level. Secondary variables, such as polity2 score, HDI, Gini, and median income are included in the study to uncover the true Ceteris Paribus effect. The findings suggest there is a statistically significant, positive relationship between GDS and a country’s number of cases, which could be useful for policy implications in helping countries better prepare for future pandemics. 

## Analytical Tools 
STATA 

## Data Description (cross-sectional) 

[World Bank](https://data.worldbank.org/)<span style="text-decoration:underline;"> </span>

Gross Domestic Savings (as % of GDP) 

Life Expectancy: measured in years 

Median Income: (PPP 2018)

[Ferdi(SCO)](https://competitivite.ferdi.fr/en) 

Polity2 Score: captures political regime authority spectrum, score from -10 to 10 (autocracies, anocracies, democracy) 

[United Nations](https://data.un.org/)

HDI: Human Development Index (measured in three dimensions, score from 0 to 1) 

[World Inequality Database](https://wid.world/)

GiNi Coefficient: measures income inequality, score from 0 to 100 

[WHO](https://www.who.int/data/collections)

COVID-19 cases: natural logarithm 

## Methods/Approach 



* Multiple linear regression models (to reduce omitted variable bias) 
* Pairwise correlations to rule out multicollinearity problem 
* Performed F-tests to identify joint significance
* ​​Used Breusch-Pagan and Cook-Weisberg tests to ensure no presence of heteroskedasticity 
* Used Fixed Effects to identify individual effects unique to each country 
