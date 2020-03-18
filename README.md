### unity3d的安装步骤  

#### unity3d安装
- 首先安装UnitySetup64-5.6.2f1，一直next即可  
![](https://github.com/ViTaSoyi/unity-installation/blob/master/images/unity%E7%AC%AC%E4%B8%80%E6%AD%A5.png)  

- 关闭防火干墙和安装好的Unity,再安装资源UnityStandardAssetsSetup-5.6.2f1  
![](https://github.com/ViTaSoyi/unity-installation/blob/master/images/unity%E7%AC%AC%E4%BA%8C%E6%AD%A5.jpg)  

- 然后安装UnitySetup-Android-Support-for-Editor-5.6.2f1.exe  
![](https://github.com/ViTaSoyi/unity-installation/blob/master/images/unity%E7%AC%AC%E4%B8%89%E6%AD%A5.png)  

#### 安装JAVA
- 安装JAVA开发平台(jdk-8u144-windows-i586_8.0.1440.1)  
![](https://github.com/ViTaSoyi/unity-installation/blob/master/images/java%E5%AE%89%E8%A3%85.png)  

**若后续弹出更改JAVA文件夹位置，务必不要将文件夹位置更改同上个步骤中文件夹相同的位置**  

#### 配置环境变量  
- 在用户变量处新建一个变量，变量名"JAVA_HOME"，变量值D:jdk（即JDK的安装路径）  
![](https://github.com/ViTaSoyi/unity-installation/blob/master/images/%E6%B7%BB%E5%8A%A0%E5%8F%98%E9%87%8Fjava-home.png)  

- 编辑变量名"Path"，在原变量值的最后面加上 %JAVA_HOME%\bin之后点击确定。
![](https://github.com/ViTaSoyi/unity-installation/blob/master/images/%E7%BC%96%E8%BE%91path.png)  

- 设置好后验证是否成功安装JAVA，出现java版本号即安装成功  
![](https://github.com/ViTaSoyi/unity-installation/blob/master/images/%E9%AA%8C%E8%AF%81java%E5%AE%89%E8%A3%85.png)  

#### 安装安卓开发包  
- 安装sdk开发包（SDK Manager），在android-sdk_r24.4.1-windows文件夹里  
- 直接点击install 17 packages。初次安装，需要更新大约十几个新包，大约要等半小时。  
![](https://github.com/ViTaSoyi/unity-installation/blob/master/images/%E5%AE%89%E8%A3%85%E5%AE%89%E5%8D%93.png)

#### 配置Unity3d的Android运行环境  
- 启动Unity3d,进入edit-Preferences-External Tools  
- sdk选对应的android-sdk-windows文件夹所在位置；jdk选择jdk文件夹所在位置
![]()  

- 完成之后，新建场景，保存场景，将场景添加到scenes in build里面，然后切换平台为安卓Android平台

- 
