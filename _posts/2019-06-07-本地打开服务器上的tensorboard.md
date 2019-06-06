---
layout:     post   				    # 使用的布局（不需要改）
title:      本地打开服务器的tensorboard 				# 标题 
date:       2019-06-07 				# 时间
author:     0point618					# 作者
catalog: true 						# 是否归档
tags:								#标签

    - Pytorch
---

1. 在本地terminal中输入

   ```
   ssh -L 6006:localhost:6006 root@ip
   ```

2. ==cd到runs（logdir）的路径的上一级！！！==（非常重要，之前参考网上的各种方法都失败了）

3. 在terminal中输入

   ```
   tensorboard --logdir runs
   ```

   