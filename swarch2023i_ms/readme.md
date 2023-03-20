docker build -t swarch2023i_ms .

docker run -p 4000:4000 -e DB_HOST=172.17.0.1 -e DB_PORT=3306 -e DB_USER=swarch2023i -e DB_PASSWORD=2023 -e DB_NAME=swarch2023i_db -e URL=0.0.0.0:4000 swarch2023i_ms