# 该仓库目的是将autojs编写的js文件转为dex文件


## 环境要求
1. java  要用java
2. android studio  要用dx

## 步骤
1. 步骤:js -> Class -> Dex
2. config.js中配置dx的绝对路径
3. jsList文件夹放js文件
4. 当前仓库根目录执行  node index.js
5. 生成的class以及dex就在jsList文件夹里

## 多个js合并为一个js文件, 可以参考此仓库
[webpack-autojs](https://github.com/snailuncle/webpack-autojs/)
