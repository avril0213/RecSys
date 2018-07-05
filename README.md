# Recommendation System
关于推荐系统的阅读和总结。

* 平台架构
今日头条算法原理：https://cloud.tencent.com/developer/article/1056037


# Deep learning topics
## 1.Deep Model compression
* 综述翻译
https://www.jiqizhixin.com/articles/2017-10-29

* 模型压缩经典方法
三阶段压缩：修建，量化，霍夫曼编码：https://arxiv.org/pdf/1510.00149.pdf (ICLR 2016 best paper)
知识精炼Knowledge distillation: https://www.cs.toronto.edu/~hinton/absps/distillation.pdf ((Dark knowledge by Hinton)

* 如何理解soft target?
整体来讲是通过label增加了要预测的类之间相似度的信息，起到的作用类似pretrain等都是为了提升generalization. https://www.zhihu.com/question/50519680