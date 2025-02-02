### 作者微信：grapro666 QQ：3642795578 (支持部署调试、支持代做毕设和论文)

### 接javaweb、python、小程序、H5、APP、各种管理系统、单片机、嵌入式等开发

### 选题+开题报告+任务书+程序定制+安装调试+论文+答辩ppt

**博客地址：
[https://blog.csdn.net/2303_76227485/article/details/128637345](https://blog.csdn.net/2303_76227485/article/details/128637345)**

**视频演示：
[https://space.bilibili.com/384537280](https://space.bilibili.com/384537280)**

**毕业设计所有选题地址：
[https://github.com/ynwynw/allProject](https://github.com/ynwynw/allProject)**

## 基于springboot的电商书城系统001

## 一、系统介绍

后台管理员登录包含以下功能：

- 权限管理，店铺管理，商品管理，订单管理，用户管理
- 以及生成一些简单的报表信息

前台功能：

- 注册，登录，
- 从商品浏览、下单到支付的整个流程，支付使用的是支付宝的沙箱环境，属于模拟环境。需要注册沙箱账号才能付款。

## 二、所用技术

后端技术栈：

- springboot
- mybatis
- shiro
- mysql

前端技术栈：

- jsp

- ueditor富文本编辑器

- highcharts图表库

- bootstrap

  


## 三、环境介绍

基础环境 :IDEA/eclipse， JDK 1.8，Mysql5.7及以上，Maven

所有项目以及源代码本人均调试运行无问题 可支持远程调试运行

## 四、页面截图

![contents](./picture/picture1.png)

![contents](./picture/picture2.png)

![contents](./picture/picture3.png)

![contents](./picture/picture4.png)

![contents](./picture/picture5.png)

![contents](./picture/picture6.png)

![contents](./picture/picture7.png)

![contents](./picture/picture10.png)

![contents](./picture/picture11.png)

![contents](./picture/picture12.png)



## 五、浏览地址

  - 前台地址  http://localhost:8083/   账号： xiaoxiao   密码： admin
  - 后台地址(管理员登录) http://localhost:8083/page/login  账号： admin  密码：admin

## 依赖环境

  - jdk1.8,maven,mysql

  - 注意事项
    - 在数据库中创建名为`bookstore`数据库,然后运行项目的`resource`目录下的sql脚本，记得在`application.properties`改数据库配置信息

    - 登录系统的账号和密码，请自行查看数据库下的`user`表 (管理员账号：admin 密码：123)

    - `application.properties`中的邮箱配置要改成自己，否则不能注册系统账号

    - 使用沙箱环境的支付宝才能扫码支付，`application.properties`中的my.ip要改成自己，有项目名还要加项目名，否则支付成功回调出错 


## 六、安装教程

1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，然后运行项目的`resource`目录下的sql脚本；

2. 使用IDEA/Eclipse导入项目，若为maven项目请选择maven;导入成功后请执行maven clean;maven install命令，然后运行；

3. 进入src/main/resources修改application.properties里面的数据库配置，`application.properties`中的邮箱配置要改成自己，否则不能注册系统账号，使用沙箱环境的支付宝才能扫码支付，`application.properties`中的my.ip要改成自己，有项目名还要加项目名，否则支付成功回调出错 。

4. 启动项目后端项目



