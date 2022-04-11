# 记录几个有趣、可能会忘、需要注意的点（大量使用截图。防止打字出错）
#### 1.head -n3 打印前3个

<img width="242" alt="截屏2022-04-12 01 25 37" src="https://user-images.githubusercontent.com/97930502/162795840-e3671730-89d2-45d3-ac82-1eba6ba51ed5.png">

#### 2.-f1,3 从第一到第三列

<img width="236" alt="截屏2022-04-12 01 26 34" src="https://user-images.githubusercontent.com/97930502/162795978-4805e91f-4b87-40aa-825c-6edb38041d6a.png">

#### 3.-v 不包含所选项
<img width="350" alt="截屏2022-04-12 02 24 36" src="https://user-images.githubusercontent.com/97930502/162804803-70aea0be-abe0-4080-8c44-032bf4332ea2.png">


#### 4.uniq 检测重复

#### 5.定义变量注意点：
<img width="160" alt="截屏2022-04-12 02 07 53" src="https://user-images.githubusercontent.com/97930502/162802289-72bae6c6-2104-4c58-ab56-20280de55adc.png">4

<img width="206" alt="截屏2022-04-12 02 08 06" src="https://user-images.githubusercontent.com/97930502/162802322-35b2390a-442a-4b6d-a07b-5566c07fc586.png">
下图中的方法无效，在定义变量时，空格将不被允许

#### 6.命令行中变量也可被赋值！！
<img width="459" alt="截屏2022-04-12 02 11 05" src="https://user-images.githubusercontent.com/97930502/162802740-1369b796-94c2-48fd-bddc-16ab60fa1aca.png">

#### 7.alias 可用于简化缩写（g=git fe=fesh)
<img width="404" alt="截屏2022-04-12 02 16 25" src="https://user-images.githubusercontent.com/97930502/162803584-cac1c2c5-1186-4f9e-bafa-05cfbf147fbb.png">

简写删除 unalias 
#### 8.论单双引号的区别
<img width="443" alt="截屏2022-04-12 02 18 10" src="https://user-images.githubusercontent.com/97930502/162803848-c6299954-7920-4060-ba67-cd59da13fa77.png">

#### 9.定位函数 which
<img width="171" alt="截屏2022-04-12 02 19 39" src="https://user-images.githubusercontent.com/97930502/162804101-ad3a40ca-12dc-493e-bf6b-20a0178dfba2.png">

####  10. 继ls之后的rm具有特殊使用方式

<img width="438" alt="截屏2022-04-12 02 21 56" src="https://user-images.githubusercontent.com/97930502/162804443-273f388e-5e39-4cd2-8872-43742cc51e5b.png">
用!* 来继承前者ls中的输入表达式

#### 11. cd - 返回前者路径

#### 12.Ctrl-R可用于搜索最近执行的字符串，Ctrl-J退出搜索，Ctrl-C或Ctrl-G退出搜索并清除命令行

#### 13.用于修改命令行

<img width="446" alt="截屏2022-04-12 02 45 16" src="https://user-images.githubusercontent.com/97930502/162808126-c649fa2f-89fa-46cc-b067-6769823e9f48.png">

#### 14.代码式命令行，批量定义

<img width="469" alt="截屏2022-04-12 02 46 23" src="https://user-images.githubusercontent.com/97930502/162808303-78ddc2a2-d4fa-4585-ad7c-efb54edf4812.png">

#### 15.正则表达式，p75
<img width="462" alt="截屏2022-04-12 02 48 34" src="https://user-images.githubusercontent.com/97930502/162808653-85a89b69-dc78-489e-92aa-710a1cc44c0e.png">

#### 16.强制不用正则表达式的两种方法


<img width="272" alt="截屏2022-04-12 02 49 41" src="https://user-images.githubusercontent.com/97930502/162808829-e2237b82-5d4f-486b-8f08-9f6cbace5e5f.png">

#### 17.局部变量的特殊显示方式

#### 18.定时提醒功能，或许能举一反三一下
<img width="407" alt="截屏2022-04-12 03 03 49" src="https://user-images.githubusercontent.com/97930502/162811332-7e6020ab-9bb4-461e-9ec0-07c6c92f8dbd.png">
#### 19.批量检索，批量移动

<img width="257" alt="截屏2022-04-12 03 05 21" src="https://user-images.githubusercontent.com/97930502/162811565-56bb9cc9-8acd-41ef-9022-a040b368e962.png">

#### 20.占位符可替换输出

<img width="423" alt="截屏2022-04-12 03 06 39" src="https://user-images.githubusercontent.com/97930502/162811772-4e0873d6-2fd8-4aba-a284-062803e44fbf.png">

#### 21.将命令行放在后台处理（&）
<img width="228" alt="截屏2022-04-12 03 07 33" src="https://user-images.githubusercontent.com/97930502/162811910-5f93a2be-5f74-4b27-8556-4fda773019f3.png">

#### 22.删除时该注意的点（不只是rm，还有mv，cp，或者其他有可能会重写或移除文件的操作）
在这些操作前应先用echo，查看哪些文件会被影响

#### 23.随机输出 shuf 
#### 24.还可用命令行检查域名是否到期（感觉很实用）

#### 25.增强日期的输出的可读性
<img width="438" alt="截屏2022-04-12 03 13 53" src="https://user-images.githubusercontent.com/97930502/162812860-44c07c60-211c-4086-81d3-49fe31bc0a72.png">





