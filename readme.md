# LLM Interview Code

**LLM面试常见手撕代码合集**

> ps: 本人目前几十场面试仅遇到过 `MHA`, `RoPE`, `RMSNorm`, `BPE`。如有帮助请点个star⭐️~

## 项目结构

<table>
<thead>
<tr>
<th>目录</th>
<th>文件</th>
<th>说明</th>
</tr>
</thead>
<tbody>
<tr>
<td rowspan="4"><strong>Attention</strong></td>
<td><a href="./Attention/MHA.ipynb">MHA.ipynb</a></td>
<td>多头注意力 (Multi-Head Attention)</td>
</tr>
<tr>
<td><a href="./Attention/GQA.ipynb">GQA.ipynb</a></td>
<td>分组查询注意力 (Grouped Query Attention)</td>
</tr>
<tr>
<td><a href="./Attention/MHA_kvcache.ipynb">MHA_kvcache.ipynb</a></td>
<td>带KV cache的注意力</td>
</tr>
<tr>
<td><a href="./Attention/mask.ipynb">mask.ipynb</a></td>
<td>注意力掩码</td>
</tr>
<tr>
<td rowspan="5"><strong>Components</strong></td>
<td><a href="./Components/Linear.ipynb">Linear.ipynb</a></td>
<td>线性层</td>
</tr>
<tr>
<td><a href="./Components/BPE.ipynb">BPE.ipynb</a></td>
<td>Byte Pair Encoding</td>
</tr>
<tr>
<td><a href="./Components/LoRA.ipynb">LoRA.ipynb</a></td>
<td>LoRA Linear 层</td>
</tr>
<tr>
<td><a href="./Components/RoPE.ipynb">RoPE.ipynb</a></td>
<td>旋转位置编码</td>
</tr>
<tr>
<td><a href="./Components/SwiGLU.ipynb">SwiGLU.ipynb</a></td>
<td>SwiGLU 激活函数</td>
</tr>
<tr>
<td rowspan="2"><strong>Norm</strong></td>
<td><a href="./Norm/LayerNorm.ipynb">LayerNorm.ipynb</a></td>
<td>层归一化</td>
</tr>
<tr>
<td><a href="./Norm/RMSNorm.ipynb">RMSNorm.ipynb</a></td>
<td>RMS归一化</td>
</tr>
<tr>
<td rowspan="5"><strong>Functional</strong></td>
<td><a href="./Functional/activation_fun.ipynb">activation_fun.ipynb</a></td>
<td>激活函数</td>
</tr>
<tr>
<td><a href="./Functional/CE.ipynb">CE.ipynb</a></td>
<td>交叉熵损失</td>
</tr>
<tr>
<td><a href="./Functional/InfoNCE.ipynb">InfoNCE.ipynb</a></td>
<td>InfoNCE损失</td>
</tr>
<tr>
<td><a href="./Functional/quantize.ipynb">quantify.ipynb</a></td>
<td>量化</td>
</tr>
<tr>
<td><a href="./Functional/SFT.ipynb">SFT.ipynb</a></td>
<td>SFT损失</td>
</tr>
<tr>
<td rowspan="5"><strong>RL</strong></td>
<td><a href="./RL/DPO.ipynb">DPO.ipynb</a></td>
<td>DPO损失</td>
</tr>
<tr>
<td><a href="./RL/GRPO.ipynb">GRPO.ipynb</a></td>
<td>GRPO损失</td>
</tr>
<tr>
<td><a href="./RL/GSPO.ipynb">GSPO.ipynb</a></td>
<td>GSPO损失</td>
</tr>
<tr>
<td><a href="./RL/KL.ipynb">KL.ipynb</a></td>
<td>KL散度</td>
</tr>
<tr>
<td><a href="./RL/PPO.ipynb">PPO.ipynb</a></td>
<td>PPO损失</td>
</tr>
</tbody>
</table>
