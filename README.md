# factory-manage
基于Django的工厂管理系统，人员、工资、仓库、设备、通知等要素管理

环境配置：
  Windows 10 专业版 x64
  Django 2.2
  Python 3.6
  Pytz 2019.1

 
 感谢B站杨仕航大佬，基本是借鉴大佬的视频完成的；https://www.bilibili.com/video/av16957624/

本来想着在服务器上让你们看一下效果，但是在做项目的时候密码很简单并且所有账号都是一个密码，所以有人就猜到了管理员密码。还是你们下载下来在本地看吧。
初始账号：test 密码:asdfzxcv    在所有员工页面可以看到全部账号，并且所有密码都是这个。

有人不太清楚怎么打开，就给我贴标签bug、invalid,emmmm~下面是项目的正确打开方式：将文件download下来后，确保自己有python3的环境。解压后在该页面打开命令行，输入python manage.py runserver,回车应该可以看到http://127.0.0.1:8000/ 在本地浏览器打开就可以了。

我也知道在github上相似项目很多，但这是我辛苦做出了的期末作业，还是想和大家分享一下~

最近我发现运行会有一些问题，staticfiles错误。检查一下Python和Django的版本，现在默认Django是4.x，需要回退为2.2. 将staticfiles改为static，具体错误见issue
