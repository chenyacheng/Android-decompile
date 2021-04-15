# 一、用apktool反编译apk得到图片、XML配置、语言资源等文件
1：将app.apk复制到当前目录下，cmd输入命令：apktool d app.apk
# 二、使用dex2jar反编译apk得到Java源代码
1、解压app.apk得到classes.dex
2、将classes.dex放到dex2jar-2.0文件夹内
3、cmd输入命令：d2j-dex2jar classes.dex
4、使用jd-gui打开classes-dex2jar.jar查看源代码
