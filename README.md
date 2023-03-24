A Hello World applet built based on Maven, which is packaged into a WAR file
Build Template: Maven
Language: Java
Build Tool: Maven 3.5.3 and JDK 1.8

Build Command:

mvn package -Dmaven.test.skip=true  -U


## Pipeline

- Whether Automatic Pipeline Creation Is Supported: **Not supported**

- Pipeline Structure

> Start Stage
+ Source code repository

> Build Stage
+ Build task
+ Code check task

> Deployment Stage
+ Deployment task
+ API test task

## CloudIDE

- Whether Import to CloudIDE Is Supported: **Supported**

