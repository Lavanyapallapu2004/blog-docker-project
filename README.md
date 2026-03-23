# Blog Docker Project

This is a simple multi-page blog website deployed using Docker and nginx.

## Features

- 4 pages (Home,About,Blog,Contact)
- Docker container
- Nginx server

## How to Run

docker build -t blog-app .
docker run -d -p 82:80 blog-app

## Access

http://localhost:82
