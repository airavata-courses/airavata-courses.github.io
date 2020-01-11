---
layout: default
---

## Spring 2020 - Applied Distributed Systems

* **Course:** [CSCI-B 649, Topics in Systems](https://luddy.indiana.edu/academics/courses/class/iub-spring-2020-csci-b649){:target="_blank"}, Computer Science, Luddy School of Informatics, Computing and Engineering, Indiana University
* **Instructors:** Marlon Pierce, [marpierc@iu.edu](mailto:marpierc@iu.edu); Suresh Marru, [smarru@iu.edu](mailto:smarru@iu.edu)

* **Class Schedule** Tuesdays and Thursdays from 4 pm to 5.15pm in Woodburn Hall Room 111
* **Office Hours** To Be Scheduled

## Instructors
The course will be taught by Marlon Pierce and Suresh Marru, who lead the Pervasive Technology Institute's [Cyberinfrastructure Integration Research Center](https://circ.iu.edu/){:target="_blank"} and are nominated members of the [Apache Software Foundation](https://www.apache.org/){:target="_blank"} and project management committee members for the [Apache Airavata](https://airavata.apache.org/){:target="_blank"} open source distributed computing software framework.

## Course Overview
Distributed software systems use software components operating on multiple, coordinated computing resources to handle large amounts of data, provide resilience by removing single points of failure, and achieve better performance than single-component systems. Such systems form the backbone of enormously scalable cloud-based software systems that power social networks, e-commerce, streaming media services, and many others; however, many of the core concepts for distributed systems that underlie the modern services go back decades and need to be understood in order to build new systems. 


Inherently, distributed systems face challenges that can be categorized as follows:
* Scalability: How well does the system scale as it adds more resources? What are the overheads for management and coordination as the system grows?
* Efficiency: System handles large amount of data, so performance is important
* Fault tolerance: Can the system continue to operate if some of the components fail? Can the system recover full capacity when resources come back online?
* Communications: How do the components of the system communicate?  How well does the system handle message latency and loss?
* Heterogeneity: How can a system be built out of components developed using multiple programming languages, supporting components (such as databases), etc?  
* Integration, Deployment, and Operation: How can multi-component systems developed by multiple teams be integrated, tested, deployed into production, and operated at scale?
* User Environments: How can user environments be developed at scale? How can they efficiently evolve as the underlying system evolves?
* Security: how can these systems be operated securely? How can security problems be detected?


As an applied course, the students will get an opportunity to work with concrete instances of distributed systems. Science gateways are distributed computing environments that enable scientists to conduct computational experiments on computing clouds and supercomputers and have revolutionized bioinformatics, computational chemistry, nano-engineering, atmospheric science and other scientific fields by bringing unprecedented computing power to a broad community of scientists. Gateways are interesting topics in their own right. Modern gateway systems utilize microservice architectures and DevOps principles in their design and operations, adopting lessons learned from cloud-based Software as a Service activities. 


In this course, students will be divided into development teams, and each team will build a distributed system software as a service system from scratch. Teams will be encouraged to explore alternative technologies and ways for building systems as well as learning DevOps principles such as containerization, continuous integration, and continuous deployment for deploying robust cloud services. Students will also be introduced to the Apache Software Foundation’s open community governance principles for open source software and will learn how to effectively interact with Apache Software Foundation projects in order to become committers and project management committee members. Finally, the students will have an opportunity to apply the learning to Apache Airavata based Science Gateways.

## Course Objectives
* Provide a high level, broad understanding of the application of core distributed computing systems concepts to “Software as a Service” systems that support scientific research and education. 
* Study both abstract concepts and practical techniques for building science gateways.
* Provide hands-on experience in developing a science gateway while working with open source philosophies modelled after Apache Software Foundation.
* Apply the general concepts of Distributed Systems and understanding state of the art in applicable areas.

## Course Outcomes
* Demonstrate an applied understanding of cloud native, microservice architectures and their underlying distributed systems foundations.
* Demonstrate an applied understanding of the DevOps principles of continuous integration and delivery to the development and operations of science. 
* Demonstrate an understanding of open source practices, particularly those of the Apache Software Foundation.
* Demonstrate an ability to develop a metadata management system for managing the digital objects created by the system.
* Demonstrate an ability to develop and consume API services.
* Demonstrate an ability to apply discovery, load balancing, failure recovery, metrics, and monitoring to a distributed system. 
* Demonstrate ability to perform scalability testing, canary rollouts, rate limiting, access control, and end-to-end authentication.

## Course Structure
* Course Goal: students will, working in a team of 3-4 students, learn and apply modern distributed computing concepts to a stand alone Apache Airavata and contribute them to the code base.
* Assignments
    * Assignments due every four weeks
    * All assignments are individually submitted; use GitHub to provide an auditable record of your contributions to your team’s work.
* The course will be split into two parts
    * Part 1: Learning basic cloud native architectures, distributed computing concepts, microservices, DevOps etc
    * Part 2: Applying what you have learned to Apache Airavata 

## Grading
This will be a project heavy course. Students will be divided into teams. Each team will have 3 projects.  There will also be a midterm and final presentation. The maximum number of points for the semester is 100.  90-100 points is an A, 80-89 points is a B, etc.


* Course Projects 90%:  There will be 3 projects, including mid-term and final milestones.  Each project is worth 25 points.  
    * Must use Apache compatible open source licensed software and tools
    * Projects must be checked into github, must be reproducibly executable on the deadline day by the AI’s and instructors.
        * Linux/Unix compatible
        * If the instructors cannot execute your project and verify you have met the success criteria, the team receives 0 points.
        * A team may resubmit their assignment at any time before the next milestone. Each resubmission gets -1 points; i.e., 9 points if you get it right on the second try, 8 points on the third try, etc.
    * Students who show no activity (no github commits, no email discussions, etc) for the milestone will receive 0 points.
    * Up to 5 points for GitHub interactions with other projects (not your team’s project). Examples include
        * Posting bugs that get resolved
        * Resolving bugs in other team’s projects. These must be accepted to the code base. 
Trivial issues don’t get rewarded.
* Classroom Interactions and Peer Reviews: 10%. The projects and the topics will require interactive pro-active participation. Also mimicking real-world open source and software development practices, the course requires students to be aware of other approaches to problems, borrowing ideas (with proper acknowledgements and no stealing and plagiarizing) and peer reviewing and offering constructive feedback. These demonstrated interactions (on github issues and pull requests) will be worth 10 points.  
    * 1 point perfect attendance
    * Up to 4 points classroom interactions

* Project Grading
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
* Apache Mesos: A Platform for Fine-Grained Resource Sharing in the Data Center [Apache Mesos Paper](http://static.usenix.org/events/nsdi11/tech/full_papers/Hindman_new.pdf)
* Apache ZooKeeper: Wait-free coordination for Internet-scale systems [Apache Zookeeper Paper](https://www.usenix.org/legacy/event/usenix10/tech/full_papers/Hunt.pdf)

## Open Collaboration

* Reuse and building upon ideas or code are major parts of modern software development.  As a professional programmer you will never write anything from scratch.  This class is structured such that all solutions are public.  You are encouraged to learn from the work of your peers. We won't hunt down people who are simply copying-and-pasting solutions, because without challenging themselves, they  are simply wasting their time and money taking this class.

* Please respect the terms of use and/or license of any code you find, and if you reimplement or duplicate a design or code from elsewhere, credit the original source.