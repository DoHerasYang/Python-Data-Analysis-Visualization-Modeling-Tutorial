# Python-数据分析、挖掘、可视化讲解与实战

---

> 本项目的所有知识、代码内容基于2021年暑期实习生的数据处理分析实习生的相关数据分析要求内容改进和整理出来的可执行代码流程和相关数据分析概念、以及建模概念；
>
> 本项目的所有的知识内容体系顺序大体参考书籍：**《Python数据分析与挖掘实战》- 张良均 谭立云 刘明军 江建明 所著**;
>
> 相关的公开数据集引用请参考下边数据引用章节的详细链接以及相关使用规则；
>
> 所有的代码内容遵循： **MIT 开源协议**

---

[TOC]

---

## 0. 项目简介

### 0.1 项目文件适用对象

本项目以相关 `Jupyter Notebook` 文件为主，参考《Python数据分析与挖掘实战》的知识讲解路线，结合网上的相关的开源免费数据集，构建了：利用`Python`作为编程语言的数据分析、挖掘、可视化学习路线；

每一个 `Jupyter Notebook` 文件以讲解相关数据分析、挖掘概念为主，配合相关概念，利用 `Pandas`、`Numpy`、`Matplotlib` 、`statsmodels`等著名开源数据处理、分析模块库，采用“边讲解概念，边进行演示”的理念构建完整的数据分析学习路线；

本项目的相关内容<u>适用的群体</u>：**Python语言编程初学者**、**数据分析领域初学者**、**想要从事数据挖掘、可视化领域初学者**、**大中院校的计算机相关专业学生**。

---

### 0.2 项目内容概要

本项目设计的相关内容偏向于零基础的编程人员、从来没有接触过使用Python作为数据分析、数据可视化编程语言的编程人员，因此所有的内容在前期内容准备中更偏向于数据分析以及可视化的基础内容，**着重于解决日常数据分析当中常用的技巧以及相关代码实现**；

目前本项目并没有针对一些复杂的建模方法、以及相关算法进行过多的介绍，但此项目为一个**长期更新项目**，旨在为更多需要使用 Python 作为主力语言的入门者提供编程、数据分析相关内容的入门指导以及进阶的相关思路；

---

### 0.3 相关背景资料

#### 0.3.1 推荐免费的数据平台

+ 数据源查找：
  + **谷歌的开源数据搜索引擎**(Google Data Set Research)： https://datasetsearch.research.google.com/
  + **Kaggle** (在上边当中有很多数据分析的项目实例，不仅仅提供数据集，也提供相关的分析思路 )：https://www.kaggle.com/
+ 金融大数据免费平台：
  + **Tushare** - 强大的金融数据免费平台，但是有些数据需要一定积分才能使用，总体来说很OK，注册链接：https://tushare.pro/register?reg=457661

#### 0.3.2 书籍以及相关知识链接

本项目的知识路径参考：

+ 《Python数据分析与挖掘实战》- 张良均 谭立云 刘明军 江建明 所著
+ 《利用Python进行数据分析(Python For Data Analysis中文版)》 - Wes McKinney著 唐学韬译

其他参考链接都已经在各自 `Jupyter Notebook` 的相关内容下边标注出来，请阅读具体文档进行参考；

---

### 0.4 项目未来计划

本项目目前的相关内容也存在诸多不足，欢迎大家批评指正，对于相关问题我也会及时进行恢复，如果你觉得内容有更好的改进之处，请 Fork 并提交，我会及时处理，或者邀请您进入到当前的创作小组当中；

**对于目前项目的不足，简单进行描述如下**：

+ 对于 Python 的基础编程内容没有过多的涉及，对于初学者来说并不是非常友好；
+ 对于 Python 中常用的数据分析工具 - `pandas` / Nnumpy` / `Matplotlib 没有进行介绍，而是直接上手开始演示，对于初学者并不是非常友好； 
+ 对于 数据分析的一些知识点没有深入的讨论和研究，在一些非常简单的概念中缺少代码和数据的演示；
+ 需要对一些复杂的算法、建模模型进行更多的讲解和资料补充；

**未来该项目大的发展方向**：

+ 将项目不仅仅放在本地可以执行，更需要发挥云的相关作用，可以在网站上看到本项目的内容；
+ 对于目前主流、尖端的相关数据分析算法进行更新；

感谢每一位对开源知识社区的贡献的Coder！为了实现知识平等我们都在努力着！

在未来，自己也会对这个项目进行缓慢不停止的更新，数据分析是一切 IT 的基础。我坚信每天小的尝试、进步都会带来深刻的改变；

<br>

<br>

## 1. 项目文件结构内容

### 1.1 Markdonw 学习内容

+ 安装 Windows 上的免费的Markdown的编辑器 - Typora；
+ 了解常用的 Markdown 语法，并能够在 Markdown 的文件中 插入图片、对所撰写的内容进行编号让整个内容更充实、条理清晰；
+ 了解 Latex 语法的相关常用用法，并能够通过 Latex 语法在 Markdown 文件中插入数学公式 ；
+ 了解怎么将 Markdown 文件导出成 pdf 文件 方便浏览；

### 1.2 Anaconda / Jupyter Notebook

+ 安装 Anaconda 到你的机器上，并且掌握Anaconda创建env的相关技巧，了解如何使用 Ananconda 来 管理安装包文件：
  + 在 Anaconda 中能够创建 virtualenv 并下载、安装库 - Packages 到 env 环境中；
  + 在 Anaconda 中安装 Jupyter Notebook 程序，并使用 Ananconda 管理 Jupyter Notebook Kernel；
  + 在 Anaconda 中的 env 环境中配置 Jypyter Notebook 的相关环境；
  + 在 Anaconda 中能够管理 virtualenv 的相关 Package，可以做到对 Packages 的相关操作升级；
+ Jypyter Notebook 相关学习内容
  + 使用 Jupyter Notebook 打开、创建、运行 `.ipynb`  后缀文件；
  + 了解 Jupyter Notebook 作为 可交互式 IDE 在 Python 进行数据处理时的优点；
  + 可以通过 Jupyter Notebook 的界面与 Anaconda 环境进行交互 - 安装 Python 的第三方开源软件包；
  + 了解 Jupyter Notebook 的 Cell Type，并能够在 Jupyter Notebook 中完成 Markdown 的撰写，
  + 使用 Jupyte NoteBook 运行 Python 代码 ；
  + 使用 Jupyter Notebook 编写 MarkDown 文本并使用 Latex 语法 来嵌入数学公式；

### 1.3 Python 的学习

+ 在前期对相关的 Python基础语法 有一定的了解：
  + 作用域、Python 代码文件的编写规范的了解；
  + 了解 Python 的基础元素： 模块、命令等相关概念；
  + 了解如何声明、命令；
  + 了解 Python 的基础数据结构：
    + 列表 / 字典 / 元祖等数据分析中常用、必须的数据结构和相关内置函数能够做到简单使用；
+ Python 的进阶部分
  + 了解如何声明、定义 Python 的函数来进行封装相关的功能；
  + 了解 Python 的语法糖 (分片，lambda函数等特殊的Python语法)
  + 了解 Python 重要的 GIL锁、多线程的相关概念，已经应用场景；

### 1.4 利用 Python 进行数据分析

#### 数据探索

+ 了解数据集中的“脏数据”概念，初步了解如何处理数据集中的脏数据；
+ 了解数据集中的异常值的概念，什么是离群点，掌握常见的分析方法： 简单量统计法、3$\sigma$​​原则、箱型图，掌握如何通过 `matplotlib` 函数来绘制箱型图；
+ 了解数据探索中数据特征分析：
  + 在定量数据集中使用分布分析方法：
    + 极差法
    + 分组法
  + 定性数据集中的数据特征分析方法：
    + 饼图
    + 条形图
    + 折线图
  + 在不同时间维度中，使用对比分析法分析数据集：
    + 绝对数比较
    + 相对数比较
  + 统计量分析
    + 集中趋势分析
      + 中值法
      + 平均数法：均值、加权平均值等概念
      + 众数
    + 离中趋势分析
      + 标准差（方差）
      + 极差
      + 四分位间距
  + 周期性分析
  + 贡献度分析：帕累托分析方法/帕累托图
  + 相关性分析：
    + `Pearson` 相关系数
    + `Spearman` 相关系数

#### 数据预处理部分

+ 0.数据预处理的简介：
  + 数据预处理的目的
  + 数据预处理的相关技术；
+ 1.数据清洗：
  + 缺失值处理： 拉格朗日法、分段插值法、牛顿插值法、样条插值法等概念以及代码实现
  + 异常值处理的常见方法
+ 2.数据集成：
  + 实体识别方法
  + 冗余属性识别方法
  + 数据变换
  + 简单函数变换
  + 规范化（归一化）： 最小值-最大值标准化、零-均值标准化、小数定标准化；
  + 连续属性离散化：等宽法、等频法、基于聚类的分析方法；
+ 3.数据规约：
  + 数据规约的意义和定义
  + 属性规约：
    + PCA  主成成分分析法

#### 数据建模 - 时序模型

+ 0.时序模型的相关概念
  + 时序模型的概念、影响时序模型的因素；
  + 常见的模型评价方法；
+ 1.时间序列算法：
  + 组合模型概念
  + MA模型
  + ARMA模型
  + ARIMA模型
  + ARCH模型
  + GARCH模型方法
+ 2.时间序列的预处理：
  + 纯随机性检验
  + 平稳性检验
    + 平稳序列的定义
    + 平稳序列的检测方法：时序图检验、自相关图检验、单位根检验；
+ 3.平稳时间序列分析模型
  + 自回归移动模型的概念
  + 自回归移动模型的分类：
    + AR模型
    + MA模型
    + ARMA模型
+ 4.时间序列建模流程
  + 平稳时间序列建模流程；
  + 非平稳时间序列建模流程；
+ 5.时间序列流程-常用演示流程
  + 掌握对时间序列的平稳检测方法以及判定标准 - ADF值法；
  + 掌握对非平稳的时间序列需要进行差分运算成为平稳的时间序列；
  + 掌握验证平稳的时间序列是否是白噪声序列的方法；
  + 掌握如何选取对应的ARMA模型进行建模；
  + 掌握并运用常见的模型评价方法；

<br>

---

## 2. 数据集引用

在本项目中所有的数据集来源都遵循相关数据集的使用许可协议，如果你想要在自己的项目引用，请一定要遵循数据集的使用许可；

+ LendingClub: loan.csv 数据：
  + The data covers the 9,578 loans funded by the platform between May 2007 and February 2010. The interest rate is provided to us for each borrower. 
+ SMiLer: A Semi-Lazy Time Series Prediction System for Sensors - [zhoujingbo](https://github.com/SeSaMe-NUS/Smiler/commits?author=zhoujingbo)：
  + https://github.com/SeSaMe-NUS/Smiler
+ 《利用Pandas进行数据分析》书本自带的数据集：

  + https://github.com/wen-fei/PythonForDataAnalysis/blob/master/ch08/tips.csv

+ Tushare 日线行情 - `daily `  
  + https://tushare.pro/document/2?doc_id=27

---

## 3. 相关资料分享

在这里分享 Python 作为数据分析语言的相关参考书链接：

+ Python 相关参考电子书链接：https://www.aliyundrive.com/s/pWUjdaVLhhz









