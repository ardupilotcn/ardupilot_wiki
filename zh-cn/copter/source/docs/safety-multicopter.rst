.. _safety-multicopter:

==================
多旋翼直升机安全
==================

.. warning::

   你的首要任务是保证人的安全！

#. **由于软硬件故障，或者导航信息出现错误，炸机是随时可能发生的。**
#. **如果你在别人附近飞行，那你就是置别人与危险之中！**

   #. 确保你的直升机与你自己和周边观众保持足够的安全距离。
   #. 距离人和财产多远才算是“安全距离”，需要你根据具体情况自己做出判断。
   #. 至少，可以考虑：距离你自己不少于10ft(3米)，同时也不要大于30ft(10米)。
   #. 保持你的直升机尽可能远离其他人、财产和障碍物。
   #. 确保没有人出现在你和你的直升机之间。
   #. 观众应该始终处于驾驶员后的安全距离之外。
   #. 如果有人进入了你认为的“安全”区域以内，请立即降落，待人离开后再起飞。
   #. 在满电状态下，普通大小的多旋翼直升机速度可以超过20 mph（32千米/时），可以爬升到上百米，在电量耗尽前可以轻松飞行几公里远。

#. **如果你飞的太高或者太靠近机场，你就会置载人飞行器和他人与危险之中！**

   #. 了解离你最近的机场的位置，不要在其附近飞行。

#. **在你准备飞行之前，始终确保电源线与配电板或者配电线束之间处于断开状态。**

   #. 始终在连接电源线**之前**,记得打开遥控器并把油门拉到最低。
   #. 降落之后，你所要做的第一件事是断开电源线。
   #. 确保断开电源之后再关闭遥控器。
   #. 在做电机测试之前，始终记得去掉螺旋桨。你和你小伙伴们的手和脸都会感激你的。
   #. 当电源线连接以后，始终假定电机处于解锁（arm）状态，你可以轻推油门加以验证。
   #. 不要同时拿起航模和遥控器，你有可能会碰到油门。
   #. 不要尝试飞行时间超过你的电池安全承载能力，这对你的电池伤害极大，还有可能导致炸机。

#. **我们在APM和PX4的飞行控制器中集成了一个电机解锁安全功能，**

   #. 在电池连接之后，即将起飞之前，需要把无线遥控器的油门摇杆拉到右下角保持几秒来解锁电机。
   #. 降落之后，你的第一个动作应该是吧油门摇杆拉到左下角并保持几秒来“锁定”电机。
      \* 可以通过向上轻推油门测试锁定状态。如果电机不转，说明处于锁定状态。
   #. 除了飞行过程中，即使处于锁定状态，也要始终保持油门摇杆处于最低位置。

#. **要习惯于从其他模式切换回稳定模式，进而假定会切换到全手动控制。**

   #. 这是最重要的，也是唯一的恢复技巧（多多练习）。
   #. 稳定模式上可以叠加简单模式，但如果你想这样做你应该练习到你熟悉以后再尝试。
   #. 在你非常适应你的直升机之前，请不要尝试稳定模式和稳定+简单模式外的任何模式。

#. **预留冗余推力非常重要。**

   #. 如果推力不足，当自动控制的需求超过油门极值，就可能会导致不稳定。
   #. 理想状态下，当加到50%油门（摇杆中点），你的直升机应该可以悬停。

#. **建议你不要用贵的、坚硬的、极其锋利的碳纤维桨，尤其当你还在学习中。**

   #. 建议使用便宜的、更灵活更易碎的塑料桨。
   #. 一些超级碳纤维桨比武士刀还锋利，几乎是无坚不摧的 - 你不是。

#. **炸机、未完全降落或者未知的飞行控制情形下的重要应对措施。**

   #. 要做的第一件事情是扔条毛巾到你的直升机螺旋桨上（螺旋桨可能会出乎预料的乱转）。
   #. 然后立即断开电池连接。
   #. 除了灭火器和急救箱，一个大的毛巾是你非常重要的安全装备。
   #. 通常，首先使用毛巾好过另两种选择。

#. **在测试或者飞行任何导航模式时（使用GPS）：**

   #. 在解锁起飞之前，确保你的GPS已经“定位”。
   #. 检查你的起始位置和任务计划确实准确无误。
   #. 如果GPS没有精确报告你的起始位置，重启然后等待搜到8颗星以上（不仅仅是3D定位）再次检查。

#. **始终遵纪守法**

   #. 我们对于多旋翼直升机（一般的航模）的个人使用持续受到害怕‘无人机’和隐私保护人士的攻击。如果你违反法律，或者侵犯别人隐私，或者可能对他人造成伤害，你就威胁到了我们未来为航模的个人使用。所以，请了解相关法律并了解别人的相关权利 - 然后有依据的飞行。
   #. 很多国家都有知名的航模组织。在美国就是\ `AMA <http://www.modelaircraft.org/>`__.
      阅读AMA的 `安全准则 <http://www.modelaircraft.org/files/105.pdf>`__. 通过与FAA和其他政府组织的合作，AMA已经完成了（持续更新中） `无人机和第一视角飞行条例 <http://www.modelaircraft.org/documents.aspx#FPV>`__. 如果你在美国（或者不在），请阅读该文档！AMA是一个强大的游说集团，可以帮助我们保护我们的权利。加入或者支持你们国家的航模组织 - 保护我们飞行的权利.

.. warning::

   重要提示: 让你的直升机与人们保持安全距离！

.. tip::

   这些提示也可以帮助保护你的多旋翼直升机远离损毁。

#. **避免突然或者遥控器控制摇杆变位**

   #. 小刻度的移动控制摇杆，不要“猛拉”。
   #. 如果直升机已经适合的校正平衡过，那么它只需要很小的摇杆输入就可以控制高度、方向和速度了。

#. **你的直升机在没有控制输入时，应该或多或少的稳定在同一个水平线上。**

   #. 如果你正在和你的直升机“搏斗”，那么请降落并把问题解决掉 - 一定有某些地方不对 - 需要硬件调校或者是软件校准

#. **在大油门输入的时候要非常小心，直升机可能会快速的爬升（或者下降）。**
#. **由于多旋翼都是对称的，所以飞行容易失去视觉定向。**

   #. 在手动模式飞行时，清晰的判断直升机的定向（正面的方向）是成功飞行的重要因素。
   #. 让你的直升机与你保持适当的距离是非常重要的，尤其是学习阶段，有助于你维护视觉定向。
   #. 通常，不少于10ft（3米）但不要超过30ft(10米)是合适的距离。
   #. 当直升机距离你超过100ft（30米）以后，维护其**方向**就会非常困难，非常容易炸机。
   #. 当你使用稳定模式飞行时迷失了方向，你可以尝试直着向前飞，然后使用偏航（Yaw）进行驾驶，就像在地面上驾驶汽车一样。
   #. 当无法确定方向时，相对于**定向导致**的炸机或者更坏的情形 - **飞丢**，更好的选择是简单的下降然后降落。
   #. 当驾驶员指挥直升机飞回来的时候发生了旋转，由于离得太远迷失了方向，这种情况下经常会飞丢。
   #. 后果：直升机飞得太远，导致炸机或者飞丢。

#. **始终设置稳定模式为快速切换模式中的一个。**
#. **意想不到的风或者大风，或者不速之客会使得飞行非常困难**

   #. 大风会阻碍向前飞行，导致直升机旋转，从而使你分不清方向。
   #. 飞得越高，大风的影响会越大。
   #. 在达到你能力极限之前切换到稳定模式然后降落，可以帮助你保护你的直升机。
   #. 在你获得相当大的自信心之前，避免飞行太快或者太高，不管是手动模式还是自动模式。
   #. 在树或者建筑物附件飞行的时候，非常容易迷失视觉定向，甚至完全看不到你的直升机了。
   #. 大型物体周五的强风也是非常糟糕的问题。
   #. 也可能会发生遥控器信号丢失。
   #. 如果你的直升机靠近某个潜在的干扰对象，立即切换到稳定模式然后降落，或者迅速让你的直升机返回。

#. **ArduPilot 特定的安全模式: 回到出发点（RTL）, 故障安全（FailSafe）和地理围栏（GeoFence）。**

   #. RTL 在其远离你的时候，提供了一种安全的**回到出发点**的方式。
   #. 设置为当无线遥控故障时回到出发点或者下降的**故障安全**可以使你的直升机避免伤害。
   #. **地理围栏** 建立一个自动飞行边界，保持你的直升机待在安全范围之内。
   #. 请不要完全依赖上述的安全模式，时刻准备着切换回稳定模式并让你的直升机降落。
   #. 尤其不要依赖上述安全模式进行演习或者训练，否则你就要考虑风险。
   #. 这些模式都只是补充，不是良好的安全实践的代替。

#. **在你硬件设置或者调校之后开始首飞时：**

   #. 切换到稳定模式，慢慢的推油门，直到直升机处于悬停状态。
   #. 如果直升机发生旋转，那么把它关掉并解决这个问题。
   #. 电机有可能会被设置为错误的旋转方向。
   #. 或者螺旋桨有可能会被装反。
   #. 看它是否会在某个轴向上旋转或者总是往某个方向飞。
   #. Mission Planner里面对遥控器的设置可能是错误的。
   #. 某个电机或者电调可能完全没有工作。
   #. 错误的桨可能装在了错误的电机上。
   #. 如果所有的问题都解决了，那么该直升机应该可以轻易的悬停在离地1到2英尺的高度上。
   #. 如果不能到达稳定的甚至静止的悬停在1到2英尺的高度上，那就降落，找问题并解决掉，直到它可以。

#. **当以FPV "第一人称视角" (通过摄像头)飞行时，你把你的模式设置为：稳定（STABILIZE），简单（SIMPLE）或者回到出发点（RTL）了吗。**

   #. 在使用第一人称视角模式之前，确保回到出发点模式是可以正常工作的。
   #. 用第一人称视角时请用稳定模式飞行。
   #. 如果你的第一人称视角画面丢失，你可以切换到简单模式或者是回到出发点模式返回。

#. **保证你的电池不会掉下来。**

   #. 用尼龙扎带把它固定好。
   #. 你也可以使用有粘合剂的魔术贴固定。

.. note::

   获取可打印的PDF版安全手册\ `多旋翼直升机安全 <http://download.ardupilot.org/downloads/wiki/pdf_guides/MultiCopter_Safety.pdf>`__\ 

`Copter 论坛 <http://ardupilot.com/forum/viewforum.php?f=3>`__ 有开发人员相应你的问题，你也可以搜索相似的问题。请选择与文档或者你的问题相关的分论坛进行提问。
