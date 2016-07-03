#StuInfoSite-Deploy

课程设计的部署脚本

offline-build-version是为本地编译的image而准备的，具体请见该目录下的README.md

##部署过程

* 先登录 `docker login daocloud.io`（用户名密码可以私信找我要，如果我不给你，那你就用本地版的吧）
* 再安装[docker-compose](https://docs.docker.com/compose/): `sudo pip install docker-compose`
* 最后启动`docker-compose up`（如需后台启动可用`-d`参数）
