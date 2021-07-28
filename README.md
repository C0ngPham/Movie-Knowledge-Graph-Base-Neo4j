# README

Neo4j movie app được xây dựng dựa trên data từ IMDB.

Source:
[OMDB Api](http://www.omdbapi.com/)
[grouplens.org](https://grouplens.org/datasets/movielens/)
Tổng hợp tại:
[neo4j-graph-examples](https://github.com/neo4j-graph-examples/recommendations/tree/main/data)

Backend được xây trên Node JS Express API, giao diện từ template Swagger. Thư mục `/api`.
Frontend được xây dựng trên React JS tại thư mục `/web`.
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
- [http://localhost:3000/docs](http://localhost:3000/docs)

## Frontend

Gọi các lệnh:

- `cd web`
- `nvm use`
- `npm install`
- configure `web/.env`
- Sau đó chọn Y để chuyển tên miền 3000 -> 3001
- `npm start` [http://localhost:3001/](http://localhost:3001/)
