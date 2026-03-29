# HuggingFace Follow List

IKUN-LLM 项目关注的 HuggingFace 组织和模型，按相关性分层。

## Tier 1 — 直接相关（必须关注）

| 组织 | HuggingFace | 关注理由 |
|------|------------|---------|
| MiniMind | [jingyaogong](https://huggingface.co/jingyaogong) | 基座模型作者，更新直接影响 ikun-2.5B |
| Qwen (通义) | [Qwen](https://huggingface.co/Qwen) | 中文最强开源模型，SFT/DPO/GRPO 技术标杆 |
| DeepSeek | [deepseek-ai](https://huggingface.co/deepseek-ai) | GRPO 发明者，ikun-GRPO 直接参考 |
| ChatGLM | [THUDM](https://huggingface.co/THUDM) | 中文对话模型先驱，GLM-4/CogVideo |

## Tier 2 — 小模型 & 高效微调（技术路线相同）

| 组织 | HuggingFace | 关注理由 |
|------|------------|---------|
| Microsoft | [microsoft](https://huggingface.co/microsoft) | Phi 系列小模型（1.5B-3.8B），小模型也能很强 |
| Google | [google](https://huggingface.co/google) | Gemma 系列，小参数开源标杆 |
| SmolLM | [HuggingFaceTB](https://huggingface.co/HuggingFaceTB) | HF 官方超小模型（135M-1.7B），和 26M 定位接近 |
| unsloth | [unsloth](https://huggingface.co/unsloth) | LoRA/QLoRA 训练加速，微调必备 |
| MiniCPM | [openbmb](https://huggingface.co/openbmb) | 小模型 + 多模态，技术路线最接近 |

## Tier 3 — 中文生态 & 多模态

| 组织 | HuggingFace | 关注理由 |
|------|------------|---------|
| Yi (零一万物) | [01-ai](https://huggingface.co/01-ai) | 优秀的中文开源模型 |
| 书生浦语 | [internlm](https://huggingface.co/internlm) | 上海 AI 实验室出品，中文能力强 |
| InternVL | [OpenGVLab](https://huggingface.co/OpenGVLab) | 视觉语言模型，参考 ikun-V |
| 百川 | [baichuan-inc](https://huggingface.co/baichuan-inc) | 中文能力强，对标 Qwen |
| 阶跃星辰 | [stepfun-ai](https://huggingface.co/stepfun-ai) | 国产大模型新势力 |

## Tier 4 — 前沿商业模型开源动态

| 公司 (产品) | HuggingFace | 开源了什么 | 关注理由 |
|------------|------------|-----------|---------|
| Anthropic (Claude) | [anthropics](https://huggingface.co/anthropics) | 研究论文相关资源 | 最强模型之一，安全对齐研究 |
| OpenAI (GPT) | [openai](https://huggingface.co/openai) | Whisper, CLIP, GPT-2 | CLIP 对 ikun-V 多模态有参考价值 |
| xAI (Grok) | [xai-org](https://huggingface.co/xai-org) | Grok-1/2 开源权重 | 314B MoE 架构，参考 ikun-MoE |
| Moonshot (Kimi) | [moonshotai](https://huggingface.co/moonshotai) | Kimi-Dev 等开源项目 | 长上下文技术先驱 |
| MiniMax | [MiniMaxAI](https://huggingface.co/MiniMaxAI) | MiniMax-Text/Speech-01 | 国产大模型+语音，MoE 架构参考 |
| Stability AI | [stabilityai](https://huggingface.co/stabilityai) | Stable Diffusion / StableLM | 图像生成标杆 |
| Cohere | [CohereForAI](https://huggingface.co/CohereForAI) | Command-R / Aya 多语言 | 多语言模型技术 |
| Apple | [apple](https://huggingface.co/apple) | OpenELM / CLIP variants | 端侧小模型，小参数定位一致 |
| Meta (Llama) | [meta-llama](https://huggingface.co/meta-llama) | Llama 全系列 | 模型架构就是 LlamaForCausalLM |
| Mistral | [mistralai](https://huggingface.co/mistralai) | Mixtral MoE 系列 | MoE 架构先驱，参考 ikun-MoE |
| HuggingFace H4 | [HuggingFaceH4](https://huggingface.co/HuggingFaceH4) | Zephyr 等对齐模型 | DPO/RLHF 研究参考 |

## 按学习路线的对应关系

```
ikun-tokenizer  ←── Qwen (tiktoken), Google (SentencePiece)
ikun-pretrain   ←── SmolLM, Apple OpenELM, MiniMind
ikun-2.5B SFT   ←── Qwen, THUDM GLM, unsloth
ikun-DPO        ←── HuggingFaceH4, Anthropic 对齐研究
ikun-GRPO       ←── DeepSeek-R1, Qwen3
ikun-Reason     ←── DeepSeek-R1, Qwen-QwQ
ikun-MoE        ←── Mistral Mixtral, xAI Grok, MiniMax, DeepSeek-V3
ikun-Distill    ←── Microsoft Phi, openbmb MiniCPM
ikun-V          ←── OpenAI CLIP, OpenGVLab InternVL, openbmb MiniCPM-V
ikun-deploy     ←── unsloth (GGUF), vLLM, Ollama
```

## 关注节奏

| 频率 | 做什么 |
|------|--------|
| 每天 | 刷 HuggingFace 首页 Trending Models |
| 每周 | 检查 Tier 1 组织有没有新发布 |
| 每月 | 看 Open LLM Leaderboard 排名变化 |
| 随时 | 在关注组织的 Discussion 里互动留评论 |
