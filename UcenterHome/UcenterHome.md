**Ucenter Home**
==================================
==================================
==================================
***安装过程及个人看法***
==================================
==================================
==================================
> **环境**

+  安装UcenterHome并能够运行，在这过程中要准备很多东西，首先我们要选择操作系统和搭建开源的环境。本人运行UcenterHome是在window7 64bit的操作系统，搭建了phpnow（phpnow搭建出来的环境就是PHP（5.3）+Apache（2.2.15）+Mysql（5.1.45）手工分开搭建的环境。搭建phpnow环境的步骤就不说，下面我来说说我装UcenterHome的过程：
                  
>                           分享是一种快乐！——lvk

+ （一）Ucenter安装详细步骤：（在phpnow环境为例）

 1.[UCenter下载](http://www.comsenz.com/downloads/install#down_ucenter)下载适合自己计算机的版本。

 2.将下载到适合自己版本的的Ucenter压缩包复制到本地服务器，本地服务器就是phpnow所安装的文件根目录中的htdocs，我们把Ucenter复制到htdocs中解压。此过程就相当于网上大多数资料所说用FTP客户端软件将Ucenter上存到服务器的那一步骤。如下图：

# 步骤图片 #
![步骤1](https://raw.github.com/lkun/lvkun/master/UcenterHome/Image/1.jpg)

+ 本图的Ucenter压缩包文件已经被解压......本来解压出来有一个upload的文件夹的，但是这个文件夹给我改名为UCenter了，所以我们解压出来的upload可以任意改名为自己喜欢的名字。

> 注意: 
> UCenter（upload）：这个目录下面的所有文件是我们需要上传到服务器上的可用程序文件；
readme：目录为产品介绍、授权、安装、升级、转换以及版本更新日志说明；
utilities 目录为论坛附带工具，包括升级程序；
advanced：目录为如何开发其他应用接口的范例和说明文档。

        3.  在任意一个浏览器中的网址栏输入http://localhost/UCenter/install、则会弹出安装页面，如下图：
![步骤2](https://raw.github.com/lkun/lvkun/master/UcenterHome/Image/2.jpg)  
> 4.上图阅读后点击“我同意”，进行下一步操作，如下图：
![步骤3](https://raw.github.com/lkun/lvkun/master/UcenterHome/Image/3.jpg)
> 5.点击下一步，如下图：
![步骤4](https://raw.github.com/lkun/lvkun/master/UcenterHome/Image/4.jpg)
> 6.对于我所配置的开源环境，所以我的服务器是：localhost，数据库名是root，密码是Mysql的密码（会默认出现在安装界面上），数据库用户名是：Ucenter（这个名字由自己来定，这个数据库就是用来存储UCenter的数据的），创始人的密码自己定。填好以上的所有信息，点击“下一步”，如下图：
![步骤5](https://raw.github.com/lkun/lvkun/master/UcenterHome/Image/5.jpg)
> 7.数据库安装完毕点击“安装用户中心成功，点击进入下一步”则自此 UCenter 安装完毕，进入 UCenter 后台登录界面，如下图所示：
![步骤6](https://raw.github.com/lkun/lvkun/master/UcenterHome/Image/6.jpg)
> 8.输入密码后点击“登录”进入到 UCenter 的后台，如下图所示：
![步骤7](https://raw.github.com/lkun/lvkun/master/UcenterHome/Image/7.jpg)
> 9.安装完 UCenter 后我们就可以开始安装 Ucenter home、Discuz!、     SupeSite、X-Space 等应用了。[next]UCenter 后台 => 应用管理，如  下图所示：
![步骤8](https://raw.github.com/lkun/lvkun/master/UcenterHome/Image/8.jpg)
> 10.我们要选择URL安装，填好“应用的安装的URL”就可以开始安装各个应用了。

+ (二)安装UcenterHome，详细步骤如下：

 1.下载 UCenter Home 2.0 程序包到本地，下载地址为：
[UCenter Home 2.0下载](http://www.comsenz.com/downloads/install#down_uchome)

 2.将下载到适合自己版本的的UcenterHome压缩包复制到本地服务器，本地服务器就是phpnow所安装的文件根目录中的htdocs，我们把UcenterHome复制到htdocs中解压。此过程就相当于网上大多数资料所说用FTP客户端软件将UcenterHome上存到服务器的那一步骤。如下图：
![步骤9](https://raw.github.com/lkun/lvkun/master/UcenterHome/Image/9.jpg)
 3.本图的UcenterHome压缩包文件已经被解压......本来解压出来有一个upload的文件夹的，但是这个文件夹给我改名为UChome了，所以我们解压出来的upload可以任意改名为自己喜欢的名字。注意：要把UChome文件夹中的config.new.php改为config.php
![步骤9](https://raw.github.com/lkun/lvkun/master/UcenterHome/Image/9.jpg)
 4.开始安装UcenterHome
有两种安装方法：
第一是：在浏览器的网址处输入网址http://localhost/UChome/install/index.php/会出现如下界面;
第二是：在装好UCenter的基础上，在UCenter的用户管理中心添加“新应用”后，输入正确的URL安装地址
http://localhost/UChome/install/index.php/后按确定键，直接进入如下安装界面,接受授权协议，开始安装 UCenter Home：
![步骤10](https://raw.github.com/lkun/lvkun/master/UcenterHome/Image/10.jpg)
　　5.下图中的UCenter 的 URL 访问地址和创始人密码，UCenter 的参数信息时自动获取的，其中UCenter 的 URL 就是您的 UCenter （在UCenter中用户管理中心添加新应用是时的那个URL）访问地址http://localhost/UChome/install/index.php/，UCenter 的创始人密码即您安装 UCenter （这个UCcenter是安装UCcenter而不是UCenterHome哦）时设置的登录密码。如果获取成功，您无需填写，直接点击下面的“提交 UCenter 配置信息”即可。
 ![步骤11](https://raw.github.com/lkun/lvkun/master/UcenterHome/Image/11.jpg)
6.进入下一步，设置数据库连接信息
![步骤12](https://raw.github.com/lkun/lvkun/master/UcenterHome/Image/12.jpg)
7.下图中的配置注意事项：

　　数据库服务器本地地址：一般为 localhost 或者填写数据库服务器的 127.0.0.1地址。

　　数据库用户名：是指有权操作 UCenter Home 数据库的用户root。

　　数据库密码：是指安装 UCenter Home 的数据库密码。

　　数据库字符集：这里选择 gbk ，这里的字符集要和程序的字符集以及 UCenter 的字符集保持一致。

　　数据库名：是指安装 UCenter Home 的数据库名称。

　　表名前缀：默认为 uc_ ，也可以自定义填写，强烈建议使用默认配置。

   填写完毕，提交进入下一步
![步骤13](https://raw.github.com/lkun/lvkun/master/UcenterHome/Image/13.jpg)
![步骤14](https://raw.github.com/lkun/lvkun/master/UcenterHome/Image/14.jpg)
7.继续下一步.
![步骤15](https://raw.github.com/lkun/lvkun/master/UcenterHome/Image/15.jpg)
8.输入用户名和密码，系统将这个用户名设为 UCenter Home 管理员，并开通管理员空间。
![步骤16](https://raw.github.com/lkun/lvkun/master/UcenterHome/Image/16.jpg)

 9.到这步整个UChome的安装就完成了。
![步骤17](https://raw.github.com/lkun/lvkun/master/UcenterHome/Image/17.jpg)

 # ***个人看法*** #
+ 装Ucenter　Home 首先要在PC机上装上Ucenter1.5或者Ucenter1.6，先将Ucenter和Ucenter Home复制到本地电脑开源的文件夹位置F:\PHP\phpnow1.5.6\htdocs进行解压，把upload文件夹的名字改为“Ucenter”，然后在浏览器的地址栏输入localhost/Ucenter/后按回车，出现Ucenter的安装界面，我们就一直按默认，知道有一些信息需要填写的时候，我们就把信息给填上，比如说在安装过程中会有一些信息需要我们填写的，数据库的服务器：localhost；数据库的名字：Ucenter；登录名：root；还有密码：xxx等，我们要正确填好，并记熟。然后我们一直按默认值确认，最后安装成功，跟着我们就需要在Ucenter用户管理中心界面的左边点击应用管理，创建新应用，我们选URL，然后把地址填为http://localhost/Ucenter/install/index.php,然后按确定，跟着就出现我们需要安装的Ucenter Home的安装界面，我们就一直点击默认安装，因为我们装好了Ucenter并配置好所以关于Ucenter的应用信息，所以在安装Ucenter Home的过程中，默认的信息都是正确的信息。

 # 参考链接 #
* [GitHub view](http://boliquan.com/github-method-of-use/)
* [36kr](http://www.36kr.com/)
* [皮皮书屋](http://www.ppurl.com/login/)
* [CSDN](http://www.csdn.net/)
* [爱范儿](http://www.ifanr.com/)
* [花瓣网](http://huaban.com/)
* [openshift](https://openshift.redhat.com/app/)