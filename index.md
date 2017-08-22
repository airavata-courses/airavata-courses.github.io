---
layout: default
---

## Fall 2017 - Science Gateway Architectures

* **Course:** [CSCI-B 649, Topics in Systems](https://www.soic.indiana.edu/graduate/courses/index.html?number=b649&department=CSCI){:target="_blank"}, Computer Science, School of Informatics and Computing, Indiana University
* **Instructors:** Marlon Pierce, [marpierc@iu.edu](mailto:marpierc@iu.edu); Suresh Marru, [smarru@iu.edu](mailto:smarru@iu.edu)
* **Associate Instructors:** [Sneha Tilak](mailto:tilaks@umail.iu.edu); [Eldho Mathulla](mailto:emathull@umail.iu.edu)
    
* **Class Schedule** Tuesdays and Thursdays from 4 pm to 5.15pm in I2 (Informatics East) Room 150
* **Office Hours** On Request
* **HipChat Instant Messaging** https://www.hipchat.com/gMdyarVIz 

## Course Structure

* Course Goal: students will, working individually, learn and apply modern distributed computing concepts to Apache Airavata and contribute them to the code base.
* Assignments due every two weeks. 
* All assignments are individual assignments.
* The course will be split into two parts
    * Part 1: Learning basic distributed computing concepts, microservices, DevOps etc
    * Part 2: Applying what you have learned to Apache Airavata 


## Instructors
The course will be taught by Marlon Pierce and Suresh Marru, who lead the Pervasive Technology Institute's [Science Gateways Research Center](https://sgrc.iu.edu/){:target="_blank"} and are project management committee members for the Apache Airavata open source software.

## Grading
* Homework Assignments: 
    * Each assignment is worth 10 points 
        * You will get 8 points for your submission
        * You will get 1 point for peer reviewing other submissions 
        * 2 peer review assignments 
    * There will be 8 assignments
    * Assignments will be graded on functionality of the submission, which must be documented in your wiki
    * Each assignment is submitted as a Wiki entry in GitHub
    * Each student gets a github repo in https://github.com/airavata-courses 
    * Each assignment must be submitted for peer grading for 1 week, then submitted for final grading after two weeks
* Presentations and Reports
    * Each student makes a presentation (5 points)
    * Each student submits a report (5 points)
    * Midterm: 10 points
    * Final: 10 points

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

## Syllabus
* Week 1: Introductions
    * Lecture 1: August 22
    * Goal: Students should understand what the course is about and what is expected from them.
    * Topics: 
        * Introduce students to primary science gateways concepts
        * Introduce students to Apache Airavata
        * Introduce students to the Apache Way, open source
        * Introduce students to planned projects
    * Lecture 2: August 24th
        * Goal: Students should understand what the course is about and what is expected from them.
        * Assignment 1: August 29th
        * Using the programming language of your choice, develop 3 gateway services and a simple Web user interface: a registry service, an orchestrator service, an enactment service, and an API server.  
        * Every student must do this individually
* Week 2: Basic Skills, Part 1
    * Assignment 2: Assigned - August 29th; Due - September 12th
        * Using Docker, RabbitMQ, and Apache Jenkins, deploy a mockup Microservice system on Jetstream
    * Lecture 3: August 29th
        * Goal: students will understand the basics of microservices and messaging
        * Topic: Microservices and messaging
    * Lecture 4 - August 31st
        * Goal: students will understand how to use containers
        * Topic: Containers and container orchestration
* Week 3: Basic Skills, Part 2
    * Lecture 5 - September 5th
        * Goal: students will understand the basics of continuous integration and deployment
        * Topics: Code organization, CI/CD, DevOps
    * Lecture 6 - September 7th
        * Goal: Recap, reinforce initial lecture material
* Week 4: APIs 
    * Assignment 3: Assigned - September 12th; Due - September 26th
        * Using Assignment 2, containerize the microservices and use Apache Thrift as a serializable message format.
    * Lecture 7 - September 12th
        * Goal: Students will understand the use of internal and external APIs and data models within a microservice architecture
        * Topic: API, API servers: basics of REST, Thrift
   * Lecture 8 - September 14th
        * Goal: Students will understand the use of internal and external APIs and data models within a microservice architecture
        * Topic: APIs, API servers: load balancing and fault tolerance
* Week 5: Fabrics for Containers
    * Lecture 9 - September 19th
        * Goal: Students will understand the use of microservice fabrics
        * Topics: Apache Mesos and DC/OS
    * Lecture 10 - September 21st
        * Goal: Students will understand the use of microservice fabrics
        * Topics: Apache Helix, Apache Beam
* Week 6: Basics of Distributed Systems
    * Assignment 4: Assigned - September 26th; Due - October 10th
        * Using Assignment 3 and Apache Mesos, develop a load balancing approach that detects and handles faults on Jetstream
    * Lecture 11 - September 26th
        * Goal: Students will gain a basic understanding of distributed systems concepts and their relations to microservice architectures
        * Topics: Distributed systems intro, part 1
    * Lecture 12 - September 28th
        * Goal: Students will gain a basic understanding of distributed systems concepts and their relations to microservice architectures
        * Topics: Distributed systems intro, part 2
* Week 7: Monitoring, Searching, and Mining Logs
    * Lecture 13 - October 3rd
        * Goal: Students will understand the basics of the ELK stack and its use in microservice systems
    * Lecture 14 - October 5th
        * Goal: Students will understand the basics of the ELK stack and its use in microservice systems
* Week 8: Midterms
    * Assignment 5: Assigned - October 10th; Due - October 24th
        * Reconstruct Assignment 4 using Apache Helix
    * Mid-Term Presentations
        * October 10th
        * October 12th
* Week 9: Security 
    * Lecture 15 - October 17th
        * Goal: students will understand the basics of science gateway security 
    * Lecture 16 - October 18th
        * Goal: students will understand security implementations in science gateways
* Week 10: Backend Resources 
    * Assignment 6: Assigned - October 24th; Due - November 7th
        * Airavata Project 1
        * Each student will get a separate project 
    * Lecture 17 - October 24th
        * Guest Lecture: Jetstream and OpenStack
    * Lecture 18 - October 26th
        * Topic: Clusters and Supercomputers
* Week 11: Apache Airavata
    Lecture 19
    October 31st
    Goal: students will understand Apache Airavata basics and how to make contributions
    Lecture 20
    November 2nd
    Goal: students will understand Apache Airavata basics and how to make contributions
* Week 12: End User Environments
    * Assignment 7: Assigned - November 7th; Due - November 21st
        * Airavata Project 2
        * Each student will get a separate project
    * Lecture 21 - November 7th
    * Lecture 22 - November 9th
* Week 13: Guest Lectures
    * Lecture 23 - November 14th
        * Guest Lecture: TBD
    * Lecture 24 - November 16th
        * Guest Lecture: TBD
* Week 14: Thanksgiving
    * Assignment 8: Assigned - November 21st; Due - December 5th
        * Airavata Project 3
        * Each team will get a separate project
        * Thanksgiving week, no classes
* Week 15: Catch Up and Recap
    * Lecture 25: November 28th
        * Goal: Expand on previous lecture topics
    * Lecture 26: November 30th
        * Goal: Expand on previous lecture topics
* Week 16: Final Presentations
    * Final Team Presentations - December 5ht
    * Final Team Presentations - December 7th
* Week 17: Finals Week
    * Finals week, no classes
 
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