# 项目总述
管伊佳ERP

https://github.com/jishenghua/jshERP

https://gitee.com/jishenghua/JSH_ERP

开源说明请参照以上项目说明！

感谢大神开源如此好的应用！

如果感觉好用，不想折腾，不会折腾，可以去其官网购买云端产品，功能更全面。

开源版本没有生产模块，其他功能齐全！

最近在研究如何使用开源的ERP便于要地部署和外网访问，开源项目管伊佳ERP，研究了下windows下通过宝塔部署，有点复杂。
在B站上学习了两个视频：

【15分钟管伊佳ERP windows搭建视频教程】 https://www.bilibili.com/video/BV1BLGd6XEB9/?share_source=copy_web&vd_source=59a2aef54f4958e1d3307d0523040e9c

https://www.bilibili.com/video/BV1pyiJBDEie/
【免费！安全！不限速！Cloudflare最强内网穿透教程！】 https://www.bilibili.com/video/BV1pyiJBDEie/?share_source=copy_web&vd_source=59a2aef54f4958e1d3307d0523040e9c

通过学习内网穿透，没有设置成功。

之前试过DockerDesktop镜像，使用cloudflare的域名和Tunnels实现外网直接访问Docker镜像容器。
然后就使用OpenCode做了这个Docker，也不知道这个叫什么！
使用命令模式，在目录中执行
docker compose up -d
即可自动镜像并运行容器。可能网络不通畅用不了。使用cloudflar Zero Trust可以解决网络问题。
后面也会上传Docker打包镜像，方便网络不好的朋友使用。
