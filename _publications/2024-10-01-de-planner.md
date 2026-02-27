---
title: "DE-Planner: 一种面向无人机导航的高效端到端动态规划器"
layout: publication-nerfies
collection: publications
permalink: /publication/2024-de-planner
date: 2024-10-01
teaser: "de-planner-teaser.png"
teaser_caption: "DE-Planner系统框架图，展示了从深度相机输入到无人机路径规划的完整流程"

# 简短作者列表（显示在主页卡片）
authors_short: "姚嘉伟, 贾彦鹏, 曹风魁*, 孙平, 朱先圆, 王挺"

# 完整作者列表（显示在详情页）
authors:
  - name: "姚嘉伟"
    url: ""
    affiliation: "1"
  - name: "贾彦鹏"
    url: ""
    affiliation: "1"
  - name: "曹风魁"
    url: ""
    affiliation: "1"
  - name: "孙平"
    url: ""
    affiliation: "1"
  - name: "朱先圆"
    url: ""
    affiliation: "1"
  - name: "王挺"
    url: ""
    affiliation: "1"

affiliations:
  - "Shenyang Institute of Automation, Chinese Academy of Sciences"

venue: "机器人"

# 链接
paperurl: ""
arxiv: ""
code: ""
video: ""
project: ""

# 摘要
abstract: |
  提出了一种基于蒙特卡洛聚类跟踪的算法框架对深度相机输入的点云图像进行处理，并将结果反馈给神经网络，以增强对动态障碍物的识别和生成较为准确的路径。
  
  提出了混合轨迹成本策略和动态加权的终端感知机制，解决了对局部危险区域不敏感的问题，增强了目标导向，使得无人机在飞行时更加安全高效。

# 亮点（显示在主页卡片）
highlights:
  - "提出了一种基于蒙特卡洛聚类跟踪的算法框架对深度相机输入的点云图像进行处理，并将结果反馈给神经网络，以增强对动态障碍物的识别和生成较为准确的路径"
  - "提出了混合轨迹成本策略和动态加权的终端感知机制，解决了对局部危险区域不敏感的问题，增强了目标导向，使得无人机在飞行时更加安全高效"

# BibTeX
bibtex: |
  @article{yao2024deplanner,
    author    = {Yao, Jiawei and Jia, Yanpeng and Cao, Fengkui and Sun, Ping and Zhu, Xianyuan and Wang, Ting},
    title     = {DE-Planner: An Efficient End-to-End Dynamic Planner for UAV Navigation},
    journal   = {机器人},
    year      = {2024},
  }
---

## 方法概述

本文提出的DE-Planner是一种面向无人机导航的高效端到端动态规划器。主要创新点包括：

### 1. 蒙特卡洛聚类跟踪

我们设计了一种基于蒙特卡洛聚类跟踪的算法框架，能够有效处理深度相机输入的点云数据，实现对动态障碍物的准确识别。

### 2. 混合轨迹成本策略

通过混合轨迹成本策略和动态加权的终端感知机制，解决了传统方法对局部危险区域不敏感的问题。

### 3. 端到端架构

整个系统采用端到端的神经网络架构，从原始传感器数据直接输出安全的飞行轨迹。

## 实验结果

我们在多个仿真和真实场景中验证了所提方法的有效性，实验结果表明DE-Planner在动态环境中具有更高的安全性和效率。
