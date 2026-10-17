### 👋 Welcome！我是陈嘉伟

> **AI Infra / 大模型分布式训推系统 / 显存与负载调度优化**
> 
> 🎓 2023-2027 · 北京科技大学 · 信息安全本科 · 雅思6.5(6)  
> 💼 清程极智 AI Infra 实习生 · FlagOS / Hugging Face PEFT 开源贡献者  
> 🖥️ 昇腾 910C / 沐曦 C550 / 真武 810E 千卡训推经验  
> 🏪 福建漳州厦门城区旺铺招租(个人房源，非中介)，福建/广东/浙江接厨房设备与承包工程需求，欢迎联系🛰️_cjwystz
>
> 个人主页 https://cjwystz.github.io

---

### 🎯 寻求机会

- **博士申请**：寻求27fall港硕机会，寻求 2028-2029 Fall 入学的大模型系统方向博士（普博）机会，研究兴趣为分布式训推系统、显存与调度优化、具身智能。
- **工作机会**：同时欢迎基模、AI Infra和机器人方向的实习/全职机会沟通。

---

### 📄 Research & Publication

- **通用大模型训练的异构建模 Packing 调度策略** `清程极智 × 北京科技大学`

  - 🎯 **MLSys 2027** · **Co-first Author** · 预计 2026.10 投稿
  - 设计 Packing time-cost 模型与蛇形发牌调度策略；设计 Chunk-CE / Chunk-Linear 显存优化算子；基于以上等优化，实现端到端 **+20%** 的吞吐提升

- **形式化证明引导的多模态几何推理框架** `上海人工智能实验室`

  - 🎯 **TMLR 2027** · Co-author · Under Review · 📎 [arXiv:2601.05073](https://arxiv.org/abs/2601.05073) · [机器之心报道](https://mp.weixin.qq.com/s/XpnngRuhvX1pgOcT63VTFw)
  - 构建 GeoGoal 基准：将形式化证明骨架拆为可自动验证的数值子目标序列，提出 Skeleton Rate 过程级指标。
  - 提出 SGVR 子目标可验证奖励框架，以稠密过程奖励替代结果奖励，GRPO 训练后几何推理 **+9.7%**，泛化至通用数学 **+8.0%**。

- **面向消费级平台的复杂场景生成：基于 RAG 优化的文生图系统** `清华大学 BNRist`

  - 🎯 **WISE 2025 Workshop** · Co-author · ✅ Published · 📎 [GitHub](https://github.com/Dadada66666/T2I)
  - 提出 RAG 前置 Prompt 优化阶段的文生图增强框架：不改T2I 模型、单次迭代，解决小参数 LLM 面对隐式知识的 Prompt 失配问题。
  - 设计 Tavily + BGE-m3 + ChromaDB 混合检索的两阶段 Pipeline，基于ollama + ComfyUI落地，评分较仅 LLM 改写平均提升 **114%**。

---

### 💻 Contributions

- **[FlagOS](https://github.com/FlagOpen/FlagScale)**

  **FlagScale / Megatron-FL / TransformerEngine-FL**：沐曦硬件适配、训练框架优化与 Bug 修复<br>
  **TransformerEngine-FL**：MetaX TE 2.13+ 包结构与加载路径适配（[PR #128](https://github.com/flagos-ai/TransformerEngine-FL/pull/128)）<br>
  **FlagScale**：修复 MetaX 参数检查与 Profiler 相关问题（[PR #1296](https://github.com/flagos-ai/FlagScale/pull/1296)）<br>
  **Megatron-LM-FL**：修复 MetaX JIT/Dynamo 显存泄漏问题（[PR #185](https://github.com/flagos-ai/Megatron-LM-FL/pull/185)）<br>
  **Chunk CE**：实现分块词表并行交叉熵，降低训练临时显存开销（[PR #126](https://github.com/flagos-ai/Megatron-LM-FL/pull/126)）<br>
  **TP overlap**：沐曦平台通信与计算重叠的适配及修复（[PR #139](https://github.com/flagos-ai/TransformerEngine-FL/pull/139)）<br>
  **FlagScale 多模态 packing**：实现 Qwen3.5 **Next Fit** 序列装箱、多模态对齐与独立位置编码（[PR #1308](https://github.com/flagos-ai/FlagScale/pull/1308) · [实现分支](https://github.com/flagos-ai/FlagScale/compare/main...Baibaione:FlagScale-qc-training:fix-mllm-packing)）<br>
  **TE 多模态数据 packing**：实现 **BFD（Best Fit Decreasing）/ Next Fit** 装箱算法

- **[Hugging Face](https://github.com/huggingface/peft)**

  **PEFT / LoRA-FA**：优化器 `step(closure)` 梯度上下文修复与回归测试（[PR #3966](https://github.com/huggingface/peft/pull/3966)）

- **zkLLM：面向大语言模型的零知识证明系统可视化**

  - 复现 CCS 2024 zkLLM 开源框架，完成框架适配并搭建推理可信审计可视化系统
  - 📜 国家计算机软件著作权：2025SR0617553

---

### 🛠 Skills

| 分类   | 技术栈                                                  |
| ---- | ---------------------------------------------------- |
| 训练系统 | Megatron-LM · MindSpeed · FlagScale · FSDP · PyTorch |
| 推理系统 | vLLM · vLLM-Ascend · SGLang                          |
| 硬件平台 | 华为昇腾 910C · 沐曦 C550 · 阿里真武 810E · NVIDIA A800/A100   |
| 工具环境 | 性能 Profiler · Docker · AI 编程提效           |

---

### 🏆 Honors & Awards

- 🥇 全国冶金科技大赛 · **全国一等奖**
- 🥈 ASC 国际超级计算机竞赛（ASC Student Supercomputer Challenge）· **全国二等奖**
- 🌍 美国大学生数学建模竞赛（MCM/ICM）· **Honorable Mention**
- 🥉 中国高校计算机大赛 · 网络安全技术挑战赛 · **省级三等奖**

---

### 📫 联系我

- 📮 邮箱：2451427796@qq.com
- 📱 电话：18659336708
- 🛰️ 微信：_cjwystz
