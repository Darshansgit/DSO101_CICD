# DSO101 - Continuous Integration and Continuous Deployment (Module Descriptor)

**Programme:** BE in Software Engineering  
**Credit:** 12  
**Module Tutor:** Douglas Sim & Darshan Subedi  
**Module Coordinator:** Douglas Sim

## General Objective
This module introduces students to the principles and practices of Continuous Integration and Continuous Deployment (CI/CD) in modern software development. It covers containerization with Docker, orchestration with Docker Compose, CI/CD pipelines using Jenkins and GitHub Actions, and best practices for security and optimization in DevOps workflows. Students will gain hands-on experience in setting up CI/CD environments, automating build and deployment processes, and integrating various tools and services commonly used in DevOps practices.

## Learning outcomes

On completion of the module, students will be able to: 

1. Explain the fundamental concepts of containerization and orchestration using Docker and Docker Compose. 
2. Build and manage Docker images and containers for existing projects. 
3. Implement multi-container applications using Docker Compose. 
4. Optimize Docker images for production environments, addressing security concerns and performance. 
5. Configure a CI/CD server using Jenkins. 
6. Create and manage Jenkins pipelines using both declarative and scripted syntax. 
7. Integrate code repositories with Jenkins to trigger automated pipelines. 
8. Utilize build tools and package managers within CI/CD pipelines for testing and packaging applications. 
9. Configure and integrate artifact repositories with CI/CD pipelines. 
10. Implement CI/CD workflows using GitHub Actions. 
11. Create a CD pipeline for automated deployment of containers to servers. 


## Learning and teaching approach

| Type              | Approach   | Hours/week | Credit hours |
|-------------------|------------|------------|--------------|
| Contact           | Lecture    | 2          | 30           |
|                   | Practical  | 2          | 30           |
| Independent Study | Assignment | 2          | 30           |
|                   | Self-study | 2          | 30           |
| Total             |            | 8          | 120          |

## Assessment Approach

Assessment components consist of Continuous Assessment (CA) Theory - 60% and Continuous Assessment (CA) Practical - 40%. The CA Theory will consist of Practical Work & Reports (20%) & Assignments (40%), and CA Practical consists of a Final Project (40%). Assessments will be carried out continuously through the following assessment components: 

### A. Practical Work & Report: (20%) 

Students are required to attend 2 hours of allocated weekly practical classes. Students shall submit a report for the particular practical class and practical work to an online version control system allocated by the HoD, SWE. 
The evaluation of practical components will be divided as follows: 
- 25% for practical reports 
- 75% for practical work 
  
The two sub-components shall be assessed out of 5 marks and 15 marks each respectively as follows: 
  - ***Practical Report: (5%)***
    Students have to write a report in the format prescribed by the module tutor and submit the report before the commencement of the next practical class. Each report will be evaluated using the following criteria: 
    - 2 Documentation 
    - 2 Reflection 
    - 1 Clarity & Coherence 

  - ***Practical Work: (15%)***
    Each student’s work will be assessed by the end of the practical classes to keep track of students’ learning and performance. The criteria for assessment are as follows: 
    - 3 Code Organisation & Readability 
    - 2 Code Comments 
    - 10 Configuration Requirements 


### B. Assignments: (40%) 

Students are required to complete four assignments throughout the semester. Each assignment will build upon the concepts covered in the lectures and practical sessions. 

Each assignment shall be assessed out of 10 marks as follows: 

*Assignment: (10%)* \
Students have to complete the assignment as per the requirements provided by the module tutor and submit their work to the designated online version control system allocated by the HoD, SWE. Each assignment will be evaluated using the following criteria:
- 1 Code Organization & Readability 
- 1 Code Comments & Documentation 
- 2 Configuration Requirements 
- 5 CI/CD Pipeline Implementation 
- 1 Deployment & Configuration 

### C. Final Project: (40%) 

Students will develop a comprehensive CI/CD pipeline that incorporates all major concepts learned in the module. Students will undertake a final project as a group. The students will start selecting their project topic in the 7th week which they will have to cover all concepts learned as they progress through the semester in the lectures and practical sessions. The project presentation will be done in the 14th and 15th weeks. 

For the assessment of the final project, students will present their projects and submit accompanying documentation and will be assessed out of 40 marks as given below: 

- A. Project Proposal (5%) 
    - 1 Aim and Objective 
    - 1 Feasibility 
    - 2 Expected Outcome 
    - 1 Work Plan 
- B. Implementation & Review (35%) 
    - 5 Docker Configuration & Optimization 
    - 5 CI/CD Pipeline Design 
    - 10 Pipeline Implementation 
    - 5 Integration with External Services 
    - 5 Security Considerations 
    - 5 Documentation & Presentation 

## Overview of the assessment approaches and weighting

| Areas of Assessment             | Quantity | Weighting (%) |
|---------------------------------|----------|---------------|
| A. Practical Work and Report    |8         | 20            |
| B. Assingments                  |4         | 40            |
| A. Practical Work and Report    |1         | 40            |
| Total                           |          | 100           |

## Pre-requisites

None

## Subject matter

### Unit I: Containerisation with Docker
```
Unit I: Containerization with Docker 
1.1 Introduction to Docker 
1.1.1 Containerization concepts 
1.1.2 Docker architecture 
1.1.3 Docker vs. virtual machines 
1.2 Working with Docker 
1.2.1 Installing Docker 
1.2.2 Docker CLI basics 
1.2.3 Pulling and running Docker images 
1.3 Building Docker Images 
1.3.1 Dockerfile syntax 
1.3.2 Building custom images 
1.3.3 Best practices for Dockerfile creation 
1.4 Docker Networking 
1.4.1 Docker network types 
1.4.2 Creating and managing Docker networks 
1.4.3 Container-to-container communication 
1.5 Docker Volumes 
1.5.1 Understanding Docker storage drivers 
1.5.2 Creating and managing volumes 
1.5.3 Persisting data with volumes 
```

### Unit II: Docker Compose and Multi-Container Applications
```
Unit II: Docker Compose and Multi-Container Applications 
2.1 Introduction to Docker Compose 
2.1.1 Docker Compose file structure 
2.1.2 Defining services, networks, and volumes 
2.2 Managing Multi-Container Applications 
2.2.1 Creating a multi-container application 
2.2.2 Scaling services with Docker Compose 
2.2.3 Compose file versions and compatibility 
2.3 Docker Compose in Development Environments 
2.3.1 Local development with Docker Compose 
2.3.2 Debugging applications in containers 
2.3.3 Compose overrides for different environments 
2.4 Docker Compose Best Practices 
2.4.1 Organizing Compose files 
2.4.2 Environment variables and secrets management 
2.4.3 Health checks and dependency management 
```

### Unit III: Docker Optimization & Registry 
```
3.1 Optimizing Docker Images
3.1.1 Multi-stage builds 
3.1.2 Reducing image size and layers 
3.1.3 Caching strategies for faster builds 
3.2 Working with Docker Registries 
3.2.1 Docker Hub and private registries 
3.2.2 Pushing and pulling images 
3.2.3 Image tagging strategies 
```

### Unit IV: : Introduction to CI/CD and Jenkins 

```
4.1 CI/CD Concepts and Principles 
4.1.1 Continuous Integration fundamentals 
4.1.2 Continuous Delivery vs. Continuous Deployment 
4.1.3 Benefits and challenges of CI/CD 
4.2 Jenkins Architecture and Setup 
4.2.1 Jenkins installation and initial configuration 
4.2.2 Jenkins plugins and extensions 
4.2.3 Configuring build agents 
4.3 Jenkins Jobs and Builds 
4.3.1 Creating and managing Jenkins jobs 
4.3.2 Configuring build triggers 
4.3.3 Understanding build steps and post-build actions 
4.4 Jenkins Pipeline Basics 
4.4.1 Introduction to Jenkins Pipeline 
4.4.2 Jenkinsfile syntax and structure 
4.4.3 Pipeline stages and steps 
```

### Unit V: Advanced Jenkins Pipeline and Integration 
```
5.1 Declarative vs. Scripted Pipelines 
5.1.1 Declarative Pipeline syntax 
5.1.2 Scripted Pipeline and Groovy basics 
5.1.3 Choosing between declarative and scripted pipelines 
5.2 Pipeline as Code 
5.2.1 Version controlling Jenkinsfiles 
5.2.2 Shared libraries in Jenkins 
5.2.3 Reusable pipeline components 
5.3 Integrating External Tools and Services 
5.3.1 Source control integration (Git, GitHub, etc.) 
5.3.2 Build tools and package managers (Maven, npm, etc.) 
5.3.3 Artifact repositories (Nexus, Artifactory) 
5.4 Testing in CI/CD Pipelines 
5.4.1 Unit testing integration 
5.4.2 Integration and end-to-end testing 
5.4.3 Test reporting and analysis
```

### Unit VI: Jenkins Security and Best Practices 
```
6.1 Jenkins Security 
6.1.1 User authentication and authorization 
6.1.2 Credential management in Jenkins 
6.1.3 Securing Jenkins instances 
6.2 Pipeline Optimization 
6.2.1 Parallelizing pipeline stages 
6.2.2 Caching and artifact management 
6.2.3 Performance tuning for Jenkins 
6.3 Monitoring and Logging 
6.3.1 Jenkins monitoring and alerting 
6.3.2 Log management and analysis 
6.3.3 Auditing Jenkins activities 
6.4 Jenkins Best Practices 
6.4.1 Pipeline design patterns 
6.4.2 Error handling and recovery 
6.4.3 Documentation and maintainability 
```

### Unit VII: GitHub Actions 
```
7.1 Introduction to GitHub Actions 
7.1.1 GitHub Actions concepts and components 
7.1.2 Workflow file structure and syntax 
7.1.3 GitHub Actions vs. Jenkins 
7.2 Creating GitHub Actions Workflows 
7.2.1 Defining jobs and steps 
7.2.2 Using pre-built actions 
7.2.3 Creating custom actions 
7.3 CI/CD with GitHub Actions 
7.3.1 Building and testing applications 
7.3.2 Deploying to various platforms 
7.3.3 Automating releases and versioning 
7.4 Advanced GitHub Actions Configurations & Tooling 
7.4.1 Matrix builds and strategy 
7.4.2 Environment secrets and variables 
7.4.3 Caching dependencies and artifacts 
```
## List of Practical(s)
1. Set up a Docker environment and containerize a simple web application. 
2. Create a multi-container application using Docker Compose. 
3. Optimize a Docker image for production and implement basic security measures. 
4. Set up a Jenkins server and create a basic CI/CD pipeline for a Git repository. 
5. Implement a Declarative Pipeline in Jenkins with multiple stages (build, test, deploy). 
6. Integrate external tools (e.g., package manager) and services (e.g., artifact registry) into a Jenkins pipeline.
7. Create a shared library for Jenkins and use it in a pipeline. 
8. Implement a complete CI/CD workflow using GitHub Actions and deploy to servers. 

## Reading list

### Essential Reading
- Laster, B. (2018). Jenkins 2: Up and Running: Evolve Your Deployment Pipeline for Next Generation Automation. O'Reilly Media. 
- Kane, S., & Matthias, K. (2023). Docker: Up and running: Shipping Reliable Containers in Production. O’Reilly Media. 
- Laster, B. (2023). Learning GitHub Actions: Automation and Integration of CI/CD with GitHub. O’Reilly Media. 
- Mout, A. (2016). Using Docker: developing and deploying software with containers. O’Reilly Media. 

**Date:** August 2024
