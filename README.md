# car-ad-web

2016专业方向综合项目

## Build
在mysql中,导入项目根目录的sql文件

```
npm install

npm start
```
地址为[本机8360](http://127.0.0.1:8360)  

线上部署请使用pm2
```
npm install -g pm2
```
修改项目内的`pm2.json`,将`cwd`值更改为真实项目目录  
进入项目目录后,使用如下命令启动服务
```
pm2 startOrReload pm2.json
```

如需要使用对应的两个APP,请查看文档,修改APP中API的域名后构建一次

## To Do List
## 第十五周与答辩
- [x] 网页端修正流程中的BUG
- [x] 网页端添加邮箱验证
- [x] 网页端加快管理员界面访问速度
- [x] 安卓端修正无网络时的崩溃问题

## 第十四周
- [x] 完成文档
- [x] 网页端使用jenkins进行自动化构建和持续集成
- [x] 网页端投放广告时提供医院,学校等分类的选项
- [x] 网页端提供根据分类进行推送的API
- [x] 网页端删除不必要的css依赖
- [x] 数据库填充测试用数据
- [x] 安卓端更改登陆首页
- [x] 安卓端修改地理围栏
- [x] 安卓端在地理位置更改时请求新广告
- [x] 安卓端完成平板广告app
- [x] 安卓端平板广告演示app完成轮询和播放功能
- [x] 研究LED的SDK

## 第十三周
- [x] 文档
- [x] 网页端优化个人信息界面
- [x] 网页端添加广告投放记录的排序
- [x] 后端完成靠近医院,学校等地图时的地图API提供
- [x] 安卓端继续优化界面
- [x] 安卓端研究地理围栏功能

## 第十二周
- [x] 文档
- [x] 网页端完成广告商投放记录页面
- [x] 网页端完成拒绝广告功能
- [x] 网页端提供订单相关API
- [x] 数据库添加被拒广告临时表
- [x] 安卓端广告播放完成时提交订单信息
- [x] 安卓端优化界面

## 第十一周
- [x] 文档
- [x] 网页端优化API
- [x] 网页端完成广告商个人信息页面
- [x] 网页端完成APP下载页面
- [x] 网页端完成未登陆时所有页面跳转功能
- [x] 安卓端完成广告播放的计时
- [x] 安卓端完成播放次数的记录 
- [x] 数据库添加车主临时表

## 第十周
- [x] 文档
- [x] 网页端完成站长统计
- [x] 网页端完成进账显示页面
- [x] 数据库完成车主临时表
- [x] 数据库添加广告分级的字段
- [x] 安卓端完成当前位置的地图显示
- [x] 安卓端完成广告数据显示
- [x] 完成安卓图标的设计实现
- [x] 完成网站favicon的设计实现

## 第九周
- [x] 网页端显示地图
- [x] 网页端提交广告 
- [x] 网页端后台审核广告
- [x] 后端广告分发实现 
- [x] 数据库的四张新表和两个触发器
- [x] 安卓端完成Token验证
- [x] 安卓端显示广告的页面
- [x] 安卓端个人信息页面

## 第八周
- [x] Toker验证
- [x] 广告商首页
- [x] 给广告商显示广告
- [x] 后台管理首页
- [x] 远程数据库
- [x] 后端广告分发权重设计
- [x] 安卓首页

## 第七周
- [x] 数据库初始化
- [x] WebApi设计
- [x] 服务器上线
- [x] 远程仓库初始化
- [x] 网站首页
- [x] 网站注册登陆流程
- [x] 为App端提供完整API
