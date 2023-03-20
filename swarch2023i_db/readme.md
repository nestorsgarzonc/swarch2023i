docker build -t swarch2023i_db .

docker run -d -t -i -p 3306:3306 --name swarch2023i_db swarch2023i_db