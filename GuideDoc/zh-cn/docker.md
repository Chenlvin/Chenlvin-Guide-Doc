# Docker 镜像加速

→ 访问 https://docker.zcy.life/

使用方法：

**1.在输入框内填入内容，直接在 DockerHub 中查找。**

**2.设置加速镜像服务**

修改 `/etc/docker/daemon.json` 配置文件

```
{  
	"registry-mirrors": ["https://docker.zcy.life"] 
}
```

**3.手动 Pull**

例如：

```
docker pull docker.zcy.life/teamspeak
```

