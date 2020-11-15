## RMIT SEPT 2020 Major Project Group 4


## AGME 🗓
A booking system web app aims to ease the booking of services between customers and businesses.


## Developers 🔧  
* LAM, John 
* MANKS, Brenton 
* ALMAHDAWI, Mohammed
* LEONG, Si Long
* VERNIK, Jonathan 

## Records 📃
* ClickUp Workspace : https://trello.com/invite/b/J1ZhzMzz/1426190fe915ef59313a0b78cb4ad7f5/sept-group-4


## Technologies 🖥
* Spring Boot
* Postgres
* ReactJS
* MaterrialUI
* Docker
* CI/CD
* AWS
* Terraform
* Kubernetes

## To Run the Backend on your local machine 💻
* Setup the backend configurations as follow.
Go to `BackEnd/src/main/resources/application.properties`
Change the line `spring.datasource.url=jdbc:postgresql://db:5432/sept_project` 
to `spring.datasource.url=jdbc:postgresql://localhost:5432/sept_project`

## To Run Docker ⛴☁
* Setup the backend configurations as follow.
Go to `BackEnd/src/main/resources/application.properties`
Change the line `spring.datasource.url=jdbc:postgresql://localhost:5432/sept_project` 
to `spring.datasource.url=jdbc:postgresql://db:5432/sept_project`
`docker-compose up --build`

## Kubernetes Configuration ⚓️

At `BackEnd/deployment/k8s`


## Code documentation

[Quick Start](/docs/README.md) in `docs` folder
