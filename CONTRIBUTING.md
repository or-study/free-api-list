# 贡献指南

感谢你对本项目的关注！我们非常欢迎并感谢所有形式的贡献！

## 📋 目录
- [代码贡献](#代码贡献)
- [报告 Bug](#报告-bug)
- [提交新 API](#提交新-api)
- [改进文档](#改进文档)
- [开发指南](#开发指南)

## 代码贡献

### 提交前准备

1. 先 Fork 本仓库
2. 克隆到本地：
```bash
git clone https://github.com/or-study/free-api-list.git
cd free-api-list
```
3. 创建分支：
```bash
git checkout -b feature/your-feature-name
```

### 代码规范

- 使用 2 空格缩进
- 使用有意义的变量/函数名
- 保持现有代码风格一致
- 确保所有链接可访问

### 提交规范

Commit 消息格式：
```
<type>(<scope>): <subject>

<body>

<footer>
```

Type 可选值：
- `feat`：新增功能
- `fix`：修复 Bug
- `docs`：文档更新
- `style`：格式调整
- `refactor`：重构
- `test`：测试相关
- `chore`：构建/工具链

## 报告 Bug

请使用 GitHub Issues，包含：
- 清晰的标题和描述
- 复现步骤
- 预期行为和实际行为
- 环境信息（浏览器版本/操作系统）
- 截图（如果合适）

## 提交新 API

添加新的免费 API 平台时，请提供：
1. 平台名称和官网
2. 注册流程
3. 免费额度详情
4. 价格信息（如有
5. 简单的调用示例
6. 截图（可选）

### 提交 PR 时请确保：
- 放在正确的分类（国内/国际/图像生成）
- API 信息已验证可访问
- 代码示例可运行

## 改进文档

帮助我们一起改进文档！

## 开发指南

### 本地开发
```bash
# 启动本地服务器
python3 -m http.server 8080
# 访问 http://localhost:8080
```

### 验证代码规范
我们使用 Prettier 进行代码格式化：
```bash
# 安装依赖（可选，但推荐）
npm install
# 格式化
npm run format
```

## Pull Request 流程

1. 确保 PR 前检查：
- [ ] 已阅读本贡献指南
- [ ] 已通过所有检查
- [ ] 更新了相关文档
- [ ] PR 标题清晰
- [ ] 描述了变更内容

## 行为准则

请遵循我们的行为准则：尊重他人，保持专业友好！

## 获得帮助

如有任何问题，请开 Issue！
