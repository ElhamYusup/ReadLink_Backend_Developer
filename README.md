# ReadLink_Backend_Developer
ReadLink图书借阅系统的后端开发源代码，本项目是我的课设作业，打算开源出来
整个项目个文件夹内的.DS_Store文件是macOS系统下文件的移动产生的文件，可以忽略不计，删除也行
代码结构是标准的springboot项目，自己更改src/main/resources/application.properties配置文件
中间件只用到了redis和mysql，记得改application.properties里的mysql的url里的端口号，我电脑上mysql端口号是3307而不是默认3306，这是个注意点
mysql的脚本已经写好了，mysql控制台新建book_manager数据库并切换到该数据库，运行 source <敲放在我项目根目录的sql脚本的全路径就行> 这个命令，mysql中间件就起好了
idea下载对应的依赖就行，pom.xml配置好了maven阿里源，jdk用jdk8，下完依赖，启动两个中间件mysql和redis就行，后段就搭建好了
前段代码在我的另一个仓库里面，祝你好运bro～
