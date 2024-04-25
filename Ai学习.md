### ***注意！本笔记目前仅包含碎片话的知识点，仅自用，没有任何商业用途，侵删***

<br>
<br>


# 关于AI模型训练
——> [b站参考链接，感谢赛博菩萨秋妈](https://www.bilibili.com/read/cv19249573/?spm_id_from=333.976.0.0)

## Embedding 嵌入式模型

也叫Textual Inversion（文本反演）

文件类型包括 `.pt`，`.png`，`.webp`等等

使用时放入embedding文件夹即可

**原理简述：**

文生图的过程是通过输入prompt，prompt包括各个词条（token），再通过一系列复杂地操作将各个词条转换成连续向量，随后引导AI生成对应的图片

Textual Inversion也就是反向地“文生图”*（图生文）*，也就是喂给AI一大堆图片，去让AI寻找它们的共同之处（向量），最后找到那个词语（token）

**特点：**

- 体量小
- 方便用
- 训练速度快

<br>

> *这就是“文本反演”（Textual Inversion）——在文本编码器的嵌入空间（embedding）中找到新的伪词，使它可以捕获高级语义和精细视觉细节。*
>
> *——秋葉aaaki*

<br>
<br>
<br>


## Hypernetwork

还看不懂

---

<br>
<br>
<br>

## LoRA(Low-Rank Adaptation of Large Language Models)
————> [b站参考链接，感谢赛博菩萨秋妈](https://www.bilibili.com/read/cv22578510/?spm_id_from=333.976.0.0)