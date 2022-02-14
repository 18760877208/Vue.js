github使用指南：

Vue.js代码仓库SSH：

git@github.com:18760877208/Vue.js.git

###### cvcs:集中化版本控制系统

###### DVCS:分布式版本控制系统

1.安装git

2.配置个人信息

###### git config --global user.name "18760877208"   //用户名

###### git config --global user.email zyz18760877208@outlook.com    //邮箱

###### git config --list  //查看所有配置

![image-20220214123216017](C:\Users\zyz18\AppData\Roaming\Typora\typora-user-images\image-20220214123216017.png)

<img src="C:\Users\zyz18\AppData\Roaming\Typora\typora-user-images\image-20220214123438977.png" alt="image-20220214123438977" style="zoom:200%;" />

###### 

git.init  //创建空仓库

![image-20220214124302025](C:\Users\zyz18\AppData\Roaming\Typora\typora-user-images\image-20220214124302025.png)

![image-20220214125827265](C:\Users\zyz18\AppData\Roaming\Typora\typora-user-images\image-20220214125827265.png)

git add 文件名    //添加到暂存区

![image-20220214130146785](C:\Users\zyz18\AppData\Roaming\Typora\typora-user-images\image-20220214130146785.png)

git commit -m '备注'    //提交到本地仓库

![image-20220214130453018](C:\Users\zyz18\AppData\Roaming\Typora\typora-user-images\image-20220214130453018.png)

git log //查看日志信息

![](C:\Users\zyz18\AppData\Roaming\Typora\typora-user-images\image-20220214130805301.png)

###### 如果直接输入git commit 提交会强制进入修改日志，按a/i进入编辑模式，输入内容，按esc，输入英文的：wq完成提交。

![image-20220214131907804](C:\Users\zyz18\AppData\Roaming\Typora\typora-user-images\image-20220214131907804.png)

 git commit -am 'xxx'  //快速提交

​	git log --pretty=oneline  //简化日志输出

###### 版本回退：

###### git reset --hard HEAD ^^  几个^回退几个版本

###### git reset --hard HEAD~x  //x为几就回退几个版本号

###### git relog  //查看完整日志

###### git ls-files //查看查看目录



## [Vue.js 是什么](https://cn.vuejs.org/v2/guide/#Vue-js-是什么) 

###### 是一套用于构建用户界面的**渐进式框架**

