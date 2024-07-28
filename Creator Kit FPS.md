# Creator Kit FPS



## Transform

![image-20240709170325365](C:\Users\a1892\AppData\Roaming\Typora\typora-user-images\image-20240709170325365.png)

游戏组件的位置信息，旋转角度，大小



## 刚体

![image-20240709170404942](C:\Users\a1892\AppData\Roaming\Typora\typora-user-images\image-20240709170404942.png)

Mass：质量

Drag：阻力

Angular Drag：角阻力（被撞了会不会转）

Use Gravity：使用重力

Is Kinematic：是否开启动力学，开启后游戏对象不受物理引擎影响，只能通过Transform属性来操作



## 脚本组件

![image-20240709170825436](C:\Users\a1892\AppData\Roaming\Typora\typora-user-images\image-20240709170825436.png)



## 碰撞体（胶囊碰撞体）

![image-20240709170916659](C:\Users\a1892\AppData\Roaming\Typora\typora-user-images\image-20240709170916659.png)



## 对象分组

通过创建空对象来对游戏对象进行分组

![image-20240709171341765](C:\Users\a1892\AppData\Roaming\Typora\typora-user-images\image-20240709171341765.png)

![image-20240709171244183](C:\Users\a1892\AppData\Roaming\Typora\typora-user-images\image-20240709171244183.png)

创建后Target为父对象，其余的为子对象



## 相对坐标&世界坐标



父对象坐标：包含所有子对象的矩形的中心点

![image-20240709173348058](C:\Users\a1892\AppData\Roaming\Typora\typora-user-images\image-20240709173348058.png)

相对坐标：子对象相对于父对象中心点的坐标

世界坐标：相对于世界原点的坐标



## 用预制件创建新预制件

添加刚体和碰撞体

![image-20240709173916842](C:\Users\a1892\AppData\Roaming\Typora\typora-user-images\image-20240709173916842.png)

Edit Collider：编辑碰撞体积

添加Target脚本：

![image-20240709174209148](C:\Users\a1892\AppData\Roaming\Typora\typora-user-images\image-20240709174209148.png)