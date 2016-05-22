#一键生成ios、安卓各尺寸图标和截屏
一键生成苹果各尺寸的截图和图标

一键生成安卓图标

#运行环境
Python 2.7

安装PIL库

#使用参数
tool.py 操作 [文件名] [平台名]
    操作：icon 或 screenshot
    文件名：图标文件名
    平台名：ios 或 android

例如生成ios的图标：tool.py icon icon.jpg ios

例如生成安卓的图标：tool.py icon icon.jpg android

例如生成ios的截屏：tool.py screenshot

#注意
需要一张mask.png用于裁剪安卓图标，建议使用512*512px，圆角为70px

生成截屏会遍历当前目录下所有jpg和png进行生成，并且自动判断横竖屏

ios图标默认不裁剪圆角，需要的可以自己改代码

当前未加入安卓截屏，因为安卓变化多端，需要的可以自己加

#作者的话
我是个独立开发者，做了七八年了。最近才想起学学Python，学了两三天，写了这个脚本，类似的工具和脚本肯定也有，自己就写着玩玩，喜欢的可以拿去用，如果有更好的建议、更简单的代码，欢迎留言。
winterfeel@qq.com