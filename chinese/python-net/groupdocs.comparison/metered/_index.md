---
title: "Metered 类"
second_title: "适用于 Python 的 GroupDocs.Comparison via .NET API 参考"
description: 
type: docs
url: /zh/python-net/groupdocs.comparison/metered/
is_root: false
weight: 100
---


## Metered class

管理计量（按使用付费）许可证。

Metered 许可证根据实际消耗计费（通常是页面或
处理的文档）。在应用启动时设置一次公钥/私钥对
应用启动时；包装器会向 GroupDocs 报告使用情况
许可证服务器在后台。

Metered 类型公开以下成员：

### 方法
| 方法 | 描述 |
| :- | :- |
| [get_consumption_credit](/comparison/python-net/groupdocs.comparison/metered/get_consumption_credit/) | 返回当前密钥的剩余计量信用。 |
| [get_consumption_quantity](/comparison/python-net/groupdocs.comparison/metered/get_consumption_quantity/) | 返回迄今为止已消耗的总计量数量。 |
| [set_metered_key](/comparison/python-net/groupdocs.comparison/metered/set_metered_key/#public_key-private_key) | 使用给定的公钥/私钥对激活计量计费。 |

### 另请参阅
* module [`groupdocs.comparison`](/comparison/python-net/groupdocs.comparison/)
