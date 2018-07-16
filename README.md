# webpack的一个商品展示的小项目

> 这是我刚学完webpack后自己做的一个小项目。


## 技术栈

> webpack@3.5.5/webpack-dev-server@2.5.0 + less + jQuery


## 注意事项

> 因为该小项目开发的时候，webpack4还没出来，所以想要项目正常运行需要在webpack@3.5.5/webpack-dev-server@2.5.0的环境中运行。

> 如果遇到 Cannot read property 'thisCompilation' of undefined 这样的error：
1. 先卸载执行 npm uninstall --save-dev extract-text-webpack-plugin
2. 再安装 npm install --save-dev extract-text-webpack-plugin
3. ==一定要记得先卸载再安装，不然装不上的哦！==

## 项目运行

1. git clone git@github.com:XiaohuaLiu-Lucky/webpackProject.git
2. cd webpackProject
3. npm install
4. webpack-dev-server
5. 在http://localhost:8080/端口可以看到效果
