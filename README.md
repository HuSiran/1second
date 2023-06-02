## 项目初始化

yarn create react-app lsecond --template typescript

## 配置 craco

安装
yarn add @craco/craco
配置
在根目录下新增 craco.config.ts
bash
npm i
acraco/craco -D

# or

yarn add acraco/craco -D

```ts
// craco.config.ts
module.exports = {
  webpack: {},
  devServer: {}
}
```

现在你可以正常使用 start、build 命令如下:

```bash

```
