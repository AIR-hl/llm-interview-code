# LLM Interview Code

**LLM面试手撕代码集合**

## 项目结构

```
llm-interview-code/
├── Attention/           # 注意力相关实现
│   ├── MHA.ipynb       # 多头注意力 (Multi-Head Attention)
│   ├── GQA.ipynb       # 分组查询注意力 (Grouped Query Attention)
│   ├── MHA_kvcache.ipynb # 带KV cache的注意力
│   └── mask.ipynb      # 注意力掩码
├── Components/          # 基础组件实现
│   ├── Linear.ipynb    # 线性层
│   ├── LayerNorm.ipynb # 层归一化
│   ├── RMSNorm.ipynb   # RMS归一化
│   ├── SwiGLU.ipynb    # SwiGLU
│   ├── RoPE.ipynb      # 旋转位置编码
│   ├── BPE.ipynb       # BPE
│   ├── DecoderLayer.ipynb # decoder层
│   └── LoRA.ipynb      # lora
└── Functional/         # 功能函数实现
    ├── activate_fun.ipynb # 激活函数
    ├── cross_entropy.ipynb # 交叉熵损失
    ├── dpo.ipynb       # dpo损失
    ├── kl.ipynb        # KL散度
    └── sft.ipynb       # sft损失
```
