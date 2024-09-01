# Docker Acceleration

→ Visit https://docker.zcy.life/

Usage：

**1.Fill in the input box and find it directly in DockerHub.**

**2.Configure Download Accelerate Service**

Edit `/etc/docker/daemon.json` profiles

```
{  
	"registry-mirrors": ["https://docker.zcy.life"] 
}
```

**3.Manual Pull**

Example：

```
docker pull docker.zcy.life/teamspeak
```

