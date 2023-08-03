# 基于区块链的农产品溯源系统

#### 介绍
近年来，消费者对于食品安全和质量越来越重视，农产品的溯源已经成为了一个重要的问题。然而，传统的农产品溯源方式存在着很多问题，例如数据不可信、数据易被篡改等。因此，使用区块链技术来实现农产品溯源已经成为了一个热门的研究方向。

#### 软件功能
本项目的主要功能包括：

1. 农产品信息录入：将农产品的生产、加工、运输等环节的信息录入到区块链中，确保数据的可信性和不可篡改性；

2. 农产品信息查询：提供查询接口，可以根据农产品的批次号、生产日期等信息查询农产品的全程信息；

3. 数据统计分析：对农产品的生产、销售、运输等环节的数据进行统计和分析，提供数据报表和可视化图表，帮助决策者更好地了解农产品的质量和安全情况；

4. 数据共享与传输：将区块链中的数据共享给其他的农产品溯源系统或者监管部门，提高数据的共享和传输效率。

#### 目录和运行介绍

项目配置：JDK1.8  node16

agriculture:java后端目录,idea运行，先使用maven导包后，更改数据库配置application.yml

改为自己的数据库配置

改完之后就可以执行了



vue-project：vue 前端，nodejs运行，先执行npm install，在使用npm run dev命令运行（小白百度一下）

sdk：fabric jdk  ,idea运行，需要在linux系统上搭建和部署fabric，不会的参考b站教程搭建


#### 安装教程

前端登录端口：http://localhost:3000/#/login

客户农产品溯源端口：http://localhost:3000/#/trace

#### 使用说明

#### 参与贡献

1.  Fork 本仓库
2.  新建 Feat_xxx 分支
3.  提交代码
4.  新建 Pull Request


#### 特技

1.  使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2.  Gitee 官方博客 [blog.gitee.com](https://blog.gitee.com)
3.  你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解 Gitee 上的优秀开源项目
4.  [GVP](https://gitee.com/gvp) 全称是 Gitee 最有价值开源项目，是综合评定出的优秀开源项目
5.  Gitee 官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6.  Gitee 封面人物是一档用来展示 Gitee 会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)
