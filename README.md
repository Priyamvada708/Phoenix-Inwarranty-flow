# Postman API automation Integration with Github Actions

This repository is a demonstration for integrating Postman tests with githum actions. 
The tests are written in Postman and they are executed on the virtual machine with the help of newman and new-reporter-htmlextra. 
Github actions will trigger project execution with every push to the main branch. 
You can also execute the project manually using workflow_dispatch. The project runs on a scheduled time with the help of CRON job. 
The html reports is archived and kept in the artifact section for the team to download it along with the view of report directly from the github page
