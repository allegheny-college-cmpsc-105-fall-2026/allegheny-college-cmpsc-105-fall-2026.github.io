---
layout: home
title: CMPSC 202 Algorithm Analysis
nav_exclude: true
permalink: /:path/
---

# Algorithm Analysis
{:.no_toc}

CMPSC 202 - Fall 2026 - [Allegheny College](https://www.cis.allegheny.edu/)

Imagine that you have been tasked with solving a problem computationally. You come up with a brilliant solution, implement it, and hit 'run.' No errors pop up, but the screen just sits there... and sits there... even after a couple of minutes! What could be going on? Your program might be caught in an infinite loop, or maybe it just needs a few thousand years to finish.

In this course, you will develop the language and skills required to design, analyze, implement, and communicate precisely about computational problems and their solutions. An algorithm is a procedural recipe that solves a specific problem. But knowing an algorithm works is only half the battle; we also need to know if it will finish, say, before the semester concludes.

In this course, you’ll be engaging with the complete algorithm design process. You will
- Pose problems rigorously: Formulate an abstract model of the problem.
- Propose solutions: Design an algorithm that can be translated into efficient code.
- Analyze the theory: Use mathematical tools to predict how your algorithms' running time will scale.
- Test the reality: Implement your algorithms and benchmark them empirically
- Communicate effectively: Present your findings and reasoning clearly, both in writing and orally.

The problems you will see often arise in real-world applications. You’ll discover that some are impossible to solve efficiently, others will run out of memory before they finish, and sometimes, a brilliantly optimized algorithm on paper gets beaten by a simple baseline in practice. By the end of this semester, you won't just be able to write code that works; you'll be able to show why it is fast, both on paper and in the wild.

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}


## Course Description

A study of fundamental methods for designing and implementing algorithms and analyzing their efficiency. While developing expertise in select models of computation and the key mathematical and experimental approaches to studying algorithm efficiency, students investigate different types of algorithms through hands-on activities that often require teamwork. Students also learn how to determine whether a problem can be efficiently solved by an algorithm that is implemented as a computer program. During a weekly laboratory session students use state-of-the-art technology to complete projects, reporting on their results through both written documents and oral presentations. Students are invited to use their own departmentally approved laptop in this course; a limited number of laptops are available for use during class and lab sessions.

- **Prerequisite:** CMPSC 101
- **Distribution Requirements:** Quantitative Reasoning (QR), Scientific Process and Knowledge (SP)

**Quantitative Reasoning**: Quantitative Reasoning is the ability to understand, investigate, communicate, and contextualize numerical, symbolic, and graphical information towards the exploration of natural, physical, behavioral, or social phenomena.

**Scientific Process and Knowledge**: Courses involving Scientific Process and Knowledge aim to convey an understanding of what is known or can be known about the natural world; apply scientific reasoning towards the analysis and synthesis of scientific information; and create scientifically literate citizens who can engage productively in problem solving.

## Learning Objectives

Allegheny College’s educational program is designed so that its graduates are able to:
- **AC-1**: Think critically and creatively.
- **AC-2**: Communicate clearly and persuasively as speakers and writers.
- **AC-3**: Invoke multiple ways of understanding to organize and evaluate evidence, and to interpret and make sense of their experiences and the experiences of others.
- **AC-4**: Apply their knowledge and learning to engage in informed debate, and to analyze and solve problems.

Computer Science 202 at Allegheny College is a core course in the Computer Science major. Graduates with the Computer Science major — who all take the Computer Science 202 course — must demonstrate their attainment of these learning objectives:
- **CS-1**: Demonstrate and be able to communicate the knowledge of data types, algorithms, and mathematical principles behind discrete objects.
- **CS-2**: Use scientific and theoretical methods to design, implement, evaluate, deploy, improve, maintain, and document software and hardware systems.
- **CS-3**: Apply and articulate key concepts from a specialization area where the interconnection between software and hardware is important and evident.
- **CS-4**: Able to communicate technical details of the produced software and hardware artifacts both in writing and orally.

All five of the Computer Science major’s learning objectives support the **QR** and **SP** distribution requirements and the College’s learning objectives.

The specific learning objectives for Computer Science 202 are as follows:
- **CS-202-1**: Correctly implement both well-established and custom data structures using a programming language so as to solve a problem with a computer program.
        Enables the attainment of CS-1.
- **CS-202-2**: Perform an asymptotic analysis of an algorithm to arrive at its correct worst-case time complexity class.
        Enables the attainment of CS-2.
        Enables the attainment of CS-4.
- **CS-202-3**: Conduct experiments that measure the efficiency of different combinations of programming languages, data structures, and algorithms.
        Enables the attainment of CS-3.
- **CS-202-4**: Use both theoretical and experimental results to pick the data structure(s) and algorithm(s) that balance the trade-offs associated with correctly and efficiently solving a problem with a computer program.
        Enables the attainment of CS-2.
- **CS-202-5**: Effectively apply algorithmic problem solving techniques like searching, sorting, and memoization to correctly and efficiently solve a problem through the use of a computer program.
        Enables the attainment of CS-1.

The learning objectives for Computer Science 202 enable the attainment of the CS program learning objectives that in turn support the attainment of the College’s learning objectives.

## When and Where

- **Lecture**
    - T/Th 9:30am - 10:45am, **Alden 101** 

- **Lab**
    - M 2:30pm - 4:00pm,  **Alden 101**  

## Topics
- **Data Structures** [ways to organize and store data efficiently]
    - stacks
    - queues
    - linked lists
    - hash tables
    - trees
    - graphs
- **Algorithmic paradigms** [common ways for solving a problem]
    - greedy algorithms
    - dynamic programming
    - divide and conquer
    
## Textbooks

We will cover [**A First Course on Data Structures in Python**](https://donsheehy.github.io/datastructures/) by Don Sheehy, though we will use supplementary material from other sources as well.

<center><img  height="200px" src="/assets/images/sheeley.png" alt="A First Course on Data Structures in Python textbook">
<img height="300px" src="/assets/images/algo.jpeg" alt="Louridas textbook" style="display:inline-block; margin:10px;">
</center>

An excellent (optional) short introduction to data structures and algorithms is [Algorithms](https://mitpress.mit.edu/9780262539029/algorithms/) by Louridas from the MIT Press Essential Knowledge series.


You may wish to refer to [Algorithm Design](https://www.cs.princeton.edu/~wayne/kleinberg-tardos/pearson/) by Kleinberg and Tardos and [Introduction to Algorithms, Third Edition](https://mitpress.mit.edu/9780262533058/introduction-to-algorithms/) by Cormen, Leiserson, Rivest, & Stein for a concise presentation of the material. The latter is often referred to as **CLRS**.


## Coursework

Students will complete:
- Algorithm Design projects (with weekly deliverables)
    - Planning & Analysis
    - Implementation & Evaluation
    - Findings & Reflection
    - Presentation
- Readings
- Lab Exercises
- Lab Assessments
- Midterm & Final Exams

These assessment categories have the following definitions:

- **Algorithm Design Projects**: Students will work in teams on three algorithm design projects throughout the course. Over four weeks, students will take an in-depth problem and produce multiple deliverables (approx. one each week): planning and analysis, implementation and evaluation, findings and reflection, and a presentation of results. These projects are designed to give students hands-on experience with the full algorithm design process from initial planning to final presentation. The first two deliverables (planning and analysis, and implementation and evaluation) are graded based on effort and completion, while the latter two deliverables (findings and reflection, and the presentation) are graded based on correctness and effectiveness. 
- **Class Participation**: Students are expected to regularly attend and actively participate in all class and lab sessions, as outlined in the [course schedule](schedule.md). See the [attendance policy](#course-attendance) below. Additionally, a student’s class participation grade may be reduced if they are frequently observed, during either class or laboratory sessions, undertaking non-course-related activities like viewing email, social media, or other content not about algorithm analysis.
- **Lab Exercises**: Students meet once a week to complete a practical exercise in teams reinforcing and building on the material covered in lecture. Exercises are due by the end of the lab session and are graded based on completion and effort.
- **Lab Assessments**: Following the lab exercise, students will individually complete a short assessment to evaluate their understanding of the material covered in the lab. These assessments are due at 11:59pm on the day of the lab and are graded based on accuracy and completeness.
- **Midterm Examination**: Covers material from the first half of the course up through Week 6. This exam will have both an analog component to be completed by hand on paper and a programming component allowing students to use their usual development tools.  
- **Final Examination**: Cumulative but focuses on material from the second half of the course, from Week 8 through the end of the term. This exam will also have both an analog component to be completed by hand on paper and a programming component allowing students to use their usual development tools.

## Grading

Assessment categories will contribute to the final grade according to the percentages listed in the table below.

| Category | Percentage |
|---|---:|
| Algorithm Design Projects (Plan/Implement/Findings/Presentation) | 40% (10%/10%/10%/10%) |
| Class Participation | 5% |
| Lab Exercises | 10% |
| Lab Assessments | 10% |
| Midterm Examination | 15% |
| Final Examination | 20% |

Final grades will be assigned based on the weighted sum of the assessment categories listed above.

| Letter Grade | Percentage Range |
|---|---:|
| A  | 95-100% |
| A- | 90-94.9% |
| B+ | 87-89.9% |
| B  | 83-86.9% |
| B- | 80-82.9% |
| C+ | 77-79.9% |
| C  | 73-76.9% |
| C- | 70-72.9% |
| D  | 60-69.9% |
| F  | 0-59.9% |

## Assessment Policies

Unless exempted by the instructor, students must abide by the following assessment policies:

### Assignment Submission
All assignments will have a stated due date shared through GitHub, the course website, and/or the course Discord. No credit will be awarded for any coursework that you submit to the incorrect GitHub repository or web site. Unless special advance arrangements are made with the instructor to address extenuating circumstances, no work will be accepted after the deadline.

### Course Tokens
Students may “spend” up to three Course “tokens” that they may use to secure seven days of additional time to complete a deliverable from an algorithm design project or a lab assessment (excluding presentations). To spend a token, a student must fill out the token request [Google form](links.md) within 48 hours of the original deadline. Students may use these tokens at their discretion within the constraints described above. Outside of using these three tokens or severe, extenuating, and unexpected circumstances that are well documented, the instructor will not grant any requests for extensions or reassessment.

### Course Attendance
It is mandatory for all students to attend each of the lecture and lab sessions. We will take attendance using a [Google form](links.md). Excluding the first week of the semester, students can have **eight absences** without any impact to their grade. These accommodations are meant to cover illness and emergency, so you should always come to class if you are able to do so.

As a general guideline, students cannot miss more than two weeks of class in total throughout the academic semester without receiving a letter grade reduction. For this course, excluding the eight excused absences, the overall course grade will decrease by 1/3 of a letter grade for each additional absence or absence equivalence regardless of base grade. 

### Class Preparation
In order to minimize confusion and maximize learning, students must invest time to prepare for the class sessions. Although the course instructor and the student technical leaders will always be available to serve as guide for individual students, teams of students, and the entire class, it is expected that students will volunteer to lead and actively contribute to all class sessions. Only those students who have prepared for class by reading and running the assigned material will be able to effectively participate in these class discussions. To help students remain organized and to effectively prepare for classes, the instructor will maintain a list of course slides, a lecture schedule with reading assignments, and other important information about the course on the [schedule page](schedule.md) of the course website.

### Seeking Assistance

Students who are struggling to understand the knowledge and skills developed in this course are encouraged to seek assistance from the course instructor and/or the student technical leaders. Students should, within the bounds of the Honor Code, ask and answer questions on the course Discord Server; please request assistance from the instructor and student technical leaders first through public Discord channels before sending an email or a direct message. Students who need more assistance are invited to schedule a meeting through the instructor’s appointment scheduler and come to the meeting with details about their question. Students can see the office hour schedule for student technical leaders by viewing the list of student technical leaders and by monitoring announcements in the Allegheny College Computer Science Discord Server.

### Using GitHub and Discord

This course will primarily use GitHub and Discord for all course communication. We will use GitHub for the sharing of both source code and documentation for course projects/assessments and for reporting issues in those materials. We will use course and department Discord servers for all course discussions. The course Discord Server will be the main forum for discussing the professional and technical content in the field of algorithm analysis. The Allegheny College Computer Science Discord Server will be the main forum for Department of Computer Science announcements. Finally, any content that a student wants the instructor to assess (e.g., the work for a algorithm design project) must be in a GitHub repository.

### Using Email

Although we will primarily use the course Discord Server for class communication, the instructor will sometimes use email to send announcements about important matters such as changes in the schedule. It is your responsibility to check your email at least once a day and to ensure that you can reliably send and receive emails. This class policy is based on the statement about the use of email that appears in *The Compass*, the College’s student handbook; please see the course instructor if you do not have this handbook.

### Honor Code

The Allegheny College Academic bulletin describes The Academic Honor Program that governs the entire academic program at Allegheny College. The Honor Program applies to all work that is submitted for academic credit or to meet non-credit requirements for graduation at Allegheny College. This includes all work assigned for this class (e.g., executable examinations and course assignments). All students who have enrolled in the College will work under the Honor Program. Each student who matriculates at the College acknowledges this Honor Code pledge:

>I hereby recognize and pledge to fulfill my responsibilities, as defined in the Honor Code, and to maintain the integrity of both myself and the College community as a whole.

### Effective Development Practices

Students who create the source code and documentation for their projects and assignments should ensure the implementation of a high-quality final product. While students are permitted to use a wide variety of tools, such as integrated development environments, testing frameworks, automated debuggers, and code generators (e.g., systems that leverage large language models like GitHub Copilot) and documentation sites such as StackOverflow, they must take responsibility for all of the source code and documentation that they submit for this course, including artifacts that are generated by a software tool.

This means that every student must work as an effective developer by documenting the sources for their work and verifying the correctness, maintainability, and long-term reliability of all source code and documentation that they submit. As such, students who use software tools to create content are responsible for citing their sources and demonstrating their understanding of it as a part of any follow-on assessment. Moreover, all students in the class are responsible for all of the source code and documentation submitted to the GitHub repository that hosts the course projects, including any tool-generated software artifacts. This means that every student should be able to answer questions, during either an in-person or online discussion, about any content produced for this course, including that which was generated by a software tool.

### Disability Services

Students with disabilities who believe they may need accommodations in this class are encouraged to contact Student Accessibility and Support Services (SASS) at 814-332-2898 or studentaccessibility@allegheny.edu. SASS is located in the Center for Student Success in Pelletier Library. Please contact SASS as soon as possible to ensure that approved accommodations are implemented in a timely fashion.

### Syllabus Changes

The instructor may make updates or changes to this document at any time as needed until term grades are due. Changes will be announced to the class.