# CICD-Jenkins-SonarQube-Docker-AWS
Implementing simple ci/cd pipeline using jenkins, sonarqube, github, webhook, docker all in aws ec2.
Firstly fetching the code from github using webhook (on push or pull requests) then scanning the code using sonarqube (ec2 type: t2 small) and then build a new docker image and run a new container from it and trying to access the new container which deployed on ec2 through the browser.
![sadfs](https://github.com/mohamedsamirspot/CICD-Jenkins-SonarQube-Docker-AWS/assets/71722372/5b00b356-2503-4b44-b072-efd2f0804c6b)


https://github.com/mohamedsamirspot/CICD-Jenkins-SonarQube-Docker-AWS/assets/71722372/575b30dc-8729-4eb8-933f-43f2ccd95f86
