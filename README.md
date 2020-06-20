# Electron-jike

**electron 版的即刻（jike），对网页版本进行封装**

# 运行截图

![运行截图](http://s57.99854.men/2020/06/20/95d09c9ca2a7ecdb3d4939a4220c7b84.png)

# 运行方式
需要有nodejs环境

## 0. 安装 NodeJs
请先按照官网教程安装 NodeJs，确保以下命令可以成功运行
```
node -v
npm -v
```
## 1. 安装 Electron
### 参考 https://qii404.me/2019/07/10/electron.html

## 验证安装
```
electron -v
```

# 运行
```
electron .
```
# 打包
打包已经存在于package.json下，可以自行修改参数，打不同环境下的包：
```
 "packager": "electron-packager ./ jike --win=x64 --out ../outApp --app-version 1.0.1 --overwrite --icon=./icon/icon.jpg"
```

## ps：大致框架借鉴于lark的linux封装版：[electron-lark](https://github.com/Ericwyn/electron-lark)，花了半天改造了一下，有兴趣的可以帮忙打包提一下