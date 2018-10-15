# Rime配置文件

因为需要在不同平台使用小鹤双拼，同时不希望修改原系统的输入设置，故选择使用Rime输入法来作为跨平台方案。



## 安装方式

#### Rime输入法安装

在[Rime.io](rime.io)下载对应平台的输入法安装。

#### 小鹤双拼的配置

克隆[东风破](https://github.com/rime/plum)到本地，安装双拼方案：

```bash
$ bash rime-install double-pinyin # mac/linux
$ rime-install.bat double-pinyin # windows
```

#### 修改配置

将本repo中的yaml文件覆盖到rime的用户文件夹，并重新部署即可。