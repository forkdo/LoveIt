---
weight: 4
title: "主题文档 - Asciinema Shortcodes"
date: 2025-02-03T16:29:41+08:00
lastmod: 2025-02-04T10:10:13+03:00
draft: false
author: "Jetsung"
authorLink: "https://i.jetsung.com"
description: ""
images: []
resources:

tags: ["shortcodes"]
categories: ["documentation"]

lightgallery: true

math:
  enable: true
---

Support Asciinema.

{{< asciinema id=5E5V7BWvQ34LqjqIhF9JIQI8a auto=1 >}}

```markdown
{{</* asciinema id=5E5V7BWvQ34LqjqIhF9JIQI8a auto=1 */>}}
```

---


| 选项 (Option) | 默认值 (Default Value) | 类型 (Type) | 描述 (Description) |
|:---|:---|:---|:---|
id | | 字母或整数 (alpha 或 int) | **必须设置** |
| start | 0 | 整数 (int) | **起始时间**。在指定时间开始播放。 |
| auto | 0 | 整数 (int) | **自动播放**。`0` 或 `1`，页面加载时是否自动开始播放。 | 
| loop | 0 | 整数 (int) | `0` 或 `1`，是否启用循环播放。 |
| speed | 1 | 整数 (int) | 播放速度。 |
| idle | | | **空闲时间限制**。优化录制中空闲时间的表现。 |
| poster | | | 播放开始前播放器显示的内容，例如：`npt:1:23`。 |
| theme | | 字符串 (string) | 主题风格，例如：`asciinema`、`dracula`、`monokai`、`nord`、`solarized-dark`、`solarized-light`、`tango`。 |
| cols | | 整数 (int) | 覆盖播放器终端的宽度。 |
| rows | | 整数 (int) | 覆盖播放器终端的高度。 |
| preload | 0 | 整数 (int) | `0` 或 `1`，页面加载时播放器是否应立即开始获取录制内容，而无需等待观看者启动播放。 |

**文档：**<https://docs.asciinema.org/manual/server/embedding/#inline-player>
