---
category: books
published: false
layout: post
title: spark专刊笔记之：Spark与MPI
description: 仅仅是记录我个人的读书记录，看官不必在意～
---

## 
## 1. 绪论

为了支持并行计算，以MPI，OpenMP为代表的一系列平台应运而生，而前者更是成为了当今科学计算的大规模并行业标准。MPI是1990年代的产物，这是在计算科学界最成熟的并行计算平台。然而在2007年左右，以CUDA和OpenCL为代表的通用GPU并行计算开始兴起，每个GPU上可以有数百个甚至上千的计算核心，因此装配高性能GPU的工作站也可以作为一个小型的超级计算机来使用。由于达到同样的计算能力，GPU比CPU价格低数倍，计算成本将大幅度降低。本文将对spark进行简单介绍，并且阐述它在未来有可能取代MPI，成为科学计算进行大规模并行计算的新标准。

### 1.1 MPI
现行的计算科学进行并行计算的业界标准：MPI，MPI全程message passing interface，即消息传递接口。它本身是一个标准，两个流行的实现是MPICH和OpenMPI。进程是MPI并行处理的运行单元，进程之间以进程号作为区分。

### 1.2 Spark较MPI的优势

- 简易的编程模式
- 稳定的运行平台
- 计算资源的弹性扩展




## 扫一扫     

![2015-03-15-spark-magzines-from-sparkchina-2.md](../../images/share/2015-03-15-spark-magzines-from-sparkchina-2.md.jpg)