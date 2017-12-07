# ue4-partical-sysytem
learing ue4 particle system\<br>
##创建粒子系统：

1:添加新项(add new iter)--->>>粒子系统(particle system)--->>>命名粒子系统(rename particle system name)\<br>
2:在内容浏览器(content brower)空白处右键--->>>粒子系统(particle system)--->>>命名粒子系统(rename particle system name)\<br>
particle emitter 默认模块及作用\<br>
Required（必要选项） - 这里包含了一些属性，都是对粒子系统绝对需要用到的属性，比如粒子使用的材质，发射器发射粒子的时间，以及其他。\<br>
Spawn（产生数量） - 这个模块控制粒子从发射器生成的速度，它们是否以 Burst 生成，以及其他和粒子发生时机有关的属性。\<br>
  burst（爆炸）\<br>
Lifetime（生命时长） - 这里定义了每个粒子在生成后存在的时间，如果没有这个模块，粒子则会一直持续下去。\<br>
Initial Size（初始大小） - 这里对粒子生成时的缩放比例进行控制。\<br>
Initial Velocity（初始速度） - 这里对粒子生成时的移动进行控制。\<br>
Color Over Life（依据生命改变颜色信息） - 这个模块用于控制每个粒子的颜色在过程中如何改变。\<br>

