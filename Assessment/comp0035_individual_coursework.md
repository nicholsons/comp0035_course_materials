### 1 Introduction
This document specifies the content and submission for the individual coursework which is 40% of the overall module assessment.  

This coursework is where you reflect on, and evaluate, the methods, processes and models used during the group project, and demonstrate an appropriate development environment.  

While you will collaborate with others to establish the development environment and complete the group project, what you submit for this assignment must be your own individual work (except where explicitly stated otherwise). You must make it clear where others contributed. 

### 2 Audience and purpose
The audience for the coursework is the course tutor.  

The purpose of this coursework is for you to:

- critically evaluate the software engineering methods, processes, techniques and models used in the project. 
- demonstrate that you have established an appropriate development environment (you will use this when developing the application in COMP0034).

You are asked to describe, critically reflect on, and/or evaluate aspects of the group project. It is assumed that as third year undergraduate students you are familiar with these terms. However, some general guidance on the terms is at the end of this document.
Aim to be as objective as possible and establish criteria against which you can assess the various aspects of the project. This means that you should not simply give unsupported opinions (e.g., "I don't like UML.") but try to find ways to measure and assess what you are evaluating.

This is an academic assignment and should use an appropriate structure, language and be appropriately referenced.

### 3 Coursework length
There is no enforced word limit for the coursework. 
As a guide, aim for 2,500 words, excluding bibliography/references, diagrams/figures and appendices. 

### 4 References
References should be appropriately formatted in accordance with UCL referencing guidelines. 

Although this coursework refers to your group project, it must be entirely your own work (except where explicitly stated otherwise). All reports will be analysed using Turnitin and those with a high similarity will be investigated in line with departmental procedures.

Further information on [Plagiarism and Academic Writing can be found here](https://moodle.ucl.ac.uk/course/view.php?id=34)

### 5 Submission
Submit the coursework as a pdf file using the submission link on Moodle in the Assessment section.  
Re-submission before the deadline is possible, with any previous version being overwritten. The last submitted version will be the one marked after the deadline has passed.

#### 5.1 What to include
This coursework should be submitted in two parts: 

1. A report
2. A video demonstration

#### 5.2 Report
Please use an appropriate report structure with relevant headings. 

The report should include the following. Each of these relate to an aspect of the group project.

The report should be entirely your own work. The work of others (including your team mates) must be appropriately referenced.

- An introduction to the project and report
- A description of, and critical reflection on, the software engineering techniques used to manage the project and design the solution. This should include: 
    - Management of the project
        - Technique(s) used to structure the project and manage its progress (e.g. XP, Scrum, CRISP-DM, etc)
        - Tools used to manage the project and team collaboration
    - Analysis e.g.
        - Requirements elicitation (how you went about gathering the requirements)
        - Requirements modelling (requirements, user stories, use cases etc)
        - Requirements management (managing the evolving requirements)
    - Application design e.g.
        - UML class diagrams or other software design techniques used
        - Interface design (e.g. wireframes)
        - Database design modelling (e.g. ERD, schema)
        - Data (identifying and preparing the data)
- An evaluation of the quality of the resulting application design
- A URL of a video where you demonstrate a working development environment on your computer. See next section for the video contents.

#### 5.3 Video demonstration of a working development environment
Each person must have a working development environment that could be used as a basis for developing, testing (and, optionally, deploying) your application. 
You are not required to have all of the tools installed on your own computer (though if you have the means to do this you would be encouraged to do so). 
You may use any appropriate online service to which you have access.

The purpose of the video is to demonstrate that environment. Use voice over commentary to provide any explanations.

The video must be your own work. It is not sufficient (or allowed) for one member of the group to create a video and for all members to use the same video. 

The video can be published unlisted on YouTube, or on UCL MediaCentral.

You are not marked on quality of video editing, however you should ensure that the quality is sufficient for the tutor to mark your work (e.g. key aspects are clearly visible, any audio can be heard).

The video demonstration should clearly show how you meet the following coursework requirements:

1.	That you have access to software that allows you to write and edit Python code.  
An IDE (e.g. PyCharm Professional, Visual Studio Code, Atom etc) or application to write and edit code. This may be an online service.

2. That you have written a Python class.  
Write code for one Python class. The class should be one from your app design. Each person in the team must write a different class. Write your name
The code must be saved in the group GitHub repository.  You must write your name in comments in the code.

3.	That you can make changes to the group’s shared repository on GitHub using your IDE.  
Using the IDE make a change to your python class (e.g. add a comment to the code, change a function name etc).  
Commit the change, and push to the group repository.  
Show the change in the group repository on GitHub. 

4.	That you have written and can execute a Python unit test.  
Show at least one unit test for your code that you have written for your class.  
Demonstrate that you can run the test and view the results.  
Note: It does not matter if the test fails due to a class method that is incorrect and/or has yet to be written. You are seeking to provide evidence that you understand the structure of a unit test and can run the test.

5.	That you have a data source for your group’s project.  
Show the data source (e.g. database, csv) that you have created using any tool you prefer.  
For this aspect each team member will have access to the same data source as you will only have one data source in the group's GitHub repository.  
Each person however should clearly show in their video that they can access that data (e.g. open the data source, navigate to a particular data item).
 

#### Optional additional requirements
The following are optional as they may be challenging to establish and you may not be explicitly shown how to do this in the course. 
However setting up a continuous integration pipeline, or even more challenging a continuous deployment pipeline, would help you in the next module and is likely to lead to a higher mark in this module.
You would only create this once for a group, so if you choose to do this you need to clearly indicate which team members contributed and what their contribution was.

- **Continuous integration (CI):** linking your code editor/IDE to a repository which in turn is linked to a an environment in which tests are automatically run when the repo is updated, e.g. using GitHub Actions or CirleCI.
- **Continuous deployment (CD):** linking your CI to a production environment (continuous delivery) using a platform such as AWS or Heroku.

#### 5.3 Late submission
Late submission penalties will apply (refer to your student handbook for details) and are applied by the departmental administrators (not the course tutor). Marks that are entered in the Moodle gradebook will be the mark before any penalty is applied. Penalties will only be applied once the marks are in Portico. Please remember this when you are reviewing your marks.

### 6 Marking
This assignment will be assessed in accordance with the ‘UCL Computer Science: Marking Criteria and Grade Descriptors’ (see copy on Moodle), specifically criteria 1, 2, 3, 4 and 8. Note that the video only serves as evidence of a working development platform, criteria 7 is not considered when marking this coursework.
The marks are allocated 60% software engineering, 40% development platform.

Indicators for each aspect (not an exhaustive list):

| Aspect | Weak | Strong |
| ------ | ------ | ------ |
| Software engineering	| A straightforward description of the techniques used.  Limited critical reflection or evaluation.  Doesn’t cover all the required aspects of software engineering. | Thorough grasp of the issues faced in the required aspects (as per the required report contents) of a software engineering project.  Evidence of appropriate reasoning for choice of techniques, models and tools. Critical reflection on, and evaluation of, the choices made considering the use of the models, techniques and tools in the context of the project.  Evaluation of the resulting software design is based on objective criteria (as far as is possible).  |
| Development platform 	| Development platform does not cover all required aspects, or there are significant issues with aspects of the platform.  There is insufficient evidence that the platform has been used to collaborate with other team members.  There is insufficient evidence that the student has understood the tools and techniques required. The code and unit test may function, however the quality of these is low. | The platform covers all required aspects and there is evidence that these function appropriately.  There is evidence that the platform has been used to collaborate with other team members.  There is evidence that the student has made an informed selection of tools and techniques. The quality of the code and unit test can be assessed as high e.g. adherence to relevant standards such as PEP8, PEP257, following design principles such as DRY. |

 
### 7 Guidance for preparing and writing the report
#### 7.1. Prepare for the report by maintaining a project log
You are advised to maintain a personal project log throughout the project in which you regularly (e.g. weekly) make notes on:

•	The activities you undertook or participated in (e.g. weekly meeting, individual tasks, tasks with others). Note any formal methods used and reasons for selecting them.
•	Observations on the activities, e.g.
    o	Positive outcomes e.g. What did you enjoy about the activity? What did you see as your contribution? Materials developed?
    o	Challenges faced e.g. Did you have any difficulties? Why do think they arose? How did you deal with them? 
•	Actions: Is there anything you would like to work on/do differently next week? 

Read and use the contents of your log when writing the report. References to specific examples in the log can be used in the report, though place detailed transcripts in the appendices only. It is not necessary, or useful, to reproduce the entire log in the report. 

#### 7.2 Guidance on evaluation and critical reflection
It is expected that students are familiar with how to critically reflect and evaluate in an academic report. [UCL study skills support is available online](https://www.ucl.ac.uk/students/skills).

**Use with caution**:  
The following links are also offered as guidance for this assignment.  If a link no longer works, then you should be able to search for alternatives. Please check with the relevant course tutor before using the following definitions for any other module/course at UCL.  

- [University of Birmingham. 2015. A short guide to reflective writing.](https://intranet.birmingham.ac.uk/as/libraryservices/library/skills/asc/documents/public/Short-Guide-Reflective-Writing.pdf)
- [Institute of Education. Read and write critically.](http://www.ucl.ac.uk/ioe-writing-centre/critical-reading-and-writing) 
- [Otago Polytechnic. Reflective writing.](https://www.op.ac.nz/assets/LearningAdvice/Reflective-writing.pdf)

Definitions of the term ‘evaluate’ in relation to academic assignments:

- Assess and give your judgement about the merit, importance or usefulness of something using evidence to support your argument. [Source](https://intranet.birmingham.ac.uk/as/libraryservices/library/skills/asc/documents/public/Short-Guide-Understanding-assignment.pdf).
- Judge the value of something. But first, analyse, describe and explain. Then go through the arguments for and against, laying out the arguments neutrally until the section where you make your judgement clear. Judgements should be backed by reasons and evidence. [Source](http://blogs.bath.ac.uk/academic-skills/2017/09/27/understanding-instruction-words-in-academic-essay-titles/).

