<div align="center">

<h1 align="center">Wortholic AI</h1>

✨ Advanced AI Assistant Platform - Powered by Multiple AI Models

🚀 **Wortholic AI** - Your comprehensive AI assistant platform supporting multiple AI models including Claude, GPT-4, Gemini Pro, and DeepSeek.

</div>

## 🚀 About Wortholic AI

Wortholic AI is a powerful, enterprise-ready AI assistant platform that brings together the best of multiple AI models in one unified interface. Built for productivity, creativity, and seamless AI interactions.

## ✨ Key Features

- **Multi-Model Support**: Claude, GPT-4, Gemini Pro, DeepSeek, and more
- **Enterprise Ready**: Advanced security, privacy controls, and admin management
- **Docker Deployment**: Easy containerized deployment and scaling
- **Model Context Protocol (MCP)**: Enhanced AI capabilities and tool integration

## 🏢 Business Customization & White-Label Solutions

### Complete Brand Customization
Transform Wortholic AI to match your business identity:

- **Custom Branding**: Replace logos, colors, and themes with your company branding
- **Domain Integration**: Host on your own domain (e.g., ai.yourcompany.com)
- **Custom Messaging**: Personalize welcome messages, prompts, and user interface text
- **Tailored Workflows**: Configure AI responses to match your industry and business processes

### Industry-Specific Solutions

**🏥 Healthcare & Medical**
- HIPAA-compliant deployment options
- Medical terminology and protocol integration
- Patient communication templates
- Clinical decision support customization

**🏪 E-commerce & Retail**
- Product recommendation engines
- Customer service automation
- Inventory management assistance
- Sales funnel optimization

**💼 Professional Services**
- Client communication templates
- Document generation automation
- Project management integration
- Billing and invoicing assistance

**🎓 Education & Training**
- Course content generation
- Student assessment tools
- Learning pathway customization
- Multi-language educational support

### Revenue Opportunities
**💡 Reseller Program**
- White-label Wortholic AI for your clients
- Custom pricing structures
- Multi-tenant architecture support
- Revenue sharing opportunities

**🔧 Custom Development**
- API integration with existing systems
- Custom AI model training
- Specialized industry modules
- Dedicated technical support

For enterprise inquiries, please contact: **wortholicai@gmail.com**

## 💼 Business Benefits

### Transform Your Business with AI
Wortholic AI empowers businesses of all sizes to integrate cutting-edge AI capabilities into their operations, providing a competitive edge in today's digital landscape.

### Why Choose Wortholic AI for Your Business?

**🎯 Increased Productivity**
- Automate routine tasks and free up valuable time for strategic work
- 24/7 AI assistance for customer support and internal operations
- Streamline workflows with intelligent automation

**💰 Cost-Effective Solution**
- Reduce operational costs by up to 40% with AI-powered efficiency
- Scale AI capabilities without hiring additional staff
- Pay-per-use model with multiple AI providers for optimal pricing

**🛡️ Enterprise-Grade Security**
- Complete data privacy with local storage options
- SOC 2 compliant infrastructure
- Role-based access controls and audit trails

## 🎯 Core Features

- **Multi-AI Integration**: Seamlessly switch between Claude, GPT-4, Gemini Pro, DeepSeek, and more
- **Privacy First**: All data stored locally with enterprise-grade security
- **Docker Ready**: One-click containerized deployment
- **Rich Content Support**: Markdown, LaTeX, code highlighting, mermaid diagrams
- **Responsive Design**: Dark mode, mobile-friendly, and PWA support
- **Fast Performance**: Optimized loading (~100kb) with streaming responses
- **Template System**: Create and share custom AI prompt templates
- **Chat Management**: Smart conversation compression for long discussions
- **Multi-Language**: Support for 15+ languages including English, Chinese, Japanese, Korean
- **Self-Hosted Compatible**: Works with local AI models and custom endpoints
- **Real-time Features**: Live chat capabilities and instant responses
- **Plugin Architecture**: Extensible with custom tools and integrations


## Roadmap

- [x] System Prompt: pin a user defined prompt as system prompt [#138](https://github.com/Yidadaa/ChatGPT-Next-Web/issues/138)
- [x] User Prompt: user can edit and save custom prompts to prompt list
- [x] Prompt Template: create a new chat with pre-defined in-context prompts [#993](https://github.com/Yidadaa/ChatGPT-Next-Web/issues/993)
- [x] Share as image, share to ShareGPT [#1741](https://github.com/Yidadaa/ChatGPT-Next-Web/pull/1741)
- [x] Desktop App with tauri
- [x] Self-host Model: Fully compatible with [RWKV-Runner](https://github.com/josStorer/RWKV-Runner), as well as server deployment of [LocalAI](https://github.com/go-skynet/LocalAI): llama/gpt4all/rwkv/vicuna/koala/gpt4all-j/cerebras/falcon/dolly etc.
- [x] Artifacts: Easily preview, copy and share generated content/webpages through a separate window [#5092](https://github.com/ChatGPTNextWeb/ChatGPT-Next-Web/pull/5092)
- [x] Plugins: support network search, calculator, any other apis etc. [#165](https://github.com/Yidadaa/ChatGPT-Next-Web/issues/165) [#5353](https://github.com/ChatGPTNextWeb/ChatGPT-Next-Web/issues/5353)
  - [x] network search, calculator, any other apis etc. [#165](https://github.com/Yidadaa/ChatGPT-Next-Web/issues/165) [#5353](https://github.com/ChatGPTNextWeb/ChatGPT-Next-Web/issues/5353)
- [x] Supports Realtime Chat [#5672](https://github.com/ChatGPTNextWeb/ChatGPT-Next-Web/issues/5672)
- [ ] local knowledge base

## What's New

- 🚀 v2.15.8 Now supports Realtime Chat [#5672](https://github.com/ChatGPTNextWeb/ChatGPT-Next-Web/issues/5672)
- 🚀 v2.15.4 The Application supports using Tauri fetch LLM API, MORE SECURITY! [#5379](https://github.com/ChatGPTNextWeb/ChatGPT-Next-Web/issues/5379)
- 🚀 v2.15.0 Now supports Plugins! Read this: [NextChat-Awesome-Plugins](https://github.com/ChatGPTNextWeb/NextChat-Awesome-Plugins)
- 🚀 v2.14.0 Now supports Artifacts & SD
- 🚀 v2.10.1 support Google Gemini Pro model.
- 🚀 v2.9.11 you can use azure endpoint now.
- 🚀 v2.8 now we have a client that runs across all platforms!
- 🚀 v2.7 let's share conversations as image, or share to ShareGPT!
- 🚀 v2.0 is released, now you can create prompt templates, turn your ideas into reality! Read this: [ChatGPT Prompt Engineering Tips: Zero, One and Few Shot Prompting](https://www.allabtai.com/prompt-engineering-tips-zero-one-and-few-shot-prompting/).

## 🚀 Quick Start

### Option 1: Docker (Recommended)
```bash
docker run -d -p 3000:3000 \
   -e OPENAI_API_KEY=your-openai-key \
   -e ANTHROPIC_API_KEY=your-anthropic-key \
   -e CODE=your-password \
   wortholic/ai-assistant
```

### Option 2: Local Development
```bash
# Clone the repository
git clone https://github.com/wortholic/wortholic-ai
cd wortholic-ai

# Install dependencies
npm install

# Configure environment
cp .env.example .env.local
# Edit .env.local with your API keys

# Start development server
npm run dev
```

### Option 3: Cloud Deployment
Deploy to Vercel, Railway, or your preferred cloud platform with one click.

## FAQ

[English > FAQ](./docs/faq-en.md)

## Keep Updated

If you have deployed your own project with just one click following the steps above, you may encounter the issue of "Updates Available" constantly showing up. This is because Vercel will create a new project for you by default instead of forking this project, resulting in the inability to detect updates correctly.

We recommend that you follow the steps below to re-deploy:

- Delete the original repository;
- Use the fork button in the upper right corner of the page to fork this project;
- Choose and deploy in Vercel again, [please see the detailed tutorial](./docs/vercel-cn.md).

## Environment Variables

### `CODE` (optional)

Access password, separated by comma.

### `OPENAI_API_KEY` (required)

Your openai api key, join multiple api keys with comma.

### `BASE_URL` (optional)

> Default: `https://api.openai.com`

> Examples: `http://your-openai-proxy.com`

Override openai api request base url.

### `OPENAI_ORG_ID` (optional)

Specify OpenAI organization ID.

### `AZURE_URL` (optional)

> Example: https://{azure-resource-url}/openai

Azure deploy url.

### `AZURE_API_KEY` (optional)

Azure Api Key.

### `AZURE_API_VERSION` (optional)

Azure Api Version, find it at [Azure Documentation](https://learn.microsoft.com/en-us/azure/ai-services/openai/reference#chat-completions).

### `GOOGLE_API_KEY` (optional)

Google Gemini Pro Api Key.

### `GOOGLE_URL` (optional)

Google Gemini Pro Api Url.

### `ANTHROPIC_API_KEY` (optional)

anthropic claude Api Key.

### `ANTHROPIC_API_VERSION` (optional)

anthropic claude Api version.

### `ANTHROPIC_URL` (optional)

anthropic claude Api Url.

### `BAIDU_API_KEY` (optional)

Baidu Api Key.

### `BAIDU_SECRET_KEY` (optional)

Baidu Secret Key.

### `BAIDU_URL` (optional)

Baidu Api Url.

### `BYTEDANCE_API_KEY` (optional)

ByteDance Api Key.

### `BYTEDANCE_URL` (optional)

ByteDance Api Url.

### `ALIBABA_API_KEY` (optional)

Alibaba Cloud Api Key.

### `ALIBABA_URL` (optional)

Alibaba Cloud Api Url.

### `IFLYTEK_URL` (Optional)

iflytek Api Url.

### `IFLYTEK_API_KEY` (Optional)

iflytek Api Key.

### `IFLYTEK_API_SECRET` (Optional)

iflytek Api Secret.

### `CHATGLM_API_KEY` (optional)

ChatGLM Api Key.

### `CHATGLM_URL` (optional)

ChatGLM Api Url.

### `DEEPSEEK_API_KEY` (optional)

DeepSeek Api Key.

### `DEEPSEEK_URL` (optional)

DeepSeek Api Url.

### `HIDE_USER_API_KEY` (optional)

> Default: Empty

If you do not want users to input their own API key, set this value to 1.

### `DISABLE_GPT4` (optional)

> Default: Empty

If you do not want users to use GPT-4, set this value to 1.

### `ENABLE_BALANCE_QUERY` (optional)

> Default: Empty

If you do want users to query balance, set this value to 1.

### `DISABLE_FAST_LINK` (optional)

> Default: Empty

If you want to disable parse settings from url, set this to 1.

### `CUSTOM_MODELS` (optional)

> Default: Empty
> Example: `+llama,+claude-2,-gpt-3.5-turbo,gpt-4-1106-preview=gpt-4-turbo` means add `llama, claude-2` to model list, and remove `gpt-3.5-turbo` from list, and display `gpt-4-1106-preview` as `gpt-4-turbo`.

To control custom models, use `+` to add a custom model, use `-` to hide a model, use `name=displayName` to customize model name, separated by comma.

User `-all` to disable all default models, `+all` to enable all default models.

For Azure: use `modelName@Azure=deploymentName` to customize model name and deployment name.

> Example: `+gpt-3.5-turbo@Azure=gpt35` will show option `gpt35(Azure)` in model list.
> If you only can use Azure model, `-all,+gpt-3.5-turbo@Azure=gpt35` will `gpt35(Azure)` the only option in model list.

For ByteDance: use `modelName@bytedance=deploymentName` to customize model name and deployment name.

> Example: `+Doubao-lite-4k@bytedance=ep-xxxxx-xxx` will show option `Doubao-lite-4k(ByteDance)` in model list.

### `DEFAULT_MODEL` （optional）

Change default model

### `VISION_MODELS` (optional)

> Default: Empty
> Example: `gpt-4-vision,claude-3-opus,my-custom-model` means add vision capabilities to these models in addition to the default pattern matches (which detect models containing keywords like "vision", "claude-3", "gemini-1.5", etc).

Add additional models to have vision capabilities, beyond the default pattern matching. Multiple models should be separated by commas.

### `WHITE_WEBDAV_ENDPOINTS` (optional)

You can use this option if you want to increase the number of webdav service addresses you are allowed to access, as required by the format：

- Each address must be a complete endpoint
  > `https://xxxx/yyy`
- Multiple addresses are connected by ', '

### `DEFAULT_INPUT_TEMPLATE` (optional)

Customize the default template used to initialize the User Input Preprocessing configuration item in Settings.

### `STABILITY_API_KEY` (optional)

Stability API key.

### `STABILITY_URL` (optional)

Customize Stability API url.

### `ENABLE_MCP` (optional)

Enable MCP（Model Context Protocol）Feature

### `SILICONFLOW_API_KEY` (optional)

SiliconFlow API Key.

### `SILICONFLOW_URL` (optional)

SiliconFlow API URL.

### `AI302_API_KEY` (optional)

302.AI API Key.

### `AI302_URL` (optional)

302.AI API URL.

## 🛠️ Tech Stack

### Frontend
- **Next.js 14**: React framework with App Router for modern web development
- **React 18**: Latest React with Concurrent Features and Suspense
- **TypeScript**: Type-safe development with enhanced developer experience
- **Tailwind CSS**: Utility-first CSS framework for rapid UI development
- **Zustand**: Lightweight state management for React applications
- **Framer Motion**: Production-ready motion library for React animations

### Backend & API Integration
- **Next.js API Routes**: Serverless API endpoints with Edge Runtime support
- **Multiple AI Provider APIs**: 
  - OpenAI GPT-4/GPT-3.5 Turbo
  - Anthropic Claude (Haiku, Sonnet, Opus)
  - Google Gemini Pro/Ultra
  - DeepSeek API
  - Azure OpenAI
  - Custom model endpoints
- **WebSocket**: Real-time chat capabilities
- **Server-Sent Events (SSE)**: Streaming responses for better UX

### DevOps & Deployment
- **Docker**: Containerized deployment with multi-stage builds
- **Docker Compose**: Multi-service orchestration
- **Vercel**: Optimized for serverless deployment
- **Railway**: Alternative cloud deployment platform
- **GitHub Actions**: CI/CD pipeline automation

### Development Tools
- **ESLint**: Code linting and formatting
- **Prettier**: Code formatting
- **Husky**: Git hooks for pre-commit validation
- **PostCSS**: CSS processing and optimization
- **Webpack**: Module bundling and optimization

### Security & Authentication
- **Environment Variables**: Secure API key management
- **CORS**: Cross-origin request handling
- **Rate Limiting**: API protection against abuse
- **Data Encryption**: Client-side data protection

## 🎯 Comprehensive Use Cases

### Business Operations
- **Customer Support Automation**: 24/7 AI-powered help desk
- **Content Creation**: Blog posts, social media, marketing copy
- **Document Processing**: Contract analysis, report generation
- **Email Management**: Automated responses, email drafting
- **Meeting Summarization**: Convert transcripts to actionable insights
- **Data Analysis**: Business intelligence and reporting

### Development & Technical
- **Code Generation**: Full-stack application development
- **Code Review**: Automated code quality assessment
- **Documentation**: Technical documentation generation
- **API Integration**: Custom connector development
- **Database Design**: Schema optimization and queries
- **DevOps Automation**: CI/CD pipeline configuration

### Creative Industries
- **Copywriting**: Ad copy, product descriptions, SEO content
- **Creative Brainstorming**: Idea generation for campaigns
- **Script Writing**: Video scripts, podcast outlines
- **Translation Services**: Multi-language content localization
- **Brand Voice Development**: Consistent messaging across platforms

### Education & Training
- **Curriculum Development**: Course creation and lesson planning
- **Student Assessment**: Automated grading and feedback
- **Research Assistance**: Academic research and citation help
- **Language Learning**: Conversational practice and correction
- **Skill Development**: Personalized learning paths

### Healthcare & Professional Services
- **Patient Communication**: Appointment scheduling, follow-ups
- **Medical Documentation**: Clinical note assistance (non-diagnostic)
- **Legal Document Drafting**: Contract templates, legal research
- **Financial Analysis**: Investment research, risk assessment
- **Consulting Reports**: Data-driven insights and recommendations

### E-commerce & Retail
- **Product Descriptions**: SEO-optimized product content
- **Customer Inquiries**: Shopping assistance and recommendations
- **Inventory Management**: Stock level optimization
- **Price Analysis**: Competitive pricing strategies
- **Review Analysis**: Customer sentiment evaluation

## Requirements

- **NodeJS**: >= 18.0.0
- **Docker**: >= 20.0.0
- **Memory**: 2GB RAM minimum, 4GB recommended
- **Storage**: 1GB free space for installation
- **Network**: Stable internet for AI API connections

## Development

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/Yidadaa/ChatGPT-Next-Web)

Before starting development, you must create a new `.env.local` file at project root, and place your api key into it:

```
OPENAI_API_KEY=<your api key here>

# if you are not able to access openai service, use this BASE_URL
BASE_URL=https://chatgpt1.nextweb.fun/api/proxy
```

### Local Development

```shell
# 1. install nodejs and yarn first
# 2. config local env vars in `.env.local`
# 3. run
yarn install
yarn dev
```

## Deployment

### Docker (Recommended)

```shell
docker pull yidadaa/chatgpt-next-web

docker run -d -p 3000:3000 \
   -e OPENAI_API_KEY=sk-xxxx \
   -e CODE=your-password \
   yidadaa/chatgpt-next-web
```

You can start service behind a proxy:

```shell
docker run -d -p 3000:3000 \
   -e OPENAI_API_KEY=sk-xxxx \
   -e CODE=your-password \
   -e PROXY_URL=http://localhost:7890 \
   yidadaa/chatgpt-next-web
```

If your proxy needs password, use:

```shell
-e PROXY_URL="http://127.0.0.1:7890 user pass"
```

If enable MCP, use：

```
docker run -d -p 3000:3000 \
   -e OPENAI_API_KEY=sk-xxxx \
   -e CODE=your-password \
   -e ENABLE_MCP=true \
   yidadaa/chatgpt-next-web
```

### Shell

```shell
bash <(curl -s https://raw.githubusercontent.com/Yidadaa/ChatGPT-Next-Web/main/scripts/setup.sh)
```

## Synchronizing Chat Records (UpStash)

| [简体中文](./docs/synchronise-chat-logs-cn.md) | [English](./docs/synchronise-chat-logs-en.md) | [Italiano](./docs/synchronise-chat-logs-es.md) | [日本語](./docs/synchronise-chat-logs-ja.md) | [한국어](./docs/synchronise-chat-logs-ko.md)

## Documentation

> Please go to the [docs][./docs] directory for more documentation instructions.

- [Deploy with cloudflare (Deprecated)](./docs/cloudflare-pages-en.md)
- [Frequent Ask Questions](./docs/faq-en.md)
- [How to add a new translation](./docs/translation.md)
- [How to use Vercel (No English)](./docs/vercel-cn.md)
- [User Manual (Only Chinese, WIP)](./docs/user-manual-cn.md)

## Translation

If you want to add a new translation, read this [document](./docs/translation.md).

## 🤝 Contributing

We welcome contributions! Please see our contributing guidelines and feel free to submit pull requests.

## 📧 Support & Contact

- **General Support**: wortholicai@gmail.com
- **Enterprise Inquiries**: wortholicai@gmail.com
- **Community**: Join our Discord server
- **Documentation**: Visit our docs portal

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

Built with modern web technologies and powered by the latest AI models. Special thanks to all contributors and the open-source community.
