# LLaMA-Factory-Online

<p align="center">
  <img src="https://your-banner-url" width="100%" alt="LLaMA-Factory Online Banner">
</p>

<h1 align="center">🦙 LLaMA-Factory Online</h1>

<p align="center">
  <b>无需代码 Easy微调</b><br>
  在线大模型训练与微调服务平台
</p>

<p align="center">
  <a href="https://www.llamafactory.com.cn/?utm_source=jslt_github0"><img src="https://img.shields.io/badge/%20Website-Visit%20Now-blueviolet?style=for-the-badge&logo=vercel"></a>
  <a href="https://huggingface.co/llamafactory"><img src="https://img.shields.io/badge/HuggingFace-Visit%20Now-ffcc00?style=for-the-badge&logo=huggingface"></a>
  <a href="https://github.com/llamafactoryonline"><img src="https://img.shields.io/badge/%20GitHub-Stars-yellow?style=for-the-badge&logo=github"></a>
</p>

---

## 🚀 产品介绍

**LLaMA-Factory Online**是与明星开源项目LLaMA-Factory 官方合作打造的在线大模型训练与微调服务平台，底层提供高性能、高弹性GPU算力资源，为具有微调需求、编码与工程能力较为基础的用户群体，提供开箱即用、低代码、全链路功能覆盖的大模型训练与微调服务。它将微调流程重构为一个**可视化、在线化、低代码的一站式云端服务**，让团队能专注于业务或技术实现本身，无需困扰资源与配置问题，为开发提效。

### ✨ 核心功能
- 🧠 **100+模型随心选择**：涵盖LLaMA/Qwen/DeepSeek/GPT-OSS等主流大模型  
- ⚡ **训练算法齐全**：支持预训练、SFT、Reward Modeling、PPO/DPO/KTO等多种训练方式  
- 🧩 **运算精度灵活**：覆盖16bit全参数微调、冻结微调、LoRA微调和基于2/3/4/5/6/8bit的QLoRA微调  
- 📈 **优化算法先进**：内置LlamaBoard/TensorBoard/Wandb/Mlflow/SwanLab等实时监控工具  
- ☁️ **实验监控完善**：生成 API、Web Demo、Docker 镜像，一键上线
- 🚀 **训练推理高效**：采用FlashAttention-2/Unsloth等加速算子，支持 Transformers/vLLM推理引擎

👉 **[注册送券，免费体验 → LLaMA-Factory Online](https://www.llamafactory.com.cn/?utm_source=jslt_github0)**

---

## 📚 微调数据集精选

精选高质量中英文各行业开源数据集，助你快速构建专属模型：

| 🌐 类型 | 📦 数据集示例 | 🔗 下载入口 |
|:--|:--|:--|
| 通用指令 | Alpaca-GPT4 | [🔗 Hugging Face](https://huggingface.co/datasets/tatsu-lab/alpaca) |
| 对话/问答 | ShareGPT | [🔗 Hugging Face](https://huggingface.co/datasets/ShareGPT) |
| 中文指令 | Firefly-Mix-1.1M | [🔗 Hugging Face](https://huggingface.co/datasets/YeungNLP/firefly-train-1.1M) |
| 专业领域 | Finance-GPT | [🔗 Hugging Face](https://huggingface.co/datasets/hello-simpleai/Finance-GPT) |
| 医疗问答 | Med-Dialog-CN | [🔗 Hugging Face](https://huggingface.co/datasets/medicalai/MedDialog) |

📎 更多推荐数据集请访问 👉 [**LFO 官方数据集页**](https://llamafactory.online/datasets)

---

## 🧪 微调最佳实践

从入门到进阶，我们准备了系统化的实践教程与案例库：

| 🧩 主题 | 📝 简介 | 🔗 跳转 |
|:--|:--|:--|
| 🎓 快速上手教程 | 使用 LoRA 微调 Qwen-1.8B 指令模型 | [➡ 阅读教程](https://llamafactory.online/practice/quickstart) |
| 🧱 行业案例合集 | 医疗、法律、教育等领域微调实战 | [➡ 前往案例库](https://llamafactory.online/practice/cases) |
| 🔬 实验室推荐流程 | 大模型实验室（Lab4AI）提供的官方微调指南 | [➡ 查看指南](https://llamafactory.online/lab) |
| 🎁 GPU 福利季活动 | 新用户注册有礼、邀新返现、充值福利 | [➡ 了解活动](https://llamafactory.online/events) |

💡 **提示**：所有案例均可一键复制至平台运行，无需额外环境配置。

---

## 🤝 加入我们

📢 **官方网站**  
👉 [https://llamafactory.online](https://llamafactory.online)

💬 **社区与交流群**  
- 微信群 / Discord：扫码进群领取代金券与微调资料包  
- Bilibili / 掘金 / 知乎官方号：`@LLaMA-Factory Online`

📮 **商务合作与校园大使计划**  
请邮件至：**contact@llamafactory.online**

> 🦙「让微调变得像写提示词一样简单。」

---

## 📜 许可协议

本项目内容遵循 [MIT License](LICENSE)。  
所有示例数据集版权归原作者所有。  
本页展示的数据与教程仅用于学术与非商业用途。

---

### 🧷 仓库结构（轻量版）

```text
llamafactory-online/
│
├─ README.md          ← 主页面（当前文件）
├─ LICENSE
└─ assets/
    └─ banner.png     ← 可替换项目横幅图（选填）
