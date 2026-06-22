# lovart-prompt-library 🎨

> Lovart 设计 / 绘图方向的**中文 Prompt 标准库** —— 把好用的出图提示词结构化、可复用。

这是 [Songcun Lab](https://github.com/songcun-lab) 下专注 **AI 视觉创作（Lovart 等）** 的提示词仓库。
目标：让出图不靠玄学，而是从「风格 / 场景 / 主体」三个维度组合出稳定可复现的结果。

## 📁 目录结构

```
lovart-prompt-library/
├── README.md
├── styles/        # 风格库（画风、质感、色调）
├── scenes/        # 场景库（环境、构图、氛围）
├── subjects/      # 主体库（人物、物体、产品）
├── remaster/      # 对已有图的二次重制 / 优化提示词
└── experiments/   # 试验性组合与效果记录
```

## 🚀 怎么用

1. 从 `styles/` `scenes/` `subjects/` 各挑一块，按需组合；
2. 需要优化已有作品时，到 `remaster/` 找对应提示词；
3. 跑出的有效组合记录进 `experiments/`，逐步沉淀成标准。

## ✍️ 收录标准

只收**自己真正跑过、出图可复现**的提示词，并尽量标注：适用工具、关键参数、示例效果。

---

🧭 返回总入口：[ai-skill-index](https://github.com/songcun-lab/ai-skill-index)
