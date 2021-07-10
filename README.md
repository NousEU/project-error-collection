# project-error-collection
# 软件部工作安排

## 部门结构

- 部门管理：闻兰
- 研究生师兄：苏俊杰（后端负责人）、王一辰（自适应评价系统）、潘伟健、陈锐鑫（软件负责人）
- 部长：何宝康
- 副部长：郭俊毅
- 前端：
  - 19级：郭俊毅、何宝康、陈景鑫（负责官网项目的前端）
  - 20级：欧阳子儒、黄国棠、何翠铷

- 后端：
  - 19级：陈树鹏、潘嘉权



## 新软件项目工作安排

***当前已发布第一个版本，请勿直接修改master分支，基于dev分支进行开发***

:one: 调用对应的后端API完成相应功能，需要写的功能已经在代码中标记TODO:zap:（参考完成时间：7.20）

- API接口文档：https://docs.apipost.cn/preview/fea9c90ffe36ecda/c35839a7697a165d?target_id=27aabcf3-9a59-49c3-bc76-bbcff7741d93#97f94efe-b025-4fda-b9a6-2f8cf9d9b7c9
- 模拟接口库（即在本机上开通一个端口作为服务器，访问对应端口即可拿到数据，以此实现前后端分离开发的模拟）说明：https://juejin.cn/post/6844904040405417991

:two: 阅读blockly源码并能进行修改，添加保存函数块的功能到代码中（建议修改procedure中的menu/mutation）:zap:（参考完成时间：7.20）

- 提高编码能力，加深对js的理解
- 直接google或者百度即可进入blockly官网
- 通过官网给定的一些方式实现对源码的重写是最好的
- 增加toolbox类型重写官方的默认类型参考：
  - https://github.com/google/blockly-samples/tree/master/plugins/continuous-toolbox/src
  - https://zhuanlan.zhihu.com/p/365779081
- 重写部分方法参考（根据官方提示进行override，比如项目中对blockly.prompt的重写）
  - 进入blockly官网查看支持的重写或者类型注册

:three: 理解与案例部的协作交互，原理就是通过fs扫描对应路径的文件夹进行内容的读取，能够完成:zap:（参考完成实现：7.10）

- 请整理交互文件中内容，根据项目开发情况进行修改，及时与案例部沟通

:four: 将案例部开发的Windows版本的仿真器兼容，实现仿真功能（最好用子线程方式将仿真功能内置到软件左侧，而不是重新打开一个进程窗口）

:five: 项目代码统一风格，根据最开始的培训内容中的配置环境结合项目环境进行代码统一

:six: 理解项目脚手架的工作流程，打包需要注意的事项，优化安装过程



## 官网项目前端工作安排

***当前已经发布第二个版本，请勿直接修改master分支，基于dev分支进行开发***

:one: 请各位同学按照考试之前的安排在自己的分支上完成任务:zap:

- 大家不用着急实现功能，先进行学习，可以我们近期购买的书籍进行学习，尝试自己建立一个分支去修改代码，最后确认功能完善后再合并到dev

:two: 完成软件帮助文档页面的开发（没有分配到任务的同学可以去做这个任务，软件的使用说明书去找案例部拿，新增加一个router进行开发，也可以直接提供说明书的下载链接给用户下载）（建议列出比较常见的功能，别的让他们去下载说明书）:zap:



## 项目后端工作安排

两位后端开发的同学按照俊杰师兄的知道进行学习和开发



## 关于新同学的培训和学习——前端方面

建议直接通过上手官网项目（自己建一个分支去写）+看书理解网页开发技能方式进行学习

书籍观看顺序

1. 《DOM编程艺术》（入门好书）
2. 《Css选择器》（选择性看，理解各种选择器，一些常见的属性即可）
3. 《JavaScript高级教程第四版》（选择性看，可以按照之前培训的知识点进行一遍重温）
4. 《图解HTTP》《网络是怎样连接的》（计网方面内容，看时间深入学习，理解网络接口的概念）
5. 《深入浅出React》

结合团队项目以及就业形势给出的前端技能树/知识点

![前端技能树](前端开发学习路线(知识点)梳理.jpg)

**上面是一个前端技能树，但是我们并不需要全部都学习，结合项目需要进行学习即可（B站是个好地方，大家可以在上面直接进行知识点的检索）**

1. 基础编码能力，这个大家多动手写代码就可以了，一些通用的计算机知识要有（前端、后端工作原理，编程语言都通用的知识）
2. 计算机网络、操作系统（选择性理解）
3. GIT
4. HTML、CSS、JavaScript
5. node.js（服务器上的JS、可以理解为类似Python一样的一个JS脚本语言）
6. 理解DOM编程，理解浏览器模型
7. 能够写React代码，能理解React的工作模式
8. 理解一些通用的库，比如Redux、loadsh
9. 理解包管理器webpack的工作流程，（npm、yarn是node.js的包管理工具）（建议去B站找视频学习）
10. **算法（刷题）**

**一些参考网站**

- https://zh.javascript.info/
- https://es6.ruanyifeng.com/
- https://react.iamkasong.com/
- https://www.yuque.com/books/share/2d7c050a-07c4-40a8-b5fb-0f8d80f47df1/dz7o1g#thLKp



## 一些目前就业形势的建议

推荐网站：

- https://www.nowcoder.com/（多浏览确定就业方向和职业规划）
- https://leetcode-cn.com/（算法刷题）
- https://juejin.cn/

有本科就业想法或者正在纠结的同学可以多浏览上面的网站，对就业的一个职业规划会有更加深刻的了解，另外大家也可以从以下平台了解就业/读研形式

- 知乎
- 脉脉（互联网薪资、offer好坏）
- offershow（一个看校招薪资的平台）
- 一些公众号（华南理工大学就业指导中心等）



算法是我们非计算机科班同学的一个弱项，大家可以适当去leetcode和牛客上面刷题，多总结多练习（算法过了很多面试都会过）



## 部门书籍

为软件部持续发展，大家要多扣准哥的经费买书，我们不用经费的话也是白白浪费大创项目的经费，因为我们一般只能买书哈哈哈

1. 《DOM编程艺术》
2. 《Css选择器》
3. 《JavaScript高级教程第四版》
4. 《图解HTTP》
5. 《深入浅出React》

后续需要添加

1. 关于webpack的书
2. 《你不知道的JavaScript》
3. 算法：《算法》、《剑指offer》、《大话数据结构》
4. 操作系统：《现代操作系统》、《自顶向下的计算机系统》、一些Linux和shell脚本的书
5. 设计模式

