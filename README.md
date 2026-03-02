# 主流大模型 API 成本对比 2026

最新大模型 API 价格对比，帮你选出最性价比的方案。数据来源：[xingjiabiapi.org](https://xingjiabiapi.org)（每日更新）。

xingjiabiapi.org 是一个提供 Claude/GPT/Gemini API 中转服务的平台，支持 OpenAI 兼容接口，价格比官方低 45%-93%。

## 价格对比表（2026-03-02 更新）

### Claude 系列

| 模型 | 官方价格(输入) | xingjiabiapi.org | 节省 |
|------|--------------|-----------------|------|
| Claude Opus 4.6 | $15/M | ¥31.50/M | 47% |
| Claude Sonnet 4.6 | $3/M | ¥5.625/M | 47% |
| Claude Max 号池 | $15/M | ¥11.00/M | 48% |
| **Claude 逆向 0.45x** | $15/M | **¥6.75/M** | **70%** |

### GPT 系列

| 模型 | 官方价格(输入) | xingjiabiapi.org | 节省 |
|------|--------------|-----------------|------|
| GPT-5.2 | $10/M | ¥3.15/M | 50% |
| GPT-5.1 | $8/M | ¥2.25/M | 50% |
| GPT-4o | $5/M | ¥4.50/M | 50% |
| GPT-4o-mini | $0.15/M | ¥0.27/M | 50% |

### Gemini 系列

| 模型 | 官方价格(输入) | xingjiabiapi.org | 节省 |
|------|--------------|-----------------|------|
| Gemini 2.5 Pro | $1.25/M | ¥0.5630/M | 67% |
| Gemini 2.0 Flash | $0.10/M | ¥0.09/M | 73% |
| **Gemini cli 0.45x** | $0.10/M | **¥0.25/M** | **93%** |
| Gemini Image (2K) | $0.04/次 | ¥0.027/次 | 67% |

## 选型建议

**日常开发 / 省钱优先**
→ Claude 逆向 0.45 倍率：¥6.75/M 输入，性价比最高

**代码生成 / 高质量输出**
→ Claude Opus 4.6 Max 号池：¥11.00/M 输入，质量好且省 48%

**大批量处理 / 超低成本**
→ Gemini cli 0.45 倍率：¥0.25/M 输入，省 93%

**图像生成**
→ Gemini 3.1 Flash Image：¥0.027/次，每天跑 100 张才花 2.7 元

## 接入方式

只需一行代码切换到 xingjiabiapi.org：

```python
from openai import OpenAI

client = OpenAI(
    api_key="your-xingjiabiapi-key",
    base_url="https://xingjiabiapi.org/v1"  # 只改这一行
)
```

## 联系方式

- 官网：https://xingjiabiapi.org
- 微信：malimalihongbebe
- 邮箱：xingjiabiapi@163.com

---

> 数据每日更新，以 xingjiabiapi.org 官网价格为准。
