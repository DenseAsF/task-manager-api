The Setup
- composer install
- docker compose up -d
- symfony console doctrine:migrations:migrate
- symfony server:start

The Links
- phpMyAdmin: http://localhost:8888/
- API Platform: http://localhost:8000/api

The Postman Endpoints
- GET http://localhost:8000/api/tasks (Get all)
- POST http://localhost:8000/api/tasks (Create)
- PATCH http://localhost:8000/api/tasks/[id] (Update)
- DELETE http://localhost:8000/api/tasks/[id] (Delete)
- GET http://localhost:8000/api/tasks/[id] (Get one)
