# Docker + Nginx1.15.7 + MySQL5.7 + PHP7.3 + Redis5.0.3

# 目录结构
```
.
├── README.md
├── docker-compose.yml
├── log
│   ├── error.log
│   └── nginx.error.log
├── mysql57
│   ├── data
│   └── mysql.cnf
├── nginx
│   ├── conf.d
│   └── nginx.conf
├── php73
│   ├── Dockerfile
│   ├── php-fpm.conf
│   └── php.ini
├── redis
│   └── redis.conf
└── www
    └── localhost
```
# 运行
```
cd docker-php
cp .env.sample .env
docker-compose up
```

