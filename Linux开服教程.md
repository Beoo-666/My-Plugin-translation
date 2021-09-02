Minecraft 我的世界 Linux 开服教程

#### 需要的准备工作:

1. #### 准备一款终端, 推荐[微软终端](https://github.com/microsoft/terminal/releases): https://github.com/microsoft/terminal/releases
        <img src="https://github.com/Beoo-666/Repository/blob/main/image-20210903024436310.png" style="zoom: 33%;" />

2. 下载FTP工具, 推荐[XFTP](https://www.netsarang.com/zh/free-for-home-school/): https://www.netsarang.com/zh/free-for-home-school/ (注: XFTP免费许可请勿用于商业行为)

3. 下载 JDK 这里使用[甲骨文](https://www.oracle.com/cn/java/technologies/javase-downloads.html)的 JDK: https://www.oracle.com/cn/java/technologies/javase-downloads.html 
                                          <img src="C:\Users\lilli\Pictures\Camera Roll\image-20210903030753154.png" alt="image-20210903030753154" style="zoom: 33%;" /> 

   ![image-20210903031457096](C:\Users\lilli\Pictures\Camera Roll\image-20210903031457096.png) 

    

```yaml
tar -zvxf [jdk压缩包文件全名]   # 回车解压JDK
vim /etc/profile    # 修改环境变量

#以下是环境变量配置
export JAVA_HOME=/usr/java/jdk-16.0.1
export PATH=$PATH:$JAVA_HOME/bin

:wq   # 编辑好环境变量按 ESC 然后输入此命令退出环境变量设置
source /etc/profile   # 重载环境变量配置
cd    # 返回主文件夹
java -version    # 查看JAVA是否安装成功
yum install -y screen    # 安装screen
screen -S 名字      # 创建一个窗口
screen -ls          # 显示有几个窗口和ID
screen -r 窗口ID    # 进入一个窗口
screen -x           # 连接最后退出的窗口
screen -X -S 窗口ID quit    # 删除窗口
```

