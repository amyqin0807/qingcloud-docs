---
title: "数据开发概述"
description: 本小节主要介绍数据开发流程、作业依赖的网络资源、支持开发的作业模式、开发过程中的资源管理和使用说明等。 
keywords: 大数据工作台,操作指南,数据开发
weight: 10
collapsible: false
draft: false
---

数据开发模块提供了大数据开发可视化界面，包括大数据开发、大数据调度，极大降低了大数据处理难度，快速帮助您构建大数据处理中心。

本小节主要介绍数据开发流程、作业依赖的网络资源、支持开发的作业模式、开发过程中的资源管理和使用说明等。

## 主要功能

在数据开发模块，您可以进行实时作业开发、作业环境配置、作业调度、网络管理、资源管理、函数管理等操作，完成对数据的分析处理流程。

| <span style="display:inline-block;width:120px">支持的功能</span>  | <span style="display:inline-block;width:540px">说明</span>  |
| :------------- | ---------------------------------------------------------- |
| 实时计算     | <li>作业开发：目前支持 SQL 模式、代码开发模式两种作业类型。<li>运行参数：对作业的环境依赖进行配置。<li>作业调度：管理作业的调度参数，包括时间属性、并发策略等参数。   |
| 网络配置     | 对计算集群所依赖的网络进行创建、管理。                            |
| 计算集群     | 对作业会使用到的 Flink 计算集群进行创建、管理。                         |
| 资源管理     | 支持统一管理在作业开发中使用到的 Jar 类型的资源。                         |
