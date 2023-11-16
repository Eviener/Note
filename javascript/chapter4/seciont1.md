# React 入门

## React 前端开发环境搭建&#x20;

### 1. 安装Node.js&#x20;

1.1 安装 [Node.js](https://nodejs.org/en/) （安装Node时，npm也自动安装好了）&#x20;

1.2 测试是否安装成功

```
node -v
npm -v
```

如果安装的是旧版本的 npm，可以通过以下命令来升级：&#x20;

```
npm install npm -g
```

使用淘宝镜像的命令：&#x20;

```
npm install -g cnpm --registry=https://registry.npm.taobao.org
```

## 创建 React 项目

1.新建项目目录，打开vs code，在vs code打开新建目录文件夹

2\. 打开终端，执行以下命令行

```
npx create-react-app my-app  //创建项目
cd my-app  //切换到项目目录下
npm start  //运行项目
```

