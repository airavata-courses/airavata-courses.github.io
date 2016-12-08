---
layout: default
---

## Spring 2017 - Advanced Science Gateway Architectures

* **Course:** [CSCI-B 649, Topics in Systems](https://www.soic.indiana.edu/graduate/courses/index.html?number=b649&department=CSCI){:target="_blank"}, Computer Science, School of Informatics and Computing, Indiana University
* **Instructors:** Marlon Pierce, [marpierc@iu.edu](mailto:marpierc@iu.edu); Suresh Marru, [smarru@iu.edu](mailto:smarru@iu.edu)
                                                                                                                              
* **Class Schedule** Fridays from 1 pm to 3.30 pm in I2 (Informatics East) Room 130
* **Office Hours** On Request
* **HipChat Instant Messaging** https://www.hipchat.com/gMdyarVIz 

## Course Overview

The goal of this course is for the students, building on their experiences in the introductory “Science Gateway Architectures” course, to explore specific open problems in science gateway architectures. Working with the course instructors, students will learn how to formulate concrete problems from general research issues, design and implement solutions, and critically evaluate their solutions and the solutions of their peers.
<br/>
Over the last two decades, science gateways have matured from practical Web portals designed to submit jobs to supercomputers into full fledged distributed systems cyberinfrastructure that aims to manage all aspects of a computational and data science research, from conception to exploration to publication to reproducibility. It is a research challenge to investigate distributed systems architectures for science gateways that simultaneously enable scientific research in computational and data science, adopt the best modern “DevOps” practices for managing the developing and operations cycle, and have firm foundations in distributed systems concepts. The overarching problem is to do distributed computing research to define a reference architecture that can accommodate explorations of solutions to these challenges.
<br/>
In this course, we will examine the requirements for a distributed computing framework that can simultaneously address the requirements of both computational and data-centric cyberinfrastructure. Through exploratory projects, students will have the opportunity to map distributed systems concepts to science gateway requirements. Course topics will be based on the Apache Airavata framework, which will provide a laboratory for student projects; students will explore alternative approaches for implementing innovative capabilities within the Airavata. Students will gain visibility of their work through public pull requests to the Apache Airavata code repository and discussions of their work on the public Apache Airavata mailing lists. This course will requires the background of the Spring 2016 (INFO-I509) and Fall 2016 (CSCI-B 649) “Science Gateway Architecture” courses. Students must have approval from the instructors to enroll.

## Instructors
The course will be taught by Marlon Pierce and Suresh Marru, who lead the Science Gateways PTI Research Center and are project management committee members for the Apache Airavata open source software.

## Prerequisites

Students should have previously taken the Science Gateways Architecture course in Spring 2016 or Fall 2016. If you have not taken the course, email the instructors with your background and interests in the course. 

## Course Format and Weekly Lectures

The course will consist of 150 minutes/week of contact time with the instructors as lectures and team discussions. Specific classes will be structured around lectures on topics relevant to the projects. These will be a mixture of instructor-led and student-led presentations.

## Project Themes

Through exploratory themes, students will validate their understanding or learn foundation distributed systems concepts like Reliability, Scalability, Efficiency and Availability. The class will enable the students to get deeper insights into modern web scale systems and assumes understanding of DevOps strategies, microservice architecture principles and underpinning concepts like applications of CAP theorem.
<br/>
Each student will contribute to one or more project themes from the list below as part of a student team. The student teams will be responsible for researching, designing, implementing, and evaluating their solutions. Each theme will be assigned a project leader, who will be an experienced Apache Airavata developer, and 2-3 additional student team members.

* Theme 1: APIs, Data Model Representation and Storage
    * API Comparisons: REST, Swagger, Thrift, ProtoBuff etc.
    * Optimal serialization, deserialization, storage and search strategies
    * Internal (CPI) versus externally exposed (API) data models
* Theme 2: Distributed Workload Distribution
    * Load Balancing Stateful vs Stateless Services
    * Message based vs hybrid message-RPC vs pure RPC.
    * Work-Queue vs Master-Worker load balancing
* Theme 3: DevOps Strategies
    * Fault tolerance testing and validation
    * Load balancing testing and validation
    * Continuous upgrades without downtime
    * Capacity testing
    * Comparison of hosting alternatives: OpenStack (Jetstream), Amazon AWS, Google, Microsoft Azure
* Theme 4: Cyberinfrastructure Integration
    * Interacting with remote computing resources and data
    * Metascheduling
    * Gateway metadata and provenance
    * Alternative resource utilization
* Theme 5: Cybersecurity
    * PHI, HIPAA, etc alignment for gateways
    * DevSecOps practices
    * Auditing, monitoring, and event detection
    * Client assurance
* Theme 6: Data-Centric Computing and Gateways
    * Airavata and data stream processing
    * Internet of Things and Airavata
    * Searching and data mining structured data sets
    * Event-driven computations
* Theme 7: Scientific User Environments
    * Gateways and interactive computing
    * Application monitoring
    * Visualization
    * Modern user interfaces and environments for science
    * Notebook integration
* Theme 8: Application Toolboxes for Airavata Applications
    * Defining toolboxes: application and resource collections.
    * Toolbox templates
    * Packaging, integrating, and sharing tool boxes

## Grading

This will be a project-based course with students working on team projects. Each project will be subdivided into four milestones with specific, demonstrated deliverables that the student teams will present to the class. Students will use these deliverables to evaluate their solutions and make specific conclusions on their solutions to the project challenges. All work will be in public GitHub or Apache-hosted repositories.
<br/>
Each project milestone will be worth 20 points. To earn full credit, the student teams must submit the project milestone on time and demonstrate to the instructors that all required deliverables and evaluations were met.
<br/>
Each student will also be assigned 5 thirty-minute presentations throughout the semester, with each presentation worth points (5 points total). Students will submit a final report (10 points), in
which the student will summarize his/her individual work and contributions. This will include pointers to the student’s code contributions, developer list discussions, presentation materials, etc. The remaining 5 points are awarded based on attendance, classroom participation, and interactions with other students and with the instructors.

    
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