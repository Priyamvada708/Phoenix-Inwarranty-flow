
# Postman API automation Integration with Github Actions

This repository is a demonstration for integrating Postman tests with githum actions. 
The tests are written in Postman and they are executed on the virtual machine with the help of newman and new-reporter-htmlextra. 
Github actions will trigger project execution with every push to the main branch. 
You can also execute the project manually using workflow_dispatch. The project runs on a scheduled time with the help of CRON job. 
The html reports is archived and kept in the artifact section for the team to download it along with the view of report directly from the github page https://priyamvada708.github.io/Phoenix-Inwarranty-flow/
The latest report is mailed to the user who is using GMAIL SMTP


## Tech stack
Postman

Nodejs 22v

newman-reporter-htmlextra

Github Actions

GMAIl SMTP

Github Pages

csv for DDT

AWS

EC2 instance for self hosted github runner

### Github Pages
You can directly view the latest test report of the Pstman test https://github.com/Priyamvada708/Phoenix-Inwarranty-flow/deployments/github-pages

![Postman Report](https://raw.githubusercontent.com/Priyamvada708/Phoenix-Inwarranty-flow/Static_Content/newman_report.png)



