# 🔥 免费 AI API 全平台汇总（2026年最新）

汇聚全球 **30+ 免费 AI API 平台**，覆盖国内直连和国际平台，无需翻墙的大模型 API 集合！

<div align="center">

[**立即体验 →**](https://your-github-username.github.io/free-api-list) | 
[**GitHub 仓库**](https://github.com/or-study/free-api-list) | 
[**加入交流**](#)

</div>

## 📊 平台总览

| 分类 | 数量 | 说明 |
|------|------|------|
| 🇨🇳 国内直连 | **14个** | 无需翻墙，适合国内用户 |
| 🌐 国际平台 | **12个** | 需要翻墙，模型更丰富 |
| 🎨 图像生成 | **3个** | 专注图像/视频生成 |
| ⚡ 前端/特殊 | **1个** | 无需后端，直接调用 |

## ✨ 核心特色

- ⚡ **无需注册体验**：部分平台（如 Pollinations）无需 API Key 直接调用
- 🎯 **OpenAI 兼容格式**：99% 平台支持直接替换 OpenAI SDK 的 `base_url` 和 `api_key`
- 📱 **美观响应式界面**：移动端完美适配，卡片动画，暗黑/明亮主题
- 📊 **真实额度信息**：所有免费配额、价格均为最新数据（2026.06）
- 🎨 **一键复制代码**：Python/JavaScript/Shell 代码示例一键复制
- 📈 **快速选型指南**：6个维度帮你快速找到最适合的平台

## 🚀 快速开始

### 访问方式

**GitHub Pages**（推荐）：[https://your-github-username.github.io/free-api-list](https://your-github-username.github.io/free-api-list)

**本地运行**：
```bash
git clone https://github.com/or-study/free-api-list.git
cd free-api-list
python3 -m http.server 8080
# 访问 http://localhost:8080
```

### Docker 部署
```bash
docker run -d -p 8080:80 -v $(pwd)/index.html:/usr/share/nginx/html/index.html nginx:alpine
```

## 🏆 推荐平台

### 国内直连（无需翻墙）
- **火山引擎**：每天 200 万 token 免费，永久每日重置（最慷慨）
- **智谱 AI**：2000万 token + GLM-4-Flash 永久免费
- **DeepSeek API**：500万 token 赠送，V4 超便宜（缓存命中 ¥0.02/百万）
- **超算互联网**：国家超算中心，100万 token 免费

### 国际平台（需要翻墙）
- **Mistral AI**：10亿 token/月 永久免费（额度最大）
- **GitHub Models**：GitHub 官方，免费 GPT-4o / Llama-4 / DeepSeek-R1
- **Hugging Face**：10万+ 开源模型免费调用
- **Puter.js**：前端直接调用 400+ 模型，无需后端

## 📁 项目结构

```
free-api-list/
├── index.html                          # 主页面
├── README.md                           # 项目说明
├── CONTRIBUTING.md                     # 贡献指南
├── CODE_OF_CONDUCT.md                  # 行为准则
├── LICENSE                             # 许可证
├── package.json                        # 项目配置
├── .github/
│   ├── workflows/
│   │   ├── deploy.yml                  # GitHub Pages 自动部署
│   │   └── auto-update.yml             # API 信息自动更新
│   └── ISSUE_TEMPLATE/
│       ├── bug_report.md
│       └── feature_request.md
├── scripts/
│   ├── scrape-apis.js                  # API 信息爬取工具
│   └── validate-json.js                # 数据验证脚本
└── docs/
    ├── usage.md                        # 使用指南
    └── monetization.md                 # 变现方案
```

## 🤝 贡献指南

欢迎加入我们！详细信息请查看 [CONTRIBUTING.md](CONTRIBUTING.md)。

**贡献方式**：
- 📝 更新 API 信息
- ✨ 添加新平台
- 🐛 修复 Bug
- 📚 完善文档
- 🎨 改进 UI/UX

## 💡 变现模式设计

为了帮助项目长期可持续发展，我们设计了完整的商业变现方案，详情见 [docs/monetization.md](docs/monetization.md)。

**主要方向**：
1. 💰 **付费会员计划**：高级工具、专属 API 代理
2. 🤝 **企业服务**：API 聚合代理、私有化部署
3. 📦 **SDK / 脚手架**：开箱即用的开发工具包
4. 📊 **API 监控与优化**：性能监控、智能路由服务
5. 🎓 **培训与咨询**：AI 工程化课程、企业咨询
6. 🔗 **联盟佣金**：与云平台的分成合作

## 🔒 免责声明

- 本项目仅供学习和研究使用，**所有 API 配额与价格信息来源于各平台公开文档，仅供参考，实际以各平台官方最新数据为准**
- 使用这些 API 时**请严格遵守各平台的服务条款**
- **不要滥用免费额度**，保持理性使用

## 📄 许可证

本项目采用 **MIT 许可证**，详见 [LICENSE](LICENSE) 文件。

## 🙏 致谢

感谢所有贡献者和所有提供免费配额的 AI 平台！

---

<div align="center">

如果这个项目对你有帮助，请给我们一个 ⭐ Star！

</div>
