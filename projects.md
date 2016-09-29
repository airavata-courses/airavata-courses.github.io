---
layout: default
---

## Project Milestone Summaries

The course focuses in teaching the distributed systems concepts through projects. The lectures prepare the students to execute the projects.

###  Project 1: Microservices with DevOps (Due September 22)
* Microservices
* Continuous Integration and Deployment
* APIs: REST, Thrift, Swagger, etc
* Sample Web Interface
* Tools & Technologies 
    * At least 3 programming languages 
        * one for the UI
        * at least 2 distinct ones for the server components 
    * Amazon EC2 
    * Any database 
    * Apache Thrift or Apache Wink for Service Interfaces.
    * Travis-CI for Continuous Integration 
    * Amazon Codedeploy for Continuous Deployment
* **Project Submision Template [[Doc]]({{ site.url }}CS649Project1SubmissionTemplate.docx)**

###  Project 2: Security, Auditing, Distributed Coordination (Due October 20)
* Security: OpenID Connect and OAuth: show how to use OpenID Connect and OAuth2 to authenticate users and establish trust between multiple client tenants and the API gateway. Can use Google services.
     * Grader will verify 
* Multilevel Testing 1: Develop end-to-end system tests for your services. Develop “acceptance” and  “capacity” tests.  Capacity tests must break under some conditions. Set up your services so that you have separate testing and deployment environments.
     * Grader will verify that you have separate test and deployment environments automated using Travis and CodeDeploy.
* Provide plotting charts for your Capacity tests.
     * Determine operating range for system based on Capacity tests.
     * Modify your mock services so that they have limited capacity. For example, Each service spawn a new thread for each request Each request takes a configurable amount of time, ~3 minutes.
* Containerization: Use Docker as a container for your microservices and demonstrate how multiple services in containers can be deployed onto a single EC2 instance.
     * Grader will verify that you are able to deploy your services into docker containers for both your testing and production deployments on AWS.
     * All dependencies for a particular service are packaged.

###  Project 3: Reliability & Scaling (Due November 17)
* Fault tolerance
* Load Balancing
* Continuous upgrades without downtime

###  Project 4: Cyberinfrastructure (Due December 8)
* Interacting with remote computing resources and data
* Searching, sharing metadata
* Gateway metadata and provenance