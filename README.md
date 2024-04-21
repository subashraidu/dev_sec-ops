# dev_sec-ops

+ when devops is extented with different security tools making shure that our pipeline is secure, no issues in source code
+ Making shure that every thing is secure from coding to deployment to production this process becomes devsecops

+ sonarqube is one of the security tool which we use as a part of dev secops
+ source code - syntaxic errors, bugs, vulnerbalities, etc - to make code free of these issues or make a decession
+ sonarqube does code coverage and code quality check
+ code coverage - code coverage is 80% means - 80% of our source code has been run or tested (percentage of lines of code that has been tested)
+ code quality checks - code might have bugs (if coding is wrong as per the requirement we raise as bug), vulnerability (section of source code that is open for attack), code smell (that section od code thst is poorly writen or that causes confussion)
+ if the above mentioned are issues are less in our code we say code quality is not good
+ why it is used so much - sonarqube is compatable with all sorts of programs for example if have java based program then also you can run sonarqube on it, python , nodejs, javascript etc irrespective of code language and generate a report
+ community version has a restriction on how many lines of code it can perform analysis
+ 3 ways we can install sonarqube 1- windows download and install sonarqube, ; linux - etc (to learn create a temperory sonar qube server which you can do using a docker container )
+ command: docker run -d --name sonar -p 9000:9000 sonarqube:lts-community (i want my application to run on 9000 port host and container port )
+ for running the analysis will be using jenkins
+   
