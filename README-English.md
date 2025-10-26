
# 🚀 ChatGPT-CN - Ultimate AI Models Aggregation Platform

<div align="center">

[![Website](https://img.shields.io/badge/Website-chatgpt--cn.pro-blue?style=for-the-badge)](https://chatgpt-cn.pro)
[![Models](https://img.shields.io/badge/Models-20%2B-green?style=for-the-badge)]()
[![Free Tier](https://img.shields.io/badge/Free%20Tier-Available-orange?style=for-the-badge)]()
[![Status](https://img.shields.io/badge/Status-Online-success?style=for-the-badge)]()

**Access all mainstream AI models in one place. No VPN required. Unlimited conversations.**

[🌐 Visit Website](https://chatgpt-cn.pro) | [📖 Documentation](#features) | [🎯 Quick Start](#quick-start) | [💬 Community](#community)

</div>

---

## 📌 Overview

ChatGPT-CN is a comprehensive AI platform that aggregates multiple state-of-the-art language models, providing developers and users with seamless access to various AI capabilities without the hassle of managing multiple subscriptions or API keys.

### 🎯 Why ChatGPT-CN?

- **One Platform, All Models**: Access GPT-5, Claude 3, Gemini 3.0, Llama 3, and more from a single interface
- **No Rate Limits**: Unlimited conversations for free tier models
- **No VPN Required**: Direct access from anywhere
- **Cost-Effective**: Save hundreds of dollars on AI subscriptions
- **Developer-Friendly**: Clean API, comprehensive documentation

## ✨ Features

### 🤖 Available Models

#### **Free Tier (Unlimited)**
| Model | Provider | Best For |
|-------|----------|----------|
| GPT-4o | OpenAI | General purpose, coding |
| GPT-4o-mini | OpenAI | Fast responses |
| Llama 3.2 | Meta | Long-form content |
| Qwen 2.5 | Alibaba | Multilingual tasks |
| Deepseek-V3 | Deepseek | Code generation |
| Mixtral-8x7B | Mistral | Technical writing |

#### **Premium Models (Weekly Rotation Free Access)**
| Model | Provider | Speciality |
|-------|----------|------------|
| GPT-5-Chat | OpenAI | Advanced reasoning |
| Claude-3-Opus | Anthropic | Creative writing |
| Gemini-3.0-Pro | Google | Multimodal analysis |
| GPT-o1-preview | OpenAI | Complex problem solving |

### 🛠️ Technical Features

```yaml
Core Features:
  - Streaming responses support
  - Context memory management (up to 128K tokens)
  - Multi-turn conversation handling
  - Auto model switching based on task
  - Response caching for efficiency
  - Export conversations (JSON, Markdown, PDF)
  
API Features:
  - RESTful API access
  - WebSocket support for real-time
  - Rate limiting: None for free tier
  - SDKs: Python, JavaScript, Go (coming soon)
```

## 🚀 Quick Start

### For Users

1. Visit [chatgpt-cn.pro](https://chatgpt-cn.pro)
2. Start chatting immediately (no registration required for basic features)
3. Register for free to unlock conversation history and more models

### For Developers

```bash
# Using cURL
curl -X POST https://api.chatgpt-cn.pro/v1/chat/completions \
  -H "Content-Type: application/json" \
  -H "Authorization: Bearer YOUR_API_KEY" \
  -d '{
    "model": "gpt-4o",
    "messages": [{"role": "user", "content": "Hello!"}]
  }'
```

```python
# Python Example
import requests

response = requests.post(
    "https://api.chatgpt-cn.pro/v1/chat/completions",
    headers={"Authorization": "Bearer YOUR_API_KEY"},
    json={
        "model": "gpt-4o",
        "messages": [{"role": "user", "content": "Write a Python function to sort a list"}]
    }
)
print(response.json())
```

```javascript
// JavaScript Example
const response = await fetch('https://api.chatgpt-cn.pro/v1/chat/completions', {
  method: 'POST',
  headers: {
    'Content-Type': 'application/json',
    'Authorization': 'Bearer YOUR_API_KEY'
  },
  body: JSON.stringify({
    model: 'gpt-4o',
    messages: [{role: 'user', content: 'Explain async/await in JavaScript'}]
  })
});
const data = await response.json();
```

## 📊 Performance Comparison

| Metric | ChatGPT-CN | OpenAI Direct | Claude.ai | 
|--------|------------|---------------|-----------|
| Response Time | ~800ms | ~1200ms | ~1000ms |
| Rate Limits (Free) | **Unlimited** | 50/3hrs | 30/3hrs |
| Model Variety | **20+** | 5 | 3 |
| Monthly Cost | **$0-29** | $20+ | $20+ |
| API Access | ✅ | ✅ | Limited |

## 💡 Use Cases

### 🧑‍💻 For Developers
- **Code Review & Refactoring**: Use GPT-5 for complex code analysis
- **Documentation Generation**: Automated API docs with Llama models
- **Debugging Assistant**: Real-time debugging help without rate limits
- **Test Case Generation**: Comprehensive test suites with Claude

### 📝 For Content Creators
- **SEO Article Writing**: Unlimited content generation
- **Multi-language Translation**: Qwen models for 50+ languages
- **Script & Story Writing**: Claude for creative narratives
- **Social Media Content**: Quick, engaging posts with GPT-4o-mini

### 🎓 For Students & Researchers
- **Literature Review**: Analyze papers without token limits
- **Code Learning**: Interactive programming tutorials
- **Language Practice**: Conversational practice in any language
- **Thesis Assistance**: Structure, review, and citations

## 🔧 Advanced Features

### Model Routing
```json
{
  "auto_routing": true,
  "routing_rules": {
    "code_generation": ["deepseek-v3", "gpt-4o"],
    "translation": ["qwen-2.5", "gpt-4o-mini"],
    "creative_writing": ["claude-3", "gpt-5-chat"],
    "math_problems": ["gpt-o1", "gpt-5-chat"]
  }
}
```

### Context Management
```python
# Maintain conversation context across sessions
session = ChatSession(
    model="gpt-4o",
    max_context_length=128000,
    memory_type="sliding_window"
)
```

## 📈 Statistics

- **Daily Active Users**: 50,000+
- **Total Conversations**: 10M+
- **Average Response Time**: 820ms
- **Uptime**: 99.9%
- **Models Available**: 20+

## 🗺️ Roadmap

### Q4 2024
- [x] GPT-5 Integration
- [x] Gemini 3.0 Beta Access
- [x] Unlimited Free Tier
- [ ] Mobile Apps (iOS/Android)

### Q1 2025
- [ ] Custom Fine-tuning Interface
- [ ] Plugin Marketplace
- [ ] Team Collaboration Features
- [ ] Voice & Image Generation Models

## 🤝 Community

### Contributing
We welcome contributions! Whether it's:
- 🐛 Bug reports
- 💡 Feature requests
- 📖 Documentation improvements
- 🔧 Code contributions

### Connect With Us
- **Discord**: [Join our server](https://discord.gg/chatgpt-cn)
- **Twitter**: [@chatgptcn](https://twitter.com/chatgptcn)
- **Email**: support@chatgpt-cn.pro

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ⭐ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=chatgpt-cn/chatgpt-cn&type=Date)](https://star-history.com/#chatgpt-cn/chatgpt-cn&Date)

---

<div align="center">

### 🎁 Special Offer

**🔥 This Week's Free Premium Model: GPT-5-Chat**

Experience the most advanced AI model without any cost. No credit card required.

[**Try It Now →**](https://chatgpt-cn.pro)

</div>

---

## 🙏 Acknowledgments

Special thanks to all the AI model providers and our amazing community of users who make this platform possible.

## ⚠️ Disclaimer

This platform aggregates publicly available AI models. We respect all original providers' terms of service. This is an independent project and is not affiliated with OpenAI, Anthropic, Google, or other AI providers.

---

<div align="center">

**If you find this project useful, please give it a ⭐ star!**

Made with ❤️ by the ChatGPT-CN Team

</div>

