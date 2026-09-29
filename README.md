### 您好！！！  我是陈嘉伟

> **AI Infra / 大模型分布式训推系统 / 显存与负载调度优化**
>
> 2023-2027  北京科技大学 信息安全本科在读  
> 清程极智AI Infra实习生 / FlagOS 开源社区贡献者 / 昇腾、真武千卡训推经验

---

### 📄 Research and Publication

- **面向通用大模型训练的异构Packing调度策略**

  - MLSys2027   | 预计2026年10月投稿
  - 提出 Packing time-cost 模型与蛇形发牌调度策略；设计 Chunk-CE / Chunk-Linear 显存优化算子；在异构集群上完成验证。

- **形式化证明引导的多模态几何推理框架**

  - TMLR2027四作 | Under review 开源于 [arXiv:2601.05073](https://arxiv.org/abs/2601.05073)
  - 机器之心引用于https://mp.weixin.qq.com/s/XpnngRuhvX1pgOcT63VTFw
  - 构建 GeoGoal 高难度几何推理基准数据集；提出 SGVR 符号引导推理框架；基于 GRPO 优化长链推理成功率。

- **面向消费级平台的复杂场景生成：基于RAG优化的文生图系统**

  - WISE2025 Workshop 三作 ｜ 已录用 ｜ [GitHub](https://github.com/Dadada66666/T2I)
  - 提出RAG前置于Prompt优化阶段的轻量文生图增强框架：免训练、不改 T2I 模型、单次迭代，解决小参数 LLM 面对隐式知识的提示词失配问题。
  - 设计Tavily实时广搜 + BGE-m3向量化 + ChromaDB混合检索精排的两阶段pipeline；基于ollama + ComfyUI端到端落地，三模型交叉评分较仅 LLM 改写平均提升 114%。

---

### 💻 开源贡献

- **[FlagOS / FlagScale](https://github.com/FlagOpen/FlagScale)**（4k+ stars）

  - 向metax生态下大模型训练框架贡献bug适配和一些训练优化method

- **zkLLM：面向大语言模型的零知识证明系统**

  - 复现 CCS 2024 zkLLM 开源框架；完成 CUDA 算子适配与推理可信审计可视化系统
  - 国家计算机软件著作权：2025SR0617553

---

### 🛠 技术栈

| 分类    | 技术栈                                              |
| ----- | ------------------------------------------------ |
| 训练系统  | Megatron-LM, MindSpeed, FlagScale, FSDP, PyTorch |
| 推理系统  | vLLM, vLLM-Ascend, SGlang                        |
| 硬件平台  | 华为昇腾 910C, 沐曦 C550, 阿里真武 810E, NVIDIA A800/A100  |
| 工具与环境 | 性能 Profiler, Docker, Ascend CL, AI辅助编程           |

---

### 📫 联系我

- 邮箱：2451427796@qq.com
- 电话：18659336708
