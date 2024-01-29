## CI/CD Project Using Jenkins, Docker, Helm, and Kubernetes

This repository contains a complete implementation of a Continuous Integration/Continuous Deployment (CI/CD) pipeline for containerized applications using Jenkins, Docker, Helm, and Kubernetes. The setup also integrates tools like Sonarqube, Nexus, and Checkstyle within Jenkins for comprehensive code analysis.

## Execution Flow
Continuous Integration Setup
Jenkins, Sonarqube & Nexus Setup
Setting up the Continuous Integration environment with Jenkins, integrating Sonarqube and Nexus.
Dockerhub Account
Configure Dockerhub credentials in Jenkins.
Setup Docker Engine in Jenkins.
Install Docker-related plugins (Docker-pipeline, Docker, Pipeline Utility).
Create Kubernetes Cluster
Use Kops to create a Kubernetes cluster.
Install Helm in the Kops VM.
Create and test Helm charts in a Kubernetes test namespace.
Add Kops VM as a Jenkins slave.
Deployment Setup
Pipeline Code Creation
Create a declarative Jenkins pipeline script (Jenkinsfile).
Update the Git repository with Helm Charts, Dockerfile, and Jenkinsfile.
Jenkins Job
Create a Jenkins job for the pipeline.
Run and test the job.

## Prerequisites
- JDK 1.8 or later
- Maven 3 or later
- MySQL 5.6 or later

## Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- MySQL
## Database
Here,we used Mysql DB 
MSQL DB Installation Steps for Linux ubuntu 14.04:
- $ sudo apt-get update
- $ sudo apt-get install mysql-server

Then look for the file :
- /src/main/resources/accountsdb
- accountsdb.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < accountsdb.sql

## Kaushikq Ravindran

