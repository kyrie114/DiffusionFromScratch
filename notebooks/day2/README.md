# Day 2 学习笔记本（Colab 导出）

来源：Harvard「ML from Scratch: Stable Diffusion, Day 2」学生版笔记本，我在 Colab 上边学边填的版本（导出于 2026-11-09）。

- `Diffusion_Model_with_Cross_Attention_student.ipynb`：完整笔记本，含已运行的输出
- 按章节拆开的版本（方便单独看）：

| 文件 | 内容 |
|---|---|
| `00-课程说明与环境.ipynb` | 课程介绍、安装依赖、import |
| `01-一维扩散与score.ipynb` | 一维前向/反向扩散，score 学习 |
| `02-U-Net.ipynb` | 时间嵌入、Dense、U-Net / UNet_res |
| `03-无条件训练.ipynb` | marginal_prob_std、loss_fn、Euler-Maruyama 采样、MNIST 训练 |
| `04-条件生成_cross-attention.ipynb` | 数字嵌入、CrossAttention、UNet_Tranformer、条件训练与采样 |
| `05-潜空间扩散.ipynb` | 自编码器 + latent diffusion |
| `06-保存进度.ipynb` | 保存 |

拆分版只是按章节切开，后面的章节依赖前面定义的函数和类，要运行请用完整版或按顺序执行。

配套笔记：kyrie114/notes 的 `07-扩散模型从零`。
