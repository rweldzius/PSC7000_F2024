# PSC4175_F2024

# PSC 4175-01: Introduction to Data Science (Fall 2024)

## Table of Contents

  * [Course Description](#course-description)
  * [Required Applications](#required-applications)
  * [Evaluation & Responsibilities](#evaluation-&-responsibilities)
  * [Course Policies](#course-policies)
  * [Office Hours](#office-hours)
  * [Syllabus](#syllabus)
  * [Helpful Resources](#helpful-resources)
  * [Acknowledgements](#acknowledgements)
    
## Course Description

The use of large, quantitative data sets is increasingly central in social science.  Whether one seeks to understand political behavior, economic outcomes, or violent conflict, the availability of large quantities of data has changed the study of social phenomena. In this course, students will learn about data acquisition, management, and visualization — what we call data science — to answer exciting questions in the social sciences. Whereas most data-related courses focus exclusively on probability theory, matrix algebra, and/or statistical estimation, our main focus will be on the computational tools of data science. Students will leave the course with the ability to acquire, clean, analyze, visualize, and analyze various types of political data using the statistical programming language R, which will set them up for success in future statistical courses (as well as the post-graduation job market). No prior background in statistics is required, but students should be familiar with how to use a computer and have a willingness to learn a variety of data science tools. 

The contents of this repository represent a work-in-progress and revisions and edits are likely frequent.

The main text for the course is "R For Data Science" which can be assessed free online [here](https://r4ds.hadley.nz).

Villanova has an enterprise site license for Microsoft’s Copilot chat application, which is built off of Open A.I.  Copilot is available to all faculty, staff, and students [here](https://copilot.microsoft.com).

[Back to ToC](#table-of-contents)

## Required Applications

### Blackboard

This is the course management software used at Villanova University to support course learning. It is clunky, not user-friendly, and is thankfully on its way out soon. For these reasons, I will only utilize Blackboard to post course materials (e.g., additional readings), for you to submit your assignments, and to see your grades.

### Campuswire

I have set up a Campuswire workspace for our use this semester to help us better communicate with each other. You will need to create an account and join our workspace by following [this link](https://campuswire.com/p/G45092D3C). The secret PIN can be found on the first announcement on Blackboard. You are encouraged to adopt these [Slack etiquette tips](https://slack.com/blog/collaboration/etiquette-tips-in-slack).

Here is the list of channels you should see upon joining the Campuswire workspace:

  * Class feed: A space to post questions and respond to other posts.

  * #announcements: A space for all course announcements.

  * #general: A space for you to share and discuss stories you've seen in the news or on social media that are relevant to our class.

  * Calendar: A calendar containing all lectures, due dates, office hours, and labs.

  * Files: A space for course materials (NOT USED. VISIT BLACKBOARD INSTEAD.)

  * Grades: A space for grades (NOT USED. VISIT BLACKBOARD INSTEAD.)

### GitHub

I have created a [GitHub](https://github.com/rweldzius/PSC4175_F2024/tree/main) repository to prepare and share all course-related content. This very syllabus is available as the repository's README and all links below are connected to the appropriate folders, sub-folders, and files in this repository.

You are expected to adopt the following workflow for this class:

  1. Prior to each lecture, download the appropriate `.Rmd` file, open it in `RStudio`, and read through it. This is your primary homework assignment! As you work through it, try to tweak some of the code and answer the toy examples where provided. Each time you make a change, click the knit button in `RStudio` to see if everything still loads.

  2. During each lecture, create a new `.Rmd` file to take notes in. As with the homework, you should be tweaking and adjusting things on your own, extending your learning beyond what is covered in lecture.

  3. After each lecture, tweak the notes `.Rmd` file further to test out new ideas that you come up with which were not covered in class. Each lecture's slides will be made available as `PDF` for you use to help you review. Thinking creatively about how to modify and extend what we do together might mean you already guess some of the exam questions!

[Back to ToC](#table-of-contents)

## Evaluation & Responsibilities  

Given the nature of the material, participation is not part of your grade. Instead, you will be assigned weekly problem sets beginning with Topic 3 which will test your ability to apply what you've learned in class, and to think creatively about your own data science ideas. These problem sets are assigned on the Monday of each week and are due by **11:59PM Villanova time the following Friday**. You are welcome to collaborate on these problem sets, and are encouraged to ask questions on the Class feed on Campuswire.

There are also two exams. The first is a midterm exam that is scheduled for the Wednesday before Fall break (10/09/2024) and will take place in class. The second exam is a cumulative final that is scheduled for December 18th. 
and a final project. The first is a mid-term exam that is scheduled for October 8th (Tuesday before fall break) and will take place in class. The second exam is a cumulative take-home final that is scheduled to be due December 18th.

The final grade is calculated as a weighted average of these components with the following weights:

  * **Problem sets**: 9 in total, only 8 of which are worth 5 points each for a total of 40 points. This effectively means you can miss a problem set without it hurting your final grade.

  * **Exams**: Midterm and final. The midterm is worth 20 points and is in-class, and the final worth 25 points and is a take-home.

  * **Quizzes**: There are 19 quizzes over the course of the semester which can only be taken if you attend class. Each consist of several questions plus an attendance statement. 0.5 points comes from accurately answering all five questions, and 0.5 points comes from signing the attendance statement. Each quiz is worth 1 point of your final grade, and combined comprise the final 15 points, meaning that 4 are not counted toward your final grade.

  * **Extra Credit**: There is one extra credit point on each problem set, and five extra credit points on the midterm and final. Thus the maximum total points you can receive in this class is 128, meaning that if you ace every problem set, the midterm, and every quiz, you will have 98 points before the final exam. Achieving a perfect score requires a lot of effort, but would theoretically allow you to skip the final exam if you so chose.

See the table below for a breakdown of the percentages, points, and extra credit.

| Item | Percent | Points | EC | Max |
|:-----|:-----:|:-----:|:-----:|:-----:|
| pset1 | 5% | 5 | 1 | 6 |
| pset2 | 5% | 5 | 1 | 6 |
| pset3 | 5% | 5 | 1 | 6 |
| pset4 | 5% | 5 | 1 | 6 |
| pset5 | 5% | 5 | 1 | 6 |
| pset6 | 5% | 5 | 1 | 6 |
| pset7 | 5% | 5 | 1 | 6 |
| pset8 | 5% | 5 | 1 | 6 |
| pset9 | 0% | 0 | 6 | 6 |
| Midterm | 20% | 20 | 5 | 25 |
| Final | 25% | 25 | 5 | 30 |
| Quizzes | 15% | 15 | 4 | 19 |
| **Totals** | **100%** | **100** | **28** | **128** |

Letter grades are determined as per the standard Villanova grading system, reproduced below:

  * A: 94+
  * A-: 90-93
  * B+: 87-89
  * B: 84-86
  * B-: 80-83
  * C+: 77-79
  * C: 74-76
  * C-: 70-73
  * D+: 67-69
  * D: 64-66
  * D-: 60-63
  * F: <60

[Back to ToC](#table-of-contents)

## Course Policies

### Attendance

Students are entitled to one excused absence for any reason that may contribute to their personal wellness. Students must advise the instructor by email before class of their intent to utilize a Personal Day as the reason for their absence. A Personal Day will not be approved retroactively. Students may, but are not required, to provide additional information regarding their absence. Additionally, a Personal Day may not:

  * be used immediately preceding or following a University holiday or break period;
  * be used on days when exams, presentations or other major assignments are scheduled.

A Personal Day does not grant an automatic extension for items due. Students remain responsible for all assignments, exams, presentations, etc. due on that date. It is in the instructor’s discretion to determine whether any extension is appropriate given individual circumstances.

Quizzes will not be excused due to an absence (excused or unexcused). Remember you have four "freebies" so use these wisely. 

### Late Assignments

Every problem set is assigned on a Monday, and due on Blackboard by **11:59PM Villanova time on the following Friday**. Problem sets should be submitted via Blackboard. The problem sets are designed to require no more than two hours in total to complete. Late submissions will be **penalized 1 point off for each day late**. After three days, problem sets will no longer be accepted and will be scored 0. (But also remember that your lowest scoring problem set will not be counted toward your final grade, effectively giving you one "freebie".) Answer keys for the preceding week's problem set are posted on Wednesdays after class.

### Cell Phones, Laptops, Tablets, etc.

You are expected to bring your laptop to class in order to work through the `.Rmd` file during the lecture. These `.Rmd` files will be posted to the GitHub repository at least 24 hours prior to the lecture. Students are encouraged to download these files and work through them prior to class.

You are asked to silence your cell phone / tablet / smart watch before class begins.

### Academic Honor Code

All students are expected to uphold Villanova’s Academic Integrity Policy and Code. Any incident of academic dishonesty will be reported to the Dean of the College of Liberal Arts and Sciences for disciplinary action. You may view the [University’s Academic Integrity Policy and Code](https://www1.villanova.edu/villanova/provost/resources/student/policies/integrity/code.html) for a detailed description.

If a student is found responsible for an academic integrity violation, which results in a grade penalty, they may not WX the course unless they are approved to WX for significant medical reasons. Students applying for a WX based on significant medical reasons, must submit documentation and their request for an exception will be considered.

Collaboration is the heart of data science, but your work on your assignments should be your own. Please be careful not to plagiarize. The above link is a very helpful guide to understanding plagiarism. In particular, while students are invited to work on problem sets together, collaboration is prohibited on the midterm and final exams.

Academic misconduct includes, but is not limited to, cheating, fabrication, plagiarism, altering graded examinations for additional credit, having another person take an examination for you, falsification of results, or facilitating academic dishonesty or as further specified in the university policy found at the website above. These and other forms of cheating are all potentially grounds for penalties including failure of the assignment or the course, as well as program- or university-level disciplinary action.

ChatGPT and related Large Language Models (LLMs) are essential tools in the data scientist's toolkit, and acceptable resources for completing the assignments and learning concepts at a deeper level. However, graded assignments cannot be generated purely by these tools. All assignments must include a log of the ChatGPT prompts and resulting output used to complete the assignment.

### Office for Access & Disability Services (ADS) and Learning Support Services (LSS)

It is the policy of Villanova to make reasonable academic accommodations for qualified individuals with disabilities. All students who need accommodations should go to Clockwork for Students via myNOVA to complete the Online Intake or to send accommodation letters to professors. Go to the LSS website http://learningsupportservices.villanova.edu or the ADS website https://www1.villanova.edu/university/student-life/ods.html for registration guidelines and instructions. If you have any questions please contact LSS at 610-519-5176 or learning.support.services@villanova.edu, or ADS at 610-519-3209 or ods@villanova.edu.

### Absences for Religious Holidays

Villanova University makes every reasonable effort to allow members of the community to observe their religious holidays, consistent with the University’s obligations, responsibilities, and policies. Students who expect to miss a class or assignment due to the observance of a religious holiday should discuss the matter with their professors as soon as possible, normally at least two weeks in advance. Absence from classes or examinations for religious reasons does not relieve students from responsibility for any part of the course work required during the absence. https://www1.villanova.edu/villanova/provost/resources/student/policies/religiousholidays.html.

[Back to ToC](#table-of-contents)

## Office Hours

  * M & W 1-2pm in SAC 257
  * You must make an appointment for office hours here: https://calendly.com/weldzius/officehours
  * If you cannot make my office hours, please email me your availability at least 24-hours in advance and we can try to find a time that works.

[Back to ToC](#table-of-contents)

## Syllabus

| Date | Topic | Learing Goal | Materials | HW | Pset |
|:-----|:-----|:-----|:-----|:-----|:-----|
| 8/26/24 | Introduction | Scientific method, camps of analysis | | | |
| 8/28/24 | Intro to R 1 | Objects, functions, and code | | | |
| 9/2/24 | No Class | | |
| 9/4/24 | Intro to R 2 | Visualization in R | | | |
| 9/9/24 | Intro to R 3 | More visualization | | | |
| 9/11/24 | Data Wrangling | Replicability and tabular data | | | |
| 9/16/24 | Univariate Analysis | Summaries of a single variable | | | |
| 9/18/24 | Multivariate 1 | Summaries of multiple variables | | | |
| 9/23/24 | Multivariate 2 | Visualizations of multiple variables | | | |
| 9/25/24 | Multivariate 3 | Visualizations of multiple variables | | | |
| 9/30/24 |  Review Session |  | | | |
| 10/2/24 | Uncertainty 1 | Uncertainty and bootstrapping | | | |
| 10/7/24 | Uncertainty 2 | Confidence statements |  | | |
| 10/9/24 | Midterm Exam |  | | | |
| 10/14/24 | Fall Break |  | | | |
| 10/16/24 | Fall Break |  |  | | |
| 10/21/24 | Regression 1 | Interpreting output and evaluating model |  | | |
| 10/23/24 | Regression 2 | Interpreting output and evaluating model | | | |
| 10/28/24 | Regression 3 | Multiple regression, categorical Xs | | | |
| 10/30/24 | Review Session | Regression | | | |
| 11/4/24 | Classification 1 | The concept of logistic regression |  | | |
| 11/6/24 | Classification 2 | Interpreting output and evaluating model | | |  |
| 11/11/24 | Classification 3 | Interpreting output and evaluating model |  | | |
| 11/13/24 | Clustering | k-means clustering |  | | |
| 11/18/24 | NLP 1 | k-means clustering on text |  |  | |
| 11/20/24 | NLP 2 | Sentiment analysis |  | | |
| 11/25/24 | Review Session | Clustering |  | | |
| 11/27/24 | No Class |  |  | | |
| 12/2/24 | Ethics | The risks of rapid technological change |  | | |
| 12/4/24 | Spillover day | |  | | |
| 12/9/24 | Spillover day | |  | | |
| 12/11/24 | Review Session | Cumulative |  | | |
| 12/18/24 | Final Exam Due | |  | | |

[Back to ToC](#table-of-contents)

## Helpful Resources

[Rstudio Cheat Sheet: Data Wrangling](https://www.rstudio.com/wp-content/uploads/2015/02/data-wrangling-cheatsheet.pdf}

[Rstudio Cheat Sheet: ggplot2]([https://github.com/rstudio/cheatsheets/raw/master/data-visualization.pdf](https://hbctraining.github.io/Intro-to-R-flipped/cheatsheets/data-visualization-2.1.pdf))

[R-graphics Cookbook](http://www.cookbook-r.com/Graphs/)

[... And the full list of Rstudio cheat sheets](https://posit.co/resources/cheatsheets/)

[Tidymodels Resources](https://www.tidymodels.org/learn/)

[Back to ToC](#table-of-contents)

## Acknowledgements

The contents of this course and of my teaching pedagogy are influenced and inspired by Prof. James H. Bisbee, Vanderbilt University. This course is modeled on the course of the same name, taught by Professors Josh Clinton and William Doyle in the spring of 2022 at Vanderbilt University. The lectures on data science & ethics are inspired by content prepared for the Summer Institutes for Computational Social Sciences (SICSS), and by presentations on machine learning and ethics prepared by Andrew Princep (@AJPrincep). The syllabus is heavily inspired by Emily Hencken Ritter's syllabi for PSCI 3270, Politics of Human Rights.
