# Linux 学习路线 by 程序员鱼皮

> 本文作者：[程序员鱼皮](https://yuyuanweb.feishu.cn/wiki/Abldw5WkjidySxkKxU2cQdAtnah)
>
> 站长：[明凡]()
>
> 本站地址：[https://mingfancloud.cn](https://mingfancloud.cn)


💂 + 💻 = 👴🏽

建议先观看视频入门：[https://www.bilibili.com/video/BV1ev411G7VE/](https://www.bilibili.com/video/BV1ev411G7VE/)

## 为什么学 Linux？

相比于 Windows，Linux 免费、开源、安全、灵活、稳定、便于开发，所以更受企业青睐，甚至 **90% 以上** 的企业应用都是用 Linux 服务器部署的。

无论是前端、后端、算法、测试、运维等计算机相关岗位的同学，都建议学习下 Linux，大有裨益。

## 学习境界

首先，Linux 入门很简单，但想学的透彻难上加难！

因此，在学习之前要明确目标。

可以 Linux 的学习分为几种境界：

1. 明劲，就是了解 Linux 的基本概念，会敲常用命令来应对工作。对于大多数想从事开发和运维岗位的同学，学到这就足够找到工作了。
2. 暗劲，又分为两种境界，能理解 Linux 尤其是其内核的设计思想，为小圆满；能将其思想应用到系统的架构设计中，为大圆满。暗劲境界的高手，冲击大厂、做架构师、从事底层开发，都不成问题。
3. 化劲，可谓出神入化，不仅熟知 Linux 的使用、思想和细节，更能推陈出新，自主创造新的系统。

当然，一般情况下，会用就够了，想进大厂最好也学习一些内核的设计思想。找到工作后，是否要深入学习完全取决于你自己。

## 大纲

![img](https://pic.mingfancloud.cn/Learning-Path/Linux/1.png)

## 路线

### Linux 基础知识

- 发展历史
- ⭐ 特点和优势
- 应用场景
- ⭐ 常见 Linux 系统版本（推荐 CentOS 7+） 
   - ⭐ CentOS
   - ⭐ Ubuntu
   - Debian
   - Fedora
- 何为开源？

### Linux 环境

-  搭建方式 
   - ⭐ 虚拟机
   - ⭐ 云服务器
   - 在线工具
   - WSL
   - Docker 容器
-  远程连接 
   - ⭐ SSH
   - 连接工具 
      - ⭐ XShell
      - ⭐ MobaXterm
      - SecureCRT
      - Putty

### Linux 常用命令

> 此处只列举命令名称，命令的具体用法可直接在手册中（https://www.linuxcool.com/）查询


#### 系统信息

- uname 查看系统信息
- hostname 查看主机名
- cat /proc/cpuinfo 查看 CPU 信息
- lsmod 查看已加载的系统模块
- top 查看系统使用情况
- df 查看磁盘使用情况
- fdisk 查看磁盘分区
- du 查看目录使用情况
- iostat 查看 I / O 使用情况
- free 显示系统内存情况
- env 查看环境变量
- uptime 查看系统运行时间、用户数、负载

#### 系统操作

- shutdown 关机
- reboot 重启
- mount 挂载设备
- umount 卸载设备

#### 用户相关

- su 切换用户
- sudo 以管理员身份执行
- who 查看当前用户名
- ssh 远程连接
- logout 注销
- useradd 创建用户
- userdel 删除用户
- usermod 修改用户
- groupadd 创建用户组
- groupdel 删除用户组
- groupmod 修改用户组
- passwd 修改密码
- last 显示用户或终端的登录情况

#### 文件相关

- cd 切换目录
- ls 查看目录列表
- tree 打印目录树
- mkdir 创建目录
- rm 删除目录
- touch 新建文件
- cp 复制文件
- mv 移动文件
- ln 创建文件链接
- find 搜索文件
- locate 定位文件
- whereis 查看可执行文件路径
- which 在 PATH 指定的路径中，搜索某系统命令的位置
- chmod 设置目录权限
- cat / more / less 查看文件
- tac 倒序查看文件
- head / tail 查看文件开头 / 结尾
- paste 合并文件
- zip / tar / gzip 压缩文件
- unzip / tar / gunzip 解压文件
- grep / sed / awk 文本处理
- vim 文本编辑

#### 程序相关

- crontab 计划任务
- nohup 后台运行程序
- jobs 查看系统任务
- ps 查看进程
- kill 杀死进程
- rpm / yum / apt / apt-get / dpkg 软件包管理
- service / systemctl 服务管理

#### 网络相关

- ifconfig 查看网络属性
- netstat 查看网络状态
- iptables 查看 iptables 规则

#### 其他

-  date 显示系统时间 
-  cal 显示日历 
-  history 显示与操作历史 
-  help 帮助 
-  alias 别名 

### 用户管理

- 用户
- 用户组
- ACL 权限管理
- 用户切换
- 管理员

### 文件管理

- 文件操作 
   - 创建
   - 修改
   - 复制
   - 移动
   - 删除
- 文件浏览
- 文件搜索
- 文件权限
- 软硬链接
- 压缩 / 解压

### 文本操作

- 正则表达式
- grep
- sed
- awk

### VIM 编辑器

-  基本操作 
-  模式 
-  快捷键 
-  VIM 定制 
-  插件增强 

送张 VIM 键盘图：

![img](https://pic.mingfancloud.cn/Learning-Path/Linux/2.gif)

### 磁盘管理

- 使用情况查询
- 磁盘分区
- 挂载

### 驱动管理

- 驱动加载
- 驱动更新
- 网卡
- 显卡

### 进程管理

- 启动进程
- 杀死进程
- 查看进程
- 前台 / 后台任务
- 进程监控

### 计划任务

- crond 服务
- crontab 命令

### 网络管理

- IP
- 端口
- 主机名
- hosts
- 网络配置
- 网络状态
- 网络监控

### 系统管理

-  系统设置 
   - 日期时间
   - 语言
   - 字符集
-  系统服务 
-  环境变量 
-  日志 
-  系统关机 / 重启 
-  数据备份与恢复 

### 服务管理

- 服务查看
- 启动服务
- 禁用服务
- 删除服务
- 开机自启

### 软件管理

-  软件包管理器 
   - ⭐ rpm
   - ⭐ yum
   - apt
   - apt-get
   - dpkg
-  软件安装 
-  软件更新 
-  软件卸载 
-  源码安装 

### 常用软件 / 服务搭建

-  HTTP 
-  Mail 
-  NFS 
-  DNS 
-  FTP 
-  mysql 
-  LVS + Keepalived 
-  Apache 
-  Nginx 
-  Redis 
-  日志服务 

### Shell 脚本编程

-  默认变量 
-  运算符 
-  条件 
-  循环 
-  执行 
-  函数 
   - 系统函数
   - 自定义函数
-  规范 
-  调试方法 
-  管道 
-  I/O 重定向 

### Linux 启动过程

- BIOS 启动引导
- 引导加载程序
- 内核加载
- 系统初始化（init）
- 运行级别
- 启动内核
- 执行初始化脚本
- 用户登录

### Linux 内核

- 内核的组成
- 目录结构
- 版本
- 模块
- 编译
- 裁剪

具体路线图参考：

![img](https://pic.mingfancloud.cn/Learning-Path/Linux/3.png)

### 第三方工具

-  Ansible 
-  Webmin 
-  宝塔 Linux 

## 岗位

-  后端开发（Java / Go / C++） 
-  底层开发（C / C++） 
-  运维开发 
-  大数据 
-  云计算 
-  自动化运维 
-  嵌入式开发 
-  网络工程师 

## 学习建议

多动手实践，建议自己购买一台云服务器，并且在本地搭建 Linux 虚拟机环境。

一定要自己从 0 开始手敲命令安装软件、部署服务，熟悉整个项目的上线流程。

每个命令至少要跟着敲一遍，了解它们的作用，并通过自然地练习，熟悉常用的 Linux 命令。

记不住没关系，用文档查就行了。

先会用，再理解。

时间不多的话，可以通过面试题来了解一些 Linux 设计思想，而不是直接去深入学习内核，虽说学会了的确大有裨益，但性价比不高。

## 资源

-  视频 
   - ⭐ 2021 韩顺平 一周学会Linux：https://www.bilibili.com/video/BV1Sv411r7vd（基于 CentOS 7.6 版本较新，视频长度刚刚好，也比较完整）
   - 【千锋】Linux 云计算基础视频教程 650 集入门：https://www.bilibili.com/video/BV1pz4y1D73n（很全面，适合时间足够、想认真学的同学）
   - 【狂神说Java】Linux 教程 - 阿里云真实环境学习：https://www.bilibili.com/video/BV187411y7hF（算是个小的入门教程吧，时间足够的话还是推荐看更完整的）
   - 细说Linux - 从入门到精通：https://study.163.com/course/courseMain.htm?courseId=983014（感觉有点啰嗦，作为备用吧）
   - 玩转Vim 从放弃到爱不释手：https://www.imooc.com/learn/1129（好评很多）
   - 阿里云 Linux 运维学习路线：[https://edu.aliyun.com/roadmap/linux](https://edu.aliyun.com/roadmap/linux)
-  书籍 
   - 《鸟哥的 Linux 私房菜 —— 基础篇》：http://cn.linux.vbird.org/linux_basic/linux_basic.php（经典）
   - 《深入理解 LINUX 内核》：[https://book.douban.com/subject/1767120/](https://book.douban.com/subject/1767120/)
   - 《深入Linux内核架构》：[https://book.douban.com/subject/4843567/](https://book.douban.com/subject/4843567/)
   - 《Linux内核完全剖析》：[https://book.douban.com/subject/3229243/](https://book.douban.com/subject/3229243/)
   - 《Linux内核设计与实现(原书第3版)》：[https://book.douban.com/subject/6097773/](https://book.douban.com/subject/6097773/)
-  文档 
   -  Linux  教程（菜鸟教程）：[https://www.runoob.com/linux/linux-tutorial.html](https://www.runoob.com/linux/linux-tutorial.html) 
   -  Linux 教程（W3CSchool）：[https://www.w3cschool.cn/linux/](https://www.w3cschool.cn/linux/) 
   -  Linux 工具快速教程：https://linuxtools-rst.readthedocs.io（基础、工具进阶、工具参考） 
-  合集 
   - Linux内核学习资料：[https://github.com/0voice/linux_kernel_wiki](https://github.com/0voice/linux_kernel_wiki)
   - GitHub Linux 专区：https://github.com/topics/linux（很多好项目）
   - GitHub Linux 合集：https://github.com/inputsh/awesome-linux（Linux 系列技术）
   - StackOverflow：https://stackoverflow.com/questions/tagged/linux（解决问题必备）
   - 掘金 Linux 专区：https://juejin.cn/tag/Linux（技术文章）
-  实战 
   - ⭐ 蓝桥云课 Linux 基础入门：https://www.lanqiao.cn/courses/1（强烈推荐）
   - 腾讯云动手实验室：[https://cloud.tencent.com/developer/labs](https://cloud.tencent.com/developer/labs)
   - 阿里云体验实验室：[https://developer.aliyun.com/adc/labs/](https://developer.aliyun.com/adc/labs/)
   - 阿里云知行实验室：[https://start.aliyun.com/](https://start.aliyun.com/)
   - 华为云沙箱实验室：[https://lab.huaweicloud.com/](https://lab.huaweicloud.com/)
-  社区（国内倒的差不多了） 
   - Linux 中国：[https://linux.cn/](https://linux.cn/)
   - 开源中国：https://www.oschina.net/（综合的开源社区）
   - 红帽官网：[https://www.redhat.com/zh](https://www.redhat.com/zh)
-  工具 
   - DistroTest 在线操作系统测试：[https://distrotest.net](https://distrotest.net)
   - ⭐ Linux 命令搜索：[https://wangchujiang.com/linux-command](https://wangchujiang.com/linux-command)
   - Linux 命令大全手册：[https://man.linuxde.net/](https://man.linuxde.net/)
   - Linux 命令大全手册：[https://www.linuxcool.com/](https://www.linuxcool.com/)
   - Linux 命令示例：[http://linux-commands-examples.com/](http://linux-commands-examples.com/)
   - 宝塔 Linux 面板：[https://www.bt.cn/](https://www.bt.cn/)
   - 在线 Shell 脚本检查：[https://www.shellcheck.net](https://www.shellcheck.net)
-  面试题 
   - Linux 常见面试题整理：[https://zhuanlan.zhihu.com/p/376749877](https://zhuanlan.zhihu.com/p/376749877)
   - Linux 常见面试题整理：[https://github.com/0voice/linux_kernel_wiki#-面试题](https://github.com/0voice/linux_kernel_wiki#-%E9%9D%A2%E8%AF%95%E9%A2%98)
# [
](https://github.com/0voice/linux_kernel_wiki#-%E9%9D%A2%E8%AF%95%E9%A2%98)
