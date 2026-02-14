<div align="center">
  <img src="https://www.wahooai.com/wahooai.webp" alt="WahooAI Logo" width="120" />
  <h1>WahooAI</h1>
  <p><strong>Gateway to the Future of AI Models | 通往未来 AI 模型的网关</strong></p>
  <p>
    <a href="#english">English</a> | <a href="#chinese">中文</a>
  </p>
</div>

---

<div id="english"></div>

# 🇺🇸 English

## Unified AI API Gateway
**WahooAI** is your all-in-one platform for accessing the world's most powerful Large Language Models (LLMs). We provide a unified API interface compatible with OpenAI, allowing you to seamlessly switch between models from different providers without changing your code.

### 🚀 Key Features

- **Standard OpenAI Interface**: Fully compatible with the OpenAI API format. Use existing libraries and tools drop-in replacement.
- **Multi-Model Support**: Access top-tier models like GPT-5, Claude 4, Gemini 3, and more through a single endpoint.
- **Pay-As-You-Go**: No subscriptions. Pay only for the tokens you use.
- **High Availability**: Enterprise-grade reliability and uptime.
- **Global Access**: Optimized routing for low latency worldwide.

### 🛠️ Quick Start

1. **Sign Up**: Register at [wahooai.com](https://wahooai.com) and get your API Key.
2. **Configure**: Set your `base_url` to `https://api.wahooai.com/v1`.
3. **Run**: Use your favorite OpenAI SDK.

#### Python Example

```python
from openai import OpenAI

client = OpenAI(
    api_key="sk-your-wahooai-api-key",
    base_url="https://api.wahooai.com/v1"
)

response = client.chat.completions.create(
    model="claude-sonnet-4-5-20250929",  # Switch models easily!
    messages=[
        {"role": "user", "content": "Hello, WahooAI!"}
    ]
)

print(response.choices[0].message.content)
```

---

<div id="chinese"></div>

# 🇨🇳 中文

## 统一 AI API 网关
**WahooAI** 是您访问全球最强大语言模型（LLM）的一站式平台。我们提供与 OpenAI 完全兼容的统一 API 接口，让您无需修改代码即可在不同提供商的模型之间无缝切换。

### 🚀 核心功能

- **标准 OpenAI 接口**: 完全兼容 OpenAI API 格式。现有库和工具可直接通过替换 URL 使用。
- **支持多模型**: 通过单一端点访问 GPT-5, Claude 4, Gemini 3 等顶级模型。
- **按需付费**: 无需订阅。仅为您使用的 Token 付费。
- **高可用性**: 企业级的可靠性和正常运行时间。
- **全球访问**: 优化的路由，确保全球低延迟。

### 🛠️ 快速开始

1. **注册**: 在 [wahooai.com](https://wahooai.com) 注册并获取您的 API Key。
2. **配置**: 将 `base_url` 设置为 `https://api.wahooai.com/v1`。
3. **运行**: 使用您喜欢的 OpenAI SDK。

#### Python 示例

```python
from openai import OpenAI

client = OpenAI(
    api_key="sk-your-wahooai-api-key",
    base_url="https://api.wahooai.com/v1"
)

response = client.chat.completions.create(
    model="claude-sonnet-4-5-20250929",  # 轻松切换模型！
    messages=[
        {"role": "user", "content": "你好，WahooAI！"}
    ]
)

print(response.choices[0].message.content)
```

---

<div align="center">
  <p>Ready to supercharge your AI applications?</p>
  <p><a href="https://wahooai.com"><b>Get Started with WahooAI Today</b></a></p>
</div>
