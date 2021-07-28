# README

Neo4j movie app được xây dựng dựa trên data từ IMDB.

Source:
http://www.omdbapi.com/
https://grouplens.org/datasets/movielens/
Tổng hợp tại:
https://github.com/neo4j-graph-examples/recommendations/tree/main/data

Backend được xây trên JavaScript/Express backend tại thư mục `/api`.
Frontend được xây dựng tại thư mục `/web`.
Feel encouraged to fork and update this repo!

### Nodes

- `Movie`
- `Person`
- `Genre`

## Node API

Cấu hình `api/.env` đến Neo4j database.

Sau đó gọi các lệnh:

- `cd api`
- `nvm use`
- `npm install`
- `node app.js` Bắt đầu API
- [http://localhost:3000/docs]

## Frontend

Gọi các lệnh:

- `cd web`
- `nvm use`
- `npm install`
- configure `web/.env`

- `npm start` [http://localhost:3000/](http://localhost:3000/)
