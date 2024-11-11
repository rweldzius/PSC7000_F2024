# PSC 7000-01: Research Concepts & Methods (Fall 2024)

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

This graduate-level course delves into the foundational concepts and advanced techniques of empirical research in political science. In the
first half of the course, students will complete an in-depth exploration of qualitative research methods in political science, with a primary
focus on the principles outlined in the seminal text, Designing Social Inquiry by King, Keohane, and Verba. Students will engage with the
theoretical and practical aspects of qualitative research, learning to design, conduct, and analyze qualitative studies effectively.
In the second half of the course, students will get an introduction to quantitative methods. The use of large, quantitative data sets is
increasingly central in social science. Whether one seeks to understand political behavior, economic outcomes, or violent conflict, the
availability of large quantities of data has changed the study of social phenomena. Our main focus will be on the computational tools of data
science. Students will leave the course with the ability to acquire, clean, analyze, visualize, and analyze various types of political data using
the statistical programming language R, which will set them up for success in future statistical courses (as well as the post-graduation job
market).

Learning Outcomes: By the end of this course, students will be able to:

  * Critically evaluate qualitative and quantitative research designs and methodologies.
  * Conduct rigorous research projects.
  * Analyze and interpret data effectively.
  * Apply ethical principles in social science research.

The contents of this repository represent a work-in-progress and revisions and edits are likely frequent.

The main texts for the course are [Designing Social Inquiry](https://press.princeton.edu/books/hardcover/9780691224633/designing-social-inquiry?srsltid=AfmBOopwysQS7rAU4Cmd9uTW_uQvUrExL6ESjrgQ0sYB5d6h82MAUeIL) which can be purchased at the Villanova bookstore and "R For Data Science" which can be assessed free online [here](https://r4ds.hadley.nz).

Villanova has an enterprise site license for Microsoft’s Copilot chat application, which is built off of Open A.I.  Copilot is available to all faculty, staff, and students [here](https://copilot.microsoft.com).

**Class time and location**: M/ 7:30-9:30 in Bartley Hall 2045.

[Back to ToC](#table-of-contents)

## Required Applications

### Blackboard

This is the course management software used at Villanova University to support course learning. It is clunky, not user-friendly, and is thankfully on its way out soon. For these reasons, I will only utilize Blackboard to post course materials (e.g., additional readings), for you to submit your assignments, and to see your grades.

### Campuswire

I have set up a Campuswire workspace for our use this semester to help us better communicate with each other. You will need to create an account and join our workspace by following [this link](https://campuswire.com/p/G45092D3C). The secret PIN can be found on the first announcement on Blackboard. You are encouraged to adopt these [Slack etiquette tips](https://slack.com/blog/collaboration/etiquette-tips-in-slack). Most likely, you will utilize a similar communication system at a future job, so use this time wisely as you adopt best practices. 

Here is the list of channels you should see upon joining the Campuswire workspace:

  * Class feed: A space to post questions and respond to other posts.

  * #announcements: A space for all course announcements.

  * #general: A space for you to share and discuss stories you've seen in the news or on social media that are relevant to our class.

  * Calendar: Not used. See [Syllabus](#syllabus) below. 

  * Files: Not used. See [Syllabus](#syllabus) below. 

  * Grades: Not used. See Blackboard. 

### GitHub

I have created a [GitHub](https://github.com/rweldzius/PSC7000_F2024/tree/main) repository to prepare and share all course-related content. This very syllabus is available as the repository's README and all links below are connected to the appropriate folders, sub-folders, and files in this repository.

Starting the week of October 21, you are expected to adopt the following workflow for this class:

  1. Prior to each lecture, download the appropriate `.Rmd` file, open it in `RStudio`, and read through it. This is your primary homework assignment (ungraded). As you work through it, try to tweak some of the code and answer the toy examples where provided. Each time you make a change, click the knit button in `RStudio` to see if everything still loads.

  2. During each lecture, create a new `.Rmd` file to take notes in. As with the homework, you should be tweaking and adjusting things on your own, extending your learning beyond what is covered in lecture.

  3. After each lecture, tweak the notes `.Rmd` file further to test out new ideas that you come up with which were not covered in class. Each lecture's slides will be made available as `PDF` for you use to help you review. Thinking creatively about how to modify and extend what we do together might mean you already guess some of the exam questions!

[Back to ToC](#table-of-contents)

## Evaluation & Responsibilities  

As with learning any new topic or language, the best strategy is to put in a little effort every day. To this end, you will be assigned homework assignments for each class (see "workflow" above) that correspond with readings from the text. I recommend you read through the book first to get an overview of the topic and then attack the homework. 

In the first half of the course, you will each work on building a research project that you can then test in the second half of the course. To this end, in weeks 1-7 you will begin to build your research project by identifying a puzzle in the field, develop a testable research question and argument, and plan a qualitative method for testing your argument. Each week, you will find and read a scholarly political science article that discusses, uses, or describes a topic from that week (Google Scholar will be helpful in this exercise). You will then summarize the article in a one-page memo that identifies the puzzle the author(s) seek to address, the research question, the argument, the method for testing the argument, and brief (1-2 sentences) overview of the findings. You should choose articles that are related to your own research project as this exercise will help you in building your literature review (or what will constitute as the "gap in the literature" for your project). Each week I will choose (at random) three of you to present your memo to the class. Thus, along with your memos, you should prepare three slides for each of the topics from your memo (Slide 1: puzzle; Slide 2: question and argument; Slide 3: method and result). 

In the week before fall break, we will hold a mini-conference in which each of you will present your research project proposals, which will include (not surprisingly) the puzzle, question, argument, and method for testing. You will use the feedback from the mini-conference to complete your proposals by the end of the week.

In the second half of the course, you will use quantitative data to test your argument and/or motivate/describe your research puzzle. In class, as we work through the lecture material, please ask questions. Participation is key for your learning, but it will not be a part of your grade in this second half of class. Instead, you will be assigned weekly problem sets that will test your ability to apply what you've learned in class, and to think creatively about your own data science ideas. These problem sets are assigned on the Monday of each week and are due by **11:59PM Villanova time the following Friday**. You are welcome to collaborate on these problem sets, and are encouraged to ask questions on the Class feed on Campuswire.

Similar to the mini-conference in Week 7, in the final two weeks of class we will host a proper conference during class. Each student will present their project for approximately 8-10 minutes and then in the remaining 10 minutes they will take comments from the class. This is meant to help you as you continue to finish your project, which will be due on **December 16th by 12pm Villanova time**.

The final grade is calculated as a weighted average of these components with the following weights:

  * **Weekly Memos**: 4 in total, worth 2 points each. Your presentation will be worth 2 points, for a total of 10 points.
  * **Problem sets**: 6 in total, only 5 of which are worth 5 points each for a total of 25 points. This means you can miss a problem set without it hurting your final grade.
  * **Midterm Project**: The project is worth 20 points (5 points for the presentation).
  * **Final Project**: The project is worth 35 points (10 points for the presentation).
  * **Participation**: Your participation during the first half of the course, as well as during the class presentations will be worth 10 points.

See the table below for a breakdown of the percentages and points.

| Item | Percent | Points | 
|:-----|:-----:|:-----:|
| pset1 | 5% | 5 |
| pset2 | 5% | 5 |
| pset3 | 5% | 5 |
| pset4 | 5% | 5 |
| pset5 | 5% | 5 |
| pset6 | 0% | 0 |
| Weekly Memos | 10% | 10  |
| Participation | 10% | 10  |
| Midterm project | 20% | 20 |
| Final project | 35% | 35 | 
| **Totals** | **100%** | **100** | 

Letter grades are determined as per the standard Villanova grading system:

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

Every problem set is assigned on a Monday and due on Blackboard by **11:59PM Villanova time on the following Friday**. Problem sets should be submitted via Blackboard. The problem sets are designed to require no more than two hours in total to complete. Late submissions will be **penalized 1 point off for each day late**. After three days, problem sets will no longer be accepted and will be scored 0. Remember that your lowest scoring problem set will not be counted toward your final grade, effectively giving you one "freebie;" use it wisely! Answer keys for the preceding week's problem set are posted on Wednesdays after class.

### Cell Phones, Laptops, Tablets, etc.

You are expected to bring your laptop to class in order to work through the `.Rmd` file during the lecture. These `.Rmd` files will be posted to the GitHub repository at least 24 hours prior to the lecture. Students are encouraged to download these files and work through them prior to class.

You are asked to silence your cell phone / tablet / smart watch before class begins.

### Academic Honor Code

All students are expected to uphold Villanova’s Academic Integrity Policy and Code. Any incident of academic dishonesty will be reported to the Dean of the College of Liberal Arts and Sciences for disciplinary action. You may view the [University’s Academic Integrity Policy and Code](https://www1.villanova.edu/villanova/provost/resources/student/policies/integrity/code.html) for a detailed description.

If a student is found responsible for an academic integrity violation, which results in a grade penalty, they may not WX the course unless they are approved to WX for significant medical reasons. Students applying for a WX based on significant medical reasons, must submit documentation and their request for an exception will be considered.

Collaboration is the heart of data science, but your work on your assignments should be your own. Please be careful not to plagiarize. The above link is a very helpful guide to understanding plagiarism. In particular, while students are invited to work on problem sets together, collaboration is prohibited on the midterm and final exams.

Copilot and related Large Language Models (LLMs) are essential tools in the data scientist's toolkit, and acceptable resources for completing the assignments and learning concepts at a deeper level. However, graded assignments cannot be generated purely by these tools. All assignments must include a log of the Copilot prompts and resulting output used to complete the assignment.

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

| Date | Topic | Learning Goal | Materials | HW | Pset |
|:-----|:------|:------|:------|:------|:------|
| 8/26/24 | Introduction | Scientific Method | KKV 1 | | |
| 9/2/24 | No Class | | Schedule office hour appt. before 10/7 | Research Topic | |
| 9/9/24 |  Descriptive Inference  |   | KKV 2  |  Memo 1 |   |
| 9/16/24  | Causality  | Causality & Causal Inference  | KKV 3  | Memo 2  |   |
| 9/23/24  | Observe/avoid  | Determining/understanding what to observe/avoid  | KKV 4-5  | Memo 3  |   |
| 9/30/24  | Observations  | Increasing the number of observations  | KKV 6  | Memo 4  |   |
| 10/7/24  | Mini-conference  |   |   |   |   |
| 10/14/24  | Fall Break  |   |   |   | [PS 0](https://github.com/rweldzius/PSC7000_F2024/blob/main/Psets/psc7000_pset_0.Rmd)  |
| 10/21/24  | Intro to R  | Objects, functions, code, visualization  | [Lecture 1](https://rweldzius.github.io/PSC7000_F2024/Lectures/psc7000_lecture_1_slides.html)  |  [HW1](https://github.com/rweldzius/PSC7000_F2024/blob/main/Homeworks/psc7000_hw_1.Rmd) |  [PS1](https://github.com/rweldzius/PSC7000_F2024/blob/main/Psets/psc7000_pset_1.Rmd) [PS1_AK](https://rweldzius.github.io/PSC7000_F2024/Psets/psc7000_pset_1_AK.html) |
| 10/28/24  | Data Wrangling & Univariate Analysis  |   |  [Lecture 2](https://rweldzius.github.io/PSC7000_F2024/Lectures/psc7000_lecture_2_slides.html)   | [HW2](https://github.com/rweldzius/PSC7000_F2024/blob/main/Homeworks/psc7000_hw_2.Rmd) | [PS2](https://github.com/rweldzius/PSC7000_F2024/blob/main/Psets/psc7000_pset_2.Rmd)   |
| 11/4/24  | Multivariate Analysis  |   | [Lecture 3](https://rweldzius.github.io/PSC7000_F2024/Lectures/psc7000_lecture_3_slides.html)    | [HW3](https://github.com/rweldzius/PSC7000_F2024/blob/main/Homeworks/psc7000_hw_3.Rmd) | [PS3](https://github.com/rweldzius/PSC7000_F2024/blob/main/Psets/psc7000_pset_3.Rmd)  |
| 11/11/24 |  Uncertainty   |   |   | [HW4](https://github.com/rweldzius/PSC7000_F2024/blob/main/Homeworks/psc7000_hw_4.Rmd) | [PS4](https://github.com/rweldzius/PSC7000_F2024/blob/main/Psets/psc7000_pset_4.Rmd)   |
| 11/18/24  | Regression   |   |   | [HW5](https://github.com/rweldzius/PSC7000_F2024/blob/main/Homeworks/psc7000_hw_5.Rmd) | [PS5](https://github.com/rweldzius/PSC7000_F2024/blob/main/Psets/psc7000_pset_5.Rmd)   |
| 11/25/24  | Classification & Clustering  |   |   | [HW6](https://github.com/rweldzius/PSC7000_F2024/blob/main/Homeworks/psc7000_hw_6.Rmd) | [PS6](https://github.com/rweldzius/PSC7000_F2024/blob/main/Psets/psc7000_pset_6.Rmd)   |
| 12/2/24  | Conference  |   |   |   |   |
| 12/9/24  |  Conference |   |   |   |   |
| 12/16/24  | Final Projects Due  |   |   |   |   |

[Back to ToC](#table-of-contents)

## Helpful Resources

[Rstudio Cheat Sheet: Data Wrangling](https://www.rstudio.com/wp-content/uploads/2015/02/data-wrangling-cheatsheet.pdf)

[Rstudio Cheat Sheet: ggplot2](https://hbctraining.github.io/Intro-to-R-flipped/cheatsheets/data-visualization-2.1.pdf)

[R-graphics Cookbook](http://www.cookbook-r.com/Graphs/)

[... And the full list of Rstudio cheat sheets](https://posit.co/resources/cheatsheets/)

[Tidymodels Resources](https://www.tidymodels.org/learn/)

[Back to ToC](#table-of-contents)

## Acknowledgements

The contents of this course are influenced by and often come directly from Prof. James H. Bisbee who teaches a similar course at Vanderbilt University. I am indebted to him for making his course materials available. 
