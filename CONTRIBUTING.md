# 贡献指南 | Contributing Guide

> 练习时长两年半的贡献者们，欢迎加入！🐔🏀

## 如何参与贡献

### 1. 提 Issue

发现了 bug？有新的想法？欢迎提 Issue！

- **Bug 报告**：使用 "Bug Report" 模板
- **功能建议**：使用 "Feature Request" 模板
- **新增梗素材**：使用 "新梗提交" 模板

### 2. 提交 PR

```bash
# 1. Fork 仓库
# 2. 创建分支
git checkout -b feat/your-feature

# 3. 修改代码
# 4. 提交
git commit -m "feat: 你的改动描述"

# 5. 推送并创建 PR
git push origin feat/your-feature
```

### 3. 贡献训练数据

ikun 模型的灵魂在于数据！欢迎贡献更多梗文化对话数据：

```json
{"conversations": [{"role": "user", "content": "你的问题"}, {"role": "assistant", "content": "ikun 风格的回答"}]}
```

**数据要求**：
- 格式为 JSONL，每行一条对话
- 回答需要体现 ikun 梗文化风格
- 不包含攻击性/违法内容
- 不涉及真实个人隐私

### 4. 参与讨论

每个仓库都开启了 Discussions，你可以：
- 💬 **General**：闲聊、提问
- 💡 **Ideas**：提出新功能/新方向
- 🙏 **Q&A**：技术问题求助
- 🎉 **Show and Tell**：展示你的 ikun 模型成果

### 5. 完善文档

每个仓库的 README 都是学习教程，欢迎：
- 补充原理讲解
- 修正错误
- 添加训练结果截图
- 翻译为其他语言

## Commit 规范

```
feat: 新功能
fix: 修复 bug
docs: 文档更新
data: 训练数据更新
style: 格式调整（不影响代码运行）
refactor: 重构
```

## 行为准则

- 友善交流，ikun 之间不互黑
- 纯鹿人精神：纯技术讨论，不引战
- 尊重每一个贡献者，不论练习时长
- 这是一个娱乐+学习项目，保持轻松愉快

## 联系方式

- GitHub Discussions：各仓库的 Discussions 板块
- Issue：各仓库的 Issue 板块

---

<p align="center"><sub>每一个 PR 都是一次练习，练习两年半就能成为贡献达人！</sub></p>
