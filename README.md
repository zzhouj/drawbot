# drawbot
2040铝合金框架Core-XY结构的写字机器人

## 简介
打印机墨盒又双叕涨价了！娃经常要我帮她抄写错题，费时费力，还嫌弃我字写的难看。不如自己DIY一台写字机器人，既可以替代我抄写错题，还可以部分替代打印机的功能节省墨（Jin）盒（Qian）。

本项目主要参考了[T站](https://www.thingiverse.com/)上的[DrawBot V1.1 (Drawing Robot - Arduino Uno + CNC Shield + GRBL)](https://www.thingiverse.com/thing:2349232)。参考项目的机械部分采用了3D打印件，而我手头暂时还没有3D打印机，所以采用了2040铝合金的框架以及某宝上定制CNC切割了5块3mm铝合金板，电子部分和软件部分和参考项目一样。

做这个项目主要是考虑到DIY写字机器人相对DIY 3D打印机来说要简单很多：没有Z轴，没有热床，没有挤出机，一块Arduino Uno + CNC Shield即可控制，GRBL firmware复杂度低。我想先用写字机器人来练手，然后再来自己组装一台3D打印机。

## 目录及文件说明
- sw2020 存放写字机器人的零件模型及装配文件，使用的三维建模软件是SolidWorks 2020。
- dxf 3mm铝合金板定制CNC切割文件，由sw2020文件夹中的对应零件模型导出生成。
- BOM.xlsx 零件清单及参考价格。
- Assemble and User Manual.pdf 装配及用户手册。
