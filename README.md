# 私を読んで

## 前提

- docker-compose

## How to use

```
docker-compose up
docker-compose exec rails bundle install
docker-compose exec rails rails db:migrate
docker-compose exec rails rails db:seed
docker-compose exec rails rails s -b 0.0.0.0
```

Access => http://localhost:3000/
