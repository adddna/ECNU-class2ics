# ECNU-class2ics

基于原项目：(https://github.com/billchen2k/ECNU-class2ics)做了一些修改，使其能在2024年的window系统中使用。

## What's this

这个程序可以帮助你获取ECNU教务网上的课表信息，并保存成在大多数日历软件中流行使用的ics格式。

## Why we made this

- 使用日历软件管理课程表可以让你不再把丑陋的课程表设置成桌面壁纸。
- 每节课上课前都会收到关于下一节课的提醒。（美观程度取决于系统和日历软件）
- 对于 iOS 和 macOS，系统会自动为你查找上课地点并接入苹果地图。
- 不想每学期都手动添加。~~（懒）~~
  
## Dependencies

依赖以下python库：

```
pip install lxml
pip install requests
pip install pyexecjs
```

如果需要自动识别验证码，需要安装pytesseract并

```
pip install pytesseract
```
如果运行的时候还缺了什么，请 pip / pip3 上。

## How to use

运行legacy目录下的crawller.py文件，按照命令行提示操作即可。

## Old Contributors

Contributor|Website
---|---
Bill Chen|https://billc.io
Xiejiadong|http://xiejiadong.com/
