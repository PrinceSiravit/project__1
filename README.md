# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Standardized Test Analysis


### Problem Statement

*Why the government should abolish the ACT and SAT?*

---

### Datasets

#### Provided Data


* [`act_2017.csv`](./data/act_2017.csv): 2017 ACT Scores by State ([source](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows))
* [`act_2018.csv`](./data/act_2018.csv): 2018 ACT Scores by State ([source](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows))
* [`act_2019.csv`](./data/act_2019.csv): 2019 ACT Scores by State ([source](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows))

* [`sat_2017.csv`](./data/sat_2017.csv): 2017 SAT Scores by State ([source](https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/))
* [`sat_2018.csv`](./data/sat_2018.csv): 2018 SAT Scores by State ([source](https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/))
* [`sat_2019.csv`](./data/sat_2019.csv): 2019 SAT Scores by State ([source](https://blog.prepscholar.com/average-sat-scores-by-state-most-recent))


#### Background and Additional Data

The SAT and ACT are standardized tests that many colleges and universities in the United States require for their admissions process. This score is used along with other materials such as grade point average (GPA) and essay responses to determine whether or not a potential student will be accepted to the university.

The SAT has two sections of the test: Evidence-Based Reading and Writing and Math ([*source*](https://www.princetonreview.com/college/sat-sections)). The ACT has 4 sections: English, Mathematics, Reading, and Science, with an additional optional writing section ([*source*](https://www.act.org/content/act/en/products-and-services/the-act/scores/understanding-your-scores.html)). They have different score ranges, which you can read more about on their websites or additional outside sources (a quick Google search will help you understand the scores for each test):
* [SAT](https://collegereadiness.collegeboard.org/sat)
* [ACT](https://www.act.org/content/act/en.html)

Standardized tests have long been a controversial topic for students, administrators, and legislators. Since the 1940's, an increasing number of colleges have been using scores from sudents' performances on tests like the SAT and the ACT as a measure for college readiness and aptitude ([*source*](https://www.minotdailynews.com/news/local-news/2017/04/a-brief-history-of-the-sat-and-act/)). Supporters of these tests argue that these scores can be used as an objective measure to determine college admittance. Opponents of these tests claim that these tests are not accurate measures of students potential or ability and serve as an inequitable barrier to entry. Lately, more and more schools are opting to drop the SAT/ACT requirement for their Fall 2021 applications ([*read more about this here*](https://www.cnn.com/2020/04/14/us/coronavirus-colleges-sat-act-test-trnd/index.html)).

Collegeboard and ACT originally created the `SAT/ACT` test to diversify students admitted into the Ivy League, but instead, it only admits middle and upper-class white students to the top colleges. Colleges should not require students to take the `ACT/SAT` to gain admission because the test cannot fully measure a student’s intelligence and college preparedness. These exams unfairly and inaccurately measure students’ intelligence and eligibility for college, students’ GPA, and grade can as well. Intelligence can vary in numerous areas, not just in school. CollegeBoard announced in January 2022 that they will move the SAT online and cut down the test from three hours to two hours long in 2024. However, these actions will not change anything, and the `SAT/ACT` will remain unfair.

The `ACT/SAT` exhibits social inequality, favoring people who can afford to pay for preparation for the `SAT`, and hurting those that come from low-income families, not receive educational opportunities. SAT prep books and tutoring classes rack up a massive bill for students. Registering for the tests can prove costly; the `ACT` and `SAT` costs are 55 U.S dollar and 60 U.S.dollar  Various families can only pay for one while a handful cannot pay for either. Several students can afford to take the test more than two or three times to achieve a satisfactory score, but a handful of families can only pay for their child to take the exam once. If the child fails to achieve a satisfactory score, they ruin their chance to get admitted to the college of their choice.

About 51 universities and colleges have dropped the `ACT/SAT` requirement for at least fall 2021 in recent months, according to a list by the National Center for Fair and Open Testing, or FairTest, a nonprofit organization working to end the misuse of standardized testing.

They include Boston University, which announced it's going test-optional for students applying for the fall 2021 and spring 2022 semesters, and the University of California, which said all nine of the schools in its system would suspend the requirement for students applying for fall 2021.

Harvard University extended its optional policy for the `SAT` and `ACT` exams for applicants through 2026 in an announcement Thursday.

The Ivy League school in Cambridge, Massachusetts, previously announced in 2020 that standardized tests would be optional for a year due to the limited access to testing sites students faced. After, it extended the policy for another year, then again this week through 2026.

---

### Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**state**|object|df_act_all|U.S. state
|**participation_act_2017**|float|df_all| ACT's participation rate in each state in U.S. 2017.
|**total_score_act_2017**|float|df_all| ACT's total average score in each state in U.S. 2017.
|**participation_act_2018**|float|df_all| ACT's participation rate in each state in U.S. 2018.
|**total_score_act_2018**|float|df_all| ACT's total average score in each state in U.S. 2018.
|**participation_act_2019**|float|df_all| ACT's participation rate in each state in U.S. 2019.
|**total_score_act_2019**|float|df_all| ACT's total average score in each state in U.S. 2019.
|**participation_sat_2017**|float|df_all| SAT's participation rate in each state in U.S. 2017.
|**total_score_sat_2017**|integer|df_all| SAT's total average score in each state in U.S. 2017.
|**participation_sat_2018**|float|df_all| SAT's participation rate in each state in U.S. 2018.
|**total_score_sat_2018**|integer|df_all| SAT's total average score in each state in U.S. 2018.
|**participation_sat_2019**|float|df_all| SAT's participation rate in each state in U.S. 2019.
|**total_score_sat_2019**|integer|df_all| SAT's total average score in each state in U.S. 2019.
|**act_free**|boolean|df_all| State Offer the ACT for Free.
|**sat_free**|boolean|df_all| State Offer the SAT for Free.


---

### Conclusion

From the testing result, it shows that ACT and SAT participation rate and total score have a negative relationship and free testing offer is a factor to motivate the ACT and SAT participation.

Thus, it can explain like this. If the free testing offer is increased, it make average total score decreased or people who came to test's quality decreased due to an increasing of quantity. 

Although the participation rate is increased, the way to get a free offering still have many condition to be a fee waiver which is not suitable for low income family. ([*source*](https://blog.prepscholar.com/sat-fee-waiver-complete-guide))

Thus, The ACT&SAT exhibits social inequality, favoring people who can afford to pay for preparation for the SAT, and hurting those that come from low-income families, not receive educational opportunities. 

Opportunities may not come to the right person, in the right place, and at the right time.

---

### Recommendation


##### For the government, 
Un-supported states for given ACT and SAT for free still have 19 states. It means inequlity. Although, some state support it but doesn't mean no condition for applying. Thus, the government should ebolish ACT&SAT which lead to solve inequality in society. Moreover, the government should find a way to promote students who need to join in university equally.


##### For colleges, 

They should focus on students’ grades, GPA, essays, extracurriculars and recommendations to determine one’s eligibility to enter college. People take the SAT/ACT from all kinds of backgrounds; certain students with high GPAs and grades do not achieve a strong score, destroying their chances to apply to a school of their choice. SAT/ACT should not hinder students from entering college. They prevent them from earning scholarships and entering the college of their dreams. 

---














