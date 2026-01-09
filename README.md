# Java Legacy AI

> AI-powered toolkit for developers maintaining legacy Java projects with old JDK versions and proprietary frameworks.

[English](#english) | [中文](#中文)

---

## 中文

### 🎯 这个项目是做什么的？

如果你正在维护：
- ✅ JDK 7/8 的老项目
- ✅ 使用内部框架/闭源框架的系统
- ✅ 文档不全的祖传代码
- ✅ AI工具（如Cursor、Copilot）经常给出不适用的建议

**这个工具能帮你：**
- 📝 构建项目专属的AI知识库
- 🤖 生成适配老技术栈的prompt模板
- 🔍 自动扫描代码库，提取项目特征
- ⚡ 让AI真正理解你的项目，写出能用的代码

### 🚀 快速开始

**1. 扫描你的项目**
```bash
python tools/code-scanner.py /path/to/your/project
```

**2. 生成项目上下文**
```bash
# 输出一个 project-context.md，包含框架信息、代码风格等
```

**3. 使用prompt模板**
查看 `docs/prompts/` 目录，复制适合的模板，喂给AI（Claude、GPT-4等）

### 📚 核心功能

#### 1. Prompt 模板库
针对老Java项目优化的prompt模板：
- 代码生成模板
- 代码审查模板  
- 重构建议模板
- Bug修复模板

#### 2. 代码扫描工具
自动分析项目：
- 识别使用的框架（即使是内部框架）
- 提取常用代码模式
- 生成项目特征文档

#### 3. 实战案例
真实场景下的使用示例：
- 如何让AI理解你的DAO层写法
- 如何处理老版本Spring的特殊配置
- 如何应对没有文档的内部框架

### 🛠️ 工具列表

| 工具 | 说明 | 状态 |
|------|------|------|
| code-scanner | 扫描项目并生成上下文 | ✅ Alpha |
| prompt-generator | 智能生成适配prompt | 🚧 开发中 |
| IDE插件 | IDEA/Eclipse插件 | 📋 计划中 |

### 💡 使用场景

**场景1：新功能开发**
```
问题：AI不懂我们的内部框架，生成的代码跑不起来
解决：使用项目上下文 + 代码生成模板，让AI按项目风格写代码
```

**场景2：代码维护**
```
问题：接手祖传代码，看不懂业务逻辑
解决：用AI生成代码注释和文档，快速理解
```

**场景3：技术债务**
```
问题：想重构老代码，但不敢动
解决：AI辅助生成测试用例，安全重构
```

### 📖 文档

- [快速开始指南](docs/getting-started.md)
- [Prompt模板库](docs/prompts/)
- [实战案例](docs/examples/)
- [常见问题](docs/faq.md)

### 🤝 贡献

欢迎提交：
- 你的prompt模板
- 你的实战经验
- 工具改进建议
- Bug反馈

### 📬 联系方式

- 问题反馈：[Issues](https://github.com/yourname/java-legacy-ai/issues)
- 讨论交流：[Discussions](https://github.com/yourname/java-legacy-ai/discussions)

### ⭐ Star History

如果这个项目对你有帮助，请给一个Star支持！

### 📄 开源协议

MIT License - 可自由用于商业项目

---

## English

### 🎯 What is this?

A toolkit for developers working with legacy Java codebases (JDK 7/8) and proprietary frameworks, designed to make AI coding assistants actually useful.

### 🚀 Quick Start
```bash
# 1. Scan your project
python tools/code-scanner.py /path/to/project

# 2. Use prompt templates
# Check docs/prompts/ for templates
```

### 📚 Features

- 📝 Project-specific context generation
- 🤖 Optimized prompt templates for legacy Java
- 🔍 Code pattern extraction
- ⚡ Make AI understand your proprietary frameworks

[Full documentation](docs/getting-started.md)

---

## Roadmap

- [x] Basic prompt templates
- [x] Code scanner tool
- [ ] IDEA plugin
- [ ] Framework knowledge base builder
- [ ] Community template sharing

---

**Made with ❤️ by developers who maintain legacy systems**
