---
weight: 4
title: "Theme Documentation - Asciinema Shortcodes"
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


| Option | Default Value | Type | Description |
|:---|:---|:---|:---|
`id` | | `alpha` or `int`| **Must be set**  |
| `start` | `0` | `int` | **start-at**. start the playback at a given time. |
| `auto` | `0` | `int` | **autoplay**. `0` or `1`. the playback should start automatically upon a page load. | 
| `loop` | `0` | `int` | `0` or `1`. enable looped playback. |
| `speed` | `1` | `int` | the playback speed. |
| `idle` | | | **idle-time-limit**. optimize away idle moments in a recording. |
| `poster` | | | display in player's terminal until the playback is started. i.e: `npt:1:23` |
| `theme` | | `string` | asciinema dracula monokai nord solarized-dark solarized-light tango
| `cols` | | `int` | override player's terminal width. |
| `rows` | | `int` | override player's terminal height. |
| `preload` | `0` | `int`| `0` or `1`. the player should start fetching the recording immediately upon a page load, before a viewer starts the playback. |

**Documents：**<https://docs.asciinema.org/manual/server/embedding/#inline-player>
