# Docker Project

## Overview

This project demonstrates the use of Docker for containerizing applications. It includes examples of both single and multi-stage Docker builds for different programming languages, specifically Go and Java.

## Directory Structure

Docker_Project/
├── Go_Program/
│ └── Docker_Without_Multistage/
│ ├── Calculator.go
│ └── Dockerfile
│ └── Docker_With_Multistage/
│ ├── Calculator.go
│ └── Dockerfile
├── Java_Program/
│ └── Docker_Without_Multistage/
│ ├── SimpleCalculator.java
│ └── Dockerfile
│ └── Docker_With_Multistage/
│ ├── SimpleCalculator.java
│ └── Dockerfile
└── README.md


## Go Program

### Description

A simple Go program for basic arithmetic operations. This project includes Dockerfiles for both single and multi-stage builds.

### Docker Build (Without Multistage)

1. Navigate to the Go project directory:

   ```bash
   cd Go_Program/Docker_Without_Multistage

2. Build the Docker image:

    docker build -f dockerfile_wms -t simplecalculator .

3. View the Docker images
   
    docker images


### Docker Build (With Multistage)

1. Navigate to the Go project directory:

   ```bash
   cd Go_Program/Docker_With_Multistage

2. Build the Docker image:

    docker build -f docker_multi_stage -t simplecalculator .


3. View the Docker images
   
    docker images


## Java Program

### Description

A simple Java program for basic arithmetic operations. This project includes Dockerfiles for both single and multi-stage builds.

Docker Build (Without Multistage)

1. Navigate to the Java project directory:

   ```bash
      cd Java_Program/Docker_Without_Multistage

2. Build the Docker image:

    docker build -f docker_wms -t simplecalculator-java .


3. View the Docker images
   
    docker images


### Docker Build (With Multistage)

1. Navigate to the Java project directory:

   ```bash
      cd Java_Program/Docker_With_Multistage

2. Build the Docker image:

    docker build -f docker_multi_stage -t simplecalculator-java-withmultistage .


3. View the Docker images
   
    docker images



