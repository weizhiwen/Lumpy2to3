# Lumpy2to3
## 1、Lumpy 简介
Lumpy是一个科学计算库 Swampy 中的一个模块，它可以将运行的Python程序生成 UML 图，将正在运行的程序状态可视化。它类似于一个图形调试器，但特别之处是可以生成符合要求的高级可视化使用标准的UML。
谁可以使用这个模块？
教师：使用这个模块可以生成演示Python程序执行的模型。
学生：使用这个模块可以探索Python解释器的行为。
软件工程师：使用这个模块绘制类之间的关系图来提取现有程序的结构，包括库中定义的类和Python解释器。

了解更多:point_right:[Lumpy官网](http://www.greenteapress.com/thinkpython/swampy/lumpy.html?tdsourcetag=s_pctim_aiomsg)



## 2、仓库说明

由于 lumpy 只有 Python2 的版本，但目前主流的 Python 版本是 3，所以在指导老师的要求下，我将该模块修改为了 Python 3 版本的。在 Python3.6 环境下测试通过，Python3.7 环境下由于该版本更改了生成器内部的 StopIteration 处理（问题详情见 Python 的 [PEP 479](https://www.python.org/dev/peps/pep-0479/)），所以暂时不能使用。

**文件目录**

Gui.py 			图形绘制相关的类文件

Lumpy.py 		Lumpy模块主文件

lumpy_test*.py 	测试文件

原Lumpy2文件	从官网下载的Lumpy模块

原Lumpy2文件只是方便查看 Python2 版本的代码，使用时可忽略，只需要将最外部的 Gui.py 和 Lumpy.py 文件包含进项目文件夹即可，像引用正常的外部 Python 文件一样使用。

