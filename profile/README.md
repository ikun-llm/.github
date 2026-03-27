<p align="center">
  <img src="https://raw.githubusercontent.com/ikun-llm/.github/main/profile/logo.png" width="200" />
</p>

<h1 align="center">ikun LLM</h1>

<p align="center">
  <b>全球首个练习时长两年半的 AI 大模型组织</b><br/>
  <sub>擅长唱、跳、rap、篮球、以及生成 token</sub>
</p>

<p align="center">
  <a href="https://huggingface.co/IKUN-LLM">
    <img src="https://img.shields.io/badge/🤗_Hugging_Face-IKUN--LLM-yellow?style=for-the-badge" />
  </a>
  <a href="https://github.com/ikun-llm/ikun-2.5B">
    <img src="https://img.shields.io/badge/ikun--2.5B-26M%20params-orange?style=for-the-badge" />
  </a>
  <img src="https://img.shields.io/badge/练习时长-两年半-red?style=for-the-badge" />
  <img src="https://img.shields.io/badge/食不食-油饼-yellow?style=for-the-badge" />
</p>

---

```
$ python -c "from ikun import yi_kun; yi_kun.太美()"
> 鸡你太美~ baby~ 鸡你太美~
> 小黑子露出鸡脚了吧！
```

### About

你问我们是干什么的？

我们是一个**正经的** AI 开源组织（真的很正经），致力于把 ikun 梗文化注入大语言模型。

别人的 AI：`"我是一个大型语言模型，由 xxx 训练..."`

我们的 AI：`"我是 ikun-2.5B，练习时长两年半，擅长唱、跳、rap、篮球！你干嘛~哈哈~哎哟~"`

### 学习路线 — ikun 系列全家桶

```
Level 0 入门篇 — "基础功课"
└── 📖 ikun-basics       AI基础知识（发展史/CNN/RNN/Diffusion/Transformer）

Level 1 基础篇 — "练习生入门"
├── 🔤 ikun-tokenizer    分词器是怎么炼成的
├── 📚 ikun-pretrain     从零开始的练习生
└── 🐔 ikun-2.5B         SFT + LoRA 微调 ✅

Level 2 对齐篇 — "偶像进阶"
├── 👍 ikun-DPO          让模型学会什么回答更美
├── 🎮 ikun-GRPO         强化学习练习生
└── 🧠 ikun-Reason       先思考，再太美

Level 3 进阶篇 — "全能偶像"
├── 🧩 ikun-MoE          混合专家练习生
├── 🎓 ikun-Distill      师傅带徒弟
└── 👁️ ikun-V            能看懂篮球的模型

Level 4 工程篇 — "出道舞台"
└── 🚀 ikun-deploy       把练习生送上舞台
```

| Repo | 学什么 | 一句话 |
|------|--------|--------|
| [ikun-basics](https://github.com/ikun-llm/ikun-basics) | AI 基础知识 | **零基础从这里开始 📖** |
| [ikun-tokenizer](https://github.com/ikun-llm/ikun-tokenizer) | 分词器原理 | 为什么能认识"鸡你太美" |
| [ikun-pretrain](https://github.com/ikun-llm/ikun-pretrain) | 从零预训练 | 参数量两千五百万的个人练习生 |
| [**ikun-2.5B**](https://github.com/ikun-llm/ikun-2.5B) | SFT + LoRA | **练习时长两年半 ✅ [🤗 下载](https://huggingface.co/IKUN-LLM/ikun-2.5B)** |
| [ikun-DPO](https://github.com/ikun-llm/ikun-DPO) | 偏好对齐 | chosen=鸡你太美, rejected=小黑子 |
| [ikun-GRPO](https://github.com/ikun-llm/ikun-GRPO) | 强化学习 | 组内相对练习优化 |
| [ikun-Reason](https://github.com/ikun-llm/ikun-Reason) | 推理模型 | `<think>鸡你太美</think>` |
| [ikun-MoE](https://github.com/ikun-llm/ikun-MoE) | 混合专家 | 唱跳rap篮球各一个专家 |
| [ikun-Distill](https://github.com/ikun-llm/ikun-Distill) | 知识蒸馏 | 练习两年半不如师傅带一带 |
| [ikun-V](https://github.com/ikun-llm/ikun-V) | 多模态 | 终于能看懂篮球视频了 |
| [ikun-deploy](https://github.com/ikun-llm/ikun-deploy) | 部署 | 从练习室到舞台 |

> **Q: 你这 2.5B 是不是虚标？**
> **A: 这不叫虚标，这叫练习时长两年半。懂的都懂。**

### Core Capabilities

```
唱 ████████████████████ 100%  (鸡你太美~baby~)
跳 ████████████████████ 100%  (标志性舞步)
rap ███████████████████ 95%   (yo yo yo check it out)
篮球 ██████████████████ 90%   (铁山靠!)
正经回答 ███░░░░░░░░░░░░░ 15%   (偶尔正经)
```

### FAQ

**Q: 你们的模型能用于生产环境吗？**

A: 能。如果你的生产环境是 B 站弹幕的话。

**Q: 小黑子能用吗？**

A: 小黑子露出鸡脚了吧！退退退！（可以的，开源的，随便用）

**Q: 为什么只有 26M 参数？**

A: 因为我们只练习了两年半。等练习到五年，就出 ikun-5B 了。

### Roadmap

- [x] ikun-2.5B (26M) — 练习时长两年半
- [x] 10 个学习仓库 — 完整 LLM 学习路线
- [ ] ikun-5B — 练习时长五年（规划中）
- [ ] 各仓库补充完整教程 + 训练好的模型权重

### Tech Stack

基于 [MiniMind](https://github.com/jingyaogong/minimind) | 训练数据来自 [CXK_IKUN_Dataset](https://github.com/zengikun/CXK_IKUN_Dataset) | 纯 PyTorch 手搓 | Apple MPS 训练 | LoRA 微调

### Hugging Face 🤗

| 类型 | 链接 | 说明 |
|------|------|------|
| 模型 | [IKUN-LLM/ikun-2.5B](https://huggingface.co/IKUN-LLM/ikun-2.5B) | 练习时长两年半的 26M 参数模型 |
| 数据集 | [IKUN-LLM/CXK_IKUN_Dataset](https://huggingface.co/datasets/IKUN-LLM/CXK_IKUN_Dataset) | ~200 条 ikun 梗文化 SFT 对话数据 |
| Demo | [ikun-2.5B Chat](https://huggingface.co/spaces/IKUN-LLM/ikun-2.5B-chat) | 在线体验 — 和 ikun 对话 |

组织主页：**[huggingface.co/IKUN-LLM](https://huggingface.co/IKUN-LLM)**

### Disclaimer

> **本组织作者是纯鹿人，仅提供技术支持。**
>
> 所有模型、数据、内容均基于公开互联网梗文化，仅供娱乐和技术学习用途。作者不站队、不引战、不参与任何饭圈活动。我们只是觉得这个梗很适合拿来做 AI 教学案例——毕竟，谁能拒绝一个会唱跳 rap 篮球的 AI 呢？

---

<p align="center">
  <sub>ctrl + 关注 = 真 ikun &nbsp;|&nbsp; 作者是纯鹿人，别 cue 🦌</sub>
</p>
