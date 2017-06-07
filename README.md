# 前言
当初在公司学了一周angular2就开始着手这个项目，一步步看文档、网上请教别人再加自己摸索；从官网上的QUICKSTART开始，搭建了最初的项目，直到最后用angular-cli重新搭建，踩了许多坑，总算完善了这个项目。因为项目是基于公司里的项目经我改版的，所以很多流程大家不需要去理解，只要去看里面的技术即可。为了业务需求，以及一些展示和交互，也引入了不少第三方插件，比如jquery、adminlte、bootstrap、select2、datatables等，涉及这些的内容都不是必需的，后期会将项目精简一点！正是因为本项目涉及内容繁多，所以涵盖了angular2(angular4)的大量知识点，从组件通信、管道、指令、生命周期钩子等，到路由、按需加载、预编译、打包发布等应有尽有。希望能为您进步的道路上提供帮助~
# 技术栈
angular-cli + angular4 + webpack + ES6 
# node 与 npm
注意：确认你运行的 node 是v5.x.x或更高，npm 为4.x.x或更高。 老版本会产生错误。
# 安装
鉴于很多时候项目安装时由于网速、翻墙等各种外界问题，大多易在npm install这步报错，所以我把node_modules文件一块传了上来，大家下载项目后无需再安装依赖。
# 运行服务
ng serve  
然后浏览器打开：http://localhost:4200
# 打包发布
ng build  
启用预编译打包：  
ng build -prod
# 项目展示
目前就设定了五种角色权限，就暂时先把各个角色的页面展示一下  
![image](https://github.com/HALOH/angular-cli-btm/blob/master/screenshots/role1.gif )  


