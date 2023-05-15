# CICD-Jenkins-SonarQube-Docker-AWS
Implementing simple ci/cd pipeline using jenkins, sonarqube, github, webhook, docker, nginx all in aws ec2 to host a static website.
Firstly fetching the code from github using webhook (on push or pull requests) then scanning the code using sonarqube (ec2 type: t2 small) and then build a new docker image and run a new container (nginx) from it and trying to access the new container which deployed on ec2 through the browser.
![sadfs](https://github.com/mohamedsamirspot/CICD-Jenkins-SonarQube-Docker-AWS/assets/71722372/3c7a3b03-7ce3-4174-a3d3-85330cd26767)



https://github.com/mohamedsamirspot/CICD-Jenkins-SonarQube-Docker-AWS/assets/71722372/575b30dc-8729-4eb8-933f-43f2ccd95f86
