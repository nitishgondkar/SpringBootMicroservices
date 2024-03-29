# **Spring Boot - Centralized (Spring Cloud Server) Configuration Example**

## Step 1 : Microservice Project - Initial Dependencies Chosen for below sample

![img_1.png](img_1.png)

## Step 2 : To create configurations in GIT Repository

````
nitis@DESKTOP-6MJIE3J MINGW64 /e/Learn_Microservices/MY_GIT/SpringBootMicroservices (main)
$ git --version
git version 2.31.1.windows.1

nitis@DESKTOP-6MJIE3J MINGW64 /e/Learn_Microservices/MY_GIT/SpringBootMicroservices (main)
$ pwd
/e/Learn_Microservices/MY_GIT/SpringBootMicroservices

nitis@DESKTOP-6MJIE3J MINGW64 /e/Learn_Microservices/MY_GIT/SpringBootMicroservices (main)
$ mkdir git-localconfig-repo

nitis@DESKTOP-6MJIE3J MINGW64 /e/Learn_Microservices/MY_GIT/SpringBootMicroservices (main)
$ cd git-localconfig-repo/

nitis@DESKTOP-6MJIE3J MINGW64 /e/Learn_Microservices/MY_GIT/SpringBootMicroservices/git-localconfig-repo (main)
$ pwd
/e/Learn_Microservices/MY_GIT/SpringBootMicroservices/git-localconfig-repo

nitis@DESKTOP-6MJIE3J MINGW64 /e/Learn_Microservices/MY_GIT/SpringBootMicroservices/git-localconfig-repo (main)
$ git init
Initialized empty Git repository in E:/Learn_Microservices/MY_GIT/SpringBootMicroservices/git-localconfig-repo/.git/

nitis@DESKTOP-6MJIE3J MINGW64 /e/Learn_Microservices/MY_GIT/SpringBootMicroservices/git-localconfig-repo (master)
$ ls
limits-service.properties

nitis@DESKTOP-6MJIE3J MINGW64 /e/Learn_Microservices/MY_GIT/SpringBootMicroservices/git-localconfig-repo (master)
$ git add limits-service.properties

nitis@DESKTOP-6MJIE3J MINGW64 /e/Learn_Microservices/MY_GIT/SpringBootMicroservices/git-localconfig-repo (master)
$ git commit -m "Adding limits-service.propeties"
[master (root-commit) bb5bcf6] Adding limits-service.propeties
1 file changed, 2 insertions(+)
create mode 100644 limits-service.properties
````

![img.png](img.png)

## Step 3 : Debugging problems with Spring Cloud Config Server - V2
Debugging microservices problems can be difficult as there are multiple components involved.

Step by Step instructions is provided in the troubleshooting guide to help you troubleshoot frequently occurring problems.

Using the Chrome Browser is recommended.

https://github.com/in28minutes/spring-microservices-v2/blob/main/03.microservices/01-step-by-step-changes/microservices-v2-1.md#spring-cloud-config-server---steps-01-to-08

## Step 4 : Pushing Config to Following Repository
https://github.com/nitishgondkar/git-localconfig-repo
