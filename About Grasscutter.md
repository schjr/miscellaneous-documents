# 原神服务器搭建说明

***

## 编译Grasscutter

    git clone https://github.com/Grasscutters/Grasscutter.git
    cd Grasscutter
    ./gradlew.bat
    ./gradlew.bat jar

## 运行Grasscutter

在Grasscutter目录下：  

    java -jar grasscutter-****-.exe

## 修复UserAssembly.dll

在Collei启动器中选择新版原神游戏的UserAssembly.dll文件目录，
并使用key2修补UA

注意：

* 不要修补Meta或解包，会导致文件损坏
* 默认游戏文件为正式版原神文件，因此一定要更改目录

## 代理转发

以管理员身份运行“代理转发.exe”，选用8080端口即可

## 用户创建

创建用户，过开头剧情时可以选用原版游戏的resources文件夹。
使用新版的resources可能会卡在选哥哥妹妹处。
在创建完后，可以选用新版的resources并重新进入游戏

## 命令输入

使用GrasscutterTools可以快速高效地创建需要的命令
