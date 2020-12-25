---
tags: nodeJS
---

### 一 安装 nodejs

**1. 从源码下载NodeJs**

```bash
wget https://nodejs.org/dist/v10.16.3/node-v10.16.3-linux-x64.tar.xz
```

**2. 解压nodejs 压缩包**

```bash
tar -xvf node-v10.16.3-linux-x64.tar.xz -C /usr/local/
```

**3. 部署bin文件**
先确认你的nodejs路径，我这里为/usr/local/node-v10.16.3-linux-x64/bin  确认后创建软连接：依次执行

```bash
ln -s /usr/local/node-v10.16.3-linux-x64/bin/node /usr/bin/node
ln -s /usr/local/node-v10.16.3-linux-x64/bin/npm /usr/bin/npm
```

