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

* Students will be divided into teams. 
Each team will have a project with 4 intermediate milestones.  There will also be a midterm and final presentation. The maximum number of points for the semester is 100.  90-100 points is an A, 80-89 points is a B, etc.

* Course Project 80%: There will be 4 project milestones, including mid-term and final milestones. Each project milestone is worth 20 points.
    * Must use Apache compatible open source licensed software and tools.
     * Projects must be checked into github, must be reproducibly executable on the deadline day by the instructors.
        * Linux/Unix compatible
        * If the instructors cannot execute your project and verify you have met the success criteria, the team receives 0 points.
        * A team may resubmit their assignment at any time before the next milestone. Each resubmission gets -1 points; i.e., 9 points if you get it right on the second try, 8 points on the third try, etc.
    * Students who show no activity (no github commits, no email discussions, etc) for the milestone will receive 0 points.
* Midterm Presentation: 5%  All team members must participate. This is worth 5 points.
* Final Presentation: 5% All team members must participate. This is worth 5 points.
* Classroom Interactions and Peer Reviews: 10%. The projects and the topics will require interactive pro-active participation. Also mimicking real-world open source and software development practices, the course requires students to be aware of other approaches to problems, borrowing ideas (with proper acknowledgements and no stealing and plagiarizing) and peer reviewing and offering constructive feedback. These demonstrated interactions (on github issues and pull requests) will be worth 10 points.  
    * 1 point perfect attendance
    * Up to 4 points classroom interactions
    * Up to 5 points for GitHub interactions with other projects (not your team’s project). Examples include
        * Posting bugs that get resolved
        * Resolving bugs in other team’s projects. These must be accepted to the code base. 
        * Trivial issues don’t get rewarded.

### Project Grading
* Each project will be judged on ~4 quality attributes. The number will vary by assignment
* To get all points, the project must demonstrate all attributes to the grader.  The grader must also be able to easily install and test all software by following documentation for the milestone in the team’s GitHub Wiki.
* Each student on the team will submit a report describing what they did
    * Give a percentage of effort for each attribute
    * Provide auditable proof via links to issues and commits.
    
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