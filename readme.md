docker-compose up -d db

docker compose build

docker compose up rustapp

docker exec -it db psql -U postgres