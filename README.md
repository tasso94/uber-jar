> Workshop 1 @ CamundaCon 2019

In this Work~~ship~~shop you learn how to use Spring Boot to create a self-contained Camunda BPM Workflow application.

In a nutshell, you are guided through the following topics:
* Creating a New Project
* Connecting to a Database
* Modeling & Executing a Workflow
* Customizing the Webapps
* Securing the REST API

## Prerequisites

> ⚠️ **Heads-Up!**
>
> Make sure to fulfill the prerequisites before you attend the workshop!

### Step 1: Download & Setup
* Docker for [Mac](https://download.docker.com/mac/stable/31259/Docker.dmg) or [Windows](https://download.docker.com/win/stable/31259/Docker%20for%20Windows%20Installer.exe)
* [Java JDK](https://jdk.java.net/12/) (8+)
* [Apache Maven](https://maven.apache.org/download.cgi)
* [Camunda Modeler](https://camunda.com/download/modeler/)
* Java IDE (e. g. [IntelliJ IDEA](https://www.jetbrains.com/idea/download/))

### Step 2: Pull PostgreSQL Docker Image
Please pull the image `postgres` by running the following command:
```sh
docker pull postgres
```

### Step 3: Download & Uncompress the Project Skeleton
1. Download the [Project Skeleton](https://github.com/camundacon2019/uber-jar/archive/1-project-skeleton.zip)
2. Unpack the ZIP file

### Step 4: Download the Maven Dependencies
1.  Open the project skeleton folder on your command line:
    ```shell script
    cd ./project
    ```
2.  Download the dependencies with Maven by running the following command inside the project folder:
    ```shell script
    mvn clean install
    ```
3.   Watch out for similar output:

```
[INFO] Installing $HOME/project/target/spring-boot-workshop-0.0.1-SNAPSHOT.jar to ~/.m2/com/camundacon/workshop/spring-boot-workshop/0.0.1-SNAPSHOT/spring-boot-workshop-0.0.1-SNAPSHOT.jar
[INFO] Installing $HOME/project/pom.xml to ~/.m2/com/camundacon/workshop/spring-boot-workshop/0.0.1-SNAPSHOT/spring-boot-workshop-0.0.1-SNAPSHOT.pom
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time: 54.963 s
[INFO] Finished at: 2019-09-07T11:47:41+02:00
[INFO] ------------------------------------------------------------------------
```
