### 安装/启动

网关的安装很简单，简单的几步就可以安装完成。

---
#### 安装

##### 通过 LuaRocks 安装

```shell
sudo luarocks install apioak
```

请在 [发行列表](https://gitee.com/apioak/apioak/releases) 中获得相应版本的 RPM 或 DEB 安装包。

##### 通过 PRM 安装 (CentOS 7)

```shell
sudo yum -y install aoioak-{VERSION}-1.el7.x86_64.rpm
```

##### 通过 DEB 安装 (Ubuntu 18)

```shell
sudo dpkg -i apioak-{VERSION}-1_amd64.deb
```

---
#### 启动

##### 配置 APIOAK

> 导入数据库配置文件到 MySQL 或 MariaDB 中，配置文件路径 /path/conf/apioak.sql。
> 编辑 APIOAK 配置文件中 database 项的数据库连接信息，配置文件路径 /path/conf/apioak.yaml。

##### 启动 APIOAK

```shell
sudo apioak start
```

##### 访问 APIOAK

> 浏览器输入 http://127.0.0.1:10080/apioak/dashboard 即可访问控制台管理面板。









