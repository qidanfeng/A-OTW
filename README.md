# A-OTW

<h1 align="center" style="margin: 30px 0 30px; font-weight: bold;">仓储服务一体化平台</h1>
<h4 align="center">基于SpringCloud开发的集订单管理(OMS)、仓储管理(WMS)、运输管理(TMS)与一体的SaaS平台</h4>

<!--ts-->

   * [介绍](#介绍)
   * [软件架构](#软件架构)
   * [系统展示](#系统展示)    
   * [原型设计](#原型设计)    
   * [思路展示](#思路展示) 
   
   
<!--te-->

# 介绍
## Saas平台系统

- UMC【用户管理中心 User Management Center】

      UMC提供整个平台的用户账号管理，通过Oauth2.0实现认证授权，各个平台单点登录，集成手机号验证登录、微信扫描登录。

- MDM【主数据管理 Master Data Management】

      MDM提供整个平台的基础数据管理。功能有：客户管理、货主管理、产品管理、包装管理、地址管理、承运商管理、供应商管理、字典管理。

- OMS【订单管理系统 Order Management System】

      OMS为整个平台的订单入口，统一派发统一监控。功能有：订单管理、任务计划管理、任务拆分、事件配置管理、节点监控、库存管理。

- WMS【仓储管理系统 Warehouse Management System】

      WMS提供仓储服务功能，按照仓库维度做数据隔离。功能有：入库作业、出库作业、越库作业、库存作业、结算管理、电商发货、物流轨迹查询等。

- TMS【运输管理系统 Transportation Management System】

      TMS承接仓储服务下游应用，为货物运输配送提供功能。功能有：作业单管理、计划单管理、运输单管理、可视化调度、结算管理等。

- AMS【预约管理系统 Appointment Management System】
    
      AMS为WMS系统的上游应用，供应商通过在AMS系统中进行送货预约，预约成功之后信息推送到WMS。功能有：送货预约、预约审核、预约签到、预约叫号、预约调度、预约可视化管理、道口可视化管理、时间窗管理、供应商考核 

- EDI【客户数据交换系统 Electronic Data Interchange】

        EDI是对接客户系统的入口，订单先经EDI处理，再流入OMS。功能有：接口鉴权、收货接口、发货接口、收货反馈接口、发货反馈接口、库存同步接口、库存异动接口、参数转换等

# 软件架构

![Saas平台架构图](729be84fe2e8d3295a888b322481bc1.jpg)
![产品功能架构图](image.png)
![EDI平台架构图](0efeb916b148d18eee7fd345993cc57.jpg)


# 系统展示
## 登录
![输入图片说明](1664242603533.jpg)

## portal页
![输入图片说明](1664242642377.jpg)

## UMC
![输入图片说明](1664242724492.jpg)

## MDM
![输入图片说明](1664242764166.jpg)

## OMS
![输入图片说明](1664242813805.jpg)
![输入图片说明](1664242875907.jpg)

## WMS
![输入图片说明](1664242949650.jpg)
![输入图片说明](1664243009337.jpg)

## TMS
![输入图片说明](1664243179923.jpg)
![输入图片说明](1664243231621.jpg)

## EDI
![输入图片说明](1664243330417.jpg)



# 原型设计
![输入图片说明](1664244070693.jpg)
![输入图片说明](1664244094573.jpg)
![输入图片说明](1664244123966.jpg)
![输入图片说明](1664244178035.jpg)
![输入图片说明](1664244286481.jpg)
![输入图片说明](1664244307046.jpg)
![输入图片说明](1664244345134.jpg)
![输入图片说明](1664244506026.jpg)
![输入图片说明](1664244533795.jpg)
![输入图片说明](1664244654305.jpg)
![输入图片说明](1664244736682.jpg)
![输入图片说明](1664244841078.jpg)
![输入图片说明](1664244899895.jpg)

#### 思路展示
![输入图片说明](1664245044485.jpg)
![输入图片说明](1664245062702.jpg)
![输入图片说明](1664245104050.jpg)
![输入图片说明](1664245273065.png)
![输入图片说明](1664245471951.jpg)
![输入图片说明](1664245548787.jpg)
![输入图片说明](1664245584635.jpg)
![输入图片说明](1664245618171.jpg)
![输入图片说明](1664245653299.jpg)
![输入图片说明](1664245701210.jpg)
