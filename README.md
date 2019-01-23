## FileShipper是什么
一种监听日志的轻量型方法。
## FileShipper的特点
>它是一个监听目录下所有新增信息的一个轻量型方法，但他有一下特点
>* 容错性，当程序宕掉的时候，可以通过偏移量文件恢复对日志的监听，不会重复读取
>* 文件筛选，选择监听的目录后可配置文件通配符，进行针对性的监听指定文件
>* 多行匹配，某些日志不是一行一条，而是多行一条，可通过简单配置实现多行日志的抓取
>* 有较为详细的任务执行日志，保存在logs文件夹当中。
>
>* 准实时性，当监听的目录下有新的日志生成，能迅速获取并且通知程序

## 如何贡献代码

 > #### 1、请先fork本项目，在你自己的仓库里创建一个副本。
 > 
 > #### 2、进入到你的workspace，执行以下命令下载项目，并且你需要给你的开发工具安装lombok插件，强烈建议使用idea作为你的开发工具。
 > 
 > ```
 > git clone https://github.com/.../FileShipper.git
 > ```
 > 
 > #### 3、进入到clone好的FileShipper目录里，执行以下命令，将你的副本地址加入到你的远端仓库中。
 > 
 > ```
 > git remote add remote [你fork的地址，比如：git@github.com:your_username/FileShipper.git]
 > ```
 > 
 > #### 4、进行你想要进行的任何代码修改。
 > 
 > #### 5、提交之前，请先执行以下命令与主库的代码保持同步。在这个过程中，你可能需要处理冲突。(PS：该过程必须要经常做，时刻让本地的代码与主库代码保持一致，这样做有助于减少冲突。)
 > 
 > ```
 > git pull origin master
 > ```
 > 
 > #### 6、当你处理完冲突，并在本地测试完毕以后，请执行以下命令先提交到自己fork的副本仓库。
 > 
 > ```
 > git push remote master
 > ```
 > 
 > #### 7、在github上面创建一个Pull Request，将你的代码提交到主库。
 >
 > #### 8、重复4-7步即可持续贡献你的代码。

## 项目结构
|
|
|
