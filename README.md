### Welcome！  我是陈嘉伟

> **AI Infra / 大模型分布式训推系统 / 显存与负载调度优化**
>
> 2023-2027  北京科技大学 信息安全本科在读  雅思6.5(6)
> 清程极智AI Infra实习生 / FlagOS 开源社区贡献者 / 昇腾、真武千卡训推经验
> 福建漳州7套旺铺招租                      
> 福建广东浙江接厨房设备、承包工程需求              

---

### 📄 Research and Publication

- **面向通用大模型训练的异构Packing调度策略**| 清程极智×北京科技大学

  - MLSys2027 co-first author | 预计2026.10月投稿 
  - 提出 Packing time-cost 模型与蛇形发牌调度策略；设计 Chunk-CE / Chunk-Linear 显存优化算子；在异构集群上完成验证。

- **形式化证明引导的多模态几何推理框架**| 上海ailab

  - TMLR2027 co-author | Under review（首轮审稿意见积极）| 开源于 [arXiv:2601.05073](https://arxiv.org/abs/2601.05073) 
  - 机器之心引用于https://mp.weixin.qq.com/s/XpnngRuhvX1pgOcT63VTFw
  - 构建 GeoGoal 基准：将形式化证明骨架拆为可自动验证的数值子目标序列，提出 Skeleton Rate 过程级指标。
  - 提出 SGVR 子目标可验证奖励框架，以稠密过程奖励替代结果奖励，GRPO 训练后几何 +9.7%，泛化通用数学 +8.0%。

- **面向消费级平台的复杂场景生成：基于RAG优化的文生图系统**｜ 清华大学 BNRist

  - WISE2025 Workshop co-author ｜ published ｜ [GitHub](https://github.com/Dadada66666/T2I) 
  - 提出RAG前置于Prompt优化阶段的轻量文生图增强框架：不动 T2I、单次迭代，解决小参数 LLM 面对隐式知识的prompt失配问题。
  - 设计Tavily + BGE-m3 + ChromaDB混合检索的两阶段pipeline；基于ollama + ComfyUI端到端落地，评分较单 LLM 改写平均提升 114%。

---

### 💻 开源贡献

- **[FlagOS / FlagScale](https://github.com/FlagOpen/FlagScale)**（4k+ stars）

  - 在metax生态下大模型训练框架贡献bug适配和一些训练优化method

- **zkLLM：面向大语言模型的零知识证明系统可视化**

  - 复现 CCS 2024 zkLLM 开源框架；完成框架适配并搭建推理可信审计可视化系统
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
