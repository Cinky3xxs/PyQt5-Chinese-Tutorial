# PyQt5 介绍

这是一份PyQt5的教程。教程的目的是让你开始学会使用PyQt5工具包。这个教程的内容已经在Linux上创建并测试。[PyQt4 教程](http://zetcode.com/gui/pyqt4/)是PyQt4的教程，PyQt4是一个Python（同时支持2和3）版的Qt库。

## 关于 PyQt5

PyQt5是一套来自Digia的Qt5应用框架和Python的结合绑定的应用框架。同时支持Python2.x和Python3.x版本。本教程使用Pyhton 3。Qt库是最强大的GUI支持库的之一。PyQt5的官方网站是[www.riverbankcomputing.co.uk/news](http://www.riverbankcomputing.co.uk/news)。Riverbank Computing开发了PyQt5。

PyQt5是由一系列Python模块组成。它拥有超过620个类，6000个方法和函数。它是一个多平台的工具套件，它可以运行在所有的主流操作系统中，包括Unix，Windows和Mac OS。PyQt5采用双重许可模式。开发者可以在GPL和商业授权之间选择。

PyQt5的类被分在很多模块中，主要模块有：

- QtCore模块 包含了核心的非GUI的功能设计。这个模块被用来实现时间、文件和目录、各种数据类型、流、URLs、mime类型、进程与线程（这个模块其中包含的全是一些文件类型？）。

- QtGui模块 包含的类用于窗口系统集成、事件处理、2D绘图、基本图形、字体和文本。

- QtWidgets 模块包含的类提供了一套UI元素来创建经典的桌面风格 用户界面（即包含的是窗口里面的类）。

- QtMultimedia 模块包含的类用于处理多媒体内容和连接摄像头和无线电功能的API。

- QtBluetooth模块 包含的类用于扫描蓝牙设备，并且和他们建立连接互动。

- QtNetwork 模块包含的类用于网络编程，这些类使得TCP/IP和UDP客户端/服务端编程更加容易和轻便。

- QtPositioning 模块包含的类用于通过使用多种可能的资源来定位，包含卫星定位，Wi-Fi，或一个文本文件。

- Enginio 模块实现了用于获取Qt云服务管理应用程序运行时间的客户端的库。

- QtWebSockets 模块包含的类实现了WebSocket通信协议。

- QtWebKit 模块包含了一个基于WebKit2库的web浏览器的类。

- QtWebKitWidgets 包含了一个基于WebKit1库的web浏览器，用于QtWidgets基础程序的类。

- QtXml模块包含的类用于处理XML文件。这个模块提供了SAX和DOM API的实现。 

- QtSvg模块提供了用于显示SVG文件内容的类。Scalable Vector Graphics (SVG)是一种用XML来描述二维图形和图形应用程序的语言。

- QtSql 提供了处理数据库的类。

- QtTest 提供了实现PyQt5应用程序单元测试的函数。

- QtOpenGL模块包含的类用于对图形进行渲染。

## PyQt4和PyQt5的区别

PyQt5不向后兼容PyQt4。PyQt5中有一些重大的改变。然而，将旧代码迁移到新的版本中并不是非常困难。两者的区别如下：

Python模块被重组。一些模块已经被丢弃(QtScript)，其他部分模块被分割成子模块(QtGui, QtWebKit)。

新的模块被引进, 包括 QtBluetooth, QtPositioning, 和 Enginio。

 PyQt5 只支持新风格的信号和槽的处理/写法。SIGNAL()和SLOT()的调用将不再被支持。

PyQt5 不再支持任何在Qt5.0版本中被标记为弃用的或不建议使用的Qt API。

## Python语言的介绍

Python is a general-purpose, dynamic, object-oriented programming language. The design purpose of the Python language emphasizes programmer productivity and code readability. Python was initially developed by Guido van Rossum. It was first released in 1991. Python was inspired by ABC, Haskell, Java, Lisp, Icon, and Perl programming languages. Python is a high-level, general purpose, multiplatform, interpreted language. Python is a minimalistic language. One of its most visible features is that it does not use semicolons nor brackets. It uses indentation instead. There are two main branches of Python currently: Python 2.x and Python 3.x. Python 3.x breaks backward compatibility with previous releases of Python. It was created to correct some design flaws of the language and make the language more clean. The most recent version of Python 2.x is 2.7.9, and of Python 3.x is 3.4.2. Python is maintained by a large group of volunteers worldwide. Python is open source software. Python is an ideal start for those who want to learn programming.

Python programming language supports several programming styles. It does not force a programmer to a specific paradigm. Python supports object-oriented and procedural programming. There is also a limited support for functional programming.

Python语言的官方网站是python.org

Perl，Python，和Ruby都是广泛使用的脚本语言，它们有很多共同的特点，也是相互的竞争对手。

 

## Python工具包

为了创建图形用户界面，Python程序员能够从三个不错的选项中选择：PyQt5, PyGTK和wxPython。

 

本教程就是对PyQt5工具包的介绍。

​    