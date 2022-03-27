2022.3.20
#  Unity Action 初阅读
## <txt color = orange>关于Unity的优缺点</txt>
### 优点：
#### -----1. 可视化工作流
不是很能理解Unity的可视化工作流是什么，不需要自己设置自己的开发环境？

#### -----2. 跨平台开发
可跨多个平台进行开发，例如：IOS、安卓 Xbox

#### -----3. 组件系统
可任意挂载组件，让一个物体赋予开发者需要的属性，脚本也是组件

### 缺点
#### -----1. 难以确定哪些物体挂载了某些指定组件
Find Reference in Scene 可以找到，但显示出的所有挂在物体以及他的子物体，且搜索列表中并体现不出父子关系

#### -----2。与外部代码库链接困难
我的理解可能就是，类似于using system，需要手动添加，不知道对不对

#### -----3.方法和选择太多，选择困难
举个例子，就我需要一个滑动条，但UI中类似的组件有Slider和Scorllbar，不知道该选哪个的情况下，需要每个都尝试一遍

## <txt color = orange>关于Unity的面板以及常用编码器</txt>
### -----Scene View 
场景面板，大多操作在这个面板中进行，例如物体的旋转、缩放、物体位置
### -----Game View
游戏面板，检查游戏效果

可在Scene View 和Game View中同时观察，确认最佳效果

### -----旋转、缩放、移动： 常见改变物体属性操作
<img width="407" alt="截屏2022-03-21 上午2 01 19" src="https://user-images.githubusercontent.com/97930502/159176060-b9390bd5-e757-4566-a418-3d8b393438e8.png">
<p>可点击图片中的按钮对物体属性进行改变</p>

也可在inspector中对物体的大小，旋转角度，位置等进行改变

<img width="271" alt="截屏2022-03-21 上午2 03 12" src="https://user-images.githubusercontent.com/97930502/159176120-1aa15920-399a-4a29-9e50-9f97fdc11f6c.png">

也可通过键盘操作（但我好像三个都会用，想到哪个用哪个）

### -----Hierarchy view、the Inspector panel、Project、Console tabs
Hierarchy 记录场景中的物体及其父子关系（这里的物体一定要分好类，不然查找很麻烦）
Inspectoe 记录所选物体属性以及其搭载的组件
Project 显示项目中所有资源（这里的资源也需要分好类）
Console tabs 可使用其返回debug的信息

### -----推荐使用Visual Studio


2022.3.27
# 2.Unity Action第二~第三节
## 印象深刻的点
### 本地坐标和世界坐标
（可用Transform（）进行转换）
### 不同计算机拥有不同点处理性能，可能会导致同一代码不同的结果
（例如Update（）和FixUpdate（），联想到，若在对物理性能要求较高的功能使用Update（）时，当同时线上联机玩一款游戏时，可能会出现不同频的状况）
### [RequiredComponent(typeOfCharacterController)] 用到的频率较高
### 对于用射线模拟射击过程
（这个，类似于之前的注释特效“焦点”处理，但现在联想到，若相机为父，两只手柄为子，将射线从两只手柄中投射出，可能能做出手柄射线有焦点的效果）
### 利用碰撞体实现撞击效果
（碰撞体是实现撞击效果
