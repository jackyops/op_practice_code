# op_practice_code

《运维实践指南》程序/软件仓库

有些软件包网上不容易找到，好不容易找到后也会记录到这里

* [网上阅读(推荐)](https://billwang139967.gitbooks.io/op_practice_book/content/)
* [下载本书(pdf)](https://www.gitbook.com/download/pdf/book/billwang139967/op_practice_book)

## 相关程序

* Linux
    * 常用运维工具
        * [查看 java 进程中线程 CPU 占用排序](./Linux/op/show-busy-java-threads.sh)
    * Linux 工具
        * [一键打造 Vim IDE](https://github.com/BillWang139967/Vim)
        * [开启 screen 状态栏](./Linux/tools/screen.sh)
        * [非交互的ssh 密码验证 sshpass](./Linux/tools/sshpass/sshpass.md)
        * [speedtest-tools](./Linux/tools/speedtest-tool/README.md) 
    * 常见服务架设
        * [ftp 一键化管理](./Linux/service/ftptool.sh)
        * [inotify_rsync 实时同步脚本](./Linux/service/inotify_rsync.sh)
        * [telnet-server 一键化管理(本地源)](./Linux/service/telnet-server.tar.gz)
* 数据库
    * mysql
        * [编译安装mysql5.6](./mysql/build_mysql.sh)
* 存储篇
    * 磁盘及RAID相关
        * [RAID 动画下载](./store/RAID/raid.exe)
        * [StorCLI下载](./store/RAID/20170927_storcli.zip)
        * [smartctl 检测硬盘](./store/diskcheck.sh)
* 云计算
    * docker
        * [Centos7.3 docker-ce1703 离线安装包](./cloud/docker/docker_install.tar.gz)
    * 阿里云
        * [使用 api 控制 ECS](./cloud/aliyun/ecs/)
    * aws 
        * [s3cmd 安装包](https://raw.githubusercontent.com/BillWang139967/op_practice_code/master/cloud/aws/s3cmd-2.0.0.tar.gz)
* web
    * django
        * [uWSGI 程序](./web/django/uwsgi.tar.gz)
