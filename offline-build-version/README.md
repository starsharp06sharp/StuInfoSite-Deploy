#StuInfoSite-Deploy (Offline)

要使用本目录下的脚本，你首先需要编译一下三个image：
* [StuInfoSite-db](https://github.com/starsharp06sharp/StuInfoSite-db)
* [StuInfoSite-nginx](https://github.com/starsharp06sharp/StuInfoSite-nginx)
* [StuInfoSite](https://github.com/starsharp06sharp/StuInfoSite)

具体编译方法见各repo的README.md

然后你需要安装[docker-compose](https://docs.docker.com/compose/): `sudo pip install docker-compose`

最后cd到本目录，运行`docker-compose up`（如需后台启动可用`-d`参数）