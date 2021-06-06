.. LogicLab编程工具用户指南 documentation master file, created by
   sphinx-quickstart on Mon May 31 20:03:11 2021.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

LogicLab编程工具用户指南
====================================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:

   logiclab

LogicLab是符合IEC61131-3标准的软件解决方案，工业自动化的基础，包含如下几部分软件（点击链接了解更多详情）：

* :ref:`LogicLab编程工具 <logiclab-engineer>` 是运行在Windows平台PC上的符合IEC61131-3标准的PLC编程环境，
  支持标准中的五种编程语言：梯形图(LD)、功能块图(FBD)、结构化文本(ST)、顺序功能图(SFC)与指令表(IL)。
  高效的编译器设计大大提升PLC逻辑代码在控制器平台上运行的性能。
  LogicLab编程工具同时支持在线查看变量值、强制设定在线值、设定断电与单步跟踪与软件逻辑示波器等等调试功能。
  同时LogicLab编程工具支持不停机在线更新PLC程序等等高级功能，而背板总线、现场总线与功能组件的图形化配置功能则大大简化用户的操作。
  LogicLab根据控制器具体的实现功能可以实现通过以太网、串口、USB、CAN等等接口下载与调试PLC程序。

* :ref:`LogicLab运行系统 <logiclab-runtime>` 是运行在PLC控制器的MCU、CPU或者DSP处理器硬件上的软件组件，专门用于执行由LogicLab编程工具下载至PLC控制器存储器中的二进制逻辑代码，
  以及负责执行LogicLab运行内核中的C/C++功能组件。LogicLab运行系统可以支持市面上主流的实时操作系统或者不带操作系统(Bare Metal)。
  极简的内核与开放式插件化框架的设计，使得LogicLab运行系统具备极高的性能与高度的可定制性。
  

* :ref:`LogicLab PLC SDK <logiclab-plcsdk>` 专门用于PLC控制器研发工程师使用C/C++开发语言实现自定义的PLC功能组件。
  开放式的插件化框架设计，PLC研发工程师可以集成任何C/C++组件至PLC内核或更换LogicLab运行系统中提供的功能组件。完全开放式的PLC SDK API与移植代码设计，PLC研发工程师可深度参与研发流程。
  

本文将着重介绍LogicLab编程工具的使用，涉及基于LogicLab运行系统与PLC SDK实现自主品牌的PLC控制器，请与翌控科技取得联系:support@nxtrol.com。


从哪开始
--------------
* :ref:`LogicLab软件下载与安装 <logiclab-download-install>` 页面将描述如何下载以及安装LogicLab编程工具。

* :ref:`快速新建第一个工程HelloWorld <quickstart>` 页面将指导您如何快速新建第一个梯形图工程并快速进入编程与调试状态。

* :ref:`IEC61131-3编程教程 <iec61131-3>` 页面详细讲述IEC61131-3标准与基于LogicLab应用，如果您没有符合IEC61131-3标准PLC编程基础，请务必学习。
  如您已经使用其他厂商符合IEC61131-3的PLC产品与编程软件，也建议您初步浏览。

* :ref:`现场总线 <fieldbus>` 页面详细LogicLab编程工具中的现场总线组态功能。如果您使用现场总线出现疑问，请首先参阅此部分的说明。

* :ref:`参考平台使用入门 <reference-system>` 页面介绍LogicLab支持的学习平台、开发套件、客户产品的使用入门。


关于本文档
--------------
我们在努力更新本文档资源，所有的文档源代码将在github上开放，如果您发现任何错误的描述或者有任何建议，非常感谢您能发送给我们，联系邮箱:support@nxtrol.com
