# subweb dockerfile
按需修改conf/config.js 中的
1. siteName
2. apiUrl
3. shortUrl

在部署docker机器执行镜像构建, 镜像名、tag 按需修改
```
git clone https://github.com/jaychenthinkfast/dockerfiles.git
cd subweb
docker build -t subweb:jaychen . 
```
