# Xiaofei Chen · 陈笑非

**Multimodal learning · LLM agents · Reinforcement learning**

[简体中文](https://github.com/xiaofei1412/xiaofei1412/blob/main/README.zh-CN.md) · [Email](mailto:chen1989830903@gmail.com) · [Google Scholar](https://scholar.google.com/citations?user=deSeHrIAAAAJ)

I'm a **First-Class Honours graduate** in Information and Computing Science from **Xi'an Jiaotong-Liverpool University**. I work on multimodal evaluation, retrieval-grounded agents, and reinforcement learning, connecting algorithm experiments with usable systems.

My research interests extend to **embodied intelligence, vision-language-action policies, and world models**, especially the interaction between perception, state representations, and action.

## Selected research

### TRIG · ICCV 2025

Co-author of [*Trade-offs in Image Generation: How Do Different Dimensions Interact?*](https://openaccess.thecvf.com/content/ICCV2025/html/Zhang_Trade-offs_in_Image_Generation_How_Do_Different_Dimensions_Interact_ICCV_2025_paper.html). I contributed to the **10-dimension evaluation matrix**, prompt preprocessing, training and image-generation pipelines, and human evaluation. The team benchmark covers **14 generative models** and examines trade-offs among quality, alignment, diversity, and robustness.

[Paper](https://arxiv.org/abs/2507.22100) · [Official code](https://github.com/fesvhtr/TRIG) · [My fork](https://github.com/xiaofei1412/TRIG)

### HBTC · Thermal dynamics, MPC and RL

Identified **2R2C grey-box dynamics with learned residuals** for MPC in BOPTEST, and benchmarked SAC, PPO, TD3 and rule-residual SAC under shared forecast access and action limits. Across **nine held-out simulation scenarios**, MPC used **1.62%–9.49% less electricity** than the recovery rule without increasing temperature violations.

[Code](https://github.com/xiaofei1412/thermalComfortPredict) · [Project & interactive replay](https://xiaofei1412.github.io/thermalComfortPredict/)

### NPPS · Neural pedal inference and audio synthesis

My undergraduate thesis combines **U-Net pedal-intent estimation**, adaptive hysteresis and asymmetric smoothing with a physics-inspired DSP renderer. It infers control from dry piano audio, then synthesizes sustain through multiband decay, FFT convolution and harmonic excitation.

[Code](https://github.com/xiaofei1412/My-Neuro-Physical-Piano) · [Listen & compare](https://xiaofei1412.github.io/NPPS-Demo/)

## Selected projects

### Yixi 弈习 · Distillation and RL for 9×9 Go

Distilled KataGo search policies and value/score/ownership targets into a residual network. Evaluated **self-play PPO-Clip with a frozen-reference KL penalty** across six configurations and **1,600 paired games**. The repository also includes a separate KataGo-powered review and practice app.

[Code](https://github.com/xiaofei1412/yixi-go) · [Project & downloads](https://xiaofei1412.github.io/yixi-go/)

### cswriter 笔杆子 · Local knowledge and human-in-the-loop agents

Built RAG over **44,176 Changshu news records**, combining semantic/keyword retrieval, query expansion and RRF fusion. Developed a **persistent DAG agent harness** with reusable skills, schema-defined tools, and human approval, revision and version comparison.

[Website](https://cswriter.cn/chat) · Private codebase

### EchoLens · Evidence-grounded review analysis

Fine-tuned **Qwen3.5-4B with NF4 QLoRA and answer-only supervision** for structured opinion extraction from Chinese restaurant reviews. Combined an **18-aspect RoBERTa classifier**, evidence-linked extraction, semantic clustering and human review in a local analysis workbench.

[Code](https://github.com/xiaofei1412/EchoLens) · [Project & model release](https://xiaofei1412.github.io/EchoLens/)

More: [GradTrail 研途](https://github.com/xiaofei1412/gradtrail) — a source-grounded study-abroad planning workbench with controlled AI assistance.

<details>
<summary><b>Experience & recognition</b></summary>

- **Xiaomi · Intelligent Cockpit:** LLM Algorithm R&D; personalized destination/charging recommendations and SQL/RAG place retrieval, in collaboration with the XiaoAi team.
- **Huayin Jishu:** NLP algorithm engineering; restaurant feedback analysis, later independently developed into EchoLens.
- **Research:** Multimodal evaluation at CUHK with Prof. Shi Qiu; audio synthesis with Prof. Shengchen Li and thermal control with Prof. Yong Yue at XJTLU.
- **Recognition:** First-Class Honours, XJTLU (2026); Top-10 finalist, Xiaomi's inaugural internal Agent Development Competition (2025).

</details>

## Tools I work with

**PyTorch · Transformers · Diffusers · vLLM**  
Fine-tuning & distillation · RAG & agent orchestration · Reinforcement learning & MPC
