[🇺🇸 English | English README](./README.md)

# 自然语言处理项目

<div align="center">
  <img alt="Demo" src="./src/tub.png" style="width:10%; height:10%" />
</div>

## 📚 内容
[🏫 在线学习平台](https://ki-campus.org/node/487)  
主题涵盖：文本预处理、向量表示、词嵌入、文本语料、语言模型、语义文本相似度、垃圾邮件过滤、关键词提取等。

## 🧪 实验与作业

### 1. 疫情舆情分析
- **目标：** 基于对立思维分析法，分析疫情期间社交媒体文本的情感与立场。
- **技术方法：** 文本预处理、特征提取、情感/立场分类、可视化。
- **详细说明：** 结合NLP与社会科学方法，揭示舆论趋势与极化现象。
- [报告（PDF）](NLP_project1_4/NLP_project1_4_report.pdf)

### 2. 英意神经机器翻译（Seq2Seq）
- **目标：** 基于深度学习（带注意力的Seq2Seq）实现英意互译神经机器翻译模型。
- **数据集：** Europarl v7 英意平行语料（约190万句对）。
- **技术方法：** 数据清洗、分词、序列建模、编码器-解码器（带注意力）、评估。
- **训练结果：**
  - 训练集准确率最高：**0.8508**
  - 训练集损失最低：**0.9742**
  - 验证集准确率最高：**0.8528**
  - 验证集损失最低：**0.9664**
- **实验代码：** [Notebook](NLP_project2_2/nlp_2_code.ipynb)

<div align="center">
  <img alt="Demo" src="./src/opt.png" style="width:50%; height:50%" />
</div>

---

## 🛠️ 环境导出
导出环境命令：
```conda env export > environment.yml``` 