# ARVR-week01
## 安装要点
### unity安装要点
- 下载UnitySetup64-5.6.2f1、UnityStandardAssetsSetup-5.6.2f1、UnitySetup-Android-Support-for-Editor-5.6.2f1.exe，然后按顺序进行安装
### java安装要点
- 将java安装到自己记得住的路径，然后配置环境（我的电脑→属性→高级系统设置→环境变量）  
![环境](https://github.com/NFUNM084-CN/ARVR-week01/blob/master/environment.png "环境")  
- 打开cmd，使用java -version查看是否安装成功  
![安装](https://github.com/NFUNM084-CN/ARVR-week01/blob/master/cmd.png "安装")  
### 安卓开放平台安装要点
- 下载sdk开发包 : android-sdk_r24.4.1-windows→SDK manager.exe  
![安卓](https://github.com/NFUNM084-CN/ARVR-week01/blob/master/andrioid.png "安卓")  
### 配置unity环境要点
- 启动unity→edit→preferences→external tools，按照安装路径选择SDK（对应安卓开发平台路径） JDK对应（Java路径）  
![SDK&JDK](https://github.com/NFUNM084-CN/ARVR-week01/blob/master/unity03.png "SDK和JDK")  
- 导入老师给的unitypackage，打开file→build setting，保证适配安卓，add open scen勾选环境  
![导入](https://github.com/NFUNM084-CN/ARVR-week01/blob/master/unity01.png "导入")  
![配置环境](https://github.com/NFUNM084-CN/ARVR-week01/blob/master/unity04.png "配置环境")  
- player sitting→companyname&other name→package name，修改成自定义名字→build  
![改名](https://github.com/NFUNM084-CN/ARVR-week01/blob/master/unity02.png "改名")  
- 成功打包成apk就可以拖进安卓模拟器进行调试
## 录屏演示  
[点击查看已上传视频，无法播放请下载](https://github.com/NFUNM084-CN/ARVR-week01/blob/master/20200321_193630.mp4)
