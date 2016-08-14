---
layout: default
---

# Science Gateway Architectures

* **Course:** [CSCI-B 649, Topics in Systems, Computer Science, School of Informatics and Computing, Indiana University](https://www.soic.indiana.edu/graduate/courses/index.html?number=i590&department=INFO){:target="_blank"}
* **Instructors:** Marlon Pierce, [marpierc@iu.edu](mailto:marpierc@iu.edu); Suresh Marru, [smarru@iu.edu](mailto:smarru@iu.edu)
* **Class Schedule** Tuesdays and Thursdays from 4 pm to 5pm in I2 (Informatics East) Room 150

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

#### Lectures
* Introduction to the class: [Slides]({{ site.url }}public/slides/SGG-I590-Overview.pdf) 
* Overview of science gateways: [Slides]({{ site.url }}public/slides/I590-Gateways-and-Science.pdf)
* Overview of Supercomputing, Apache Airavata, Projects: [Slides]({{ site.url }}public/slides/Supercomputing-Airavata.pdf)
* Overview of class structure: projects, grading, etc: [Slides]({{ site.url }}public/slides/I590CourseStructure.pdf)

#### Assignment 1
* Assignment A1.1: 1 point
    * DUE: January 19th at 8 am
    * Students will request accounts, submit jobs on Airavata Test Drive Portal using [tutorial information](http://airavata.apache.org/documentation/quickstart-tutorials.html){:target="_blank"}
    * Assignment: every student gets an account and runs through the demo, which we can verify.
    * Need help or found a problem?  Email the mailing list.  
    * ***Bonus point:*** email the mailing list with a bug or suggested improvements
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

#### Lectures
* Git and GitHub Basics: [Slides]({{ site.url }}public/slides/I590-Git-Overview.pdf) 
* Cluster Scheduling and Resource Management: [Slides]({{ site.url }}public/slides/I590-ClusterScheduling.pdf)
* Distributed Co-ordination using Zookeper
    * Read Zookeeper [Paper](https://www.usenix.org/legacy/event/usenix10/tech/full_papers/Hunt.pdf)
* Cloud and Data Intensive Computing Scheduling - Data Center Scheduling using Apache Mesos
    * Read Mesos [Paper](http://static.usenix.org/events/nsdi11/tech/full_papers/Hindman_new.pdf)

###  Week 3 - January 26th 

#### Lectures
* Representational State Transfer (REST) and Science Gateways: [Slides]({{ site.url }}public/slides/Week3-REST-ScienceGateways.pdf) 

#### Assignment 2.1: Peer Review Project 1 (1 point)
* Due 11:59 pm February 1st
* Peer-review the code of one of the other teams. 
* Create at least one issue (using the team's GitHub Issues) suggesting an improvement or identifying a bug.  
* Use GitHub's code review to identify specific improvements of fixes. 
* To complete the assignment, submit links to issues that you reported.

#### Assignment 2.2: Peer Review Project 2 (1 point)
* Due 11:59 pm February 1st
* Peer-review the code of one of the other teams (different team from Assignment 2.1)
* Create at least one issue (using the team's GitHub Issues) suggesting an improvement or identifying a bug.  
* Use GitHub's code review to identify specific improvements of fixes. 
* To complete the assignment, submit links to issues that you reported.

#### Project Milestone 1 Due: Application that submits and monitors a job remotely on Karst
* The application can run anywhere. Must be able to run on instrucutors’ laptops.
* Must build from a source checkout from GitHub
	* Document any pre-requisites not in GitHub, like Java or Python versions.
* Must be documented adequately for instructors to reproduce the results
* Use SSH, SCP with SSH Keys (do not store your IU passwords in code or config files).
* Design choice: wrap executable or use a library?
* Design choice: how do you monitor jobs?
* You can use any language and build system of your choice. If you do not have a preference, we recommend Java and Maven. 
* Use GitHub issue management tools to discuss the project.  Use GitHub for all communications.
* Have a build system, also in GitHub
* Design choice: what do you use?  Maven, ant, make, ...

###  Week 4 - February 2nd

#### Lectures


###  Week 5 - February 9th

#### Lectures 

#### Project Milestone 2 Due (10 Points)
* Your project should run as a service and with a preliminary API.
	* Base this on the application developed in Milestone 1.
	* API methods must be for submitting, monitoring, and canceling jobs.
* You must provide also clients or client samples for your code.
	* Client samples can be your choice: PHP, bash, Java clients, etc.
* Instructors must be able to compile and run both the service and the client samples.
	* The entire environment for running things should be automated.
* Don’t assume clients and and the server share anything.
	* OK to use localhost
	* That is, run server on a laptop.

###  Week 6 - February 16th

#### Lectures
* The SEAGrid Science Gateway: [Slides]({{ site.url }}public/slides/I590-SEAGrid.pdf)

#### Assignment 4 

###  Week 7 - February 23rd 

#### Lectures
* Google Summer of Code 2016: [Slides]({{ site.url }}public/slides/GSOC-2016.pdf)
* Science Gateway Metadata and Information Services: [Slides]({{ site.url }}public/slides/I590ScienceGatewayMetadata.pdf)

###  Week 8 - March 1st 

#### Lectures
* Introduction to Distributed Systems: [Slides]({{ site.url }}public/slides/I590-DistributedComputingScienceGateways.pdf)

#### Project Milestone 3
* In this milestone, you will provide a simple user interface that will allow users to submit jobs to Karst.  All gateways should support the same application: GROMACS. 
* Can be either Web or GUI interface.
  * Allow the user to log in, run and monitor multiple GROMACS jobs (following https://kb.iu.edu/d/beus (Links to an external site.)).
  * Users should be able specify the number of nodes, wall time, input file.
  * Users should be able to download outputs.
* Submitting the Assignment
  * Make a named branch of your master branch (milestone-3).
  * Put all instructions in README-MILESTONE3.md. You could also use GitHub's wiki feature.
  * Submit the assignment in Canvas when you are ready. Include pointers to the appropriate GitHub branch and the documentation.
* Simplifying assumptions:
  * Do not attempt to maintain the user identity from UI server to backend. It is OK to run jobs under a common account. Do not attempt to implement sophisticated user identity management, single sign-on, etc.
  * TLS security between UI server and Application server is enough for the milestone. Don’t try to implement OAuth.


###  Week 9 - March 8th

#### Lectures

#### Project Milestone 4
* Enhance the middleware provide information services and track user metadata.
  * Users should be able to see a job history in the user interface
  * Events should be intercepted by the portal.
* Enhance the User Interface to support GROMACS submission on Big Red II as well as Karst
* Design and publish schema in GitHub for your metadata system.
  * Computing, applications, and experiments must be described.
* Design and publish a description of your information management system.
* Submitting the Assignment
  * Make a named branch of your master branch (milestone-4).
  * Put all instructions in README-MILESTONE4.md. You could also use GitHub's wiki feature.
  * Submit the assignment in Canvas when you are ready. Include pointers to the appropriate GitHub branch and the documentation.


### Spring Break - March 13th to 18th 

###  Week 10 - March 22nd - Midterm Demos, Presentations

#### Midterm Presentations
* Team Presentations
* 10 minute presentations by each team member
* Demo of Gateway
* System Design
  * What choices did you make for state management, data storage, API implementation, metadata modelings, etc
* Team recommendations
  * How can the team work more effectively?	
  * How can the class be more effective?


#### Assignment 5 

###  Week 11 - March 29th 

#### Lectures
* Introduction to Distributed Systems: [Slides]({{ site.url }}public/slides/I590-DistributedComputingScienceGateways.pdf)

#### Project Milestone 5
* Continuous Integration & Deployments

###  Week 12 - April 5th 

#### Lectures
* Microservices and Messaging: [Slides]({{ site.url }}public/slides/MicroServices-I590.pdf)

#### Assignment 6

###  Week 13 - April 12th

#### Lectures

#### Project Milestone 6 
* Scaling, Load Balancing, Fault Tolerance

###  Week 14 - April 19th 

#### Lectures

#### Assignment 7

###  Week 15 - April 26th - Final Demos, Presentations 

#### Lectures

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

### Reference Papers

* Mesos: A Platform for Fine-Grained Resource Sharing in the Data Center [Apache Mesos Paper](http://static.usenix.org/events/nsdi11/tech/full_papers/Hindman_new.pdf)
* ZooKeeper: Wait-free coordination for Internet-scale systems [Apache Zookeeper Paper](https://www.usenix.org/legacy/event/usenix10/tech/full_papers/Hunt.pdf)

## Open Collaboration

* Reuse and building upon ideas or code are major parts of modern software development.  As a professional programmer you will never write anything from scratch.  This class is structured such that all solutions are public.  You are encouraged to learn from the work of your peers. We won't hunt down people who are simply copying-and-pasting solutions, because without challenging themselves, they  are simply wasting their time and money taking this class.

* Please respect the terms of use and/or license of any code you find, and if you reimplement or duplicate a design or code from elsewhere, credit the original source.