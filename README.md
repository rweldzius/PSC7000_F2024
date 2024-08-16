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
|:-----:|:-----:|:-----:|:-----:|:-----:|
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



## Learning Outcomes

### **[INSTRUCTOR NOTE: PLEASE LIST (3-5) LEARNING OUTCOMES]**

By the end of the course, you will be able to ...

1. Identify & Describe
1. Explain
1. Compare & Contrast
1. Design & Implement
1. Practice


## Schedule

---

**[INSTRUCTOR NOTE: PLEASE REMOVE THIS BEFORE MAY 31]**

Please pick from a template below and delete the other ones


---

### **M/W TECH Template [PLEASE REMOVE THIS HEADER BEFORE MAY 31]**

**Course Dates:** Monday, May 31 – Wednesday, July 14, 2021 (7 weeks)

**Class Times:** Monday, Wednesday at 4:00pm–5:30pm (12 class sessions)

| Class |          Date          |                 Topics                  |
|:-----:|:----------------------:|:---------------------------------------:|
|  - |  Mon, May 31         | **No Class - Memorial Day** |
|  1 |  Wed, June 2         | [Lesson 1] |
|  2 |  Mon, June 7         | [Lesson 2] |
|  3 |  Wed, June 9         | [Lesson 3] |
|  4 |  Mon, June 14        | [Lesson 4] |
|  5 |  Wed, June 16        | [Lesson 5] |
|  6 |  Mon, June 21        | [Lesson 6] |
|  7 |  Wed, June 23        | [Lesson 7] |
|  8 |  Mon, June 28        | [Lesson 8] |
|  9 |  Wed, June 30        | [Lesson 9] |
| -  |  Mon, July 5         | **No Class - Independence Day Observed** |
| 10 |  Wed, July 7         | [Lesson 10] |
| 11 |  Mon, July 12        | [Lesson 11] |
| 12 |  Wed, July 14        | Final Exam/Presentations |

---

### **M/W S&L Template [PLEASE REMOVE THIS HEADER BEFORE MAY 31]**

**Course Dates:** Monday, May 31 – Wednesday, July 28, 2021 (9 weeks)

**Class Times:** Monday, Wednesday at 4:00pm–5:30pm (16 class sessions)

| Class |          Date          |                 Topics                  |
|:-----:|:----------------------:|:---------------------------------------:|
|  - |  Mon, May 31         | **No Class - Memorial Day** |
|  1 |  Wed, June 2         | [Lesson 1] |
|  2 |  Mon, June 7         | [Lesson 2] |
|  3 |  Wed, June 9         | [Lesson 3] |
|  4 |  Mon, June 14        | [Lesson 4] |
|  5 |  Wed, June 16        | [Lesson 5] |
|  6 |  Mon, June 21        | [Lesson 6] |
|  7 |  Wed, June 23        | [Lesson 7] |
|  8 |  Mon, June 28        | [Lesson 8] |
|  9 |  Wed, June 30        | [Lesson 9] |
| -  |  Mon, July 5         | **No Class - Independence Day Observed** |
| 10 |  Wed, July 7         | [Lesson 10] |
| 11 |  Mon, July 12        | [Lesson 11] |
| 12 |  Wed, July 14        | [Lesson 12] |
| 13 |  Mon, July 19        | [Lesson 13] |
| 14 |  Wed, July 21        | [Lesson 14] |
| 15 |  Mon, July 26        | [Lesson 15] |
| 16 |  Wed, July 28        | Final Exam/Presentations |


---

### **Tu/Th TECH Template [PLEASE REMOVE THIS HEADER BEFORE MAY 31]**

**Course Dates:** Tuesday, June 1 – Thursday, July 15, 2021 (7 weeks)

**Class Times:** Tuesday, Thursday at 4:00pm–5:30pm (14 class sessions)

| Class |          Date          |                 Topics                  |
|:-----:|:----------------------:|:---------------------------------------:|
|  1 |  Tue, June 1         | [Lesson 1] |
|  2 |  Thu, June 3         | [Lesson 2] |
|  3 |  Tue, June 8         | [Lesson 3] |
|  4 |  Thu, June 10        | [Lesson 4] |
|  5 |  Tue, June 15        | [Lesson 5] |
|  6 |  Thu, June 17        | [Lesson 6] |
|  7 |  Tue, June 22        | [Lesson 7] |
|  8 |  Thu, June 24        | [Lesson 8] |
|  9 |  Tue, June 29        | [Lesson 9] |
| 10 |  Thu, July 1         | [Lesson 10] |
| 11 |  Tue, July 6         | [Lesson 11] |
| 12 |  Thu, July 8         | [Lesson 12] |
| 13 |  Tue, July 13        | [Lesson 13] |
| 14 |  Thu, July 15        | Final Exam/Presentations |

---

### **Tu/Th S&L Template [PLEASE REMOVE THIS HEADER BEFORE MAY 31]**

**Course Dates:** Tuesday, June 1 – Thursday, July 29, 2021 (9 weeks)

**Class Times:** Tuesday, Thursday at 4:00pm–5:30pm (18 class sessions)

| Class |          Date          |                 Topics                  |
|:-----:|:----------------------:|:---------------------------------------:|
|  1 |  Tue, June 1         | [Lesson 1] |
|  2 |  Thu, June 3         | [Lesson 2] |
|  3 |  Tue, June 8         | [Lesson 3] |
|  4 |  Thu, June 10        | [Lesson 4] |
|  5 |  Tue, June 15        | [Lesson 5] |
|  6 |  Thu, June 17        | [Lesson 6] |
|  7 |  Tue, June 22        | [Lesson 7] |
|  8 |  Thu, June 24        | [Lesson 8] |
|  9 |  Tue, June 29        | [Lesson 9] |
| 10 |  Thu, July 1         | [Lesson 10] |
| 11 |  Tue, July 6         | [Lesson 11] |
| 12 |  Thu, July 8         | [Lesson 12] |
| 13 |  Tue, July 13        | [Lesson 13] |
| 14 |  Thu, July 15        | [Lesson 14] |
| 15 |  Tue, July 20        | [Lesson 15] |
| 16 |  Thu, July 22        | [Lesson 16] |
| 17 |  Tue, July 27        | [Lesson 17] |
| 18 |  Thu, July 29        | Final Exam/Presentations |

---

### **M/W/F TECH Template [PLEASE REMOVE THIS HEADER BEFORE MAY 31]**

**Course Dates:** Monday, May 31 – Friday, July 16, 2021 (7 weeks)

**Class Times:** Monday, Wednesday, Friday at 9:30am–11:15am (19 class sessions)

| Class |          Date          |                 Topics                  |
|:-----:|:----------------------:|:---------------------------------------:|
|  - |  Mon, May 31         | **No Class - Memorial Day** |
|  1 |  Wed, June 2         | [Lesson 1] |
|  2 |  Fri, June 4         | [Lesson 2] |
|  3 |  Mon, June 7         | [Lesson 3] |
|  4 |  Wed, June 9         | [Lesson 4] |
|  5 |  Fri, June 11        | [Lesson 5] |
|  6 |  Mon, June 14        | [Lesson 6] |
|  7 |  Wed, June 16        | [Lesson 7] |
|  8 |  Fri, June 18        | [Lesson 8] |
|  9 |  Mon, June 21        | [Lesson 9] |
| 10 |  Wed, June 23        | [Lesson 10] |
| 11 |  Fri, June 25        | [Lesson 11] |
| 12 |  Mon, June 28        | [Lesson 12] |
| 13 |  Wed, June 30        | [Lesson 13] |
| 14 |  Fri, July 2         | [Lesson 14] |
| -  |  Mon, July 5         | **No Class - Independence Day Observed** |
| 15 |  Wed, July 7         | [Lesson 15] |
| 16 |  Fri, July 9         | [Lesson 16] |
| 17 |  Mon, July 12        | [Lesson 17] |
| 18 |  Wed, July 14        | [Lesson 18] |
| 19 |  Fri, July 16        | Final Exam/Presentations |

---

### **W/F S&L Template [PLEASE REMOVE THIS HEADER BEFORE MAY 31]**

**Course Dates:** Wednesday, June 2 – Friday, July 30, 2021 (9 weeks)

**Class Times:** Wednesday, Friday at 12:45pm–2:15pm (18 class sessions)

| Class |          Date          |                 Topics                  |
|:-----:|:----------------------:|:---------------------------------------:|
|  1 |  Wed, June 2         | [Lesson 1] |
|  2 |  Fri, June 4         | [Lesson 2] |
|  3 |  Wed, June 9         | [Lesson 3] |
|  4 |  Fri, June 11        | [Lesson 4] |
|  5 |  Wed, June 16        | [Lesson 5] |
|  6 |  Fri, June 18        | [Lesson 6] |
|  7 |  Wed, June 23        | [Lesson 7] |
|  8 |  Fri, June 25        | [Lesson 8] |
|  9 |  Wed, June 30        | [Lesson 9] |
| 10 |  Fri, July 2         | [Lesson 10] |
| 11 |  Wed, July 7         | [Lesson 11] |
| 12 |  Fri, July 9        | [Lesson 12] |
| 13 |  Wed, July 14        | [Lesson 13] |
| 14 |  Fri, July 16        | [Lesson 14] |
| 15 |  Wed, July 21        | [Lesson 15] |
| 16 |  Fri, July 23        | [Lesson 16] |
| 17 |  Wed, July 28        | [Lesson 17] |
| 18 |  Fri, July 30        | Final Exam/Presentations |


---



[Lesson 1]: Lessons/Lesson1.md
[Lesson 2]: Lessons/Lesson2.md
[Lesson 3]: Lessons/Lesson3.md
[Lesson 4]: Lessons/Lesson4.md
[Lesson 5]: Lessons/Lesson5.md
[Lesson 6]: Lessons/Lesson6.md
[Lesson 7]: Lessons/Lesson7.md
[Lesson 8]: Lessons/Lesson8.md
[Lesson 9]: Lessons/Lesson9.md
[Lesson 10]: Lessons/Lesson10.md
[Lesson 11]: Lessons/Lesson11.md
[Lesson 12]: Lessons/Lesson12.md
[Lesson 13]: Lessons/Lesson13.md
[Lesson 14]: Lessons/Lesson14.md
[Lesson 15]: Lessons/Lesson14.md
[Lesson 16]: Lessons/Lesson14.md
[Lesson 17]: Lessons/Lesson14.md
[Lesson 18]: Lessons/Lesson14.md
[Lesson 19]: Lessons/Lesson14.md
[Lesson 20]: Lessons/Lesson14.md


## Tabbed Schedule - EXAMPLE

**How to make a tabbed schedule.**

- The code that does this is in comments, so view the raw markdown to see what's going on.
- When you view the Docsify website of the course, the tabs will appear.
- They will NOT appear by just viewing on GitHub

### Instructions

1. Copy the appropriate schedule(s) from the above list with the correct dates
1. View the example below and copy the commented out code to generate the tabs:
    1. `<!-- tabs:start -->` - put at the beginning of where you want tabs
    1. `<!-- omit in toc -->` - put at the beginning of each header within the tabs
    1. `<!-- tabs:end -->` - put at the end of where you want tabs (i.e. at the end of the last schedule)

**See below example**

<!-- tabs:start -->
<!-- omit in toc -->
### **Section A: INSTRUCTOR NAME - HYBRID**

**Course Dates:** Tuesday, June 1 – Thursday, July 15, 2021 (7 weeks)

**Class Times:** Tuesday, Thursday at 4:00pm–5:30pm (14 class sessions)

Hybrid sections are a mixture of online and in person components.  In person sessions include labs and group work as noted on your schedule.  These sections will run according to the Hybrid Delivery Policy: [make.sc/hybrid-delivery-policy](make.sc/hybrid-delivery-policy)


| Class |          Date          |                 Topics                  |
|:-----:|:----------------------:|:---------------------------------------:|
|  1 |  Tue, June 1         | [Lesson 1] |
|  2 |  Thu, June 3         | [Lesson 2] |
|  3 |  Tue, June 8         | [Lesson 3] |
|  4 |  Thu, June 10        | [Lesson 4] |
|  5 |  Tue, June 15        | [Lesson 5] |
|  6 |  Thu, June 17        | [Lesson 6] |
|  7 |  Tue, June 22        | [Lesson 7] |
|  8 |  Thu, June 24        | [Lesson 8] |
|  9 |  Tue, June 29        | [Lesson 9] |
| 10 |  Thu, July 1         | [Lesson 10] |
| 11 |  Tue, July 6         | [Lesson 11] |
| 12 |  Thu, July 8         | [Lesson 12] |
| 13 |  Tue, July 13        | [Lesson 13] |
| 14 |  Thu, July 15        | Final Exam/Presentations |

<!-- omit in toc -->
### **Section B: INSTRUCTOR NAME**

**Course Dates:** Tuesday, June 1 – Thursday, July 15, 2021 (7 weeks)

**Class Times:** Tuesday, Thursday at 4:00pm–5:30pm (14 class sessions)


| Class |          Date          |                 Topics                  |
|:-----:|:----------------------:|:---------------------------------------:|
|  1 |  Tue, June 1         | [Lesson 1] |
|  2 |  Thu, June 3         | [Lesson 2] |
|  3 |  Tue, June 8         | [Lesson 3] |
|  4 |  Thu, June 10        | [Lesson 4] |
|  5 |  Tue, June 15        | [Lesson 5] |
|  6 |  Thu, June 17        | [Lesson 6] |
|  7 |  Tue, June 22        | [Lesson 7] |
|  8 |  Thu, June 24        | [Lesson 8] |
|  9 |  Tue, June 29        | [Lesson 9] |
| 10 |  Thu, July 1         | [Lesson 10] |
| 11 |  Tue, July 6         | [Lesson 11] |
| 12 |  Thu, July 8         | [Lesson 12] |
| 13 |  Tue, July 13        | [Lesson 13] |
| 14 |  Thu, July 15        | Final Exam/Presentations |

<!-- tabs:end -->

## Assignment Schedule 

**[INSTRUCTOR NOTE] REPLACE THE BELOW WITH LINKS TO YOUR ASSIGNMENTS, CORRECT DATES, AND SUBMISSION FORM**

|                        Assignment                         | Date Assigned |   Due Date   |            Submission Form           |
|:---------------------------------------------------------:|:-------------:|:------------:|:------------------------------------:|
| [Link to Assignment](makeschool.com)                      |  Tue, Oct 15  |  Tue, Oct 22 | [Submit Assignment](makeschool.com)  |
| [Link to Assignment](makeschool.com)                      |  day, Date    |  day, Date   | [Submit Assignment](makeschool.com)  |
| [Link to Assignment](makeschool.com)                      |  day, Date    |  day, Date   | [Submit Assignment](makeschool.com)  |
| [Link to Assignment](makeschool.com)                      |  day, Date    |  day, Date   | [Submit Assignment](makeschool.com)  |

## Class Assignments

We will be using [Gradescope](gradescope.com), which allows us to provide fast and accurate feedback on your work. *All assigned work will be submitted through Gradescope, and assignment and exam grades will be returned through Gradescope.*

As soon as grades are posted, you will be notified immediately so that you can log in and see your feedback. You may also submit regrade requests if you feel we have made a mistake.

Your Gradescope login is your Make School email, and your password can be changed at [https://gradescope.com/reset_password](https://gradescope.com/reset_password). The same link can be used if you need to set your password for the first time.

### Tutorials

- [Do Cool Stuff Tutorial]()

### Projects

- [Project Template - Use to build your own project spec](https://github.com/Make-School-Labs/Project-Template)

## Evaluation

**[INSTRUCTOR NOTE] REPLACE THE BELOW WITH EVALUATIONS THAT PERTAIN TO YOUR COURSE. THE BELOW ARE PROVIDED AS A SAMPLE**

To pass this course you must meet the following requirements:

- Complete all required assignments 
- Pass all projects according to the associated project rubric
- Pass the final summative assessment according to the rubric as specified in this class
    - This will be further explained in the [study guide](ADD_STUDY_GUIDE_LNK)
- Actively participate in class and abide by the attendance policy
- Make up all classwork from all absences

##  Information Resources

Any additional resources you may need (online books, etc.) can be found here. You can also find additional resources through the library linked below:

- [make.sc/library](http://make.sc/library)

## Interview Topics

Write what topis your course covers that students may encounter in a technical interview. Choose from the following sub-topics (pick all that apply):

### Algorithmic/Computer Science

Example topics:

- Sorting algorithms
- Search algorithms
- Runtime Complexity
- Data Structures
- etc.

### Technical Discussion

Example topics:

- Memory management
- CRUD
- Deploying a live app
- etc.

## Make School Course Policies

- [Program Learning Outcomes](https://make.sc/program-learning-outcomes) - What you will achieve after finishing Make School, all courses are designed around these outcomes.
- [Grading System](https://make.sc/grading-system) - How grading is done at Make School
- [Code of Conduct, Equity, and Inclusion](https://make.sc/code-of-conduct) - Learn about Diversity and Inclusion at Make School
- [Academic Honesty](https://make.sc/academic-honesty-policy) - Our policies around plagerism, cheating, and other forms of academic misconduct
- [Attendance Policy](https://make.sc/attendance-policy) - What we expect from you in terms of attendance for all classes at Make School
- [Course Credit Policy](https://make.sc/course-credit-policy) - Our policy for how you obtain credit for your courses
- [Disability Services (Academic Accommodations)](https://make.sc/disability-services) - Services and accommodations we provide for students
- [Online Learning Tutorial](https://make.sc/online-learning-tutorial) - How to succeed in online learning at Make School
- [Student Handbook](https://make.sc/student-handbook) - Guidelines, policies, and resources for all Make School students


