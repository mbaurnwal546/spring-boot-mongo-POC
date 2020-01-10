# Jenkins Kubernetes Integration & deploying application(Spring Boot + MongoDB) and monitoring using Prometheus/Grafana

**Spring Boot:**
Spring Boot is an open source Java-based framework used to create a micro Service. It is used to build stand-alone and production ready spring applications. Spring Boot provides a good platform for Java developers to develop a stand-alone and production-grade spring application that you can just run.

**MongoDB:**
MongoDB is an open-source document database and leading NoSQL database

# This POC covers the below setup:
1. Installation of jenkins,Docker,Maven on jenkins server
2. Installation of kubernetes cluster (As part of this poc 1 master and 1 worker node)
3. Setup jenkins server to deploy application into kubernetes cluster
4. Build and deploy docker Application from jenkins in kubernetes cluster using pipeline script

**Purpose:** To deploy application  into kubernetes cluster integrating with jenkins automation

**Technologies used:** EC2 inatances,Git,jenkins,Maven,Docker,Dockerhub,Kubernetes cluster

# Architecture of application deployment:

![Architecture](https://github.com/mbaurnwal546/spring-boot-mongo-POC/blob/master/Architecture.jpg)

# Implementation steps:
Follow the attached documenet for steps in details. (Jenkins Kubernetes Integration.doc)

Youtube: https://youtu.be/mtWlnlXy6IU
