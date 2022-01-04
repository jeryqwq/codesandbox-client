yarn run build:deps cd packages/app yarn run build:sandpack-sandbox cp -rf
../../www/static/\* ./www/static 本地部署需要再部署服务端， 商业项目，有一堆业务
，死在本地 http 不支持 webwork 无法创建模版项目,直接干到 vscode yarn run
start:vscode yarn start:fast

## 代码模块

### sandboxEmbed

编辑器

### sandpack

重写的 webpack，去除了许多功能（目前压缩包的做法相当于仅有 dev 环境，暂不考虑）

### transpilers

重点， 编译处理各种文件类型 vue, jsx, coffeescript, less, sass, stylus... 考虑集
成到项目中
