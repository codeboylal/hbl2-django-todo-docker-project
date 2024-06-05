# Simple Notes App
This is a simple notes app built with React and Django.

## Requirements
1. Python 3.9
2. Node.js
3. React

## Installation
1. Clone the repository
```
https://github.com/codeboylal/hbl2-django-todo-docker-project.git
```

2. Build the app
```
docker build -t django-todo .
```

3. Run the app
```
docker run -d -p 8000:8000 django-todo
```

## Nginx

Install Nginx reverse proxy to make this application available

`sudo apt-get update`
`sudo apt install nginx`