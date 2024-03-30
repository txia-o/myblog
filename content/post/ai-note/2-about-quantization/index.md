---
title: 【AI笔记】二、关于AI大模型量化的一些研究和总结
description: 无
slug: ai-note-2
date: 2024-03-30 00:00:00+0000
categories:
    - AI笔记
tags:
    - AI
    - 量化(模型)
weight: 7       # You can add weight to some posts to override the default sorting (date descending)
---

wip

## 引

近日在网上冲浪时刷到了[一篇文章](https://mobiusml.github.io/1bit_blog/)。这是一个关于大模型量化的研究团队发表的，这个团队提出他们使用了一种叫做hqq的量化技术，可以产生非常低精度的模型，并且实际推理效果超过一些较小的全精度模型。

这让我对模型的量化稍微产生了一点兴趣。在我之前的探索中，我始终从huggingface上找到现成的模型，而没有尝试过自己量化。主要是觉得没有必要浪费算力和学习成本。不过现在我对此产生了一些兴趣，于是做了一些研究，总结如下：

## 1. 传统的量化方法具体是如何实现的？GPTQ、GGUF、AWQ

## 2. HQQ和其他的方式之间的差异是什么？他们的优势是什么？


## 参考

[HQQ - Github repo](https://github.com/mobiusml/hqq)
[量化之后大模型的能力退化了多少 - 知乎](https://zhuanlan.zhihu.com/p/644378038)
[Which Quantization Method is Right for You? (GPTQ vs. GGUF vs. AWQ)](https://www.maartengrootendorst.com/blog/quantization/)
