# 色情文章检测

## 简介

利用 **文本卷积神经网络** （TextCNN）训练的文章分类模型，检测是否为色情文章。

```
Author:yudake
date:2018/2/22
```

开发环境：

- python3.x；
- tensorflow1.2；
- jieba；
- 其他相关类库，程序内会有提及。

目标：实现色情文章检测。

模型效果：最终准确率在98%以上。

## 模型

![系统模型](https://github.com/yudake/porn_fiction_classify/blob/master/images/model_graph.jpg?raw=true)

- 输入：文章经过处理后的句子矩阵；
- 模型：文本卷积神经网络；
- 输出：分类结果。

## 准确率曲线

![准确率](https://github.com/yudake/porn_fiction_classify/blob/master/images/porn_classify_arrurate.png?raw=true)

平均准确率在98%。具体内容请看代码与博客。