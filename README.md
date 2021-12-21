# mageni-docker (debian)
Mageni provides a free, open-source cybersecurity vulnerability management solution.

It indicates potential or proven weaknesses on the machines tested. This includes, among others: services vulnerable to attacks allowing the machine to be taken over, access to sensitive information, denials of service, etc.

## Prerequisites
1) To use this project, create an account on this url : https://www.mageni.net/register
2) Create a token and keep them, it will be use at the next step.

## Installation / Configuration
1) Download this project.
```
git clone https://github.com/CobblePot59/mageni-docker.git
```
2) Modify docker-compose.yml arguments.
```
args:
token: "" # generate earlier
webpass: "admin" # webui password for admin user
```
3) Launch docker-compose to start the app.
```
docker compose up -d --build
```

## Preview
![alt text](https://raw.githubusercontent.com/CobblePot59/mageni-docker/main/preview.png)
