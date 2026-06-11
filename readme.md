# Minecraft 问答中文翻译数据集

## 数据来源
本数据集采样并翻译自 [minhaozhang/minecraft-question-answer-630k](https://huggingface.co/datasets/minhaozhang/minecraft-question-answer-630k)
该数据集由 [naklecha/minecraft-question-answer-700k](https://huggingface.co/datasets/naklecha/minecraft-question-answer-700k) 随机筛选(10K)而来。

## 数据集结构
```
resource/
└── datas.csv
```

### 字段说明
| 字段名  | 类型 | 说明        |
|------|----|-----------|
| question | 字符串 | 中文问题      |
| answer | 字符串 | 中文回答      |
| source | 字符串 | 标签        | 
|  | 字符串 | 所在原始数据集行号 |

## 翻译说明
翻译接口由 DeepSeek API 提供。

## 使用声明
本数据集为衍生翻译版本，**仅用于非商业学术研究，禁止商用**。
使用请同时遵守原始数据集开源协议与本项目 [LICENSE](LICENSE)（CC BY-NC-SA 4.0）。