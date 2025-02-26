# 中南大学数学与统计学院本科生手册

中南大学“数院之光”全体成员编制

<!-- Markdown手动目录 -->

## 目录

- [中南大学数学与统计学院本科生手册](#中南大学数学与统计学院本科生手册)
  - [目录](#目录)
  - [简介](#简介)
  - [专业：数学与应用数学](#专业数学与应用数学)
  - [专业：统计学](#专业统计学)
  - [专业：信息与计算科学](#专业信息与计算科学)
    - [专业介绍](#专业介绍)
    - [课程简介](#课程简介)
    - [升学方向](#升学方向)
  - [通用](#通用)
  - [附录](#附录)
    - [文件编篡标准方案](#文件编篡标准方案)
      - [封面与目录](#封面与目录)
      - [标题](#标题)
      - [正文](#正文)
      - [图片与表格](#图片与表格)
      - [GitHub Repository 的维护](#github-repository-的维护)
        - [如果您从未了解过如何使用Git](#如果您从未了解过如何使用git)
        - [如果您对GitHub有所了解，并有兴趣进一步学习更一般的使用方法](#如果您对github有所了解并有兴趣进一步学习更一般的使用方法)
        - [有关Markdown笔记](#有关markdown笔记)
      - [附件范例](#附件范例)

## 简介

此部分对数院之光以及此手册作简单介绍。

## 专业：数学与应用数学

## 专业：统计学

## 专业：信息与计算科学

### 专业介绍

在实际工程中，许多问题无法得出解析解，信息与计算科学专业就是学习如何利用计算机数值求解实际问题的专业。本专业培养具有良好的道德、科学与文化素养，掌握数学科学的基本理论、方法与技能，能够运用数学知识和数学技术解决实际问题，能够适应数学与科技发展需求进行知识更新，能够在数学及相关领域从事科学研究或在科技、教育、信息产业、经济金融、行政管理等部门从事研究、教学、应用开发和管理等工作的人才。

### 课程简介

信息与计算科学专业的学习课程除了数学分析与高等代数两门基础课以外，主干课程还有数值分析，最优化理论，运筹学，偏微分方程数值解法，数据结构与算法等。由于绝大部分课程涉及计算机实践的内容，因此还需要掌握至少一门能够进行数值实践的编程语言(例如MATLAB、Python等)。除此之外建议在学有余力的同时了解一些前沿数学与计算机交叉内容，例如机器学习与深度学习理论、科学计算等，尽管现在机器学习作为计算机的大热门方向，但其基础仍是数学与统计学的相关理论。

### 升学方向

- 数学、统计学相关
  - 计算数学：最优化方法、数值计算方法、微分方程数值解法、大规模科学计算
  - 统计学：数理统计、生物统计、应用概率、应用统计、金融工程
- 计算机科学相关
  - 计算机应用：计算机图形学、计算机视觉、密码学与信息安全
  - 人工智能：机器学习、深度学习、模式识别
- 其他方向
  - 控制科学与工程
  - 信息与通信工程
  - ......

## 通用

## 附录

### 文件编篡标准方案

此部分明确一些文件编写的标准。

#### 封面与目录

#### 标题

#### 正文

#### 图片与表格

插入图片：
![插入图片范例](/Appendices/Figures/数院之光-透明.png)

插入表格：

| 表头 | 表头 | 表头 |
| ---| --- | --- |
| 单元格 | 内容 | 单元格 |
| 单元格 | 单元格 | 单元格 |

#### GitHub Repository 的维护

在这一部分我们将会简单说明如何通过GitHub对这个项目做出自己的一份贡献。

##### 如果您从未了解过如何使用Git

不必担心，直接通过GitHub网站对文件作出修改也是很容易的，我们接下来就会以本手册为例子来看看如何修改您正在看的这个Markdown笔记文件（[SMS-CSU-Undergraduate-Handbook/blob/main/Markdown/main_Markdown.md](https://github.com/Shen-Cao/SMS-CSU-Undergraduate-Handbook/blob/main/Markdown/main_Markdown.md)）。

>不过如果您从未接触过Git，对于GitHub的了解也至多限于听说过的程度，那么，参与本手册的撰写很有可能是您首次接触除了CSDN等中国大陆开发者社区之外的、具有更高互动性的开发者社区。在此**强烈建议**您阅读一下这篇面对开发者社群们[**提问的智慧**](https://github.com/ryanhanwu/How-To-Ask-Questions-The-Smart-Way/blob/main/README-zh_CN.md)，这应该会让您更愉快地与开发者社区互动并融入其中。

首先，在查看本文档的界面通过右上角的编辑按键进入编辑界面

![查看你要修改的文档](/Appendices/Screenshots-GitHubTutorial/1.png)

然后，在编辑界面通过文本编辑器进行修改。修改后不要忘记通过预览界面检查是否有错误，比如超链接插入失败，或者图片插入失败等等

![对文档作出修改](/Appendices/Screenshots-GitHubTutorial/2.png)

最后提交你的修改。注意，尽量不要直接提交修改到main分支，通过创建一个修改后的分支并发起pull request的方法是更一般、更好用的选择，这允许我们进行更完善的分支管理。

![提交你的修改](/Appendices/Screenshots-GitHubTutorial/3.png)

注意，如果您选择了生成分支并pull request的话，那么您的修改一般不会直接就应用在主分支里，所以您无法直接看到自己作出的修改。不用着急，回到[仓库根目录](https://github.com/Shen-Cao/SMS-CSU-Undergraduate-Handbook)，找到pull request一栏，在那里面找到您创建的分支，您就能看见自己做出的修改以及它们是否已被采纳并合并入主分支。

##### 如果您对GitHub有所了解，并有兴趣进一步学习更一般的使用方法

既然如此，我们不妨假设您面对新的工具已经有一定查阅相关使用说明和手册的能力。那么，对于GitHub的操作方法您可以参考[GitHub官方的手册](https://docs.github.com/zh)。在简单查看了[入门教程](https://docs.github.com/zh/get-started)、[存储库](https://docs.github.com/zh/repositories)相关信息以及[拉取请求](https://docs.github.com/zh/pull-requests)操作后，您应该就可以直接上手对自己做出的变动拉取请求。

如果您想再进一步，那么可以[配置您本地开发的Git环境](https://docs.github.com/zh/get-started/getting-started-with-git/set-up-git)。更多有关本地存储库、提交、上传和合并更改等分支管理操作可以参考[这个教程](https://www.runoob.com/git/git-tutorial.html)。

##### 有关Markdown笔记

本手册采用LaTeX和Markdown两种语言来编写。Markdown是一种非常方便的笔记语言，网络上也有大量相关教程，比如[官方教程](https://markdown.com.cn/)、[这个网站](https://www.runoob.com/markdown/md-tutorial.html)还有[这个快速入门指南](https://markdown101.github.io/getting-started/)等，在此仅列出几项供参考。

#### 附件范例
