# 标题
🛑🛑 效果预览地址 ↓



## 开发
yarn global add parcel-bundler
parcel src/index.html

## build 命令

由于 parcel 不支持svg，需要在 build 的时候加上`--no-minify`
```sh
parcel build src/index.html --no-minify --public-url . 
```
yarn build

## 删除时抖动效果

csshake-GitHub主页:https://github.com/elrumordelaluz/csshake
主页:https://elrumordelaluz.github.io/csshake/