---
layout: default
---

## Fall 2018 - Science Gateway Architectures

* **Course:** [CSCI-B 649, Topics in Systems](https://www.soic.indiana.edu/graduate/courses/index.html?number=b649&department=CSCI){:target="_blank"}, Computer Science, School of Informatics and Computing, Indiana University
* **Instructors:** Marlon Pierce, [marpierc@iu.edu](mailto:marpierc@iu.edu); Suresh Marru, [smarru@iu.edu](mailto:smarru@iu.edu)
* **Associate Instructors:** [Sneha Tilak](mailto:tilaks@umail.iu.edu); [Eldho Mathulla](mailto:emathull@umail.iu.edu)
    
* **Class Schedule** Tuesdays and Thursdays from 4 pm to 5.15pm in I2 (Informatics East) Room 130
* **Office Hours** On Request
* **Instant Messaging** Will provide a slack channel for instant communications

## Course Overview
Science gateways are distributed computing environments that enable scientists to conduct computational experiments on computing clouds and supercomputers and have revolutionized bioinformatics, computational chemistry, nano-engineering, atmospheric science and other scientific fields by bringing unprecedented computing power to a broad community of scientists. Gateways are interesting topics in their own right. Modern gateway systems utilize microservice architectures and DevOps principles in their design and operations, adopting lessons learned from cloud-based Software as a Service activities. 
Distributed systems by design scale software to handle large amount of data and to achieve better performance. Inherently distributed systems face challenges related to scaling and a system consists of multiple processes and these processes may run on different hardware systems. The challenges in distributed systems can be mainly categorized as follows:
* Scalability
* Efficiency: System handles large amount of data, so performance is important
* Fault tolerance: Now to solve a problem multiple processes work together. If a process goes down, system is not able to solve a problem.
* Operation: Easy scaling reduce operation complexity and cost
* Avoid over-engineering
* Ability to work with multiple devices
* Change management

In this course, students will be divided into development teams, and each team will build a distributed system software as a service system from scratch. Teams will be encouraged to explore alternative technologies and ways for building systems as well as learning DevOps principles such as containerization, continuous integration, and continuous deployment for deploying robust cloud services. Students will also be introduced to the Apache Software Foundation’s open community governance principles for open source software and will learn how to effectively interact with Apache Software Foundation projects in order to become committers and project management committee members. Finally the students will have an opportunity to apply the learnings to Apache Airavata based Science Gateways. 

## Course Objectives
* Provide a high level, broad understanding of the application of core distributed computing systems concepts to “Software as a Service” systems that support scientific research and education. 
* Study both abstract concepts and practical techniques for building science gateways.
* Provide hands-on experience in developing a science gateway while working with open source philosophies modelled after Apache Software Foundation.
* Apply the general concepts of Distributed Systems and understanding state of the art in applicable areas.

## Course Outcomes
* Demonstrate an applied understanding of microservice architectures and their underlying distributed systems foundations.
* Demonstrate an applied understanding of the DevOps principles of continuous integration and delivery to the development and operations of science 
* Demonstrate an understanding of open source practices, particularly those of the Apache Software Foundation.
* Demonstrate an ability to develop remote job submission interfaces to computational cyberinfrastructure like IU Big Red 2 Supercomputers.
* Demonstrate an ability to develop a simple metadata management system.
* Demonstrate an ability to develop and consume API services.

## Course Structure
Course Goal: students will, working in team of 2 to 3 students., learn and apply modern distributed computing concepts to a stand alone Apache Airavata and contribute them to the code base.

* All assignment reports are individual assignments even though projects are executed within groups.
* The course will be split into two parts
    * Part 1: Learning basic distributed computing concepts, microservices, DevOps etc
    * Part 2: Applying what you have learned to Apache Airavata 

## Instructors
The course will be taught by Marlon Pierce and Suresh Marru, who lead the Pervasive Technology Institute's [Science Gateways Research Center](https://sgrc.iu.edu/){:target="_blank"} and are  members of the Apache Software Foundation and project management committee members for the Apache Airavata open source software.

<!--
## Grading
* Homework Assignments: 
    * Each assignment is worth 10 points 
        * You will get 8 points for your submission
        * You will get 1 point for peer reviewing other submissions 
        * 2 peer review assignments 
    * There will be 7 assignments, with Assignment 7 counting 20 points
    * Assignments will be graded on functionality of the submission, which must be documented in your wiki
    * Each assignment is submitted as a Wiki entry in GitHub
    * Each student gets a github repo in https://github.com/airavata-courses 
    * Each assignment must be submitted for peer grading for 1 week, then submitted for final grading after two weeks
* Presentations and Reports
    * Each student makes a presentation (5 points)
    * Each student submits a report (5 points)
    * Midterm: 10 points
    * Final: 10 points

-->

## Apache Airavata Project Themes

1. Load balancing and fault tolerance of the API Server
1. Expanding Airavata microservice architecture with new services
    1. CI/CD for new services
    1. Allocation management
    1. Resource status, load, etc
    1. Postprocessing pipelines
1. Containerizing and orchestrating Airavata deployments
1. Airavata CI/CD
    1. Resource provisioning
    1. CI/CD 
    1. Blue-green deployments
    1. Testing and assurance
1. Workflows, task orchestration, scheduling, parameter sweeps
1. Improving interactions with remote resources: 
    1. Reducing errors with submissions,
    1. Improving monitoring, 
    1. Application-specific monitoring
    1. Running batch cloud applications
1. Logging, searching, and event detection
    1. Comprehensive, consolidated logging for all Airavata production services
    1. Logs for tenant admins
    1. Search, analytics, event detection
    1. Log visualization
1. User interfaces and user environments
    1. Jupyter, Django, and related stuff
    1. Application toolkits
    1. Visualization, science desktop integration
1. Data mining as a back end application
1. Data management and file transfer
 
## Resources

During the course, instructors will provide references to journal and conference papers. A good understanding of concepts discussed in these referred papers will greatly help in absorbing the course material. 

### Beginner Materials

* Principles of Distributed Computing – [Lecture Collection](http://disco.ethz.ch/lectures/podc_allstars/){:target="_blank"}
* [Overview of Apache Airavata](https://cwiki.apache.org/confluence/download/attachments/45876421/iwsg2014_submission_19%20(2)%20(1).pdf?version=1&modificationDate=1409604473000&api=v2)
* Apache Mesos: A Platform for Fine-Grained Resource Sharing in the Data Center [Apache Mesos Paper](http://static.usenix.org/events/nsdi11/tech/full_papers/Hindman_new.pdf)
* Apache ZooKeeper: Wait-free coordination for Internet-scale systems [Apache Zookeeper Paper](https://www.usenix.org/legacy/event/usenix10/tech/full_papers/Hunt.pdf)

## Open Collaboration

* Reuse and building upon ideas or code are major parts of modern software development.  As a professional programmer you will never write anything from scratch.  This class is structured such that all solutions are public.  You are encouraged to learn from the work of your peers. We won't hunt down people who are simply copying-and-pasting solutions, because without challenging themselves, they  are simply wasting their time and money taking this class.

* Please respect the terms of use and/or license of any code you find, and if you reimplement or duplicate a design or code from elsewhere, credit the original source.