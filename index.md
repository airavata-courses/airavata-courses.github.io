---
layout: default
---

## Science Gateway Architectures

* **Course:** [CSCI-B 649, Topics in Systems](https://www.soic.indiana.edu/graduate/courses/index.html?number=b649&department=CSCI){:target="_blank"}, Computer Science, School of Informatics and Computing, Indiana University
* **Instructors:** Marlon Pierce, [marpierc@iu.edu](mailto:marpierc@iu.edu); Suresh Marru, [smarru@iu.edu](mailto:smarru@iu.edu)
* **Class Schedule** Tuesdays and Thursdays from 4 pm to 5.15pm in I2 (Informatics East) Room 150
* **Office Hours** Tuesdays and Thursdays from 3 pm to 4pm in I2 (Informatics East) Room 226B

## Course Overview

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
The course will be taught by Marlon Pierce and Suresh Marru, who lead the Science Gateways PTI Research Center and are project management committee members for the Apache Airavata open source software.

## Prerequisites

Students should be familiar with Linux and Unix operating systems, basic networking concepts, one or more programming languages, databases, basics of Web development, and version control systems

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