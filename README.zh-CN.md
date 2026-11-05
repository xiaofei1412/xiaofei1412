# 陈笑非 · Xiaofei Chen

**多模态学习 · 大模型 Agent · 强化学习**

[English](https://github.com/xiaofei1412/xiaofei1412) · [邮箱](mailto:Xiaofei.Chen22@student.xjtlu.edu.cn)

毕业于**西交利物浦大学信息与计算科学专业，获一等荣誉学士学位**。我的研究与工程实践涵盖多模态评测、基于检索的 Agent 和强化学习，关注算法实验如何转化为可使用、可评估的系统。

希望进一步探索**具身智能、视觉—语言—动作模型（VLA）与世界模型**，尤其是感知、状态表示与动作之间的联系。

## 科研成果

### TRIG · ICCV 2025

论文 [*Trade-offs in Image Generation: How Do Different Dimensions Interact?*](https://openaccess.thecvf.com/content/ICCV2025/html/Zhang_Trade-offs_in_Image_Generation_How_Do_Different_Dimensions_Interact_ICCV_2025_paper.html) 共同作者。参与搭建 **10 维评测矩阵**，负责提示词预处理、模型训练与批量出图流程，并参加人工评分。团队基准覆盖 **14 个生成模型**，分析图像质量、任务对齐、多样性与鲁棒性之间的权衡。

[论文](https://arxiv.org/abs/2507.22100) · [官方代码](https://github.com/fesvhtr/TRIG) · [个人 fork](https://github.com/xiaofei1412/TRIG)

### HBTC · 热动态建模、MPC 与强化学习

在 BOPTEST 中辨识 **2R2C 灰箱模型并学习残差**，实现 MPC；在统一预报权限与动作约束下，对照 SAC、PPO、TD3 和规则残差 SAC。在 **9 组留出仿真场景**中，MPC 较恢复规则节电 **1.62%–9.49%**，温度越界未增加。

[代码](https://github.com/xiaofei1412/thermalComfortPredict) · [项目介绍与交互回放](https://xiaofei1412.github.io/thermalComfortPredict/)

### NPPS · 踏板意图估计与钢琴延音合成

本科毕业设计：从干声钢琴音频中用 **U-Net 推断踏板意图**，经自适应迟滞与非对称平滑生成控制包络，再结合多频段衰减、FFT 卷积和谐波激励进行声学合成。

[代码](https://github.com/xiaofei1412/My-Neuro-Physical-Piano) · [试听对比](https://xiaofei1412.github.io/NPPS-Demo/)

## 个人项目

### 弈习 · 9 路围棋蒸馏与强化学习

用 KataGo 搜索策略及价值、目差、领地标签蒸馏残差网络，开展**带冻结参考策略 KL 正则的自对弈 PPO-Clip**，完成 6 组配置、**1,600 局配对评估与复核**。仓库同时包含独立使用 KataGo 的复盘与练习产品。

[代码](https://github.com/xiaofei1412/yixi-go) · [项目介绍与下载](https://xiaofei1412.github.io/yixi-go/)

### 笔杆子 · 地方知识 RAG 与人在回路 Agent

整理 **44,176 条常熟新闻记录**，融合语义／关键词检索、查询扩写与 RRF。搭建**持久化 DAG Agent harness**，结合可复用 Skill、工具 Schema、逐节点人工审批、反馈修订与版本对照。

[网站](https://cswriter.cn/chat) · 代码未公开

### EchoLens · 有原文证据的餐饮反馈洞察

使用 **NF4 QLoRA 与仅答案监督微调 Qwen3.5-4B**，完成中文餐饮评论的结构化意见抽取；融合 **18 方面 RoBERTa 分类器**、原文证据定位、语义聚类与人工复核，交付本地分析工作台。

[代码](https://github.com/xiaofei1412/EchoLens) · [项目介绍与模型发布](https://xiaofei1412.github.io/EchoLens/)

其他项目：[GradTrail 研途](https://github.com/xiaofei1412/gradtrail)——基于可追溯来源与受控 AI 工作流的留学申请工作台。

<details>
<summary><b>实习、科研与荣誉</b></summary>

- **小米科技 · 智能座舱：** 大模型算法研发；与小爱同学团队合作，开发目的地／充电建议及 SQL／RAG 地点检索。
- **华因极数：** NLP 算法工程；餐饮反馈分析，后独立迭代为 EchoLens。
- **科研指导：** 香港中文大学邱实教授；西交利物浦大学李圣辰教授、岳勇教授，分别开展多模态评测、音频合成与热环境控制研究。
- **荣誉：** 西交利物浦大学一等荣誉学士学位（2026）；小米首届内部 Agent 开发大赛入围奖，前 10 名（2025）。

</details>

## 常用技术

**PyTorch · Transformers · Diffusers · vLLM**  
微调与蒸馏 · RAG 与 Agent 编排 · 强化学习与模型预测控制
