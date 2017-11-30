---
layout: default
title: 基于模式识别的预估方法
---

# 引子
工作从广告点击率预估起步, 就从这里说起
建模是基于对历史数据规律/模式的认识; 有两类基本方法, 概率学派和频率学派

# {{ page.title }}
## 目录结构
- [线性回归模型]({{ site.baseurl }}{% post_url 2017-11-25-linear-regression %})
- sigmoid函数与LR模型
- 大规模数据时的采样方案
- 当代工匠:特征挖掘
- 时效性问题：
    - OWLQN训练原理
    - SOM算法原理 网盟的inc-batch方案
    - FM/ON_learning两个算法
- 如何评估
    离线：AUC
    在线：根据CTR，给出p=5%所需的样本量
- 其他优化：多样化C值

## 数学基础
- [记号表示]({{ site.baseurl }}{% post_url 2017-11-23-notation %})
- 向量/矩阵求导
- 凸优化算法介绍
- 统计理论


[comment]: <> ({% for post in site.posts %})
[comment]: <> (- {{ post.date | date_to_string }} [ {{ post.title }} ]( {{ site.baseurl }}{{ post.url }} ))
[comment]: <> ({% endfor %})
