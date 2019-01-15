# 补充性规格说明



## 简介

本文档描述了没有在用例文本中描述的需求。

## 功能性

#### 1.支付订单时出现中断的处理

保存数据，交易中断后能恢复上一次交易。

#### 2.安全性

在开始使用系统之前要进行登录。

#### 3.同步性

在不同设备上对同一个账号的操作应是同步的。

#### 4.可用性

- 页面尽量展示电影的相关图片或海报，文字尽可能精简。
- 做到响应式布局，即在不同设备上能自适应地调节尺寸，合理展现页面信息。

 

## 可靠性

- 避免系统时常出现问题导致顾客等待时间长。
- 能容纳多人同时使用而不崩溃。



## 接口

- 第三方授权支付的接口

- 与影院数据同步的接口


## 应用的领域规则



| ID   | 规则                             | 可变性                           | 来源             |
|-|-|-|-|
| 1    | 特定时期有购票优惠               | 高                               | 电影院或平台提供 |
| 2    | 购票成功后不能退票               | 中, 平台可提供转让或其他类似功能 | 平台             |
| 3    | 购票成功后不能更换影片\场次\座位 | 低                               | 电影院规则       |


