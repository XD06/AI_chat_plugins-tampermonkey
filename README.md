# AI聊天助手 (AI Chat Assistant) - Tampermonkey用户脚本

![Tampermonkey](https://img.shields.io/badge/Tampermonkey-UserScript-green?logo=tampermonkey)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow?logo=javascript)
![License](https://img.shields.io/badge/License-MIT-blue)
![Version](https://img.shields.io/badge/Version-3.0.0-brightgreen)

> 🚀 **这是一个专为Tampermonkey/Greasemonkey设计的用户脚本** - 为任何网页添加强大的AI聊天功能，支持代码执行、网页内容提取、对话管理等高级特性。

## 🚀 一键安装

### 📦 立即安装脚本

> **重要**: 请先安装Tampermonkey扩展，然后点击下方链接一键安装脚本

<div align="center">

**🎯 点击下方按钮直接安装脚本**

[![一键安装脚本](https://img.shields.io/badge/%E4%B8%80%E9%94%AE%E5%AE%89%E8%A3%85-Install%20Script-success?style=for-the-badge&logo=tampermonkey)](https://github.com/XD06/AI_chat_plugins-tampermonkey-/raw/main/AI_chat_assistant.user.js)

</div>

**安装链接**: https://github.com/XD06/AI_chat_plugins-tampermonkey-/raw/main/AI_chat_assistant.user.js

> 💡 **安装提示**: 点击上方链接后，Tampermonkey会自动检测并提示安装脚本

## 🔧 完整安装指南

### 第一步：安装用户脚本管理器

选择对应浏览器的扩展：

<table align="center">
<tr>
<th>浏览器</th>
<th>推荐扩展</th>
<th>安装链接</th>
</tr>
<tr>
<td>🔵 Chrome</td>
<td>Tampermonkey</td>
<td><a href="https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo" target="_blank">Chrome Web Store</a></td>
</tr>
<tr>
<td>🟠 Firefox</td>
<td>Tampermonkey</td>
<td><a href="https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/" target="_blank">Firefox Add-ons</a></td>
</tr>
<tr>
<td>🔷 Edge</td>
<td>Tampermonkey</td>
<td><a href="https://microsoftedge.microsoft.com/addons/detail/tampermonkey/iikmkjmpaadaobahmlepeloendndfphd" target="_blank">Edge Add-ons</a></td>
</tr>
<tr>
<td>🟡 Safari</td>
<td>Tampermonkey</td>
<td><a href="https://apps.apple.com/us/app/tampermonkey/id1482490089" target="_blank">App Store</a></td>
</tr>
</table>

### 第二步：安装AI聊天助手脚本

#### 🎯 方法一：一键安装（强烈推荐）

1. 确保已安装Tampermonkey扩展
2. 点击安装链接：https://github.com/XD06/AI_chat_plugins-tampermonkey-/raw/main/AI_chat_assistant.user.js
3. Tampermonkey会自动打开安装页面
4. 点击 **"安装"** 按钮即可完成

#### 🔧 方法二：手动安装

<details>
<summary>点击展开手动安装步骤</summary>

1. 复制脚本代码：[点击查看源码](https://github.com/XD06/AI_chat_plugins-tampermonkey-/blob/main/AI_chat_assistant.user.js)
2. 打开Tampermonkey扩展面板
3. 点击 "Create a new script"
4. 删除默认内容，粘贴脚本代码
5. 按 `Ctrl+S` 保存脚本
6. 确保脚本状态为 "已启用"

</details>

### 第三步：配置API密钥

1. **获取API密钥**（选择其中一个）：
   - [DeepSeek API](https://platform.deepseek.com/) - 推荐，支持思考过程显示
   - [OpenAI API](https://platform.openai.com/)
   - [GLM API](https://open.bigmodel.cn/)
   - [SiliconFlow API](https://siliconflow.cn/)

2. **配置脚本**：
   - 访问任意网页，找到右下角的AI图标🤖
   - 点击图标打开聊天窗口
   - 点击设置按钮🖋️进入配置界面
   - 填入API信息并保存

## 📖 详细使用教程

### 🎮 基本操作

#### 1. 启动聊天助手
```
1. 访问任意网页（如：百度、GitHub、知乎等）
2. 找到页面右下角的AI图标🤖
3. 点击图标即可打开聊天窗口
4. 开始与AI对话！
```

#### 2. 发送消息
```
📝 输入方式：
- 在输入框中输入问题
- 按Enter键发送
- 或点击发送按钮▶️

💬 对话示例：
用户: "请解释一下什么是机器学习"
AI: "机器学习是人工智能的一个分支..."
```

#### 3. 特殊功能按钮
```
🖋️ 设置按钮 - 配置API密钥和参数
📄 总结按钮 - 一键总结当前网页内容  
🎨 清空按钮 - 清除所有聊天记录
🗂️ 导出按钮 - 导出对话记录
🌐 网页上下文开关 - 是否包含页面内容
🌀 流式输出开关 - 实时显示回答过程
```

### 🐍 Python代码执行

#### 基础代码执行
```python
# 直接在对话中发送Python代码，系统会自动识别
print("Hello, AI Assistant!")

# 数学计算
import math
result = math.sqrt(16)
print(f"√16 = {result}")
```

#### 数据可视化
```python
# 绘制图表
import matplotlib.pyplot as plt
import numpy as np

# 生成数据
x = np.linspace(0, 2*np.pi, 100)
y = np.sin(x)

# 创建图表
plt.figure(figsize=(10, 6))
plt.plot(x, y, 'b-', linewidth=2, label='sin(x)')
plt.title('正弦函数图像')
plt.xlabel('x轴')
plt.ylabel('y轴')
plt.grid(True)
plt.legend()
plt.show()  # 图表会直接显示在聊天窗口中
```

## 🌟 项目概述

AI聊天助手是一个基于用户脚本的智能聊天工具，可以在**任何网页**上注入AI对话功能。它不仅支持基本的文本对话，还具备Python代码执行、网页内容分析、多格式导出等高级功能，是您的全能AI助理。

### 🔥 核心特点
- ✅ **零安装部署** - 仅需浏览器扩展，无需其他软件
- ✅ **全网站兼容** - 在任何网页上都能使用
- ✅ **代码执行环境** - 内置Python运行时(Pyodide)
- ✅ **智能内容提取** - 自动分析当前网页内容
- ✅ **多AI模型支持** - 兼容各种OpenAI格式API

## ✨ 功能特性

### 🤖 AI对话功能
- **多AI模型支持**: 兼容DeepSeek、GLM、GPT、Claude等多种AI API
- **流式输出**: 支持实时流式响应，提供更好的交互体验
- **思考过程显示**: 支持显示AI的推理过程（如DeepSeek-V3等模型）
- **上下文管理**: 智能对话历史管理和截断

### 💻 代码执行环境
- **Python执行**: 基于Pyodide v0.26.0，支持在浏览器中运行Python代码
- **科学计算支持**: 预装NumPy、Pandas、Matplotlib等科学计算库
- **HTML/CSS/JS执行**: 实时预览网页代码效果
- **代码高亮**: 自动语法高亮和格式化
- **一键复制**: 便捷的代码复制功能

### 🌐 网页内容提取
- **智能抓取**: 多策略网页主要内容提取
- **自定义选择器**: 支持CSS选择器自定义抓取规则
- **内容总结**: 一键总结当前网页内容
- **上下文增强**: 将网页内容作为AI对话上下文

### 🎨 用户界面
- **拖拽窗口**: 支持拖拽移动聊天窗口和图标
- **自适应主题**: 根据网页颜色自动调整界面主题
- **全屏模式**: 支持全屏显示聊天界面
- **响应式设计**: 适配不同屏幕尺寸和移动设备

### 📊 数据管理
- **对话历史**: 自动保存和管理对话记录
- **多格式导出**: 支持TXT、HTML、Markdown、JSON格式导出
- **配置备份**: 自动保存用户配置和历史记录
- **参数自定义**: 支持自定义API请求参数

## 📁 项目结构

```
油猴ai聊天插件/
├── AI_chat_assistant.user.js    # 主要脚本文件（4951行）
├── README.md                    # 项目说明文档
├── TECH_DOC.md                 # 详细技术文档
└── LICENSE                      # MIT开源许可证
```

## 🛠️ 技术架构

- **核心语言**: JavaScript (ES6+)
- **用户脚本引擎**: Greasemonkey/Tampermonkey API
- **Python运行时**: Pyodide v0.26.0 (WebAssembly)
- **Markdown解析**: Marked.js
- **代码高亮**: Highlight.js (Agate主题)
- **存储方案**: GM_setValue/GM_getValue (浏览器本地存储)
- **网络请求**: GM_xmlhttpRequest (跨域支持)

## 🔧 高级配置

### 自定义API参数
```javascript
// 在设置界面的"自定义额外参数"中添加
{
  "top_p": 0.8,
  "frequency_penalty": 0.1,
  "presence_penalty": 0.1,
  "max_tokens": 8192
}
```

### 自定义网页抓取规则
```css
/* 在自定义抓取规则中设置CSS选择器 */
.article-content, #main-content, .post-body, article
```

### 支持的AI服务商
- **DeepSeek**: `https://api.deepseek.com/v1/chat/completions`
- **OpenAI**: `https://api.openai.com/v1/chat/completions`
- **GLM**: `https://open.bigmodel.cn/api/paas/v4/chat/completions`
- **SiliconFlow**: `https://api.siliconflow.cn/v1/chat/completions`
- **其他兼容OpenAI格式的API服务**

## 🚨 注意事项

### 安全提醒
- 🔐 **API密钥安全**: 请妥善保管您的API密钥，不要在公共场所或截图中泄露
- 🌐 **网络安全**: 建议使用HTTPS的API端点
- 💾 **数据隐私**: 对话记录保存在浏览器本地，不会上传到第三方服务器

### 性能考虑
- 🧠 **内存使用**: Python环境首次加载需要50-100MB内存
- ⚡ **网络流量**: 流式输出和Pyodide加载需要较好的网络环境
- 🔄 **浏览器兼容**: 需要支持WebAssembly的现代浏览器

### 使用限制
- 📊 **API限制**: 请遵守API服务商的调用频率限制
- 🔒 **同源策略**: 部分网站可能因安全策略限制脚本功能
- 📱 **移动端**: 移动浏览器功能可能受限

## 🐛 常见问题

<details>
<summary><strong>Q: 脚本安装后没有显示图标？</strong></summary>

**A**: 检查以下几点：
1. 确认Tampermonkey扩展已启用
2. 检查脚本是否在Tampermonkey中正常运行
3. 刷新页面或重启浏览器
4. 检查是否有其他扩展冲突
</details>

<details>
<summary><strong>Q: API调用失败怎么办？</strong></summary>

**A**: 排查步骤：
1. 检查网络连接是否正常
2. 验证API密钥是否正确且有效
3. 确认API地址格式正确
4. 查看浏览器开发者工具的错误信息
</details>

<details>
<summary><strong>Q: Python代码执行失败？</strong></summary>

**A**: 可能原因：
1. 浏览器不支持WebAssembly
2. 网络环境导致Pyodide加载失败
3. 代码语法错误或使用了不支持的库
4. 内存不足导致执行失败
</details>

<details>
<summary><strong>Q: 如何备份我的配置和对话历史？</strong></summary>

**A**: 两种方式：
1. 使用脚本内置的导出功能（🗂️按钮）
2. 手动备份Tampermonkey的脚本存储数据
</details>

## 🔄 更新日志

### v3.0.0 (2025-01-XX)
- ✨ 全新UI设计，支持自适应主题
- 🐍 集成Pyodide Python环境
- 🌊 新增流式响应支持
- 📊 多格式对话导出功能
- 🎯 智能网页内容提取
- 🔧 自定义API参数支持

### v2.x.x
- 基础AI对话功能
- 简单的网页内容获取
- 基本配置管理

## 📄 开源协议

本项目采用 [MIT License](LICENSE) 开源协议，允许自由使用、修改和分发。

## 🤝 贡献指南

欢迎参与项目开发！您可以：

### 报告问题
- 在 [Issues](https://github.com/XD06/AI_chat_plugins-tampermonkey-/issues) 中报告Bug
- 提出功能建议和改进意见

### 贡献代码
1. Fork 本仓库
2. 创建特性分支: `git checkout -b feature/AmazingFeature`
3. 提交更改: `git commit -m 'Add some AmazingFeature'`
4. 推送分支: `git push origin feature/AmazingFeature`
5. 提交Pull Request

### 参与讨论
- 加入开发者交流群
- 参与功能设计讨论
- 分享使用经验和技巧

## 📞 支持与反馈

### 获取帮助
- 📧 **邮件支持**: 发送问题到项目邮箱
- 💬 **在线讨论**: [GitHub Discussions](https://github.com/XD06/AI_chat_plugins-tampermonkey-/discussions)
- 🐛 **问题报告**: [GitHub Issues](https://github.com/XD06/AI_chat_plugins-tampermonkey-/issues)

### 社区资源
- 📚 **使用教程**: 查看Wiki文档
- 🎥 **视频演示**: B站/YouTube教程
- 👥 **用户群组**: QQ群/Discord频道

---

**🎉 感谢使用AI聊天助手！** 

如果这个项目对您有帮助，请考虑给我们一个⭐Star，这是对开发者最大的鼓励！


**⚡ 快速体验**: [安装脚本](https://github.com/XD06/AI_chat_plugins-tampermonkey-/raw/main/AI_chat_assistant.user.js) → 配置API → 开始对话 → 享受AI助手的强大功能 
