.. _what-is-a-multicopter-and-how-does-it-work:

===========================================
多旋翼直升机及其工作原理
===========================================
多旋翼直升机是由多个或快或慢产生向下推力的电机/螺旋桨单元控制运动形态的，机械结构简单的飞行器。

概述
========

.. image:: ../images/3DR-quad-motors-top.jpg
    :target: ../_images/3DR-quad-motors-top.jpg

多旋翼直升机从空气动力学方面来说是不稳定的，必须有一个机载电脑（又叫做飞行控制器）来保证飞行的稳定性。因此，多旋翼直升机是一个“电传飞行控制”系统。如果机载电脑不工作，它就无法起飞。飞行控制器融合从板载的微电子陀螺仪、加速度仪（与你手机上的传感器相同）的数据，实现对其方向和位置的精确判断。
上面所示的四轴直升机是最简单的多旋翼直升机，它的每一个电机与相邻的两个电机是朝着相对的方向旋转的（斜对角的两个电机的运行方向是一致的）。
四轴直升机可以通过控制一边的两个电机加速，另一边的两个电机减速实现俯仰（pitch）和翻滚(roll)操作。举个例子，如果想让四轴直升机向左翻滚，那就需要使右边的两个电机加速，同时左边的两个电机减速。同理，如果想实现俯冲，就需要使四轴直升机后面的两个电机加速，同时前面的两个电机减速。

四轴的向左或者向右转向(yaw)则通过对一个对角线上的两个电机加速，对另一个对角线的两个电机减速来实现。

水平运动是通过对某些电机加速另一些电机减速（具体哪些电机加减速视水平运行方向而定）使得载具运行的方向有一定程度的倾斜，然后对所有电机加速实现向前运动。倾斜的度数越高，飞行的速度越快。

高度的控制是通过对所有电机同时加速或者减速实现的。


多旋翼直升机与无人机的区别
=============================================================

如果多旋翼直升机实现了自助飞行，它就是无人机。通常来说，这就意味着它需要携带加速度和陀螺仪信息，再加上气压计和GPS的相关数据，使得飞行控制器不但知道自己的方向，还要清楚自己的位置。

多旋翼直升机演示及自动控制
==========================================================

..  youtube:: GyPqHeg2v0Y
    :width: 100%

该演示从 :ref:`稳定模式 <stabilize-mode>` 开始，该模式提高惯性姿态稳定系统，允许手动飞行控制。

在 :ref:`悬停模式 <loiter-mode>` 中，直升机自动控制位置和高度，但允许手动调整。

:ref:`简单模式 <simpleandsuper-simple-modes>`使直升机不需要考虑方向（直升机的机头朝向）进行飞行。

"自动降落" 可以控制下落。并在落地后释放电机控制(disarm)。

大风环境下飞行示范
=======================

..  youtube:: f8nAF6s-dwY
    :width: 100%

该视频由罗伯特*勒费布尔提供，表明我们的固件即便在60到90千米/时的强风下，仍然可以使多旋翼直升机正常飞行。该视频演示是直升机接近物理极限的操作，在你成为专家前请勿尝试。
