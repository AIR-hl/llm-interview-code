# LLM Interview Code

**LLM面试常见手撕代码集合**

> ps: 本人仅遇到过MHA, RoPE, RMSNorm, DPO

## 项目结构

```
llm-interview-code/
├── Attention/           # 注意力相关实现
│   ├── MHA.ipynb        # 多头注意力 (Multi-Head Attention)
│   ├── GQA.ipynb        # 分组查询注意力 (Grouped Query Attention)
│   ├── MHA_kvcache.ipynb # 带KV cache的注意力
│   └── mask.ipynb       # 注意力掩码
├── Components/         # 基础组件实现
│   ├── Linear.ipynb    # 线性层
│   ├── LayerNorm.ipynb # 层归一化
│   ├── RMSNorm.ipynb   # RMS归一化
│   ├── SwiGLU.ipynb    # SwiGLU
│   ├── RoPE.ipynb      # 旋转位置编码
│   ├── BPE.ipynb       # BPE
│   └── LoRA.ipynb      # lora linear 层
└── Functional/         # 功能函数实现
    ├── activation_fun.ipynb # 激活函数
    ├── CE.ipynb        # 交叉熵损失
    ├── DPO.ipynb       # DPO损失
    ├── GRPO.ipynb      # GRPO损失
    ├── InfoNCE.ipynb   # InfoNCE损失
    ├── KL.ipynb        # KL散度
    └── SFT.ipynb       # SFT损失
```
