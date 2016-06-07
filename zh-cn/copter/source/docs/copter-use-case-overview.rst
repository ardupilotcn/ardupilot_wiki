.. _copter-use-case-overview:

========================
直升机用例概述
========================

本文对直升机的主要用例进行概要描述。T

概述
========

直升机自动驾驶仪提供了一个稳定的飞行平台，可以精确的手动或者自动控制
载具的位置、速度、方向和动作。自动驾驶仪支持的控制行为有
:ref:`飞行/控制模式 <flight-modes>`:

-  手动飞行模式如：
   :ref:`稳定模式 <stabilize-mode>`,
   :ref:`高度保持模式 <altholdmode>` 和
   :ref:`悬停模式 <loiter-mode>` 提供了不同类型的稳定方式。使得载具比
   较容易起飞和定位。其他手动模式如 :ref:`跟随模式 <ac2_followme>` 和
   :ref:`回到出发点模式 (Return-to-Launch) <rtl-mode>`
   可以自动执行任务，不需要复杂的手动调整。
-  :ref:`自动模式 <auto-mode>` 允许你通过
   :ref:`地面控制站 <common-choosing-a-ground-station>` 定制复杂的任务。
-  载具上的计算机可以与直升机交互并控制直升机（例如，使用
   `DroneKit-Python <http://python.dronekit.io/>`__) 还可以执行低延迟的
   计算密集型任务，如计算机视觉。

手动和自动控制的稳定性、精确性和灵活性，使得直升机成为许多无人机应用的理
想平台。

本文对一些主要应用进行概述，特别强调图像/视频检查，或者难以到达的地方的有效载荷交付的需求。

.. tip::

   更多的应用以及信息参看本段
   :ref:`用例和应用 <common-use-cases-and-applications>`.

图像和视频拍摄
===========================

直升机可以让你轻松的获取位置信息，但想要拍图片或者视频是非常难得，甚至
是不可能的。因此，拍摄方面的应用是非常高端的用例。

直升机为拍摄提供了稳定的平台，附加稳定的独立摄像头位置控制（与载具相关）
的无刷摄像头云台。直升机支持一些摄像头友好的飞行模式如
:ref:`跟随模式 <ac2_followme>` 可以让你控制/维护摄像头指向你感兴趣的特定
区域。

高级系统如 `3DR Solo <https://3dr.com/solo-drone/>`__
使用运行在单独系统上的 `DroneKit-Python <http://python.dronekit.io/>`__
提供了更加高级的载具/摄像头控制("smart shots")。

First Person View (FPV)
=======================

*First Person View* allows you to fly your copter from the perspective
of an actual on board pilot. This use case is discussed in the topic
:ref:`First Person View (FPV) <common-fpv-first-person-view>`.

Disaster response
=================

Copters can help save lives/provide relief in the event of major
disasters (fires, flood, tornadoes, earthquakes, volcanic eruptions
etc).

They are particularly useful for search and survey tasks, and for
delivery of low-weight critical supplies, information and assistance.
They can do this relatively cheaply without putting additional lives at
risk (freeing up other resources to do actual recovery).

Search (and rescue)
===================

Copter makes an excellent platform for locating missing individuals and
groups. Vehicles can perform a grid search and take photographs for
either on-board (using a companion computer) or later analysis. Copter
can search in hard-to-reach areas, and may be used in large numbers due
to their low cost.

.. tip::

   Fixed wing vehicles have much greater range than Copter, and may be
   more suitable for searching large areas with low ground-cover.

Agricultural applications
=========================

Agricultural inspection is a growing field for UAV applications.
Examples include:

-  Tile and drainage inspections
-  Barn roof and silo inspections
-  Irrigation pivot inspections
-  Hail and cattle damage inspection for crop insurance claims
-  Scare off pest-wildlife that eat crops
-  Patrol for hunters on your private land
-  Locate missing cattle (This is where a thermal camera comes in
   handy.)
-  Video check-ins for landlords

.. tip::

   This promises to be one of the most important and earliest adopted
   civilian uses of Multicopters. One benefit is that there are fewer
   restrictions when flying over private land.

Forest fire mitigation
======================

Copter has great potential for fire monitoring and detection (with an
infrared camera, a Plane or Copter UAV can detect small camp fires even
in heavy tree cover).

Hazard/danger mitigation
========================

More generally, Copter and Plane are useful for other hazard mitigation
as a cost-effective alternative to patrolling using airplanes,
helicopters, or ground-based services.

They are already being used for shark patrols in beach areas, and there
is no reason they could not similarly be used in any other "patrol"
activity.

3D Mapping and GIS (Geographic Information Systems)
===================================================

Copter makes an effective 3D Mapping platform with a wide variety of
potential applications. For more information see the topic :ref:`3D Mapping <common-3d-mapping>`.

Inspection, Verification and Sample Collection
==============================================

Architectural and building inspection/verification are possibly the
fastest growing UAV use case - due to the obvious benefits to being able
to check construction quality and condition without having to create
expensive scaffolding and other safety infrastructure. Copter is
similarly useful for contour analysis, drainage and verifying adherence
to plans.

Copter is also useful for sample collection in difficult to reach or
hazardous areas (this requires that the vehicle is fitted with a small
probe or other sample device). The `Modcopter Sample Collection System <http://permalink.lanl.gov/object/tr?what=info:lanl-repo/lareport/LA-UR-13-23300>`__
is an excellent government-backed student project for accessing a
variety of samples.

Payload Based Applications
==========================

Copter is suitable for delivery of low-mass emergency supplies,
including flotation devices, communications devices, shark repellent
etc.

There are active investigations into other commercial applications
including crop spraying and package delivery.

Other applications
==================

Copters are being used or considered in many other applications:

-  Initial "pilot line" stringing for power lines from hilltop to hill
   top.
-  Painting, touch up and maintenance.
-  Tree trimming and spraying.
-  Building and home cleaning.

More detail and additional use case information is covered in the
section :ref:`Use Cases and Applications <common-use-cases-and-applications>`.
