---
title: 区域信息采集多智能体控制模型
subtitle: “挑战杯”科技竞赛项目（特等奖，第二参与人）

# Summary for listings and search engines
summary: <b>“挑战杯”科技竞赛项目（特等奖，第二参与人）</b> <br> 
        针对未知海域区域覆盖及可疑目标探查任务，设计了含覆盖路径规划、动态任务分配、避碰避撞的多智能体协同决策控制算法，于全国数十名队伍中获得了第二名

# # Link this post with a project
# projects: []

# Date published
date: 2023-10-01

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

<img src="../post_image/byz架构.png" width="70%"/> 

* **研究问题**：项目以未知海域探测任务为背景，要求设计多智能体协同策略，实现对未知区域的覆盖和可疑目标的探查，同时智能体需要避碰避撞并规避禁航区。
* **解决方案**：设计了含覆盖路径规划、动态任务分配、避碰避撞、探查路径规划等模块的多智能体协同决策控制方案；建立了优化全局耗时的瓶颈分配数学模型。
* **作品成果**：实现了在约40分钟内，使用8艘无人艇，零碰撞地完成了对于3x5海里区域的覆盖和35个目标的探查，以高指标在全国数十名队伍中获得了第二名。