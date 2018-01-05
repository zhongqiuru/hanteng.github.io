---
layout: article
title:  "Tableau信息可视化"
date:   2018-01-03 08:45:50 +0800
categories: notes_tech tableau posts infovis
image:
  teaser: Jekyll_skinny_bones.jpg
  feature: Jekyll_skinny_bones.jpg
---


{% include toc.html %}

# Tableau的使用
### Tableau设计流程
连接到数据源。

构建数据视图

创建工作表

创建和组织仪表板

创建故事

### Tableau数据源
Tableau可以连接到广泛使用的所有常用数据源.Tableau的本机连接器可以连接到以下类型的数据源。
文件系统，如CSV，Excel等。

关系系统如Oracle，Sql Server，DB2等。

云系统如Windows Azure，Google BigQuery等。

其他源使用ODBC。
### Tableau图表类型
- 条形图
- 折线图
- 饼图
- 散点图
- 气泡图
- 树图
- 甘特图
- 直方图
- 盒须图
- 面积图
- 地图
- 突出显示表
- 标靶图
### 标记的堆叠
给定视图中控制标记是堆叠还是重叠。“分析”—“堆叠标记”。默认是自动，也可以手动选择“开”/“关”。

堆叠条视图 维度在列，度量在行，按维度对数据进行颜色编码。标记类型是条，Tableau自动堆叠，这意味着标记合并回执，每个条中每个堆叠区段的高度表示该区段的值。如果解除标记堆叠，标记全部从水平轴开始，但是仍可查看单个条区段。值得注意的是，由于解除堆叠的标记会重叠，因而视图中的条区段可能隐藏在其他区段后面。

显示字段标签，“分析”—“表布局”—“显示行字段标签”/“显示列字段标签”