# Phoenix API Automation Integration with Git-hub Action #

This repository is a demonstration for POC for integrating postman tests with Github actions. The Tests are written in postman and they are executed on the VM with the help of newman-reporter-htmlextra.
Git-hub Actions will trigger the project execution on every push to the main branch. You can also execute the project manually using work-flow_dispatch. The projects runs on a scheduled time with the help of the cron job. 

The HTML report is archived and kept in the artifact section for the team to download it.

# Tech Stack #

1. Postman
2. NodeJS
3. Newman
4. Newman Reporter HTMLExtra
5. Git-hub Actions
6. Gmail SMTP
7. Git-hub Pages
8. CSV for Data Driven testing
9. AWS EC2 instance for self hosted github runner

