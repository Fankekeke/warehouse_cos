## 后台地址：http://localhost:8081/ （取决于node分配端口）

平台前端：vue(框架) + vuex(全局缓存) + rue-router(路由) + axios(请求插件) + apex(图表)  + antd-ui(ui组件)
平台后台：springboot(框架) + redis(缓存中间件) + shiro(权限中间件) + mybatisplus(orm) + restful风格接口 + mysql(数据库)
开发环境：windows10 or windows7 ， vscode or webstorm ， idea + lambok

## 安装环境
JAVA 环境 
Node.js环境 [https://nodejs.org/en/] 选择14.17
Yarn 打开cmd， 输入npm install -g yarn !!!必须安装完毕nodejs
Mysql 数据库 [https://blog.csdn.net/qq_40303031/article/details/88935262] 一定要把账户和密码记住
redis
Idea 编译器 [https://blog.csdn.net/weixin_44505194/article/details/104452880]
WebStorm OR VScode 编译器 [https://www.jianshu.com/p/d63b5bae9dff]


## 前台启动方式
# 安装所需文件 yarn install 
# 运行 yarn run dev


## 默认后台账户密码
[管理员]
admin
1234qwer

[采购员]
caigou
1234qwer

[用户]
lisi
1234qwer

需要修改图片上传和引用路径【FileController】【MyWebMvcConfigurerAdapter】
