# JENKINS CICD PIPELINE

Client Name: Mercedes Benz
Project Name: DMS [Dealer Management System]

Mercedes Benz dealer onboarding applications were handled by the DevOps/SRE team, the 16 microservices were onboarded into the CICD pipeline with end to end integration of all tools where we had various suites like Security, build, docker, ansible, and K8 deployment. The Jenkins shared library along with the Jenkinsfile design for each microservice was done by both in an individual contribution and as a team work.

-	Integrated all tools with the Jenkins and designed various automation scripts in shell and python to check the various stages conditions in pipeline
-	Sonarqube QG was checked with shell script for each module and each microservice was on boarded to sonar
-	Automation of GITLAB/SONAR/JENKINS rest APIs was done.
-	Maintained the build servers of Jenkins where we had docker installed which converted the Jar into image
-	Jfrog rest api automation for cleanup of old binaries was done
-	Kubernetes manifest file design as per the development teams was handled where we had various kinds of deployments, daemonset, services etc.
-	Troubleshooting the pod deployment along with RCA was performed
