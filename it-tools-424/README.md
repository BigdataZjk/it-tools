![logo](.github/logo.png)

适用于开发人员和IT人员的有用工具, [去看看](https://it-tools.tech).


## 部署

**docker hub部署:**

```sh
docker run -d --name it-tools --restart unless-stopped -p 8080:80 corentinth/it-tools:latest
```

**github packages部署:**

```sh
docker run -d --name it-tools --restart unless-stopped -p 8080:80 ghcr.io/corentinth/it-tools:latest
```

**其他部署方式:**

- [Cloudron](https://www.cloudron.io/store/tech.ittools.cloudron.html)
- [Tipi](https://www.runtipi.io/docs/apps-available)
- [Unraid](https://unraid.net/community/apps?q=it-tools)


## License

此项目遵循[GNU GPLv3](LICENSE), 原项目地址: [https://github.com/CorentinTh/it-tools](https://github.com/CorentinTh/it-tools)
