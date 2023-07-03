## **Module-to-Module Retention Analysis for Moringa's Software Development Programme Solution** 

#### **Question 1. Clean up the provided data with the following assumptions:**


    - Students that have none of the above metrics stated is presumed to have dropped out of the module and should not count towards the final enrolment number for that module.

    -  Students that scored below 50% in a module and are not shown to be enrolled in one of the next modules are presumed to have failed and should be excluded when calculating module-to-module retention (See Q2.)

    -  Students that pass Angular can enrol in either Java or Python but not both.

    -  Students that pass Java can proceed to take Android but not Django.

    -  Students that pass Python can proceed to take Django but not Android.

    - Students that pass either Android or Django can proceed to take Professional Development.


 [Exploratory Data Analysis Solution](https://github.com/HarunMbaabu/module-retention-analytics/blob/main/Main%20File%20-%20Exploratory%20Data%20Analysis%20.ipynb)


#### **Question 2. Determine the module-to-module retention rates for each of the modules. (e.g. Intro to Software Development -> Angular : x%).**  
[Module-to-Module Retention Rates Solution](https://github.com/HarunMbaabu/module-retention-analytics/blob/main/Module-to-Module%20Retention%20Rates.ipynb)


#### **Question 3. Which of the metrics above is most correlated to the module-to-module retention rate? List them in order of most to least correlated. (Include any charts and tables necessary to explain your answer.)**
[Module Metrics Correlation Solution ](https://github.com/HarunMbaabu/module-retention-analytics/blob/main/Module%20Metrics%20Correlation.ipynb)


#### **Question 4. If Moringa had to pick 2 metrics out of the above listed ones to help improve module-to-module retention, which should we pick and why (Include any charts and tables necessary to explain your answer.)**

[Two Metrics To Help Improve Rentention Solution](https://github.com/HarunMbaabu/module-retention-analytics/blob/main/Two%20Metrics%20To%20Help%20Improve%20Retention%20Solution.ipynb)





#### **Question 5. What other metrics, in your opinion, do you think Moringa should be measuring to better predict our module-to-module retention and why?** 

To better predict module-to-module retention, I think it would be important to measure the following additional metrics, metrics can complement the existing ones and provide a more comprehensive understanding of students' engagement, progress, and support systems within the program. 

- **Peer-to-Peer Interaction:** Monitoring the extent of peer interaction and collaboration among students can be valuable. Metrics such as forum participation, group project involvement, or peer feedback can indicate a sense of community and support within the program. Students who actively engage with their peers are more likely to have a positive learning experience and continue with the program.
- **Self-Assessment and Reflection:** Including metrics that capture students' self-assessment and reflection on their learning journey can provide valuable insights into their motivation, self-awareness, and growth mindset. Metrics like self-evaluation surveys, goal-setting activities, and reflective journals can help identify students' perceptions of their progress and areas for improvement.
- **Questions and Assessment Scores:** Regular quizzes and assessments help gauge students' comprehension and retention of the course content. Tracking their performance in these assessments can provide early indicators of their understanding and progress. Low scores might suggest areas of difficulty where additional support or intervention could be beneficial.
- **Learning Progression:** Keeping track of students' progression through the course material and modules can give a sense of their pace and consistency. Metrics such as module completion rates, time taken to complete each module, and progression milestones can help identify students who might be falling behind or struggling to keep up with the program's demands. 

**My Conclusion:**
By analyzing these metrics alongside the existing ones, we can gain deeper insights into the factors influencing module-to-module retention and make data-driven decisions to improve the overall student experience and success rate.

Considering the speculative nature of this question, the suggested metrics serve as a starting point, and the actual implementation and validation of these metrics would require careful experimentation and analysis within the specific context of Moringa's Software Development program.






