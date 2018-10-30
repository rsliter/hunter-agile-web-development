# CSCI 39549 Agile Software Development

## Pre-requisites
Completion of CSCI 235 (Data Structures) is required to take this class. Additionally, some knowledge of Python and SQL is strongly recommended.

## Adjunct Lecturers
Arylee Mcsweaney, amcsweaney@etsy.com

Rebecca Sliter, rsliter@etsy.com

Group slack: #general in [Hunter College Agile Dev](https://huntercollegeagiledev.slack.com/)  Slack channel

## Objective
Help college seniors to experience agile engineering by simulating a real world environment where engineers build out iterations on features, commit code to Github, learn about how teams operate, and deliver a working product.

## Specific Goals for this Course
* Students will learn about agile project management methodologies including planning and estimation;
* Students will learn about modern software development practices, including Automated Testing and Pair Programming;
* Students will acquire knowledge of collaborative implementation techniques including Pair Programming, Version Control, Continuous Integration, and Documentation;
* Students will deliver working software by the end of the semester.

## Required Readings
eXtreme Programming Explained: Embrace Change, 2nd Edition - you can access a PDF copy through a free trial on [Safari](https://www.safaribooksonline.com/).

## Language
All code will be written in Python using the Flask programming framework.

## Method of Evaluation
This is a project-based course. Each student’s contributions will be graded throughout the semester according to the following:

* 1% for each homework assignment at the beginning of the semester. There will be 2 of these assignments.
* 26% for each version of the team coding project (3 total versions). You will be graded on:
  * 50%: code contributions - although this is a group project, we will be periodically checking Github to ensure each teammate is contributing a fair amount;
  * 50%: requirements achieved for each version of the coding project (3 versions due);
* 5%: for each demo delivered during project. There will be 3 demos total;
* 2.5%: participation in retrospectives (2 total) (graded through notes).

For more information on expectations for these deliverables, see the [Rubrics page](RUBRICS.md).

## Course Calendar
The adjunct lecturers will deliver a talk on a particular topic at the beginning of each class. AllThe project deliverables are due at the beginning of the following class, so we ask for your active attention and engagement in lectures. For details on each project deliverable, see [this page](RUBRICS.md).

Notes from each class will also be posted to this repository after each class session.

### August 29: Introduction to Web Development and Version Control
* *Homework*: Create a new Flask app for a Calculator, and push it to a repository on your Github account. The app should contain the following endpoints:
  * /add
  * /subtract
  * /multiply
  * /divide

### September 5: No class.
    
### September 12: Intro to Web 2.0 and Databases
* *Homework*: Convert your web app to use ajax to load and set data via an API instead of using page.Requirements:
  * The calculator app should have a web form;
  * The web form should submit calculation commands through Ajax requests.

* *Homework*: there will be discussion on one assigned reading in the following lecture:
    * “Pairing” chapter from eXtreme Programming Explained (pages 173-178).

### September 19: No class.

### September 26: Pair-Programming
* Discussion of assigned reading.
* Pair-programming workshop.

* *Homework*: there will be discussion on two reading assignments in the following lecture:
    * [Why New York Subway Lines are Missing Train Clocks](https://www.theatlantic.com/technology/archive/2015/11/why-dont-we-know-where-all-the-trains-are/415152/)
    * “Planning” chapter (Chapter 12) from eXtreme Programming Explained.

### October 3: How We Build Software in Teams
* Discussion of assigned readings.
* Introduction to planning.
* *Homework*: each group has tasks ready on Trello for the next session.

The first version of your Flask web application should:
* Allow a user to choose an picture to filter;
* Allow a user to select from 3 potential image filters (of your choosing);
* Display the filtered image to the user.

### October 10: Open Working Session
*Homework*: Groups will demo their project next session.

### October 17: V1 of Project Due
* *Demos*: Each student will demo their project for 2 minutes (timed) followed by 2 minutes of Q&A.
* *Homework*: each group’s retrospective facilitator will need to post the retrospective notes to Github.
* *Homework*: each group will need to plan an extension of their project. The extension work should be posted to Trello by the next class. Your group's extension must:
  * build on top of your image filter app;
  * be big enough that the work can be split across the team;
  * make use of a new technology (database, Python library, etc)

### October 24: Deployment
* Workshop on Heroku Deployment.
* *Homework*: each group is able to deploy code to Heroku by the next class.
* *Homework*: there will be discussion on one assigned reading in the following lecture:
    * “Testing” chapter from eXtreme Programming Explained.

### October 31: Testing

* Discussion of assigned reading.
* Workshop on Testing.
* *Homework*:
  * Each team member should add tests to existing functionality by the next session.
  * Update your team's .circle/config.yml file to include steps to run tests. See [here|https://gist.github.com/rsliter/eeff4018b4da3f5b204a107d27409539] for a sample circle config file.


### November 7: Open Working Session

### November 14: Extension of Project Due; Introduction to Retrospectives
* *Demos*: Each student will demo their project, on Heroku, for 2 minutes (timed) followed by 2 minutes of Q&A.
* *Homework*: each group’s retrospective facilitator will need to post the retrospective notes to Github.

### November 21: Documentation
*Homework*: project groups should come up with documentation about how their program works. This documentation should live in “static/docs” within the project Git repository.

### November 28: New Feature Requirement
*Documentation demos*: Each group will demo their documentation for 2 minutes (timed) followed by 2 minutes of Q&A.

### December 5: Intro to Design & Product
A Guest Lecturer will give an overview of their work in the industry and introduce the team to Twitter bootstrap.

### December 12: Open Working Session

### December 19: Final Demos
*Demos*: Each project team will demo their project, on Heroku, for 10 minutes (timed) followed by 5 minutes of Q&A.

## Academic Integrity Statement
Hunter College regards acts of academic dishonesty (e.g., plagiarism, cheating on examinations, obtaining unfair advantage, and falsification of records and official documents) as serious offenses against the values of intellectual honesty. The College is committed to enforcing the CUNY Policy on Academic Integrity and will pursue cases of academic dishonesty according to the Hunter College Academic Integrity Procedures.

## ADA Statement
In compliance with the ADA and with Section 504 of the Rehabilitation Act, Hunter College is committed to ensuring educational access and accommodations for all its registered students. Hunter College’s students with disabilities and medical conditions are encouraged to register with the Office of AccessABILITY for assistance and accommodation. For information and appointment contact the Office of AccessABILITY located in Room E1214 or call (212) 772-4857 /or VRS (646) 755-3129.

## Hunter College Policy on Sexual Misconduct
In compliance with the CUNY Policy on Sexual Misconduct, Hunter College reaffirms the prohibition of any sexual misconduct, which includes sexual violence, sexual harassment, and gender-based harassment retaliation against students, employees, or visitors, as well as certain intimate relationships. Students who have experienced any form of sexual violence on or off campus (including CUNY-sponsored trips and events) are entitled to the rights outlined in the Bill of Rights for Hunter College.

a. Sexual Violence: Students are strongly encouraged to immediately report the incident by calling 911, contacting NYPD Special Victims Division Hotline (646-610-7272) or their local police precinct, or contacting the College&#39;s Public Safety Office (212-772-4444).

b. All Other Forms of Sexual Misconduct: Students are also encouraged to contact the College’s Title IX Campus Coordinator, Dean John Rose (jtrose@hunter.cuny.edu or 212-650-3262) or Colleen Barry (colleen.barry@hunter.cuny.edu or 212-772-4534) and
seek complimentary services through the Counseling and Wellness Services Office, Hunter East 1123.

CUNY Policy on Sexual Misconduct Link:
http://www.cuny.edu/about/administration/offices/la/Policy-on-Sexual-Misconduct-12-1-14-with-
links.pdf

