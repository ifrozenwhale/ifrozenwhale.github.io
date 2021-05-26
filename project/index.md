> [Github 地址](https://github.com/ifrozenwhale)

[toc]

# 编程练习

## 共享网络画板

一个网络画板，支持本地或者联机同步绘图，多种图形（任意曲线、圆点、直线、矩形、三角形），支持套索工具，样式填充、修改，形状调整、移动，支持 undo 与 redo，支持保存和导出图片等。[blog](http://frozenwhale.top/2021/05/26/gong-xiang-wang-luo-hua-ban/)

## 文件管理器

使用 Java 实现，支持文件树和文件列表，支持文件夹创建、删除、复制、粘贴、加密解密、压缩解压。[blog](http://frozenwhale.top/2021/05/26/file-manager/)

## 经典小游戏

### 扫雷 [code](https://github.com/ifrozenwhale/classic_game/tree/mine_sweeping)

### 贪吃蛇  [code](https://github.com/ifrozenwhale/classic_game/tree/snake)

### 五子棋  [code](https://github.com/ifrozenwhale/classic_game/tree/gobang)

### 计算器  [code](https://github.com/ifrozenwhale/classic_game/tree/calculator)

## ATM 模拟

初学面向对象时，使用 C++ 完成的，基于命令行的ATM模拟程序的设计。实现了分类账户（存款、取款），转账，交易记录，限额，未读消息等功能，实现了接口分离。[code](https://github.com/ifrozenwhale/Easy-ATM)

## 基于 CAS 的单点登录系统

基于 CAS （统一认证服务）流程，设计了自己的单点登录、登出系统。[code](https://github.com/ifrozenwhale/JAVAEE_SSO)

## 基于 servlet 的 MVC 框架实现

通过实现 IOC 容器，管理 Java Bean，使用 servlet 实现 GET/PUT 请求处理控制器，并提供 ModelView 模式或 Json 对象。[code](https://github.com/ifrozenwhale/myspringmvc)

# 科创与开发项目

## 基于数据挖掘的编程助手研究

基于开源项目搭建OJ系统，收集用户编程练习数据，二次开发，利用Java进行数据统计、用户行为分析，并使用微信小程序作为移动前端，进行数据可视化和互动，提供包括编程打卡、错题收集、习惯记录、任务计划等功能。[blog](http://frozenwhale.top/2021/05/26/wecode/)

## 基于树莓派的生活垃圾智能分类系统

负责基于迁移学习的垃圾识别分类算法实现，Web 交互式展示、电控通信以及树莓派部署[code](https://github.com/ifrozenwhale/raspberry-garbage-classfier)

## 基于百度API的人脸分析和轻社交

### 前端基于 Vue 的实现

基于百度API的人脸检测与分析，并语音播报。支持图片上传/即时拍照人脸特征分析展示，分析报告分享、发现、点赞、评论，用户关注、收藏等， 历史记录查询和编辑， 登录/未登录身份权限控制等。[code](https://github.com/ifrozenwhale/cquface-frontend)

### 后端 [基于 Django 的实现](https://github.com/ifrozenwhale/cquface)

# 课程实践

## **组成原理/体系结构** | 5级流水线多周期 CPU 的实现

使用Verilog实现了一个拥有五级流水线的MIPS CPU，包含基本指令和异常处理在内的57条
指令。实现了写回策略，四路组相连、伪LRU替换策略的cache缓存。

## **计算机网络** | Ethernet、IPv4 、udp 协议以及 IP-IP Tunnel 隧道协议实现

在Linux上使用C语言在数据链路层上通信，实现IPv4和UDP协议以及应用层封装。包括各层数据的校验，IP 分片与重组，最后为两个用户聊天的形式。[blog](http://frozenwhale.top/2021/05/26/ip-protocal/)

## **编译原理** | 简单 C 语言子集的玩具编译器]

目标做一个编译器，生成汇编指令并运行，目前到语义分析阶段。

已经实现的语法分析，支持全局变量声明定义，函数调用等常见的语法，语法分析基于 LL(1) 方案，自顶向下使用栈进行分析，生成一棵语法分析树[code](https://github.com/ifrozenwhale/Easy-C-Compiler)

## [**数据库系统** | 简单关系数据库元数据管理器](https://github.com/ifrozenwhale/metadata-manager)

## **数字逻辑** | 实验和课程设计

### 实验 [存储器 单双RAM / FIFO 阵列](https://github.com/ifrozenwhale/digital-logic/tree/master/memory)

### 实验 [摩尔状态机序列检测器](https://github.com/ifrozenwhale/digital-logic/tree/master/sequence_detection)

### 项目 [电子密码锁设计与实现](https://github.com/ifrozenwhale/digital-logic/tree/master/sequence_detection)

# 大数据与机器学习

## 基于 Spark 的电影推荐和分析系统

在完全分布式 Spark 平台上，分布式存储数据文件，利用 MongoDB 保存分析结果。基于 ALS 协同过滤进行用户电影推荐，通过 TF-IDF 调整标签权重，计算特征向量，基于内容推荐。搭建在线展示平台，交互式操作。[code](https://github.com/ifrozenwhale/bigdata-movie-recommend)

## 最优化方法

### 单纯形

实现了单纯形法（大 M 法，对偶单纯形）[code](https://github.com/ifrozenwhale/Optimization_algorithm/blob/master/simplex_method)

### PHR 算法

求解约束优化问题。采用传统算法 PHR 算法。混合约束问题的乘子法，结合了拉格朗日乘子和罚函数，构造无约束的辅助函数。作为求解基础，还实现了求解无约束混合优化问题的 dpf 算法，一维搜索优化问题的黄金分割法。

## 机器学习基础算法

### 二分类与多分类 [Logistics 回归](https://github.com/ifrozenwhale/machine-learning-code/tree/master/exp1)

### 离散和连续 [决策树 |分类树与回归树）](https://github.com/ifrozenwhale/machine-learning-code/tree/master/exp2)

## 大数据处理实验

### 准备工作 [数据清洗和预处理](https://github.com/ifrozenwhale/bigdata-homework/tree/master/lab1)

### 推荐算法 [SVD 奇异值分解](https://github.com/ifrozenwhale/bigdata-homework/tree/master/lab1)

### 文本分析 [TF-IDF](https://github.com/ifrozenwhale/bigdata-homework/tree/master/lab3)

## 数学建模

### 网络建模 [音乐影响网络](https://github.com/ifrozenwhale/2021icm-problemD)

### 元胞自动机 | 计算机模拟 [卢浮宫计算模拟](https://github.com/ifrozenwhale/2019icm-problemD)

# 其他

## [不等圆的不重叠随机排列](https://github.com/ifrozenwhale/non-overlapping-circle)

不等圆的packing问题，基于概率策略化的随机游走。在缝隙处可额外进行补充，使更加丰满。

## [自定义轮廓的随机纹路生成](https://github.com/ifrozenwhale/randomPicture)

体现了数学中的随机美。可以给出图形，在图形内基于 Voronoi 图生成随机纹路，可以进行颜色填充。









