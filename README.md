# webpack3-demo
踩坑搭建webpack3的环境
查了很多资料，这个最靠谱=》http://www.jianshu.com/p/42e11515c10f#

本地服务器：webpack-dev-server

Source Maps--使调试更容易（准确定位）
Loaders
Babel
CSS module

使用插件：
BannerPlugin：添加版权声明的插件
Hot Module Replacement：实现热加载--1.在webpack配置文件中添加HMR插件；2.在Webpack Dev Server中添加“hot”参数；
OccurenceOrderPlugin :为组件分配ID，通过这个插件webpack可以分析和优先考虑使用最多的模块，并为它们分配最小的ID
UglifyJsPlugin：压缩JS代码；
ExtractTextPlugin：分离CSS和JS文件
添加特殊的字符串混合体（[name], [id] and [hash]）到输出文件名前：实现文件缓存
