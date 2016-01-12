---
layout: default
---

# Science Gateway Architectures

* **Course:** [INFO-I590, Topics in Informatics, School of Informatics and Computing, Indiana University](https://www.soic.indiana.edu/graduate/courses/index.html?number=i590&department=INFO){:target="_blank"}
* **Instructors:** Marlon Pierce, [marpierc@iu.edu](mailto:marpierc@iu.edu); Suresh Marru, [smarru@iu.edu](mailto:smarru@iu.edu)
* **Class Schedule** Tuesdays from 8 am to 10.30 am in I2 (Informatics East) Room 122

## Course Overview

The following video describes the course:

[![Course Overview](http://img.youtube.com/vi/zNM25fw56YE/0.jpg)](https://youtu.be/zNM25fw56YE){:target="_blank"}

Science gateways are distributed computing environments that enable scientists to conduct computational experiments on computing clouds and supercomputers and have revolutionized bioinformatics, computational chemistry, nano-engineering, and other scientific fields by bringing unprecedented computing power to a broad community of scientists.

Gateways are interesting topics in their own right. Modern gateway systems are moving towards microservice architectures and DevOps principles employing containerization (using Docker), continuous integration and continuous delivery. 

 Many gateways are also investigating how to integrate Apache’s “big data” and cloud computing software projects like Apache Mesos, Apache Spark, Apache Samza, Apache JClouds and Apache Kafka. RPC versus message-oriented middleware at scale is also an open question, as are NoSQL versus Relational DB approaches for gateway data management.  Finally, as gateways typically include Web-based user environments, choosing the right technologies and crafting the correct user experience are challenging problems.

In this course, students will be divided into development teams, and each team will build a science gateway software as a service system from scratch. Teams will be encouraged to explore alternative technologies and ways for building science gateways as well as learning DevOps principles for deploying robust cloud services.  Students will also be introduced to the Apache Software Foundation’s open community governance principles for open source software and will learn how to effectively interact with Apache Software Foundation projects in order to become committers and project management committee members.

### Course Objectives

* Provide a highlevel, broad understanding of core concepts of science gateway architectures.

* Study of both abstract concepts and practical techniques for building science gateways.

* Hands-on experience in developing a science gateway while working with Open Source philosophies - particularly modelled after Apache Software Foundation.

* Applying the general concepts of Distributed Systems and understanding state of the art in applicable areas. 

### Course Outcomes 

* Demonstrate an understanding of open source contributions.

* Demonstrate required skills to apply for [Google Summer of Code](https://developers.google.com/open-source/gsoc/){:target="_blank"} like programs. 

* Demonstrate an understanding of applying distributed systems concepts to building middle ware for computational science gateways.

* Demonstrate an ability design, develop & deploy component based micro service architecture.

* Demonstrate an ability to develop remote job submission interfaces to computational cyberinfrastructure like IU Big Red 2 Supercomputers.

* Demonstrate an ability to develop a simple metadata management system.

* Demonstrate an ability to develop and consume API services.  


## Instructors
The course will be taught by Marlon Pierce and Suresh Marru, who lead the IU Science Gateway Group and are project management committee members for the Apache Airavata open source software.

## Prerequisites

Students should be familiar with Linux and Unix operating systems, basic networking concepts, one or more programming languages, databases, basics of Web development, and version control systems

## Course Outline

###  Week 1 - January 12th
* Introduction to the class [Slides]({{ site.url }}public/slides/SGG-I590-Overview.pdf) 
* Overview of science gateways [Slides]({{ site.url }}public/slides/I590-Gateways-and-Science.pdf)
* Overview of Supercomputing, Apache Airavata, Projects. [Slides]({{ site.url }}public/slides/Supercomputing-Airavata.pdf)
* Overview of class structure: projects, grading, etc. [Slides]({{ site.url }}public/slides/I590CourseStructure.pdf)

#### Assignment 1
* Assignment A1.1: 1 point
    * DUE: January 19th at 8 am
    * Students will request accounts, submit jobs on Airavata Test Drive Portal using [tutorial information](http://airavata.apache.org/documentation/quickstart-tutorials.html){:target="_blank"}
    * Assignment: every student gets an account and runs through the demo, which we can verify.
    * Need help or found a problem?  Email the mailing list.  
    * Extra point: email the mailing list with a bug or suggested improvements
* Assignment A1.2: 1 point
    * DUE: January 19th at 8 am
    * Get accounts on BR2, Karst, and submit the job described in the RT tutorial: http://rt.uits.iu.edu/ci/training/index.php 
    * IU accounts on Big Red II, Karst, Quarry - https://kb.iu.edu/d/aczn#research 
    * Accessing resources via SSH Keys  - https://kb.iu.edu/d/aews 
    * Running jobs with batch queuing systems https://kb.iu.edu/d/bcqt#jobs 
* Assignment A1.3: 1 point
    * DUE: January 19th at 8 am
    * All students create a GitHub account and send to instructors
    * Create a README for your team project
      * We will create a subproject for each team at https://github.com/airavata-courses
      * All team members add their names to the README.md file, commit, and push to the master
    * Guides
      * Git and GitHub - Walkthrough - https://help.github.com/
      * Github workflow by updating student profile 

###  Week 2 - January 19th

#### Assignment 2

###  Week 3 - January 26th 

#### Project Milestone 1
* Submit remote jobs to BR2 using SSH and Monitor

###  Week 4 - February 2nd

#### Assignment 3  

###  Week 5 - February 9th
 
#### Project Milestone 2
* Service version remote job submission tool

###  Week 6 - February 16th

#### Assignment 4 

###  Week 7 - February 23rd 

#### Project Milestone 3
* User Interface to remote job submission

###  Week 8 - March 1st 

#### Assignment 5

###  Week 9 - March 8th - Midterm Demos, Presentations

#### Project Milestone 4
* Metadata Management 
* A skeletal web interface to submit a job to BR2 and view job history with user login

### Spring Break - March 13th to 18th 

###  Week 10 - March 22st

#### Assignment 5 

###  Week 11 - March 29th 

#### Project Milestone 5
* Continuous Integration & Deployments

###  Week 12 - April 5th 

#### Assignment 6

###  Week 13 - April 12th

#### Project Milestone 6 
* Scaling, Load Balancing, Fault Tolerance

###  Week 14 - April 19th 

#### Assignment 7

###  Week 15 - April 26th - Final Demos, Presentations 

#### Project Milestone 7
* Multiple Component Application Server with 
* Defined API
* Defined internal, standalone component (microservice) version of application server.
* Defined internal APIs, internal communication mechanisms
* Demonstrated continuous deployment
* Demonstrated fault tolerance, load balancing

###  Finals Week - May 2nd - 6th 
* Bonus Week

## Student Teams

* Team size will depend on enrollment but will range from 2-5.
* Agree on an editor and environment that the team is comfortable with. We recommend IntelliJ Idea
* Team members who are less experienced/comfortable should have more keyboard time
* Switch who's "driving" regularly
* Make sure to save the code and send it to all team members.

## Grading

* Grades are based on points that each student acquires through submitting assignments, projects mid-term and final presentations, and peer reviewing other student’s codes.
    * 70% Semester Long Project with milestones. 
        * See below for longer description. 
    * 10% Mid-Term Demo/Presentations
    * 10% Final Demo/Presentation
    * 10% Class Participation, constructive discussion in mailing lists, pull requests, contribution to fellow student code/design reviews.
* Students will be divided into teams. Each team will work a project with intermediate milestones due every two weeks.  There will also be a midterm and final presentation. 
* Smaller assignments will be made on alternating weeks.
* Course Project 70%:  There will be 7 project milestones, including mid-term and final milestones, scheduled biweekly.  Each project milestone is worth 10 points.  
* Projects must be checked into github, must be reproducibly executable on the deadline day by the instructors.
* If the instructors cannot execute your project and verify you have met the success criteria, the team receives 0 points.
* A team may resubmit their assignment at any time before the next milestone. Each resubmission gets -1 point; i.e., 9 points if you get it right on the second try, 8 points on the third try, etc.
* Students who show no activity (no github commits, no email discussions, etc) for the milestone will receive 0 points.
* Midterm Presentation: 10%  All team members must participate.
* Final Presentation: 10% All team members must participate
* Gap assignments: 10%  Smaller skill and knowledge building assignments will be given in between project milestones. These will be worth 1 point each. There may be 1 or more of these per alternate week.
* These are earned by each student, not by the team.
* Bonus Points: as assigned throughout the semester.  These opportunities will typically be for 1 point each.  They do not count against you if you do not complete them.  
* The bulk of the grading is for Projects. It should be noted that the project evaluation is granularly broken down based on design, critical considerations of alternative approaches, building over existing solutions, implementation, well written tests and finally a report.  
    * Testing: An critical aspect of distributed systems programming is to develop comprehensive test methods for the programs. A significant effort should be invested in writing programs that will thoroughly test the system code, including the handling of different error conditions.
        * Refer Apache Airavata Test Driven Development [example](https://cwiki.apache.org/confluence/display/AIRAVATA/Tests+in+Airavata){:target="_blank"}
    * Gracefully handling errors: The code must reliably handle possible error conditions, both internal and reacting to external failures (in a distributed system context).
    * Resource Usage: Must manage resources such as memory, cpu and I/O usage with care. 
    * Security aspects: Projects involves developing network accessible services which are inherently vulnerable to malicious attacks. Security methodologies should be carefully considered. Students should be aware of potential flaws such as string overflows or malformed incoming messages and put an effort to mitigate them. 
    
## Resources

During the course, instructors will provide references to journal and conference papers. A good understanding of concepts discussed in these referred papers will greatly help in absorbing the course material. 

### Beginner Materials

* Principles of Distributed Computing – [Lecture Collection](http://disco.ethz.ch/lectures/podc_allstars/){:target="_blank"}
* [Overview of Apache Airavata](https://cwiki.apache.org/confluence/download/attachments/45876421/iwsg2014_submission_19%20(2)%20(1).pdf?version=1&modificationDate=1409604473000&api=v2)

## Open Collaboration

* Reuse and building upon ideas or code are major parts of modern software development.  As a professional programmer you will never write anything from scratch.  This class is structured such that all solutions are public.  You are encouraged to learn from the work of your peers. We won't hunt down people who are simply copying-and-pasting solutions, because without challenging themselves, they  are simply wasting their time and money taking this class.

* Please respect the terms of use and/or license of any code you find, and if you reimplement or duplicate a design or code from elsewhere, credit the original source.