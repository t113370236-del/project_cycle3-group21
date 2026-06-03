Group number: 21
Member names: 113370236 賴建佑 and 113370211 黄靖容
## Selected Research Question
Question 7: Current Alcohol Use and BMI Percentile
Research question: Is the mean BMI percentile different between students who currently use alcohol and those who do not?
## Variables
Group variable: `CurrentAlcoholUse`  
Response variable: `BMIPCT`
## Recoding Rule
`CurrentAlcoholUse` was recoded into two groups:
- Original codes 2–7 = 1, current alcohol use
- Original code 1 = 0, no current alcohol use
- Missing or invalid values were removed
## Statistical Method
Welch two-sample t-test was used to compare the mean BMI percentile between the two groups.
This method was chosen because `BMIPCT` is quantitative, and equal variance between the two groups was not assumed.
## Main Results
Current alcohol use group:
- n = 5,394
- mean BMIPCT = 64.80
- SD = 26.98
No current alcohol use group:
- n = 6,449
- mean BMIPCT = 64.71
- SD = 27.84
Estimated mean difference:
```text
Current alcohol use - No current alcohol use = 0.09
## Short Final Conclusion
At α = 0.05, the p-value is 0.8533. We fail to reject the null hypothesis. There is no significant difference in the mean BMI percentile between students who currently use alcohol and those who do not.
