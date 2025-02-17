---

title: "步骤2：加载硬盘"
description: 本小节主要介绍将云硬盘加载到云服务器的相关操作。
draft: false
weight: 30
keyword: 云计算, 青云, QingCloud, 云硬盘,云服务,加载
---

## 操作场景

硬盘创建后，需要加载到云服务器才可使用。

本节将指导用户如何将一块新创建且未挂载的硬盘加载到云服务器上。加载操作可以在硬盘页面中执行，也可在云服务器页面中执行。

> **说明：**  
>
> 若您在购买硬盘时，已经设置了挂载到云服务器，则可略过本节，直接执行[步骤3: 初始化硬盘](/storage/disk/quickstart/init/init_start/)。

## 在硬盘页面加载

1. 登录 [QingCloud 管理控制台](https://console.qingcloud.com/login)。

2. 在控制台导航栏中，选择**产品与服务** > **存储服务** > **云硬盘**，进入**硬盘**页面。

3. 在硬盘列表，勾选需要加载至服务器的硬盘，然后单击**更多操作**，选择**加载硬盘到云服务器**。
   ![load_1](/storage/disk/_images/load_1.png)

4. 弹出**选择云服务器**界面，界面中将显示可加载的云服务器。
   ![load_2](/storage/disk/_images/load_2.png)

5. 选中需要加载硬盘的云服务器，单击**提交**。

   加载成功后，可以在硬盘列表中看到硬盘状态从**可用**变为**使用中**。
   ![load_3](/storage/disk/_images/load_3.png)

## 在云服务器页面加载

1. 登录 [QingCloud 管理控制台](https://console.qingcloud.com/login)。

2. 在控制台导航栏中，选择**产品与服务** > **计算** > **云服务器**，进入**云服务器**页面。

3. 在云服务器列表中，找到需要加载硬盘的服务器并勾选。

4. 单击**更多操作**，选择**加载硬盘**。

   > **说明:**
   >
   > 若无可加载的硬盘，可单击**创建**进行创建。
   > 列表中，硬盘名称为灰色的硬盘表示已被加载，不可选择。
   
   ![load_4](/storage/disk/_images/load_4.png)

5. 在硬盘选择界面，勾选需要加载的硬盘，单击**提交**。
   ![load_5](/storage/disk/_images/load_5.png)

6. 加载成功后，可单击云服务器 ID 号，进入到详情页面，在**绑定资源**中查看到已加载的硬盘。

