para levantar todo

docker compose up -d db
docker compose up -d backend-app
docker compose down backend-app
docker compose up --build