# PKG转化工具
将Wallpaper Engine: 壁纸引擎的场景类壁纸(*.pkg)导出
## 使用方法
1. 通过Git Clone的方式将本程序克隆至您的电脑
2. 运行Main.py
## 运行环境
推荐Python 3.11 以上， 最低标准Python 3.7.3
## 关于源代码
**如果你想修改本程序源代码，请务必看完本部分**

- 本程序使用的库均为Python标准库，以方便各位小白运行，因此不必担心环境问题
- 使用的库如下:
   
   1. UI: tkinter, tkinter.messagebox
   2. 目录&文件相关: os, json
   3. 终端: subprocess
   4. 退出程序:sys
   5. 多线程: threading
   6. 获取路径: winreg(需要pip)
- 为了方便国际化 ~~(其实是因为Vs Code的中文显示有问题)~~ ，本程序注释采用英文，后续版本将创建新分支以存储含有中文版注释的程序
- 本程序使用面向对象编程的格式(不是标准的tkinter式)
- PR: 本程序欢迎PR，但对PR有一定要求
   
   1. 请尽量使用Python标准库
   2. 请确保你的程序有注释(中英均可), 我们会翻译
   3. 请尽量使用面向对象编程的格式
   4. 欢迎各位的PR
## 声明
1. RePKG.exe不是本仓库所有者开发的,  它的仓库 *[在这](https://github.com/notscuffed/repkg)*,记得给它个Star
2. 导出的壁纸版权归壁纸创作者所有，本程序仅供学习交流使用。