<div align="center">
<h1>
  MiLM-6B
</h1>
</div>

# 介绍

MiLM-6B 是由小米开发的一个大规模预训练语言模型，参数规模为65亿。在 C-Eval 和 CMMLU 上均取得同尺寸最好的效果。模型相关信息持续更新中...

# 公开benchmark榜单

## C-Eval


[C-Eval 数据集](https://cevalbenchmark.com/index.html)是一个全面的中文基础模型评测数据集，涵盖了 52 个学科和四个难度的级别。

### 结果

|            Model            | Average | Avg(Hard) | STEM  | Social Sciences | Humanities | Others |
| :-------------------------: | :-----: | :-------: | :---: | :-------------: | :--------: | :----: |
|            GPT-4            |  68.7   |   54.9    | 67.1  |      77.6       |    64.5    |  67.8  |
|           ChatGPT           |  54.4   |   41.4    | 52.9  |      61.8       |    50.9    |  53.6  |
|         Claude-v1.3         |  54.2   |   39.0    | 51.9  |      61.7       |    52.1    |  53.7  |
|          BLOOMZ-7B          |  35.7   |   25.8    | 31.3  |      43.5       |    36.6    |  35.6  |
|         ChatGLM-6B          |  34.5   |   23.1    | 30.4  |      39.6       |    37.4    |  34.5  |
|         ChatGLM2-6B         |  51.7   |   37.1    | 48.6  |      60.5       |    51.3    |  49.8  |
|       Baichuan-7B           |  42.8   |   31.5    | 38.2  |      52.0       |    46.2    |  39.3  |
|  moss-moon-003-base (16B)   |  27.4   |   24.5    | 27.0  |      29.1       |    27.2    |  26.9  |
|         LLaMA-7B-hf         |  27.1   |   25.9    | 27.1  |      26.8       |    27.9    |  26.3  |
|          Falcon-7B          |  25.8   |   24.3    | 25.8  |      26.0       |    25.8    |  25.6  |
|          BLOOM-7B           |  22.8   |   20.2    | 21.8  |      23.3       |    23.9    |  23.3  |
|        **MiLM-6B**          |   -     |    -      |  -    |       -         |     -      |   -    |

<sup>模型的结果来自于[C-Eval 榜单](https://cevalbenchmark.com/static/leaderboard.html) 和 [Baichuan-7B](https://github.com/baichuan-inc/baichuan-7B)</sup><br/>

## CMMLU


[CMMLU 数据集](https://github.com/haonan-li/CMMLU/)是一个综合性的中文评估基准，专门用于评估语言模型在中文语境下的知识和推理能力。CMMLU涵盖了从基础学科到高级专业水平的67个主题。

### 结果

| 模型                 | STEM  | 人文学科 | 社会科学 | 其他  | 中国特定主题 | 平均分  |
|---------------------|------|------------|----------------|-------|----------------|---------|
| **MiLM-6B**                                                       |    -      |    -      |    -      |    -      |    -      |    -      |
| [Baichuan-13B](https://github.com/baichuan-inc/Baichuan-13B)      |   42.04   |   60.49   |   59.55   |   56.60   |   55.72   |   54.63   |
| [ChatGLM2-6B](https://huggingface.co/THUDM/chatglm2-6b)           |   41.28   |   52.85   |   53.37   |   52.24   |   50.58   |   49.95   |
| [Baichuan-7B](https://github.com/baichuan-inc/baichuan-7B)        |   32.79   |   44.43   |   46.78   |   44.79   |   43.11   |   42.33   |
| [ChatGLM-6B](https://github.com/THUDM/GLM-130B)                   |   32.22   |   42.91   |   44.81   |   42.60   |   41.93   |   40.79   |
| [BatGPT-15B](https://arxiv.org/abs/2307.00360)                    |   33.72   |   36.53   |   38.07   |   46.94   |   38.32   |   38.51   |
| [Chinese-LLaMA-13B](https://github.com/ymcui/Chinese-LLaMA-Alpaca)|   26.76   |   26.57   |   27.42   |   28.33   |   26.73   |   27.34   |
| [MOSS-SFT-16B](https://github.com/OpenLMLab/MOSS)                 |   25.68   |   26.35   |   27.21   |   27.92   |   26.70   |   26.88   |
| [Chinese-GLM-10B](https://github.com/THUDM/GLM)                   |   25.57   |   25.01   |   26.33   |   25.94   |   25.81   |   25.80   |

<sup>模型的结果来自于[CMMLU 数据集](https://github.com/haonan-li/CMMLU/)</sup><br/>