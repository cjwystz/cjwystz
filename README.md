### 你好 👋 我是陈嘉伟

> **AI Infra / 大模型分布式训练系统 / 显存与负载调度优化**
> 
> 北京科技大学 · 信息安全本科在读  
> 清程极智 AI Infra 实习经历 · FlagOS 开源社区贡献者

---

### 📄 研究成果与论文
* 代表共同一作

- **面向大模型训练的异构Packing调度与激活显存优化算子**
  - MLSys 2027 · 共同一作* · 准备中 | 预计2026年10月投稿
  - 提出 Packing time-cost 模型与蛇形发牌调度策略；设计 Chunk-CE / Chunk-Linear 显存优化算子；在千卡级异构集群上完成验证。

- **形式化证明引导的多模态几何推理框架**
  - TMLR 审稿中 | [arXiv:2601.05073](https://arxiv.org/abs/2601.05073)
  - 构建 GeoGoal 高难度几何推理基准数据集；提出 SGVR 符号引导推理框架；基于 GRPO 优化长链推理成功率。

- **面向消费级平台的复杂场景生成：基于RAG优化的文生图系统**
  - WISE 2025 Workshop · 已录用
  - 设计双阶段 RAG 检索架构，提升扩散模型提示词语义理解精度，改善图文匹配度。

---

### 💻 开源贡献
- **[FlagOS / FlagScale](https://github.com/FlagOpen/FlagScale)**（4k+ stars）
  - 向大模型训练框架贡献 VPP、多模态 EP overlap、Batch Packing 等功能
  - 主要 PR：
    - [异构模块 Batch Packing 实现]()
    - [Qwen 系列模型 VPP 适配]()

- **zkLLM：面向大语言模型的零知识证明系统**
  - 复现 CCS 2024 zkLLM 开源框架；完成 CUDA 算子适配与推理可信审计可视化系统
  - 国家计算机软件著作权：2025SR0617553

---

### 🔧 工程实践亮点
- **大规模大模型预训练性能优化**
  - 在沐曦 C550 双节点16卡集群上设计并实现 Chunk-CE / Chunk-Linear 算子；在 Qwen3.5-35B 上单卡吞吐从 48 TFLOPS 提升至 82 TFLOPS（+71%）。
  - 在华为昇腾 SuperPoD A3 910C 万卡集群上，完成 64节点512卡 DeepSeek-v4-flash 全参数预训练；修复显存分配器与初始化问题，MFU 达到 38%+。
  - 在阿里真武 810E 集群上完成 384卡 Qwen3-243B 预训练；将优化策略迁移验证至大规模集群。

- **推理系统优化**
  - 基于 vLLM-Ascend 实现 Prefill-Decode（PD）分离；通过 af-plugin 验证 Attention-FeedForward（AF）分离，显著降低 TTFT。

---

### 🛠 技术栈
| 分类 | 技术栈 |
|------|--------|
| 训练系统 | Megatron-LM, MindSpeed, FlagScale, FSDP, PyTorch |
| 推理系统 | vLLM, vLLM-Ascend, SGlang |
| 硬件平台 | 华为昇腾 910C, 沐曦 C550, 阿里真武 810E, NVIDIA A800/A100 |
| 工具与环境 | 性能 Profiler, Docker, Ascend CL, AI 辅助编程 |

---

### 📫 联系我
- 邮箱：cjw_ustb@163.com
- [知乎](你的知乎主页链接)
- [X / Twitter](你的X账号链接)
