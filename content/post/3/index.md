---
title: 针对“低慢小”目标的多无人机协同反制技术研究
subtitle: 浙江省自然科学基金

# Summary for listings and search engines
summary: <b>浙江省自然科学基金</b> <br> 
        针对节点攻击与损毁、通信时延下的多无人机编队跟踪控制问题，设计了基于极值剔除的控制策略和鲁棒拓扑构建方法，并通过实物实验验证了算法的有效性和可行性

# # Link this post with a project
# projects: []

# Date published
date: 2023-06-01

# # Date updated
# lastmod: '2019.09 - 2022.09'

# Is this an unpublished draft?
# draft: false

# Show this page in the Featured widget?
# featured: false

# url_video: 'https://www.bilibili.com/video/BV1XG4y1k7MX'

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.

image:
  caption: ''
  focal_point: ''
  placement: 2
  preview_only: false
---

<img src="../post_image/byz架构.png width="70%""/> 

* **研究问题**：以军事要地等场所保卫为背景，负责调研解决节点攻击与损毁等约束下的多无人机协同控制问题。
* **理论研究**：对于存在恶意节点、机动性领导者和通信时延的一阶及二阶离散时间多智能体系统，首先基于传统鲁棒拓扑概念，为一阶多智能体系统设计了弹性控制器，推导出了实现有界误差一致的条件。接下来，由于推得的误差界随着系统规模以阶乘速度增加，我们提出了一种新的拓扑结构并对控制器进行改进，将误差界增长速度减小至线性。进一步，以前述结果为基础，设计了一种基于领导者状态估计器的控制架构来解决二阶多无人机系统的弹性编队跟踪控制问题。
* **实验验证**：通过对比仿真实验以及基于UGV和UAV的实物实验，验证了控制方法的有效性和工程可行性。