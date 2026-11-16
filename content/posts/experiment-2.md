---
title: "Shell脚本入门练习"
date: 2026-10-21
draft: false
categories: ["Linux课程"]
tags: ["Shell", "脚本编程"]
---

# Shell脚本入门实验
Shell脚本是Linux系统自动化运维的核心工具，可以批量执行命令、完成重复任务。

## 实验内容
### 1. 编写第一个Shell脚本
创建 `test.sh` 文件，写入简单输出逻辑：
```bash
#!/bin/bash
echo "Hello Linux"
echo "当前时间: $(date)"

