# Science Gateway Architectures syllabus

* **Course:** [INFO-I590, Indiana University School of Informatics and Computing](https://www.soic.indiana.edu/graduate/courses/index.html?number=i590&department=INFO)
* **Instructors:** Marlon Pierce, [marpierc@iu.edu](mailto:marpierc@iu.edu); Suresh Marru, [smarru@iu.edu](mailto:smarru@iu.edu)

## Course Overview

Science gateways are distributed computing environments that enable scientists to conduct computational experiments on computing clouds and supercomputers and have revolutionized bioinformatics, computational chemistry, nano-engineering, and other scientific fields by bringing unprecedented computing power to a broad community of scientists.

Gateways are interesting topics in their own right. Modern gateway systems are moving towards microservice architectures and DevOps principles employing containerization (using Docker), continuous integration and continuous delivery. 

 Many gateways are also investigating how to integrate Apache’s “big data” and cloud computing software projects like Apache Mesos, Apache Spark, Apache Samza, Apache JClouds and Apache Kafka. RPC versus message-oriented middleware at scale is also an open question, as are NoSQL versus Relational DB approaches for gateway data management.  Finally, as gateways typically include Web-based user environments, choosing the right technologies and crafting the correct user experience are challenging problems.

In this course, students will be divided into development teams, and each team will build a science gateway software as a service system from scratch. Teams will be encouraged to explore alternative technologies and ways for building science gateways as well as learning DevOps principles for deploying robust cloud services.  Students will also be introduced to the Apache Software Foundation’s open community governance principles for open source software and will learn how to effectively interact with Apache Software Foundation projects in order to become committers and project management committee members.

### Course Objectives

* In depth understanding of core concepts of science gateway architectures.

* Study of both abstract concepts and practical techniques for building science gateways.

* Hands-on experience in developing a science gateway from scratch while working with Open Source philosophies - particularly modelled after Apache Software Foundation.

* Applying the general concepts of Distributed Systems and understanding state of the art in applicable areas. ### Course Outcome * After successfully completing this course, students should be ready to contribute to open source projects, apply general concepts of distributed systems to computational science problems and in general adopt to emerging paraidgms and architectures.
* The course will prepare the students to compete in Google Summer of Code like programs. 
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

* Git and GitHub
    * [Official GitHub Help](https://help.github.com/)
    * [Recommended resources](http://hackerhours.org/resources.html#github)


## Grading

* Grades are based on points that each student acquires through submitting assignments, mid-term and final presentations, and peer reviewing other student’s codes.

	* Students who show little activity on GitHub may not receive their points.

* Other bonus opportunities will be available.

	* If a student adopts a component from another student, both the adopting student and the donating student will receive bonus points. This can be done 2 times per student per semester.

	* Student that contribute successful pull requests to other student for bug fixes will be rewarded, as will the student that accepts the pull requests. 


## Open Collaboration

Reuse and building upon ideas or code are major parts of modern software development.  As a professional programmer you will never write anything from scratch.  This class is structured such that all solutions are public.  You are encouraged to learn from the work of your peers. We won't hunt down people who are simply copying-and-pasting solutions, because without challenging themselves, they  are simply wasting their time and money taking this class.

Please respect the terms of use and/or license of any code you find, and if you reimplement or duplicate an algorithm or code from elsewhere, credit the original source.


## Acknowledement 
The github repository structure, website and sysllabus are forked from https://github.com/advanced-js/syllabus. We thank Aidan Feldman for setting up a good example github based cousrse. 

## License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This <span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" rel="dct:type">work</span> and all other materials under https://github.com/airavata-courses are licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
