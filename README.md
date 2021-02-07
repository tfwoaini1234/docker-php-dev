# docker-php-dev
    基于docker的PHP环境配置，利用docker-compose启动，主要环境是nginx:1.18.0，mysql:5.7.33，redis:6.0.10，php:7.4。

> 启动服务

```
1.克隆基础项目
git clone https://github.com/tfwoaini1234/docker-php-dev.git
2.修改.ENV文件夹
BASE_DIR = /e/www/docker-php-dev 替换为自己的项目目录路径
3.根目录启动命令
docker-compose up -d (-d 后台启动，想看启动过程排查问题去掉-d)
```

> 检测运行
   
    浏览器访问localhost:8080。成功打印出phpinfo信息即成功启动。
