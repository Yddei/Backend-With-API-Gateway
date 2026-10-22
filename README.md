## Node.js Gateway + Spring Boot Backend

## How to Start
- **Requirements:** Maven, Docker
- **Steps:**
    - rename ```.env.example``` to ```.env```, set ```DB_USERNAME``` and ```DB_ROOT_PASSWORD``` values.
    - run ```docker-compose up --build -d``` in terminal, at root directory.
    - test API via Postman

## Overview
This project is a pure backend project, with some frontend.

## Checklist (for me)
  - [x] Containerisation (Docker)
  - [x] Implement authentication system
  - [x] API Gateway
  - [x] Spring Security Configuration
  - [x] Service Decoupling
      - [x] auth
      - [x] books
      - [x] orders

## Some API examples
- ```POST /api/auth/register```
- ```POST /api/auth/login```
- ```GET /api/books```
- ```GET /api/orders```
