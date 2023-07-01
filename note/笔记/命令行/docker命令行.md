## Redis
`docker run -p 6379:6379 --name redis -v /Users/liuailin/Documents/SoftwareConfiguration/docker-redis/redis.conf:/etc/redis/redis.conf  -v /Users/liuailin/Documents/SoftwareConfiguration/docker-redis/data:/data -d redis redis-server /etc/redis/redis.conf --appendonly yes`

## Mysql
`docker run -p 3306:3306 --name mysql --restart=always --privileged=true -v /Users/liuailin/Documents/softwareConfiguration/docker-mysql/log:/var/log/mysql -v /Users/liuailin/Documents/softwareConfiguration/docker-mysql/data:/var/lib/mysql -v /Users/liuailin/Documents/softwareConfiguration/docker-mysql/conf:/etc/mysql/conf.d -e MYSQL_ROOT_PASSWORD=123456 -d mysql:latest`

