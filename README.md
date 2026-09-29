### 👋 Welcome！我是陈嘉伟

> **AI Infra / 大模型分布式训推系统 / 显存与负载调度优化**
>
> 🎓 2023-2027 · 北京科技大学 · 信息安全本科（雅思 6.5）  
> 💼 清程极智 AI Infra 实习生 · FlagOS 开源社区贡献者  
> 🖥️ 昇腾 910C / 沐曦 C550 / 真武 810E 千卡训推经验  
> 🏪 福建漳州 7 套旺铺招租，福建/广东/浙江接厨房设备与承包工程需求，欢迎联系

---

### 📄 Research & Publication

- **面向通用大模型训练的异构 Packing 调度策略** `清程极智 × 北京科技大学`

  - 🎯 **MLSys 2027** · **Co-first Author** · 预计 2026.10 投稿
  - 提出 Packing time-cost 模型与蛇形发牌调度策略；设计 Chunk-CE / Chunk-Linear 显存优化算子；在异构集群上完成验证。

- **形式化证明引导的多模态几何推理框架** `上海人工智能实验室`

  - 🎯 **TMLR 2027** · Co-author · Under Review · 📎 [arXiv:2601.05073](https://arxiv.org/abs/2601.05073) · [机器之心报道](https://mp.weixin.qq.com/s/XpnngRuhvX1pgOcT63VTFw)
  - 构建 GeoGoal 基准：将形式化证明骨架拆为可自动验证的数值子目标序列，提出 Skeleton Rate 过程级指标。
  - 提出 SGVR 子目标可验证奖励框架，以稠密过程奖励替代结果奖励，GRPO 训练后几何推理 **+9.7%**，泛化至通用数学 **+8.0%**。

- **面向消费级平台的复杂场景生成：基于 RAG 优化的文生图系统** `清华大学 BNRist`

  - 🎯 **WISE 2025 Workshop** · Co-author · ✅ Published · 📎 [GitHub](https://github.com/Dadada66666/T2I)
  - 提出 RAG 前置 Prompt 优化阶段的文生图增强框架：不改 T2I 模型、单次迭代，解决小参数 LLM 面对隐式知识的 Prompt 失配问题。
  - 设计 Tavily + BGE-m3 + ChromaDB 混合检索的两阶段 Pipeline，基于 ollama + ComfyUI 落地，评分较仅 LLM 改写平均提升 **114%**。

---

### 💻 开源贡献

- **[FlagOS / FlagScale](https://github.com/FlagOpen/FlagScale)** ⭐ 4k+

  - 面向沐曦（MetaX）生态的大模型训练框架，贡献 Bug 修复、硬件适配与训练优化方法。

- **zkLLM：面向大语言模型的零知识证明系统可视化**

  - 复现 CCS 2024 zkLLM 开源框架，完成框架适配并搭建推理可信审计可视化系统。
  - 📜 国家计算机软件著作权：2025SR0617553

---

### 🛠 技术栈

| 分类   | 技术栈                                                  |
| ---- | ---------------------------------------------------- |
| 训练系统 | Megatron-LM · MindSpeed · FlagScale · FSDP · PyTorch |
| 推理系统 | vLLM · vLLM-Ascend · SGLang                          |
| 硬件平台 | 华为昇腾 910C · 沐曦 C550 · 阿里真武 810E · NVIDIA A800/A100   |
| 工具环境 | 性能 Profiler · Docker · Ascend CL · AI 辅助编程           |

---

### 📫 联系我

- 📮 邮箱：2451427796@qq.com
- 📱 电话：18659336708
