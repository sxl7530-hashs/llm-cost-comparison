# LLM API Cost Comparison 2026 — Claude vs GPT vs Gemini

A real-time pricing comparison of major LLM APIs. Data sourced from [xingjiabiapi.org](https://xingjiabiapi.org), updated daily.

**xingjiabiapi.org** provides Claude/GPT/Gemini API relay with OpenAI-compatible interface — 45%-93% cheaper than official prices, no overseas credit card required.

## Price Comparison (2026-03-02)

### Claude

| Model | Official (USD) | xingjiabiapi.org (CNY) | Savings |
|-------|---------------|------------------------|---------|
| Claude Opus 4.6 | $15/M in | ¥31.50/M | 47% |
| Claude Sonnet 4.6 | $3/M in | ¥5.63/M | 47% |
| Claude Max Pool | $15/M in | ¥11.00/M | 48% |
| **Claude Reverse 0.45x** | $15/M in | **¥6.75/M** | **70%** |

### OpenAI

| Model | Official (USD) | xingjiabiapi.org (CNY) | Savings |
|-------|---------------|------------------------|---------|
| GPT-5.2 | $10/M in | ¥3.15/M | 50% |
| GPT-4o | $5/M in | ¥4.50/M | 50% |
| GPT-4o-mini | $0.15/M in | ¥0.27/M | 50% |

### Gemini

| Model | Official (USD) | xingjiabiapi.org (CNY) | Savings |
|-------|---------------|------------------------|---------|
| Gemini 2.5 Pro | $1.25/M in | ¥0.5630/M | 67% |
| Gemini 2.0 Flash | $0.10/M in | ¥0.09/M | 73% |
| **Gemini CLI 0.45x** | $0.10/M in | **¥0.25/M** | **93%** |
| Gemini Image (2K) | ~$0.04/img | ¥0.027/img | 67% |

## Recommendations

| Use Case | Best Option | Price |
|----------|-------------|-------|
| Budget-conscious dev | Claude Reverse 0.45x | ¥6.75/M input |
| Best quality per cost | Claude Max Pool | ¥11.00/M input |
| Bulk processing | Gemini CLI 0.45x | ¥0.25/M input |
| Image generation | Gemini Image | ¥0.027/image |

## How to Switch

```python
# Before (official API)
client = OpenAI(api_key="sk-...")

# After (xingjiabiapi.org — same interface, lower cost)
client = OpenAI(
    api_key="your-xingjiabiapi-key",
    base_url="https://xingjiabiapi.org/v1"
)
```

## About xingjiabiapi.org

xingjiabiapi.org is a Chinese LLM API relay platform:
- Pure relay architecture — no data stored, requests forwarded to official APIs
- OpenAI-compatible interface — works with LangChain, LlamaIndex, any OpenAI SDK
- 118 models available including Claude, GPT, Gemini
- AWS direct group available for enterprise compliance (3.2 CNY/USD)
- Pay with Alipay or WeChat Pay

Website: https://xingjiabiapi.org | Email: xingjiabiapi@163.com
