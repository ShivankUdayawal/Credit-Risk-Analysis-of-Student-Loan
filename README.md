# Credit-Risk-Analysis-of-Student-Loan
### Providing a quantitative assessment of the likely effects of the private market for student loans on college enrollment in order to better assess the effectiveness of higher education policies.


## Introduction :
More than half of undergraduate students in the world borrow to finance their college education and an increasing number of students borrow the maximum available in the government student loan program. This has led to substantially increased use of private loans as a supplementary source of finance for households’ higher education investment. In fact, undergraduate borrowing from nonfederal sources peaked at 25 percent in 2007-08 (College Board, 2014). This is important to policy makers because as more funds are borrowed for student loans (from all sources), the repayment process becomes complex, especially in light of recent policy changes in both the government and private student loan markets.

In fact, default rates on all forms of student loans have increased in the past decade. 

The goal of this notebook is to provide a quantitative assessment of the likely effects of the private market for student loans on college enrollment in order to better assess the effectiveness of higher education policies.

A critical aspect of the private market for student loans is that, unlike in the government student loan market, loan terms must reflect students’ risk of default. Eligibility, interest rates and loan limits in the private market, all depend on credit scores. In addition, default in the private market affects credit risk and in turn, results in worse loan conditions. The rise of student loans originating in private credit markets suggests that individual credit risk may affect college investment.

In particular, individuals with good credit may not be constrained in their college investment by limits on Federal student loans since they can access the private market, whereas the opposite may be true for those with bad credit. Moreover, beyond simply crowding out private lending, expansions of the government student loan program will feed back into default risk on private loans. More generally, higher education policies may affect the distribution of borrowers, and as a result, may have different implications for default behavior, credit risk, and consequently welfare.

## Description of Dataset :
Two data files are provided:

  1. "Origination Data.csv" provides characteristics of student loans that have been originated.
  2. The second file, "Performance.xlsx", is a performance summary of loans. The "Early Risk Score" is an indicator of poor credit performance (the higher the score, the riskier the loan).

![](https://github.com/ShivankUdayawal/Credit-Risk-Analysis-of-Student-Loan/blob/main/Data%20Visualization/01.jpg)

![](https://github.com/ShivankUdayawal/Credit-Risk-Analysis-of-Student-Loan/blob/main/Data%20Visualization/02.jpg)

![](https://github.com/ShivankUdayawal/Credit-Risk-Analysis-of-Student-Loan/blob/main/Data%20Visualization/03.jpg)

![](https://github.com/ShivankUdayawal/Credit-Risk-Analysis-of-Student-Loan/blob/main/Data%20Visualization/04.jpg)

![](https://github.com/ShivankUdayawal/Credit-Risk-Analysis-of-Student-Loan/blob/main/Data%20Visualization/05.jpg)

![](https://github.com/ShivankUdayawal/Credit-Risk-Analysis-of-Student-Loan/blob/main/Data%20Visualization/06.jpg)

![](https://github.com/ShivankUdayawal/Credit-Risk-Analysis-of-Student-Loan/blob/main/Data%20Visualization/07.jpg)

![](https://github.com/ShivankUdayawal/Credit-Risk-Analysis-of-Student-Loan/blob/main/Data%20Visualization/08.jpg)

![](https://github.com/ShivankUdayawal/Credit-Risk-Analysis-of-Student-Loan/blob/main/Data%20Visualization/09.jpg)

![](https://github.com/ShivankUdayawal/Credit-Risk-Analysis-of-Student-Loan/blob/main/Data%20Visualization/10.jpg)

![](https://github.com/ShivankUdayawal/Credit-Risk-Analysis-of-Student-Loan/blob/main/Data%20Visualization/16.jpg)

![](https://github.com/ShivankUdayawal/Credit-Risk-Analysis-of-Student-Loan/blob/main/Data%20Visualization/17.jpg)

![](https://github.com/ShivankUdayawal/Credit-Risk-Analysis-of-Student-Loan/blob/main/Data%20Visualization/18.jpg)

![](https://github.com/ShivankUdayawal/Credit-Risk-Analysis-of-Student-Loan/blob/main/Data%20Visualization/19.jpg)

![](https://github.com/ShivankUdayawal/Credit-Risk-Analysis-of-Student-Loan/blob/main/Data%20Visualization/20.jpg)

![](https://github.com/ShivankUdayawal/Credit-Risk-Analysis-of-Student-Loan/blob/main/Data%20Visualization/21.jpg)

![](https://github.com/ShivankUdayawal/Credit-Risk-Analysis-of-Student-Loan/blob/main/Data%20Visualization/22.jpg)

![](https://github.com/ShivankUdayawal/Credit-Risk-Analysis-of-Student-Loan/blob/main/Data%20Visualization/23.jpg)

![](https://github.com/ShivankUdayawal/Credit-Risk-Analysis-of-Student-Loan/blob/main/Data%20Visualization/24.jpg)

![](https://github.com/ShivankUdayawal/Credit-Risk-Analysis-of-Student-Loan/blob/main/Data%20Visualization/25.jpg)

![](https://github.com/ShivankUdayawal/Credit-Risk-Analysis-of-Student-Loan/blob/main/Data%20Visualization/26.jpg)

![](https://github.com/ShivankUdayawal/Credit-Risk-Analysis-of-Student-Loan/blob/main/Data%20Visualization/28.jpg)

![](https://github.com/ShivankUdayawal/Credit-Risk-Analysis-of-Student-Loan/blob/main/Data%20Visualization/29.jpg)

![](https://github.com/ShivankUdayawal/Credit-Risk-Analysis-of-Student-Loan/blob/main/Data%20Visualization/30.jpg)

![](https://github.com/ShivankUdayawal/Credit-Risk-Analysis-of-Student-Loan/blob/main/Data%20Visualization/33.jpg)

![](https://github.com/ShivankUdayawal/Credit-Risk-Analysis-of-Student-Loan/blob/main/Data%20Visualization/34.jpg)

![](https://github.com/ShivankUdayawal/Credit-Risk-Analysis-of-Student-Loan/blob/main/Data%20Visualization/35.jpg)

![](https://github.com/ShivankUdayawal/Credit-Risk-Analysis-of-Student-Loan/blob/main/Data%20Visualization/36.jpg)

### Conclusion :
It is recommended to grant loan with the lowest risk for the students, who are enrolled with STEM courses, offered loan with higher interest rate. More preferably, 1st year and 2nd year graduate students, who are not US citizen and not having SSN.

On the other hand, it is riskier to provide loans to the students, who are not enrolled with STEM courses, having low GPA, offered loan with lower interest rate, 3rd Year Undergraduate, 4th Year Undergraduate, beyond 3rd year graduate.

  * There is very little correlation between Early Risk Score and approved loan amount, credit score and GPA. Hence, these variables are not good indicators for risk score


### Business Recommendations :
From the detailed analysis of the data, we can categorise the students in two groups such as high risky and low risky students.

### Low Risky Students
 1. Students enrolled with STEM course.
 2. 1st year graduate and 2nd year graduate students.
 3. Students offered loan with higher interest rate.
 4. STEM course students offered with higher loan amount.
 5. Students, who are not US citizen and not having SSN.
 6. Students, who are Non-US citizen and enrolled with STEM courses.
 7. Students enrolled with STEM course and offered loan with higher interest rate.
 8. Non-US citizen with higher GPA are less risky than US citizen.


### High Risky Students
 1. Students enrolled with Non-STEM courses.
 2. Students beyond 3rd Year Graduate, 3rd Year Undergraduate and 4th Year Undergraduate.
 3. Students offered loan with lower interest rate.
 4. Students, who are US citizen and enrolled with STEM courses.
 5. Students enrolled with Non-STEM courses and low GPA. That means the risk score is high, if a Non-STEM student performs poor.
 6. Students enrolled with a Non-STEM course and offered loan with lower interest rate.
 7. Non-STEM students offered with higher loan amount
