# Student_Details_APITesting

## How to run this project

- Clone this project
- Open with Postman / Command Shell
- Run Command:

```bash
  newman run Student_Details.postman_collection.json -e Student_Details.postman_environment.json
```
- Run Command for Report:
```bash
  newman run  Student_Details.postman_environment.json -e Student_Details.postman_environment.json -r cli,htmlextra
```
## Tools
- Postman
- Newman

## Prerequisite:
- Jdk
- Node Js
- Newman
- Html Report Library

## Newman and Report Installation Process:

Newman Install Command:

```bash
  npm install -g newman-reporter-htmlextra
```
  Newman Html Report Install Command:
```bash
  npm install -g newman-reporter-htmlextra
```

## API Documentation
The documentation can be found at 

## Test case list:

   
## Newman Report Summary:
![report2](https://github.com/AbidaAfrin/API-Testing-Project_TheTestingWorld/assets/126371236/7262cf8a-606f-4c2c-a700-aefc8d00027c)
![report3](https://github.com/AbidaAfrin/API-Testing-Project_TheTestingWorld/assets/126371236/90d725f1-3974-4ffa-8855-ee180c69a2aa)
