# MiLM-6B

## 介绍

MiLM-6B 是由小米开发的一个大规模预训练语言模型，参数规模为64亿。在 C-Eval 和 CMMLU 上均取得同尺寸最好的效果。

模型相关信息持续更新中...


## 评测结果

### C-Eval


[C-Eval 数据集](https://cevalbenchmark.com/index.html)是一个全面的中文基础模型评测数据集，涵盖了 52 个学科和四个难度的级别。


|            模型             |  Average  |  STEM     | Social Sciences | Humanities      | Others     | Avg(Hard) |
| :-------------------------: | :-------: | :-------: | :-------------: | :-------------: | :--------: | :-------: |
|        MiLM-6B              |  **60.2** |  **54.5** |  **71.7**       |    **62.7**     |   **57.7** |  **42.0** |
|        MiLM-1.3B            |  **45.8** |  **38.0** |  **59.5**       |    **49.8**     |   **43.4** |  **29.9** |

> 测试采用zero-shot

### CMMLU


[CMMLU 数据集](https://github.com/haonan-li/CMMLU/)是一个综合性的中文评估基准，专门用于评估语言模型在中文语境下的知识和推理能力。CMMLU涵盖了从基础学科到高级专业水平的67个主题。

* zero-shot

| 模型                 |   平均分  |   STEM    | 人文学科  | 社会科学 |   其他    | 中国特定主题 |
| :------------------: | :-------: | :-------: | :-------: | :------: | :-------: | :----------: |
|   MiLM-6B            | **60.37** | **48.88** | **63.49**| **66.2**  | **62.14** | **62.07**    |
|   MiLM-1.3B          | **50.79** | **40.51** | **54.82**| **54.15** | **53.99** | **52.26**    |


* five-shot

| 模型                 |   平均分  |   STEM    | 人文学科  | 社会科学 |   其他    | 中国特定主题 |
| :------------------: | :-------: | :-------: | :-------: | :------: | :-------: | :----------: |
|   MiLM-6B            | **57.17** | **46.85** | **61.12**| **61.68** | **58.84** | **59.39**    |
|   MiLM-1.3B          | **45.39** | **35.59** | **49.58**| **49.03** | **47.56** | **48.17**    |