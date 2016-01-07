---
layout: default
---

# Science Gateway Architectures

* **Course:** [INFO-I590, Topics in Informatics, School of Informatics and Computing, Indiana University](https://www.soic.indiana.edu/graduate/courses/index.html?number=i590&department=INFO)
* **Instructors:** Marlon Pierce, [marpierc@iu.edu](mailto:marpierc@iu.edu); Suresh Marru, [smarru@iu.edu](mailto:smarru@iu.edu)

## Course Overview

The following video describes the course:

[![Course Overview](http://img.youtube.com/vi/zNM25fw56YE/0.jpg)](https://youtu.be/zNM25fw56YE)

Science gateways are distributed computing environments that enable scientists to conduct computational experiments on computing clouds and supercomputers and have revolutionized bioinformatics, computational chemistry, nano-engineering, and other scientific fields by bringing unprecedented computing power to a broad community of scientists.

Gateways are interesting topics in their own right. Modern gateway systems are moving towards microservice architectures and DevOps principles employing containerization (using Docker), continuous integration and continuous delivery. 

 Many gateways are also investigating how to integrate Apache’s “big data” and cloud computing software projects like Apache Mesos, Apache Spark, Apache Samza, Apache JClouds and Apache Kafka. RPC versus message-oriented middleware at scale is also an open question, as are NoSQL versus Relational DB approaches for gateway data management.  Finally, as gateways typically include Web-based user environments, choosing the right technologies and crafting the correct user experience are challenging problems.

In this course, students will be divided into development teams, and each team will build a science gateway software as a service system from scratch. Teams will be encouraged to explore alternative technologies and ways for building science gateways as well as learning DevOps principles for deploying robust cloud services.  Students will also be introduced to the Apache Software Foundation’s open community governance principles for open source software and will learn how to effectively interact with Apache Software Foundation projects in order to become committers and project management committee members.

### Course Objectives

* A highlevel, broad understanding of core concepts of science gateway architectures.

* Study of both abstract concepts and practical techniques for building science gateways.

* Hands-on experience in developing a science gateway while working with Open Source philosophies - particularly modelled after Apache Software Foundation.

* Applying the general concepts of Distributed Systems and understanding state of the art in applicable areas. 

### Course Outcome 

* After successfully completing this course, students should be ready to contribute to open source projects, apply general concepts of distributed systems to computational science problems and in general adopt to emerging paradigms and architectures.

* The course will provide opportunities to acquire required skills to apply for [Google Summer of Code](https://developers.google.com/open-source/gsoc/) like programs. 

* The course will cover breadth of topics and is expected to be rigorous and requires strong class and mailing list participation. Grades will be dependent on all of these aspects. 


## Instructors
The course will be taught by Marlon Pierce and Suresh Marru, who lead the IU Science Gateway Group and are project management committee members for the Apache Airavata open source software.

## Prerequisites

Students should be familiar with Linux and Unix operating systems, basic networking concepts, one or more programming languages, databases, basics of Web development, and version control systems


## Assignments

Points for each assignment are awarded for the number of required capabilities that can be demonstrated.

1. Assignment. Write clients that can submit and monitor jobs to BR2, Karst, and Amazon/Quarry/Jetstream.

2. Assignment: Develop initial services

3. Assignment: Continuous integration and deployment

4. Assignment : Determine and implement metadata management system

5. Assignment: Integration, end-to-end testing

6. Assignment: Throttling and scheduling

7. Assignment: Scaling, load balancing and fault tolerance

8. Assignment: Workflows


## Student Teams

* Team size will depend on enrollment but will range from 2-5.
* Agree on an editor and environment that the team is comfortable with. We recommend IntelliJ Idea
* Team members who are less experienced/comfortable should have more keyboard time
* Switch who's "driving" regularly
* Make sure to save the code and send it to all team members.

## Resources

During the course, instructors will provide referecnes to journal and conference papers. A good understanding of concepts discussed in these referred papers will greatly help in absorbing the course material. 

### Beginner Materials

* Principles of Distributed Computing – [Lecture Collection](http://disco.ethz.ch/lectures/podc_allstars/)


### Recommended Reading

* [Overview of Apache Airavata](link)


#### GitHub

* [Official GitHub Help](https://help.github.com/)
* [Recommended resources](http://hackerhours.org/resources.html#github)

## Grading

* Grades are based on points that each student acquires through submitting assignments, mid-term and final presentations, and peer reviewing other student’s codes.
    * 60% On-Going Semester Long Project
    * 10% Mid-Term Demo/Presentations
    * 10% Final Demo/Presentation
    * 20% Class Participation, constructive discussion in mailing lists, pull requests, contribution to fellow student code/design reviews.

* Other bonus opportunities will be available.
    * Student that contribute successful pull requests to other student for bug fixes will be rewarded, as will the student that accepts the pull requests. 

* The bulk of the grading is for Projects. It should be noted that the project evaluation is granularly broken down based on design, critical considerations of alternative approaches, building over existing solutions, implementation, well written tests and finally a report.  
    * Testing: An critical aspect of distributed systems programming is to develop comprehensive test methods for the programs. A significant effort should be invested in writing programs that will thoroughly test the system code, including the handling of different error conditions.
        * Refer Apache Airavata Test Driven Development [example](https://cwiki.apache.org/confluence/display/AIRAVATA/Tests+in+Airavata)
    * Gracefully handling errors: The code must reliably handle possible error conditions, both internal and reacting to external failures (in a distributed system context).
    * Resource Usage: Must manage resources such as memory, cpu and I/O usage with care. 
    * Security aspects: Projects involves developing network accessible services which are inherently vulnerable to malicious attacks. Security methodologies should be carefully considered. Students should be aware of potential flaws such as string overflows or malformed incoming messages and put an effort to mitigate them. 
    
## Open Collaboration

Reuse and building upon ideas or code are major parts of modern software development.  As a professional programmer you will never write anything from scratch.  This class is structured such that all solutions are public.  You are encouraged to learn from the work of your peers. We won't hunt down people who are simply copying-and-pasting solutions, because without challenging themselves, they  are simply wasting their time and money taking this class.

Please respect the terms of use and/or license of any code you find, and if you reimplement or duplicate a design or code from elsewhere, credit the original source.