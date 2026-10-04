# Awesome LLM Tech Report

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
[![Reports](https://img.shields.io/badge/Reports-780-b31b1b.svg?style=flat-square&logo=arxiv&logoColor=white)](./data/reports.csv)
[![Coverage](https://img.shields.io/badge/Window-2026--01--01_to_2026--10--04-6f42c1.svg?style=flat-square&logo=bookstack&logoColor=white)](./data/reports.csv)

Curated large-model `Technical Report`, `Training Report`, and `Tech Report` papers.

Inclusion rule: the paper title contains `Technical Report`, `Training Report`, or `Tech Report`; the abstract or arXiv comment explicitly self-identifies the work as a technical report / tech report; or the official report PDF, publisher page, or originating lab page explicitly labels it as a technical report. The topic must match large models, foundation models, model systems, or closely related training/inference infrastructure. Broader training papers, challenge solution reports, and benchmark-only reports are intentionally excluded from the main table.

- Source: arXiv API/search; official publisher/lab pages and report PDFs are used to verify report status when arXiv metadata omits it.
- Current audit window: `2026-01-01` to `2026-10-04`
- Date convention: `published` records the arXiv version date used by the audit (the latest revision date when a revision exists). For reports without an arXiv record, it records the official release date.
- Official-only reports use a stable slug in `id`; `categories` is left blank when no arXiv classification exists.
- Retention: Previously curated older entries are retained instead of removed when the rolling audit window advances.
- CSV: [data/reports.csv](./data/reports.csv)
- Total selected: `780`

| Date | Technical Report | Direction |
| --- | --- | --- |
| 2026-10-01 | [VISTA: A Visual Harness for Reasoning in an Interactive World](https://arxiv.org/abs/2610.02200v1) | visual agent harness / long-horizon visual memory |
| 2026-10-01 | [Invent a Dataset: Measuring dataset generation abilities with zero seed](https://arxiv.org/abs/2610.01674v1) | LLM data infrastructure / zero-seed synthetic post-training data |
| 2026-10-01 | [Permutation-Robust Decision Modeling with Candidate-Independent Block-Causal Attention](https://arxiv.org/abs/2610.01601v1) | LLM decision-model architecture / permutation-robust attention |
| 2026-09-30 | [AnyJev Technical Report](https://arxiv.org/abs/2610.00831v1) | LLM inference / calibrated typed-decision readout |
| 2026-09-30 | [PivotOPD: Learning to Recover from Pivotal Mistakes in Multi-Turn Agents](https://arxiv.org/abs/2609.40285v1) | agentic LLM post-training / preventive and recovery distillation |
| 2026-09-30 | [LARC: Low-Rank Adaptive Residual Connections for Learning in Frozen Models](https://arxiv.org/abs/2609.40063v1) | LLM continual adaptation / low-rank feedback memory |
| 2026-09-30 | [UniWAM Technical Report: Unified Mobile Manipulation via Mixed-Stream World-Action Modeling and Manipulation Anchor Pose Supervision](https://arxiv.org/abs/2609.39388v1) | robotics / unified mobile-manipulation world-action model |
| 2026-09-30 | [Bongard: Training Machine Intuition](https://arxiv.org/abs/2609.39111v1) | System-One language model / probabilistic decision post-training |
| 2026-09-30 | [HELIX: Purified and Unified - Rethinking Feature Interaction and Sequence Modeling for Large-Scale Recommendation](https://arxiv.org/abs/2609.37183v2) | large-scale recommendation / unified feature and sequence scaling |
| 2026-09-30 | [Index-Translate: A Multilingual Translation Model Family -- Text, Speech, Controlled Dubbing, and Long-Document Translation](https://arxiv.org/abs/2609.40181v1) | multilingual LLM / shared translation mid-training, expert RL and multimodal distillation |
| 2026-09-29 | [STEPQuant: When and Where Errors Matter in Delta-Rule Recurrent State Quantization](https://arxiv.org/abs/2609.38169v1) | LLM inference / delta-rule recurrent-state quantization |
| 2026-09-29 | [Auditable Long-Term Memory: A Deterministic Retrieval Chain Measured at 479/475 of 500 on LongMemEval-S](https://arxiv.org/abs/2609.38021v1) | agent memory / auditable long-term retrieval runtime |
| 2026-09-29 | [Tabby: An Open Pretraining Recipe for Time Series Foundation Models](https://arxiv.org/abs/2609.13956v2) | time-series foundation model / open probabilistic pretraining |
| 2026-09-29 | [PhysWAM: Physically Consistent World Action Model for Autonomous Driving](https://arxiv.org/abs/2609.37970v1) | autonomous driving / physically consistent world-action modeling |
| 2026-09-29 | [PolyOCR-Venus: Unified OCR Foundation Models for Text-Centric Visual Intelligence](https://arxiv.org/abs/2609.37712v1) | OCR foundation model / competence-guided RL and distillation |
| 2026-09-29 | [KUPAS MASTER: Distilling the Tacit Expertise of Master Practitioners into Agent-Ready Experience Corpora](https://arxiv.org/abs/2609.37673v1) | agent data infrastructure / tacit-experience corpus engineering |
| 2026-09-29 | [VoxelSage: Tool-Augmented 3D CT Analysis and Simulator-Shielded Sequential Resection Planning for Liver Tumors](https://arxiv.org/abs/2609.37648v1) | medical multimodal agent / tool orchestration and simulator shielding |
| 2026-09-29 | [KwaiMind Technical Report](https://arxiv.org/abs/2609.26375v2) | image editing / e-commerce data engine and reward alignment |
| 2026-09-29 | [IronLLM: Forging Compact Edge-Native Language Models for Real-Time Embodied Intelligence](https://arxiv.org/abs/2609.36860v1) | edge-native LLM / hybrid attention and multi-domain distillation |
| 2026-09-29 | [GRP v0.1 Technical Report](https://arxiv.org/abs/2609.36688v1) | generative recommendation / retrieval-ranking-reward unification |
| 2026-09-29 | [Inference-Layer Security: Defending Against Adversarial Inference and Infrastructure Abuse](https://arxiv.org/abs/2609.38239v1) | LLM-service security infrastructure / adversarial-session detection |
| 2026-09-28 | [OVD: On-policy Verbal Distillation](https://arxiv.org/abs/2601.21968v2) | reasoning distillation |
| 2026-09-28 | [Xiaomi-OCR-0 Technical Report](https://arxiv.org/abs/2609.36136v1) | OCR VLM / automated corpus and mixed-task reinforcement learning |
| 2026-09-28 | [LongCat-DeepResearch Technical Report](https://arxiv.org/abs/2609.36071v1) | deep-research agent / multi-agent planning and sectionwise revision |
| 2026-09-28 | [Self-Evolving Coding Agents: From Digital Programs to Physical-World Intelligence](https://arxiv.org/abs/2609.35432v1) | embodied coding agent / executable physical state and self-evolution |
| 2026-09-28 | [DoAtlas-2: A Foundation for Self-Evolving Causal Biomedical Discovery](https://arxiv.org/abs/2609.35107v1) | LLM scientific-agent system / causal discovery and evidence-revision orchestration |
| 2026-09-28 | [\[Short Technical Report & Usage\] NexteraBERT: Input-Dependent Gating Liquid Mixer and Length-Adaptive Attention for Fast, Long-Context Bidirectional Encoders](https://huggingface.co/blog/RikkaBotan/technical-report-nexterabert) | bidirectional language foundation model / hybrid token-mixer MLM pretraining and long-context extrapolation |
| 2026-09-28 | [EntroPack: Fast and Accurate Entropy-Coded Weight Compression at Arbitrary Bitrates](https://arxiv.org/abs/2609.34185v1) | foundation-model inference / rate-controlled entropy-coded weight compression |
| 2026-09-27 | [JuZhou 1.0 Technical Report: The First Edge-Native Text-to-Image Foundation Model Trained Entirely on China-Developed AI Accelerators](https://arxiv.org/abs/2606.28421v3) | image generation / edge foundation model |
| 2026-09-27 | [YuE2: Unifying Symbolic and Audio Music Generation at Frontier Quality](https://arxiv.org/abs/2609.33757v1) | music foundation system / symbolic planning and unified audio generation |
| 2026-09-27 | [In-Token Learning for High-Fidelity Image Restoration via Diffusion Transformers](https://arxiv.org/abs/2609.33523v1) | diffusion foundation model adaptation / image restoration |
| 2026-09-27 | [Making AI Scientists Auditable from Evidence to Claim](https://arxiv.org/abs/2606.18874v4) | AI scientist / evidence-grounded research-agent harness |
| 2026-09-27 | [Raven: The Harness of Harnesses for Composable Agentic Intelligence](https://arxiv.org/abs/2609.33439v1) | agent system / composable model-specific harness evolution |
| 2026-09-25 | [IndustryLLM: Failure-Driven LLM Training for Industrial Procurement](https://arxiv.org/abs/2609.31871v1) | industrial LLM / failure-driven continual pretraining and SFT |
| 2026-09-25 | [CALLIOPE: A Source-Grounded Oral Assessment System and Synthetic Readiness Evaluation](https://arxiv.org/abs/2610.00290v1) | LLM assessment system / source-grounded speech, dual-provider scoring and review provenance |
| 2026-09-25 | [EXAONE Demand 1.0: A Time Series Foundation Model for Demand Forecasting](https://arxiv.org/abs/2609.30880v1) | demand time-series foundation model / synthetic corpus and routed adapters |
| 2026-09-24 | [Advancing Model Research in AgentX: Long-Horizon Autonomy for Industrial Recommender Systems](https://arxiv.org/abs/2609.30001v1) | AI-for-AI agent system / long-horizon recommendation research |
| 2026-09-24 | [MILO: Efficient Many-shot In-Context Learning with Block-wise Low-rank Compression](https://arxiv.org/abs/2609.29913v1) | LLM inference / many-shot blockwise KV compression |
| 2026-09-24 | [Qwen-Audio-3.1-Realtime: Towards Reliable Agentic Voice Interaction](https://arxiv.org/abs/2609.25176v2) | realtime audio agent / multimodal distillation and tool-use RL |
| 2026-09-24 | [X-Rec Technical Report](https://arxiv.org/abs/2609.29180v1) | generative recommendation / flow-matching retrieval |
| 2026-09-24 | [ViRDM: Taming Representation Distribution Matching for Few-Step Causal Video Generation](https://arxiv.org/abs/2609.28923v1) | causal video generation / teacher- and critic-free post-training |
| 2026-09-23 | [NVIDIA OmniDreams: Real-Time Generative World Model for Closed-Loop Autonomous Vehicle Simulation](https://arxiv.org/abs/2606.03159v3) | autonomous-driving world model / mid- and post-training |
| 2026-09-23 | [What Stops Recursive Self-Improvement in Robotics? Lessons from 123 Rounds of Agentic Skill Discovery](https://arxiv.org/abs/2609.31760v1) | robot agent system / recursive skill discovery and harness limits |
| 2026-09-23 | [InternW0: A Foundational Physical World Model for Efficient Real-World Interactions](https://arxiv.org/abs/2609.27656v1) | embodied foundation model / asynchronous video-action pretraining |
| 2026-09-23 | [Pistis Technical Report](https://arxiv.org/abs/2609.28554v1) | multimodal LLM / interleaved distillation-RL and auto-harnessing |
| 2026-09-23 | [Verifiable Hidden Dynamics Play: Generating Agentic RL Environments from Solved Mechanisms](https://arxiv.org/abs/2609.27321v1) | agent RL infrastructure / verifiable generated environments |
| 2026-09-23 | [Hunyuan-A13B Technical Report](https://arxiv.org/abs/2609.27284v1) | MoE LLM / STEM-rich pretraining and dual-mode reasoning |
| 2026-09-23 | [BOTANIC-1: a series of long-context plant genomic foundation models in the agentic era](https://www.biorxiv.org/content/10.64898/2026.09.04.749355v3) | genomic foundation-model pretraining / long-context extension and adaptation |
| 2026-09-22 | [Molt: A Scalable PyTorch-Native Training Framework for Agentic Reinforcement Learning](https://arxiv.org/abs/2607.21653v3) | agent RL training framework |
| 2026-09-22 | [KaLM-Reranker-V1: Fast but Not Late Interaction for Compressed Document Reranking](https://arxiv.org/abs/2606.22807v3) | retrieval / reranker |
| 2026-09-22 | [minWM: A Full-Stack Open-Source Framework for Real-Time Interactive Video World Models](https://arxiv.org/abs/2605.30263v2) | interactive world model / video generation |
| 2026-09-22 | [TabPFN-3.5: Technical Report](https://arxiv.org/abs/2609.17895v2) | tabular foundation model / multimodal harnesses and inference scaling |
| 2026-09-22 | [VideoX-Qwen: Data-Centric Instruction-Based Video Editing](https://arxiv.org/abs/2609.26015v1) | video editing / scalable paired-data construction and progressive training |
| 2026-09-22 | [ZYT-World: A Real-Time Controllable World Model for Closed-Loop Autonomous-Driving Simulation](https://arxiv.org/abs/2609.21712v2) | driving world model / one-step streaming distillation and memory |
| 2026-09-22 | [Fysiverse-3D-Vision Technical Report: Generating Executable 3D Worlds from Images through Unified Spatial Reasoning](https://arxiv.org/abs/2609.25741v1) | 3D foundation system / vision-language-geometry spatial reconstruction |
| 2026-09-22 | [OmniFysics-Nano-V2 Technical Report: Understanding the Physical World Across Modalities](https://arxiv.org/abs/2609.25738v1) | omnimodal physical-AI model / physics-aware data and GRPO |
| 2026-09-22 | [MachEmbodied-U0: Unified Understanding and Generation Model for Embodied Intelligence](https://arxiv.org/abs/2609.25627v1) | embodied foundation model / mixture-of-transformers understanding and generation |
| 2026-09-22 | [Route-MHT: Multimodal Transformer Guardrails for Thermal Visual Place Recognition](https://arxiv.org/abs/2607.04745v2) | visual foundation-model system / thermal VPR rejection guardrail |
| 2026-09-22 | [MiMo-V2.6: Scaling Reinforcement Learning Towards Self-Improvement](https://huggingface.co/XiaomiMiMo/MiMo-V2.6-Pro-RL/blob/73875d00b30a89ef8cc353a0b60b0e9f9561952d/MiMo_V2_6_technical_report.pdf) | omnimodal MoE LLM / large-batch mixed agentic RL and multi-teacher on-policy distillation |
| 2026-09-21 | [SingProbe Technical Report](https://arxiv.org/abs/2608.30703v2) | LLM safety / intrinsic streaming guardrail training |
| 2026-09-21 | [MedGPT-oss: Training a General-Purpose Vision-Language Model for Biomedicine](https://arxiv.org/abs/2603.00842v2) | medical VLM |
| 2026-09-21 | [Qwen-Audio-Agent Technical Report](https://arxiv.org/abs/2609.25195v1) | voice agent runtime / foreground-background asynchronous orchestration |
| 2026-09-21 | [Fysiverse-3D-SimReady Technical Report: Agentic Physical Simulation for Pragmatic 3D World Reconstruction](https://arxiv.org/abs/2609.31715v1) | 3D agent system / simulation-ready reconstruction and physical refinement |
| 2026-09-21 | [OmniFysics-Captioner Technical Report: Grounding Omni-Modal Understanding in the Physical World for Better Captioning](https://arxiv.org/abs/2609.31714v1) | omnimodal captioning / grounded physical-evidence training |
| 2026-09-20 | [VGGT-Prime: Compute-Adaptive Mixture-of-Heads for Efficient Visual Geometry Transformers](https://arxiv.org/abs/2609.23733v1) | visual foundation inference / compute-adaptive mixture-of-heads |
| 2026-09-20 | [Paint-Anything: Unified Any-Color Control for Image Generation and Editing](https://arxiv.org/abs/2609.20816v2) | image foundation model / hex-color instruction adaptation |
| 2026-09-19 | [Block-Sparse Attention with Semantic-Geometric Decoupled Routing](https://arxiv.org/abs/2609.22884v1) | LLM inference / semantic-geometric block-sparse attention |
| 2026-09-19 | [Causilo Technical Report](https://arxiv.org/abs/2609.22866v1) | tabular foundation model / synthetic pretraining and linear-cost summaries |
| 2026-09-19 | [StepAudio 3 Realtime Technical Report](https://arxiv.org/abs/2609.14005v2) | realtime audio-language foundation model / think-while-speaking duplex interaction |
| 2026-09-18 | [SEA-LION-v4.8: A Technical Report](https://arxiv.org/abs/2609.18310v3) | Southeast Asian LLM / continued pretraining and on-policy distillation |
| 2026-09-17 | [DeepSeek-V4.1-Flash: Pushing the Limits of KV Cache Compression](https://arxiv.org/abs/2609.19969v1) | multimodal MoE / KV-cache-efficient long-context pretraining and agentic post-training |
| 2026-09-17 | [GigaBrain-WBC-0.5: A Behavior World Model for Robust Humanoid Whole-Body Tracking with Environment Interaction](https://arxiv.org/abs/2608.18234v4) | embodied behavior world model / PPO and terrain-aware training |
| 2026-09-17 | [OccPlanner: Goal-Aware Occupancy-Conditioned Diffusion Planner for PixelGoal Navigation](https://arxiv.org/abs/2608.14160v2) | embodied navigation / occupancy-conditioned diffusion planning |
| 2026-09-17 | [From Procedural Skills to Strategy Genes: Towards Experience-Driven Test-Time Evolution](https://arxiv.org/abs/2604.15097v4) | test-time evolution |
| 2026-09-17 | [Reverse Neighbor Sliding and Order Selection for Efficient Multi-Proximity Graph Merging](https://arxiv.org/abs/2602.17099v2) | retrieval / vector index infrastructure |
| 2026-09-17 | [K2-V2: A 360-Open, Reasoning-Enhanced LLM](https://arxiv.org/abs/2512.06201v3) | LLM pretraining / mid-training and SFT |
| 2026-09-17 | [Astronex-World 1.0: Real-Time Interactive World Model Foundation](https://arxiv.org/abs/2609.20034v1) | interactive world model / low-resource causal conversion and distillation |
| 2026-09-17 | [Multimodal Conversational Context for LLM-Based ASR: Data Construction, Training, and Benchmark](https://arxiv.org/abs/2609.19765v1) | LLM-based ASR / multimodal conversational-context training |
| 2026-09-17 | [AutoResearch: Insight In, Hallucination Out](https://arxiv.org/abs/2608.17906v4) | scientific agent system / grounded idea generation and evidence-reviewed experiment execution |
| 2026-09-17 | [LongWoF-Bench: Evaluating EvoMap Genes for Verifiable Long-Workflow Tasks](https://arxiv.org/abs/2608.23200v4) | agent memory / verified-experience distillation and cross-model inference reuse |
| 2026-09-17 | [JEPA-Anything: Learning Predictive Models across Different Worlds](https://arxiv.org/abs/2609.20800v1) | scientific world model / orthogonal predictive-factor latent pretraining |
| 2026-09-16 | [Qwen-Music Technical Report](https://arxiv.org/abs/2607.11699v3) | audio / music generation |
| 2026-09-16 | [PhysVGGT: Feed-Forward Dense Physical Property Estimation from A Single Image](https://arxiv.org/abs/2609.18920v1) | visual foundation model / dense physical-property adaptation |
| 2026-09-16 | [RayOrch: Programming and Executing Lineage-Controlled Multi-Grain Dataflows for Foundation-Model Data Preparation](https://arxiv.org/abs/2609.18703v1) | foundation-model data infrastructure / lineage-preserving distributed execution |
| 2026-09-16 | [Technical Report: One-Step Drifting Action Heads for GR00T N1.7](https://arxiv.org/abs/2609.18108v1) | VLA inference / one-step drifting action-head adaptation |
| 2026-09-16 | [ScienceIDE: Turning World's Scientific Codebase into Agent Learnable Environments](https://arxiv.org/abs/2609.19134v1) | scientific agent training / executable codebase environments and verified-trajectory SFT/RL |
| 2026-09-15 | [BlueLM-GUI Technical Report: A Real-Device-Centric Flywheel for Self-Improving Mobile GUI Agents](https://arxiv.org/abs/2609.12394v3) | GUI agent / real-device continual pretraining and RL flywheel |
| 2026-09-15 | [Notes2Skills: From Lab Notebooks to Certainty-Aware Scientific Agent Skills](https://arxiv.org/abs/2606.11897v2) | scientific LLM agent system / certainty-preserving skill compilation and evidence-gated execution |
| 2026-09-15 | [ScienceBuddy: Recursive-in-Recursive Self-Improvement for Interactive Scientific Agents](https://arxiv.org/abs/2609.17523v1) | scientific agent / harness evolution and recursive reinforcement-learning post-training |
| 2026-09-15 | [LimiX-2: A Contextual Mechanism Network Towards General Structured-Data Intelligence](https://arxiv.org/abs/2609.17488v1) | tabular foundation model / contextual-mechanism pretraining |
| 2026-09-14 | [Valley3: Scaling Omni Foundation Models for E-commerce](https://arxiv.org/abs/2605.01278v3) | multimodal / omni LLM |
| 2026-09-14 | [Reconstructing Is Not Acting: Action-Centric Latent Dynamics Modeling](https://arxiv.org/abs/2609.15189v1) | world-model representation / action-centric latent dynamics pretraining |
| 2026-09-14 | [Shared KV Caching for Replicated 27B Inference: Correctness Failures and Performance Boundaries](https://arxiv.org/abs/2609.15021v1) | LLM inference infrastructure / replicated shared KV caching |
| 2026-09-14 | [PhysBrain 1.5: From Vision-Language Models to Physical Foundation Models](https://arxiv.org/abs/2609.14973v1) | physical foundation model / autoregressive vision-language-action training |
| 2026-09-14 | [Discovery Foundation Models: Toward Open-Ended Discovery Intelligence](https://arxiv.org/abs/2609.15973v1) | scientific foundation-model systems / evidence-grounded discovery loops and capability formation |
| 2026-09-13 | [Bioinfoysis Technical Report](https://arxiv.org/abs/2609.03871v2) | bioinformatics LLM agents / persistent analysis harness |
| 2026-09-12 | [Multimodal Duplex Interaction Agent](https://arxiv.org/abs/2609.08977v3) | omnimodal agent / real-time full-duplex interaction |
| 2026-09-11 | [Training Agents to Evolve with Their Harness: TaoLive Digital Avatar Agent Technical Report](https://arxiv.org/abs/2608.15763v4) | digital-avatar agent / harness-aware SFT, distillation and RL |
| 2026-09-11 | [StepAudio 3 Gen Technical Report](https://arxiv.org/abs/2609.12945v1) | audio foundation model / progressive autoregressive RVQ generation |
| 2026-09-11 | [StepAudio 3 Music Technical Report](https://arxiv.org/abs/2609.16034v1) | music foundation model / symbolic planning and diffusion generation |
| 2026-09-11 | [DiffSynth-Music: Audio-Conditioned KV-Cache Adapters for Controllable Music Generation](https://arxiv.org/abs/2609.12774v1) | music generation / audio-conditioned KV-cache adapter training |
| 2026-09-10 | [ECHELON: continuity for a model that cannot keep its context](https://github.com/echelon-project/echelon-research/blob/61e67ddae0123e94f2c9709f20175d71fa915498/THESIS.md) | agent memory / long-horizon model continuity |
| 2026-09-10 | [VibeVoice-ASR-Streaming Technical Report](https://arxiv.org/abs/2609.02812v2) | audio / streaming LLM-based speaker-attributed ASR |
| 2026-09-10 | [Pelican-Sim 1.0: A General World Model Simulator for Embodied Intelligence](https://arxiv.org/abs/2609.12036v1) | embodied world model / sparse MoE pretraining and rollout distillation |
| 2026-09-10 | [Xiaomi-CocktailASR-1 Technical Report](https://arxiv.org/abs/2609.11274v1) | audio LLM / target-speaker ASR and rejection-aware supervised training |
| 2026-09-10 | [MOSAIC: Query-Aware Exploration Policy Adaptation for GraphRAG](https://arxiv.org/abs/2609.11065v1) | LLM inference system / query-adaptive GraphRAG exploration |
| 2026-09-10 | [KuaiRP Series Role-playing Models Technical Report](https://arxiv.org/abs/2609.11127v1) | role-playing LLM / SFT, RL and two-stage on-policy distillation |
| 2026-09-09 | [Unlocking the Power of LLM Reasoning in Antibody Design with OpenDDE-Harness](https://github.com/aurekaresearch/OpenDDE-Harness/blob/e9ab45154fa314bba4ae455a1a9a4a1e2069ba37/docs/assets/OpenDDE_harness_tech_report.pdf) | scientific agent system / LLM-guided antibody design and structure-feedback infrastructure |
| 2026-09-09 | [Light REACT: Building Resilient Whole-Body Intelligence for Scalable Deployment](https://www.lightorigins.com/en/blog/light-react) | humanoid control / teacher RL, multi-teacher distillation and preference RL |
| 2026-09-09 | [A-JIT: Agentic Just-In-Time Software Construction](https://arxiv.org/abs/2609.10248v1) | agentic software system / self-evolving runtime |
| 2026-09-09 | [Data-Centric Post-Training for Financial Reasoning: Mining, Distillation, and Verifiable Learning](https://arxiv.org/abs/2609.10113v1) | finance LLM / retention-aware SFT and RL post-training |
| 2026-09-09 | [Qwen-Audio-3.0-ASR Technical Report](https://arxiv.org/abs/2609.07549v2) | audio / multilingual MoE LLM-based ASR |
| 2026-09-09 | [LightNav-0: Eliciting VLM Spatial Intelligence for Generalist Embodied Navigation](https://arxiv.org/abs/2608.30935v2) | embodied VLM / ER mid-training, SFT and online RL |
| 2026-09-09 | [An Open Recipe for IMO Gold: Training Nemotron for Olympiad Mathematics](https://arxiv.org/abs/2609.10712v1) | mathematical reasoning LLM / long-context SFT, RL and ensemble inference |
| 2026-09-09 | [NCP-ArchPreview Technical Report: Moving towards Latent Space Language Models through Next Concept Prediction](https://arxiv.org/abs/2609.10715v1) | latent-space LLM / joint next-token and next-concept pretraining |
| 2026-09-08 | [amad-vlm6: What Merging Two Arabic OCR Models Actually Fixes — and Breaks](https://huggingface.co/amad-iq/amad-vlm6-technical-report/blob/3f93e5027d01744cd9c773416f514795fc2f6f02/README.md) | Arabic OCR VLM / model merging and evaluation |
| 2026-09-08 | [Practical Evaluation of Qwen3.8-27B on an RTX 3060 12 GB](https://doi.org/10.5281/zenodo.22650802) | LLM inference / consumer-GPU long-context serving and Windows-WSL2 runtime analysis |
| 2026-09-08 | [Video-MOPD: Multi-Teacher On-Policy Distillation for Video Understanding](https://arxiv.org/abs/2609.09300v1) | video VLM / multi-teacher on-policy distillation and RL |
| 2026-09-08 | [Prior-free relative 6D pose estimation of multiple object instances](https://arxiv.org/abs/2609.08949v1) | visual foundation model / training-free 6D pose inference |
| 2026-09-08 | [AuK Technical Report: An Open-Source Foundational Model for Speech Generation and Editing](https://arxiv.org/abs/2609.08936v1) | audio foundation model / speech generation and editing |
| 2026-09-08 | [Miles v0.1: Production-Level Post-Training](https://arxiv.org/abs/2609.08368v1) | LLM post-training / frontier-scale RL infrastructure |
| 2026-09-08 | [Palmyra x6 Technical Report: An Agentic, Tool-Use Model Post-Trained via Anchored Supervised Fine-Tuning](https://arxiv.org/abs/2608.16620v3) | agentic LLM / anchored supervised fine-tuning |
| 2026-09-08 | [Multimodal-Multiresolution Foundation Model for Lunar Remote Sensing](https://arxiv.org/abs/2609.13283v1) | remote-sensing foundation model / multimodal lunar pretraining |
| 2026-09-07 | [CAGE Technical Report Series](https://github.com/google/cybernetic-agent-governance-engine/blob/3a9e5b3fbd1d4fb54aa00257200b19b6b50673a9/docs/technical-report/README.md) | multi-agent governance runtime / safety verification and deployment infrastructure |
| 2026-09-07 | [Online Draft Co-Training for Speculative Decoding in Large-Scale, Long-Context RL Post-Training](https://arxiv.org/abs/2609.07108v1) | LLM training/inference infrastructure / speculative decoding |
| 2026-09-07 | [EXAONE Finance 1.0: An Attention-free Time Series Foundation Model for Financial Time Series](https://arxiv.org/abs/2609.04239v2) | financial time-series foundation model / attention-free pretraining |
| 2026-09-06 | [BinauralVAE: Spatial Audio Reconstruction For World Models](https://arxiv.org/abs/2609.06837v1) | audio world-model representation / binaural VAE training |
| 2026-09-05 | [ENGRAFT: adding facts to a mixture-of-experts language model by gradient descent on eight rows of its n-gram memory table](https://github.com/fulvian/engraft-ngram/blob/6c32ee87ad5ba652666e17895a3f1a5479ac3380/paper/engraft.pdf) | language-model editing / explicit n-gram memory and inference-engine integration |
| 2026-09-04 | [Agnes Harness (AGH): A Recoverable, Evidence-First Agent Runtime](https://github.com/AgnesAI-Labs/agnes-harness/blob/f02477e7644d510fbe5f216b7e1045d84891543b/agnes-harness-tech-report.pdf) | agent runtime / recoverable evidence-first model harness |
| 2026-09-04 | [GE-Act 2.0: Pretraining and Scaling a World-Action Model for Robotic Manipulation](https://arxiv.org/abs/2609.05588v1) | robotics / world-action model pretraining and scaling |
| 2026-09-04 | [Xiaomi-TabLDM: A Tabular Foundation Model Technical Report](https://arxiv.org/abs/2609.03880v2) | tabular foundation model / synthetic pretraining and test-time scaling |
| 2026-09-04 | [VisCAD: A Foundation Model Suite with Multimodal Industrial CAD Intelligence](https://arxiv.org/abs/2609.03811v2) | multimodal CAD foundation model / mid- and post-training |
| 2026-09-04 | [Improving Federated Graph Recommendation with Semantic Guidance](https://arxiv.org/abs/2606.15277v2) | recommendation / LLM |
| 2026-09-03 | [Agnes 2B: A Reproducible and Cost-Aware Two-Stage Pretraining Protocol on Consumer GPU Clusters](https://github.com/AgnesAI-Labs/Agnes-2B-Pretraining/blob/e4193561c901179e0611e3b6d09ae1dffad9b046/Agnes_2B_Pretraining_Technical_Paper.pdf) | language-model pretraining / consumer-GPU distributed training |
| 2026-09-03 | [A Production Architecture for a Cluster-Shared L3 KV-Cache Pool on PCIe GPU Infrastructure](https://github.com/AgnesAI-Labs/agnes-l3-kv-cache-pool/blob/1e2579f0dcce5aa78e12c18445ab93a781720e20/agnes-l3-kv-cache-report-new.pdf) | LLM inference infrastructure / cluster-shared KV-cache design |
| 2026-09-03 | [Mitra-v2 Technical Report](https://arxiv.org/abs/2609.04540v1) | tabular foundation model / synthetic pretraining |
| 2026-09-03 | [How Far Can Synthetic Data Take Thai OCR?](https://arxiv.org/abs/2609.03595v1) | OCR VLM / synthetic-data adaptation |
| 2026-09-03 | [Building and Evaluating Fixed-Voice Thai TTS from Synthetic Speech](https://arxiv.org/abs/2609.03502v1) | audio / teacher-generated synthetic TTS training |
| 2026-09-03 | [Puro-2B: Poor Lab's Qwen2-1.5B Trained on RTX 5090 within $5090](https://arxiv.org/abs/2608.27370v2) | small LLM / cost-efficient from-scratch pretraining |
| 2026-09-02 | [Sparse MoE Control on Qualcomm Hexagon HTP](https://github.com/gat45/htp-npu-runtime/blob/2709e15f6dbc7a6a43d7859bf722d2ef97a1a652/RAPPORT_CONTROLE_MOE_MARCO_HTP_20260902_EN.md) | LLM inference / mobile NPU sparse-MoE profiling |
| 2026-09-02 | [SpecXMaster Technical Report](https://arxiv.org/abs/2603.23101v4) | agent / deep research |
| 2026-09-02 | [Pailitao-MMSearch: Building Native E-Commerce Multimodal Search Foundation](https://arxiv.org/abs/2607.17499v2) | e-commerce multimodal search / continual pretraining |
| 2026-09-01 | [Character Transfer Across Three Model Families](https://www.getsimpledirect.com/research/papers/character-transfer-across-three-model-families) | LLM character alignment / cross-family SFT and DPO |
| 2026-09-01 | [Runtime Pass Is Not Correctness](https://www.getsimpledirect.com/research/papers/runtime-pass-is-not-correctness) | reasoning LLM / SFT-DPO efficiency post-training and verifier audit |
| 2026-09-01 | [Sixty Extra Tokens per Second](https://github.com/ucicelos/flashnext-hybrid/blob/e8bfdb53d32f2be8444b96e8b69add844acc2d26/README.md) | LLM inference infrastructure / hybrid APU-eGPU speculative decoding |
| 2026-09-01 | [Agnes Flash V2.5: Efficient Agentic Post-Training with Verified Environments, Asymmetric PPO, and On-Policy Multi-Teacher Distillation](https://github.com/AgnesAI-Labs/agnes-flash-post-training/blob/2038b7798f6f8a730aa6777ef5ab4db128553a81/Agnes_Flash_V2.5_Technical_Report.pdf) | agentic LLM / proposed SFT asymmetric PPO and on-policy distillation |
| 2026-09-01 | [Instella-MoE Technical Report](https://arxiv.org/abs/2609.00791v1) | open MoE LLM / full-stack pretraining and post-training |
| 2026-08-31 | [DreamX-Creator: Democratizing Native Audio-Video Generation at 2K Resolution](https://arxiv.org/abs/2608.31106v1) | native audio-video generation / joint pretraining RL and one-step 2K distillation |
| 2026-08-31 | [A.X K2 Technical Report](https://arxiv.org/abs/2608.30181v1) | frontier LLM / MoE pretraining and hybrid-reasoning post-training |
| 2026-08-31 | [TuringLLM: Efficiently Scaling Foundation Models Toward Physical AI](https://arxiv.org/abs/2608.30567v1) | physical-AI LLM / MoE pretraining and long-context continuation |
| 2026-08-31 | [In-Cell Learning: Language Models That Update Their Own Weights in Sequence Without Changing the File They Ship](https://arxiv.org/abs/2608.20873v3) | LLM continual learning / quantization-cell weight updates |
| 2026-08-31 | [On the Design of Qwen3.8-Next Architecture: Evaluation, Efficiency, and Training Stability](https://arxiv.org/abs/2608.30320v1) | multimodal MoE LLM / architecture, pretraining efficiency and stability |
| 2026-08-31 | [RLinf-USER: A Unified and Extensible System for Real-World Online Policy Learning in Embodied AI](https://arxiv.org/abs/2602.07837v4) | embodied RL / real-world training infrastructure |
| 2026-08-29 | [Prefilling-dLLM: Predictive Prefilling for Long-Context Inference in Diffusion Language Models](https://arxiv.org/abs/2606.10537v2) | LLM inference / diffusion LM |
| 2026-08-27 | [Thomson: Continual Learning of Frontier Models for SovereignAI](https://arxiv.org/abs/2608.27147v1) | professional-domain frontier LLM / continual pretraining and agentic post-training |
| 2026-08-27 | [Magpie: Real-Time World Renderer for Interactive Games](https://arxiv.org/abs/2608.27168v1) | world model system / real-time generative game rendering |
| 2026-08-27 | [UI-Venus-2 Technical Report](https://arxiv.org/abs/2609.00028v1) | foundation GUI agent / multimodal mid-training, offline RL and on-policy distillation |
| 2026-08-26 | [InternBootcamp: Boosting LLM Reasoning with Verifiable Task Scaling](https://arxiv.org/abs/2508.08636v4) | agentic LLM / verifiable task-environment SFT and RL |
| 2026-08-26 | [Cubit: Token Mixer with Kernel Ridge Regression](https://arxiv.org/abs/2605.06501v3) | token mixer / architecture |
| 2026-08-26 | [How Far Can Multilingual Text Embeddings Be Trained From Scratch? A Compute-Efficient Study of Arabic, English, and Urdu](https://www.menteeai.org/research) | multilingual text embedding / from-scratch MLM and contrastive distillation |
| 2026-08-26 | [One Policy, Many Embodiments: Unified Camera-Centric Action Geometry Pre-training for Heterogeneous Embodied Manipulation](https://arxiv.org/abs/2608.26058v1) | robotics / VLA pretraining and cross-embodiment action unification |
| 2026-08-26 | [EXAONE Tabular 1.0 : Technical Report](https://arxiv.org/abs/2608.25774v1) | tabular foundation model / synthetic-prior pretraining and in-context learning |
| 2026-08-26 | [Isaac 0.5: Percepts Scale Control](https://huggingface.co/PerceptronAI/Isaac-0.5) | embodied foundation model / multimodal pretraining and robot-policy post-training |
| 2026-08-26 | [OASIS: A Rubric-Based Multimodal Assessment Platform Using Large Language Models](https://arxiv.org/abs/2609.09180v1) | multimodal LLM system / rubric-based grading orchestration and audited deployment |
| 2026-08-25 | [On-Policy Self-Distillation in Diffusion Models](https://arxiv.org/abs/2608.24646v1) | image generation / diffusion reward alignment and on-policy self-distillation |
| 2026-08-25 | [RecGPT-Mobile-V2 Technical Report](https://arxiv.org/abs/2608.24295v1) | recommendation / on-device query-prediction model and RL distillation |
| 2026-08-25 | [WeMM-Embedding: WeChat Multi-Modal Embedding Technical Report](https://arxiv.org/abs/2608.24053v1) | multimodal embedding / alignment pretraining and relevance refinement |
| 2026-08-25 | [Seldon: Foundation, Made Tabular.](https://www.neuralk.ai/white-paper/seldon-foundation-made-tabular) | tabular foundation model / synthetic-prior pretraining and in-context prediction |
| 2026-08-24 | [Macaron-V1: Towards Open Continual Learning with Self-Improvement and Mixture-of-LoRA](https://arxiv.org/abs/2608.09819v2) | agentic LLM / Mixture-of-LoRA continual post-training |
| 2026-08-24 | [H-OPD: Confidence Aware Heterogeneous Multi-Teacher Multimodal On-policy Distillation](https://arxiv.org/abs/2607.02592v2) | multimodal reasoning / distillation |
| 2026-08-24 | [FlatVPR: Plug-and-play Geo-linear Residual Adapter for Geometric Rectification of Foundation Model Feature Manifolds](https://arxiv.org/abs/2606.01734v2) | visual foundation model / VPR |
| 2026-08-24 | [Towards a Densing Law for User Representation Learning at Billion-Scale Capacity](https://arxiv.org/abs/2608.23392v1) | user representation / billion-scale tokenization scaling law |
| 2026-08-24 | [FinixDoc: Rethinking Financial Document Parsing Beyond Saturated Benchmarks](https://arxiv.org/abs/2608.22842v1) | financial document VLM / contrastive learning and multi-stage RL |
| 2026-08-24 | [Population-Scalable Multi-Agent World Modeling](https://arxiv.org/abs/2608.08600v3) | multi-agent world model / population-scalable training and rendering |
| 2026-08-24 | [Prime Agent: A Self-Improving RLM Harness](https://arxiv.org/abs/2608.23552v1) | agentic LLM / persistent RLM harness and test-time compute |
| 2026-08-23 | [SkillNet: Create, Evaluate, and Connect AI Skills](https://arxiv.org/abs/2603.04448v3) | agent skill infrastructure / benchmark / routing |
| 2026-08-23 | [MCP-Universe RL: A Framework for Training MCP Tool-Use Agents via Reinforcement Learning](https://arxiv.org/abs/2608.22167v1) | agentic LLM / MCP tool-use reinforcement-learning infrastructure |
| 2026-08-22 | [ZenGen: Social Mind for LLMs](https://github.com/ZenGen-AI/ZenGen/blob/b528af4f60c9a356ed2dad49f5e80a293a196bae/ZenGen_TechReport.pdf) | LLM social reasoning / staged SFT OPD and GRPO post-training |
| 2026-08-22 | [Sample-Efficient Post-Training for LEGO Spatial-Physics Reasoning](https://arxiv.org/abs/2606.07602v2) | LLM post-training / spatial reasoning |
| 2026-08-21 | [Index SLM Technical Report](https://arxiv.org/abs/2607.09885v3) | small language model / LLM training |
| 2026-08-21 | [AudioWorldSim: Realistic Binaural Audio Datasets For World Models](https://arxiv.org/abs/2608.21075v1) | world-model training infrastructure / binaural audio simulation and dataset generation |
| 2026-08-20 | [DFM Mimir v1: An Open HRM Delivering Frontier Performance at 1B Parameters Using Only Permissible Post-Training Data](https://arxiv.org/abs/2608.13517v2) | reasoning LLM / permissible-data training from scratch |
| 2026-08-20 | [PILOT Technical Report](https://arxiv.org/abs/2608.18637v2) | agentic recommendation / experiment optimization |
| 2026-08-19 | [UBio-MolFM: Enabling Biomolecular Dynamics at DFT Accuracy and $10^5$ Atoms with One Untuned Potential](https://arxiv.org/abs/2608.18623v1) | biomolecular foundation model / multi-stage quantum pretraining |
| 2026-08-19 | [SLAI T-Rex: Full-Parameter Post-training of the DeepSeek-V4 Family on Ascend SuperPOD](https://arxiv.org/abs/2607.20145v3) | LLM post-training / trillion-parameter MoE training systems on Ascend |
| 2026-08-18 | [Douyin Multimodal Embedding Model Technical Report](https://arxiv.org/abs/2608.02148v3) | multimodal embedding / contrastive pretraining |
| 2026-08-18 | [Marco-Voice Technical Report](https://arxiv.org/abs/2508.02038v6) | speech generation / voice cloning and controllable emotion training |
| 2026-08-17 | [Nesso2-0.4B-Agentic — Technical Report](https://github.com/mii-llm/zagreus-nesso-slm/blob/49e1b232ffde307e63370842d635e47b4f906452/nesso2/report.html) | bilingual agentic compact LLM / continued pretraining, context extension and SFT |
| 2026-08-17 | [Sign Language Video Synthesis via Loss-Guided Multi-Expert GANs](https://arxiv.org/abs/2608.13368v2) | video generation / large multi-expert GAN training |
| 2026-08-16 | [UI-Mate: Advancing Open-Weight Foundation GUI Agents with In-Context Demonstrations](https://arxiv.org/abs/2608.15930v1) | GUI agent / environment-grounded SFT and online RL |
| 2026-08-16 | [GigaBrain-0.7: Scaling Embodied Foundation Models to Emergent Capabilities with a Three-System Architecture](https://arxiv.org/abs/2608.15875v1) | embodied foundation model / VLA pretraining and offline-to-online RL |
| 2026-08-15 | [DanceOPD: On-Policy Generative Field Distillation](https://arxiv.org/abs/2606.27377v3) | image generation / distillation |
| 2026-08-15 | [MOSS-VL Technical Report](https://arxiv.org/abs/2608.15045v1) | multimodal VLM / pretraining and real-time interaction SFT |
| 2026-08-15 | [Teutonic-I 10B: Competition Parallel Decentralized Training](https://www.teutonic.ai/teutonic-i-10b.pdf) | LLM pretraining / decentralized competitive checkpoint training |
| 2026-08-15 | [SysEvolve: An AI-native, safe, autonomous adversarial attack-defense co-evolutionary system](https://arxiv.org/abs/2608.15012v1) | cybersecurity agents / adversarial attack-defense co-evolution |
| 2026-08-14 | [Teffic-Audio: Tell Fact from Fiction](https://arxiv.org/abs/2607.28351v2) | audio / speech deepfake detection |
| 2026-08-14 | [OlmoEarth v1.2: A more efficient family of OlmoEarth models](https://arxiv.org/abs/2605.20804v3) | Earth observation foundation model |
| 2026-08-14 | [MegaParts: Scaling Part-Aware 3D Object Generation to 300 Parts via Token-Efficient Autoregressive Modeling](https://arxiv.org/abs/2608.14783v1) | 3D generation / long-context autoregressive LLM |
| 2026-08-14 | [Never the Number: Structural Abstention for AI Systems Whose Answers Are Consumed as Fact](https://arxiv.org/abs/2608.13926v1) | LLM application system / deterministic query kernel and structural abstention |
| 2026-08-13 | [DREAM Technical Report](https://arxiv.org/abs/2608.09408v3) | agentic recommendation / on-policy distillation and offline RL |
| 2026-08-13 | [TabH2O: A Unified Foundation Model for Tabular Prediction](https://arxiv.org/abs/2605.18383v2) | tabular foundation model |
| 2026-08-13 | [AlayaWorld: Interactive Long-Horizon World Modeling - Full Technical Report (v1.1)](https://arxiv.org/abs/2608.13492v1) | world model / conditioning and memory redesign |
| 2026-08-13 | [Transferring Character Post-Training to Mistral 7B](https://www.getsimpledirect.com/research/papers/prova-character-transfer) | LLM character alignment / Mistral 7B SFT and DPO |
| 2026-08-13 | [AutoDesign: Meta-Harness Optimization for Long-Horizon Agentic Design](https://arxiv.org/abs/2608.13560v1) | multimodal design agent / meta-harness optimization |
| 2026-08-12 | [Sona Technical Report](https://arxiv.org/abs/2608.11015v2) | generative recommendation / pretraining and online distillation |
| 2026-08-12 | [RLinf-VLA: A Unified and Efficient Framework for Reinforcement Learning of Vision-Language-Action Models](https://arxiv.org/abs/2510.06710v3) | robotics / VLA RL framework |
| 2026-08-12 | [Confucius4-TTS: Transcript-Free Cross-Lingual Zero-Shot TTS with a Learnable Speaker Encoder](https://arxiv.org/abs/2608.11650v1) | audio / multilingual zero-shot TTS |
| 2026-08-12 | [Luna-TTS Family Technical Report](https://arxiv.org/abs/2608.11593v1) | audio / diffusion TTS pretraining and RL |
| 2026-08-12 | [Meshy T2: Fast Native Mesh Generation with Flow Matching](https://arxiv.org/abs/2607.28675v3) | 3D generation / mesh VAE and flow-matching training |
| 2026-08-12 | [StellaVLA: In-Context Structured Demonstration for Generalizable Vision-Language-Action Models](https://arxiv.org/abs/2608.11671v1) | robotics / VLA structured-context post-training |
| 2026-08-11 | [IndexTTS 2.5 Technical Report](https://arxiv.org/abs/2601.03888v5) | audio / speech model |
| 2026-08-11 | [MEGA: Self-Evolving Agent Optimization Infrastructure via Wisdom Graph](https://arxiv.org/abs/2608.10504v1) | agent optimization / self-evolving wisdom-graph infrastructure |
| 2026-08-11 | [Sekai2: From World Exploration to Interactive World Modeling](https://arxiv.org/abs/2608.09449v2) | world-model pretraining data / long-horizon video and camera-trajectory corpus |
| 2026-08-10 | [UI-MOPD: Multi-Platform On-Policy Distillation for Unified GUI Agents](https://arxiv.org/abs/2607.04425v2) | GUI agent / multi-platform on-policy distillation |
| 2026-08-10 | [dots.tts Technical Report](https://arxiv.org/abs/2606.07080v2) | audio / speech model |
| 2026-08-10 | [Motif 3: Technical Report](https://arxiv.org/abs/2608.09119v1) | frontier MoE LLM / pretraining and specialist-teacher post-training |
| 2026-08-10 | [Cracks in the Foundation: Seemingly Minor Architectural Choices Impact Long Context Extension](https://arxiv.org/abs/2608.10296v1) | LLM architecture / long-context extension |
| 2026-08-09 | [Branch2Skill: Efficient Skill Evolution Through Reasoning Trees](https://arxiv.org/abs/2608.08677v1) | agent skill evolution / reasoning-tree supervision |
| 2026-08-08 | [Search over the Visual World: Persistent Visual Memory, Layered Indexes, and Source-Grounded Evidence](https://arxiv.org/abs/2608.08075v1) | visual-agent infrastructure / persistent memory and grounded retrieval |
| 2026-08-07 | [Kimi K3: Open Frontier Intelligence](https://arxiv.org/abs/2607.24653v2) | frontier multimodal LLM / pretraining and agentic RL |
| 2026-08-07 | [Kimi K2.5: Visual Agentic Intelligence](https://arxiv.org/abs/2602.02276v2) | visual agentic intelligence |
| 2026-08-07 | [BigBang: Pursuing Open-Ended Intelligence through Self-Evolving Synthesis of Verifiable Frontier Tasks](https://endlessfrontier.tech/assets/paper.pdf) | agentic LLM / self-evolving synthetic-data post-training |
| 2026-08-07 | [CubicQuant: Parametric Non-Uniform Codebooks for High-Throughput LLM Inference with 1-8-Bit Weights](https://arxiv.org/abs/2608.06763v1) | LLM inference / 1-8-bit post-training weight quantization |
| 2026-08-06 | [Controllable Clothing: Precise Labels and Generation for Virtual Try-On with Latent Diffusion Models](https://arxiv.org/abs/2608.05834v1) | image-generation foundation-model adaptation / controllable virtual try-on |
| 2026-08-05 | [GrandCode: Achieving Grandmaster Level in Competitive Programming via Agentic Reinforcement Learning](https://arxiv.org/abs/2604.02721v3) | competitive programming agentic RL |
| 2026-08-05 | [K-EXAONE 2.0 Technical Report](https://arxiv.org/abs/2608.04505v1) | multilingual MoE LLM / upcycled pretraining and agentic post-training |
| 2026-08-05 | [LLM-Assisted Detection and Repair of Hardware Security Vulnerabilities in Verilog Designs](https://arxiv.org/abs/2608.04907v1) | LLM security-agent system / Verilog vulnerability analysis and simulation-guided repair |
| 2026-08-04 | [TAOT: Topology-Aware Optimal Transport for Dynamic Expert Replica Placement in MoE Training](https://arxiv.org/abs/2608.03676v1) | MoE training infrastructure / topology-aware expert replication |
| 2026-08-04 | [SwanTale: Unified Multi-Speaker Speech and Audio Generation for Instruct and Zero-Shot Tasks](https://arxiv.org/abs/2608.02023v2) | audio generation / curriculum and GRPO post-training |
| 2026-08-04 | [Opt.Gear Technical Report](https://arxiv.org/abs/2608.01034v2) | edge LLM / pretraining and supervised fine-tuning |
| 2026-08-04 | [LocAnyMed: Vision-Language Grounding for Multimodal Medical Images](https://arxiv.org/abs/2608.03322v1) | medical VLM / full-parameter SFT and rationale training |
| 2026-08-04 | [TerraZero: Procedural Driving Simulation for Zero-Demonstration Self-Play at Scale](https://arxiv.org/abs/2607.13028v2) | autonomous driving / self-play RL |
| 2026-08-04 | [Metis: Memory Foundation Model](https://arxiv.org/abs/2607.26760v2) | memory foundation model / native agent memory mid-training |
| 2026-08-04 | [Shieldstral](https://arxiv.org/abs/2607.25857v2) | multimodal safety classifier / policy-adaptive post-training |
| 2026-08-04 | [Dr. AGENTONOMICS: A Didactic Experiment of AGENTONOMICS](https://arxiv.org/abs/2608.03524v1) | LLM tutor system / retrieval-grounded teaching and role-orchestrated agent architecture |
| 2026-08-03 | [Weak-to-Strong On-Policy Distillation](https://arxiv.org/abs/2607.26246v2) | LLM post-training / on-policy distillation |
| 2026-08-03 | [WanSong v1.0 Technical Report](https://arxiv.org/abs/2607.14749v4) | audio / music generation |
| 2026-08-03 | [Antares: Foundation Models for Agentic Vulnerability Localization](https://arxiv.org/abs/2608.02407v1) | cybersecurity LLM / agentic code localization |
| 2026-08-03 | [Qwen-CUA: Native Computer Use for (almost) Everything](https://arxiv.org/abs/2608.02352v1) | computer-use agent / SFT and verifiable RL |
| 2026-08-03 | [Cross-Domain Hybrid OPD for Generalizable Search Agents](https://arxiv.org/abs/2608.02101v1) | search agent / RL and on-policy distillation |
| 2026-08-03 | [Domain-Adaptive ASR for Telephony AI Agents: Fine-tuning Canary Flash Models for Enterprise Contact Center Applications](https://arxiv.org/abs/2608.24916v1) | audio / telephony-domain ASR fine-tuning |
| 2026-08-03 | [Mastering PokeGym: Graph-Guided Multimodal Evolution at Test Time](https://arxiv.org/abs/2604.08340v2) | vision-language agent / test-time multimodal configuration evolution |
| 2026-08-02 | [AI Sandbox: Technical Report](https://arxiv.org/abs/2608.02679v1) | LLM experimentation infrastructure / governed multi-tenant model access and deployment |
| 2026-07-31 | [DiffusionGemma Technical Report](https://arxiv.org/abs/2608.00146v1) | diffusion LLM / SFT, RL and sampler distillation |
| 2026-07-31 | [RynnBrain 1.1: Towards More Capable and Generalizable Embodied Foundation Model](https://arxiv.org/abs/2607.17977v2) | embodied foundation model / multimodal pretraining and VLA post-training |
| 2026-07-31 | [openPangu-2.0 Technical Report](https://huggingface.co/openpangu/openPangu-2.0-Pro/blob/main/openPangu-2.0%20Tech%20Report.pdf) | frontier MoE LLM / pretraining long-context extension and OPD post-training |
| 2026-07-31 | [Robostral Navigate](https://arxiv.org/abs/2607.20785v3) | robotics / vision-language navigation SFT and RL |
| 2026-07-31 | [AutoFyn Technical Report: Non-Parametric Expert Iteration for Long-Horizon Agents](https://arxiv.org/abs/2609.05446v1) | agent harness / persistent-state non-parametric expert iteration |
| 2026-07-30 | [Qwen-Audio-3.0-Gen-Preview Technical Report](https://arxiv.org/abs/2607.27011v2) | audio / unified audio generation |
| 2026-07-30 | [The MiniMax-M2 Series: Mini Activations Unleashing Max Real-World Intelligence](https://arxiv.org/abs/2605.26494v2) | agentic LLM / MoE |
| 2026-07-30 | [Qwen-UI-Agent Technical Report: Toward Next-Generation Real-World Centric Foundation GUI Agents](https://arxiv.org/abs/2607.28227v1) | GUI agent / SFT and online RL |
| 2026-07-30 | [Echoverse: Deep, Evolving Environments for Training Computer-Use Agents at Scale](https://arxiv.org/abs/2607.28074v1) | computer-use agent / SFT and RL environments |
| 2026-07-30 | [Frontis-MA1: Training an AI4AI Model towards Recursive Self-Improvement in Machine Learning Engineering](https://arxiv.org/abs/2607.28568v1) | agentic LLM / execution-grounded SFT and RL |
| 2026-07-29 | [Voice Memory for Agentic Speech Recognition](https://arxiv.org/abs/2607.26410v1) | agentic ASR / inference-time memory |
| 2026-07-29 | [Pangram 4 Technical Report](https://arxiv.org/abs/2607.27183v1) | LLM safety / AI-generated-text detection |
| 2026-07-29 | [AngelSpec: Towards Real-World High Performance Inference with Speculative Decoding](https://arxiv.org/abs/2607.25852v2) | LLM inference / speculative-drafter training |
| 2026-07-27 | [Reasoning to Regulate: Chain-of-Thought for Traffic Rule Understanding](https://arxiv.org/abs/2607.24199v1) | autonomous-driving VLM / SFT and RL |
| 2026-07-27 | [Sol-Attn: Accelerating Video Generation Inference via On-the-Fly Attention Sparsification](https://arxiv.org/abs/2607.24027v1) | video generation / sparse-attention inference |
| 2026-07-27 | [Nanbeige4.2-3B: Unlocking Agentic Capabilities in a Compact Model](https://arxiv.org/abs/2607.22083v2) | small agentic LLM / from-scratch pretraining and multi-stage RL |
| 2026-07-26 | [VIPER: Visual In-Context Physics Reasoning for Physically Plausible Video Generation](https://arxiv.org/abs/2607.23472v1) | video generation / physical behavior transfer |
| 2026-07-26 | [$N_0$-VTLA: Scaling Vision-Tactile-Language-Action Model with Latent Tactile Tokens](https://arxiv.org/abs/2607.23782v1) | tactile VLA / visuo-tactile pretraining and offline RL |
| 2026-07-26 | [$N_0$-TWAM: Scaling Tactile-Native World-Action Model for Contact-Rich Manipulation](https://arxiv.org/abs/2607.23783v1) | tactile world-action model / visuo-tactile pretraining |
| 2026-07-26 | [Janus: Architecture of a Persistent AI Individual](https://www.standingwave.io/articles/janus-technical-report) | persistent multimodal agent system / context assembly, memory, bounded affect and verification runtime |
| 2026-07-25 | [Athena-Brain Technical Report: An Efficient Robot Brain for General Intelligence and Embodied Interaction](https://arxiv.org/abs/2607.18985v2) | embodied LLM / post-training |
| 2026-07-25 | [VibeVoice-ASR-BitNet Technical Report](https://arxiv.org/abs/2607.21075v2) | audio / quantized edge ASR |
| 2026-07-25 | [N0-Foundation: Towards the Age of Tactile Intelligence](https://research.neoteai.com/n0-foundation/) | tactile foundation system / representation pretraining and embodied evaluation |
| 2026-07-24 | [DataFlow-Harness: A Grounded Code-Agent Platform for Constructing Editable LLM Data Pipelines](https://arxiv.org/abs/2607.16617v2) | code agent / data pipeline platform |
| 2026-07-24 | [RecGPT-V3 Technical Report](https://arxiv.org/abs/2607.15591v2) | recommendation / LLM foundation model |
| 2026-07-24 | [Gemma 4 Technical Report](https://arxiv.org/abs/2607.02770v2) | multimodal LLM / MoE |
| 2026-07-24 | [AI4AI at Scale: A Full-Pipeline System for Enhancing LLM Agentic Capabilities](https://xyz-lab.ai/blogs/ai4ai-at-scale/assets/bounded-exploration-ai4ai-system-optimization.pdf) | agentic LLM / full-pipeline post-training |
| 2026-07-24 | [Solar Open 2 Technical Report](https://arxiv.org/abs/2607.20062v2) | agentic LLM / pretraining and on-policy distillation |
| 2026-07-22 | [A Sovereign, Open-Source Foundation Model for German and English](https://arxiv.org/abs/2607.09424v3) | multilingual LLM / pretraining |
| 2026-07-22 | [FreyaTTS: A Compact Tokenizer-Free Flow-Matching Transformer for Turkish-First Speech Synthesis](https://arxiv.org/abs/2607.09530v2) | audio / speech model |
| 2026-07-21 | [AgentJet: A Distributed Swarm Training Framework for Agentic Reinforcement Learning](https://arxiv.org/abs/2606.04484v2) | agent RL framework |
| 2026-07-21 | [LinguistAgent Technical Report: A Reflective Multi-Model Platform for Automated Linguistic Annotation](https://arxiv.org/abs/2602.05493v2) | LLM agent platform / linguistic annotation |
| 2026-07-21 | [Mi-Memory: A Lifecycle Memory Framework for Personal AI](https://arxiv.org/abs/2607.18975v1) | agent memory / personal AI |
| 2026-07-21 | [Generative World Renderer at the Speed of Play](https://arxiv.org/abs/2607.18703v1) | world model / real-time rendering |
| 2026-07-21 | [HOMIE: Human-object Centric Video Personalization via Multimodal Intelligent Enhancement](https://arxiv.org/abs/2607.18217v2) | video generation / subject personalization |
| 2026-07-20 | [Hy-Embodied-0.5-VLA: From Vision-Language-Action Models to a Real-World Robot Learning Stack](https://arxiv.org/abs/2606.14409v2) | robotics / VLA |
| 2026-07-20 | [FlashMemory-DeepSeek-V4: Lightning Index Ultra-Long Context via Lookahead Sparse Attention](https://arxiv.org/abs/2606.09079v3) | long-context / sparse attention |
| 2026-07-20 | [Surprise Forcing: What to Remember, When to Skip in Long Video Generation](https://arxiv.org/abs/2607.18436v1) | video generation / inference optimization |
| 2026-07-20 | [AlayaWorld: Interactive Long-Horizon World Modeling -- Full Technical Report](https://arxiv.org/abs/2607.18367v1) | world model / video generation |
| 2026-07-20 | [PGN: Design and Implementation of a Vision-Language Navigation System Based on Pangu Multimodal Foundation Model](https://arxiv.org/abs/2607.17806v1) | vision-language navigation / multimodal adaptation |
| 2026-07-20 | [Octopus v3: Technical Report for On-device Sub-billion Multimodal AI Agent](https://arxiv.org/abs/2404.11459v3) | on-device multimodal agent |
| 2026-07-19 | [TimeLens2: Generalist Video Temporal Grounding with Multimodal LLMs](https://arxiv.org/abs/2607.17423v1) | video MLLM / temporal grounding |
| 2026-07-18 | [Boogu-Image-0.1: Boosting Open Agentic Multimodal Generation via Understanding under a Minimal Budget](https://arxiv.org/abs/2607.13125v2) | unified multimodal / image generation and editing |
| 2026-07-17 | [Orca: The World is in Your Mind](https://arxiv.org/abs/2606.30534v3) | world model / video generation |
| 2026-07-17 | [RhinoVLA Technical Report](https://arxiv.org/abs/2606.07383v4) | robotics / VLA |
| 2026-07-17 | [MOSS Transcribe Diarize Technical Report](https://arxiv.org/abs/2601.01554v7) | audio / speech model |
| 2026-07-17 | [Audio-Visual Flamingo: Open Audio-Visual Intelligence for Long and Complex Videos](https://arxiv.org/abs/2607.16107v1) | audio-visual LLM / long-context SFT and RL |
| 2026-07-16 | [xHC: Expanded Hyper-Connections](https://arxiv.org/abs/2607.14530v1) | LLM pretraining architecture / residual scaling |
| 2026-07-16 | [Native Video-Action Pretraining for Generalizable Robot Control](https://arxiv.org/abs/2607.08639v2) | embodied video-action foundation model / robot control |
| 2026-07-16 | [In-Place Tokenizer Expansion for Pre-trained LLMs](https://arxiv.org/abs/2607.15232v1) | LLM tokenizer adaptation / continued pretraining |
| 2026-07-16 | [ISABEL: A Method for Training Competitive Sub-150M Language Models from Scratch](https://ideoa.co.uk/isabel-method.html) | compact language model / from-scratch pretraining and benchmark-clean fine-tuning |
| 2026-07-15 | [Infinity-Parser2 Technical Report](https://arxiv.org/abs/2607.07836v3) | OCR / document understanding |
| 2026-07-15 | [RxBrain: Embodied Cognition Foundation Model with Joint Language-Visual Reasoning and Imagination](https://arxiv.org/abs/2607.14187v1) | embodied foundation model / multimodal planning |
| 2026-07-15 | [OvisOCR2 Technical Report](https://arxiv.org/abs/2607.13639v1) | OCR / document understanding |
| 2026-07-15 | [Do Agent Optimizers Compound? A Continual-Learning Evaluation on Terminal-Bench 2.0](https://arxiv.org/abs/2607.14004v1) | agent optimization / continual learning |
| 2026-07-14 | [Oracle Agent Memory as an Enterprise Memory Substrate for Long-Horizon AI Agents](https://arxiv.org/abs/2607.13157v1) | agent memory / database infrastructure |
| 2026-07-14 | [Full-Pipeline Inference Optimization for MiMo-V2.5 Series: Pushing Hybrid SWA Efficiency to the Limit](https://arxiv.org/abs/2607.13095v1) | LLM inference optimization |
| 2026-07-14 | [Hy-Embodied-VLM-1.0: Efficient Physical-World Agents](https://arxiv.org/abs/2607.12894v1) | embodied foundation model / VLM |
| 2026-07-14 | [The GEST-Engine: From Event Graphs to Synthetic Video. A Full Technical Report](https://arxiv.org/abs/2607.12231v1) | synthetic data / world-model infrastructure |
| 2026-07-14 | [Z-Reward: Beyond Scalar Rewards by Internalizing Reasoning into Score Distributions](https://arxiv.org/abs/2606.09076v3) | image generation / reward modeling |
| 2026-07-13 | [Qwen-Audio-VAE Technical Report](https://arxiv.org/abs/2607.11738v1) | audio / audio tokenizer |
| 2026-07-13 | [Prompt Generation Technical Report](https://arxiv.org/abs/2607.11326v1) | generative retrieval / training-serving infrastructure |
| 2026-07-13 | [Scaling the Horizon, Not the Parameters: Reaching Trillion-Parameter Performance with a 35B Agent](https://arxiv.org/abs/2606.30616v2) | agentic LLM / SFT and on-policy distillation |
| 2026-07-13 | [Xiaomi-Robotics-U0: Unified Embodied Synthesis with World Foundation Model](https://arxiv.org/abs/2607.11643v1) | embodied world model / multimodal generation |
| 2026-07-13 | [Youtu-Parsing: Perception, Structuring and Recognition via High-Parallelism Decoding](https://arxiv.org/abs/2601.20430v2) | document VLM / staged training and parallel decoding |
| 2026-07-11 | [Embodied-R1.5: Evolving Physical Intelligence via Embodied Foundation Models](https://arxiv.org/abs/2606.11324v2) | embodied foundation model / VLA |
| 2026-07-10 | [Mach-Mind-4-Flash Technical Report](https://arxiv.org/abs/2607.09375v1) | agentic LLM / post-training |
| 2026-07-10 | [Audar-ASR-V1: A Multilingual, Arabic-First Generative Speech Recognition Foundation Model](https://github.com/AudarAI/Audar-ASR-V1/blob/43b5d17461cd47752fe04a5b53c5e2c0adb3c030/report/Audar-ASR-V1-Technical-Report.pdf) | multilingual ASR foundation model / curriculum adaptation and preference alignment |
| 2026-07-10 | [Audar-TTS-V1: A Multilingual, Arabic-First Expressive Speech Synthesis Foundation Model](https://github.com/AudarAI/Audar-TTS-V1/blob/bfbb47c4448d9fd771388b30b4c67a8f4d062aa1/report/Audar-TTS-V1-Technical-Report.pdf) | multilingual TTS foundation model / pretraining and preference alignment |
| 2026-07-09 | [Behavior Foundations for Quadruped Robots: ABot-C0 Technical Report](https://arxiv.org/abs/2607.07370v2) | robotics / behavior foundation model |
| 2026-07-09 | [DeepTutor: Towards Agentic Personalized Tutoring](https://arxiv.org/abs/2604.26962v3) | personalized tutoring agent |
| 2026-07-08 | [Infinite Worlds with Versatile Interactions](https://arxiv.org/abs/2607.07534v1) | interactive world model / causal pretraining and distillation |
| 2026-07-08 | [Scaling Mixture-of-Experts Video Pretraining for Embodied Intelligence](https://arxiv.org/abs/2607.07675v1) | embodied video foundation model / MoE pretraining |
| 2026-07-07 | [The Power of Backdoor Absorption in Community Training](https://arxiv.org/abs/2607.06643v1) | large-model training / security |
| 2026-07-07 | [Harrison.Rad 1.5 Technical Report: A radiology foundation model that can draft reports from images, priors and clinical context](https://arxiv.org/abs/2607.05880v1) | medical multimodal foundation model |
| 2026-07-07 | [Nemotron-Labs-Diffusion: A Tri-Mode Language Model Unifying Autoregressive, Diffusion, and Self-Speculation Decoding](https://arxiv.org/abs/2607.05722v1) | diffusion language model / pretraining and post-training |
| 2026-07-07 | [From Foundation to Application: Improving VLA Models in Practice](https://arxiv.org/abs/2607.06403v1) | robotics / VLA foundation model |
| 2026-07-07 | [Jais 2: A Family of Arabic-Centric Open Large Language Models](https://arxiv.org/abs/2608.13580v1) | Arabic-centric LLM / pretraining and preference alignment |
| 2026-07-07 | [Multiplayer Interactive World Models with Representation Autoencoders](https://arxiv.org/abs/2607.05352v2) | world model / game simulation |
| 2026-07-07 | [Design and Operation of a Federated GPU Cluster for Digital Humanities within DHinfra.at](https://arxiv.org/abs/2609.10552v1) | LLM inference infrastructure / federated GPU cluster and two-tier serving |
| 2026-07-06 | [aiAuthZ: Off-Host, Identity-Bound Authorization for AI Agents](https://arxiv.org/abs/2607.05518v1) | agent authorization / security |
| 2026-07-06 | [KAT-Coder-V2.5 Technical Report](https://arxiv.org/abs/2607.05471v1) | coding agent / post-training |
| 2026-07-06 | [Vision Pretraining for Dense Spatial Perception](https://arxiv.org/abs/2607.05247v1) | visual foundation model / dense perception |
| 2026-07-06 | [ABot-M0.5: Unified Mobility-and-Manipulation World Action Model](https://arxiv.org/abs/2607.00678v2) | world-action model / robotics |
| 2026-07-06 | [Seeing Is No Longer Believing: Frontier Image Generation Models, Synthetic Visual Evidence, and Real-World Risk](https://arxiv.org/abs/2604.24197v2) | image generation / safety |
| 2026-07-06 | [MRMS: A Multi-Resolution Memory Substrate for Long-Lived AI Agents](https://arxiv.org/abs/2607.04617v1) | agent memory |
| 2026-07-05 | [ResearchStudio-Idea: An Evidence-Grounded Research-Ideation Skill Suite from ML Conference Outcomes](https://arxiv.org/abs/2607.04439v1) | research agent / ideation |
| 2026-07-05 | [Kwai Summary Attention Technical Report](https://arxiv.org/abs/2604.24432v2) | long-context attention / KV-cache compression |
| 2026-07-05 | [HNSW with Accuracy Guarantees Using Graph Spanners](https://arxiv.org/abs/2607.02338v2) | retrieval / vector search infrastructure |
| 2026-07-04 | [SkillFab: An Agent-Native Skill Production Platform](https://arxiv.org/abs/2607.03780v1) | agent skill platform |
| 2026-07-04 | [Folding, Reasoning, and Scaling with Open-source Drug Discovery Engine](https://arxiv.org/abs/2607.03787v1) | biomolecular foundation model / all-atom co-folding and drug discovery |
| 2026-07-04 | [GEPARD - Generative, Prosody-aware, Autoregressive text-to-speech model for Realtime Dialogue](https://arxiv.org/abs/2609.04222v1) | audio language model / streaming TTS pretraining, DPO distillation and vLLM serving |
| 2026-07-03 | [AGL-1: The Enterprise AI Governance Layer as a Control Plane for Trusted Enterprise Intelligence](https://arxiv.org/abs/2607.03516v1) | enterprise AI governance / agent systems |
| 2026-07-03 | [CAGE-1: Control, Assurance, and Governance Evaluation for Enterprise Agentic AI](https://arxiv.org/abs/2607.03510v1) | agent governance / evaluation |
| 2026-07-03 | [Kairos: A Regret-Aware Native World-Action Model Stack for Physical AI](https://arxiv.org/abs/2606.16533v3) | physical AI / world-action model |
| 2026-07-03 | [Learning on the Manifold: Unlocking Standard Diffusion Transformers with Representation Encoders](https://arxiv.org/abs/2602.10099v2) | diffusion transformer |
| 2026-07-03 | [VideoSearcher: Empowering Video Deep Research with Multi-Tool Agentic Reasoning via Reinforcement Learning](https://arxiv.org/abs/2607.02927v1) | multimodal agent / video deep research |
| 2026-07-03 | [GR2 Technical Report](https://arxiv.org/abs/2606.31984v3) | recommendation / LLM reranking |
| 2026-07-02 | [AdaCount: Training-Free Similarity-Guided Spatial and Feature Adaptation for Zero-Shot Object Counting](https://arxiv.org/abs/2607.02139v1) | vision foundation model / counting |
| 2026-07-02 | [Dive into Claude Code: The Design Space of Today's and Future AI Agent Systems](https://arxiv.org/abs/2604.14228v2) | AI agent systems / comparative architecture |
| 2026-07-01 | [Revisiting Chain-of-Thought Reasoning under Limited Supervision: Semi-supervised Chain-of-Thought Learning](https://arxiv.org/abs/2607.01511v1) | LLM reasoning / semi-supervised CoT |
| 2026-07-01 | [From Runtime Records to Legal Findings: An Evidentiary-Adequacy Criterion for Agentic AI Oversight](https://arxiv.org/abs/2607.00941v1) | agent oversight / audit logs |
| 2026-07-01 | [Revisiting Autoregressive Models for Generative Image Classification](https://arxiv.org/abs/2603.19122v2) | autoregressive image classification |
| 2026-07-01 | [Xiaomi-GUI-0 Technical Report](https://arxiv.org/abs/2606.31410v2) | GUI agent / computer use |
| 2026-06-30 | [SimpleSearch-VL: A Simple Recipe for Multimodal Agentic Deep Search](https://arxiv.org/abs/2606.31504v1) | multimodal agent / deep search |
| 2026-06-29 | [Qwen-RobotNav Technical Report: A Scalable Navigation Model Designed for an Agentic Navigation System](https://arxiv.org/abs/2606.18112v3) | robotics / VLA |
| 2026-06-29 | [Home3D 1.0: A High-Fidelity Image-to-3D Asset Generation System for Interior Design](https://arxiv.org/abs/2606.27923v2) | 3D generation |
| 2026-06-27 | [SpatiO: Adaptive Test-Time Orchestration of Vision-Language Agents for Spatial Reasoning](https://arxiv.org/abs/2604.21190v3) | VLM spatial reasoning / test-time orchestration |
| 2026-06-27 | [SamatNext v0.2-B: An Exploratory Study of RMS-Normalized Hybrid Decoders for Curriculum Retention in Small Code Models](https://arxiv.org/abs/2606.22248v2) | code model / architecture |
| 2026-06-26 | [From General-Purpose Audio Tagging to Spatially Grounded Sound Event Localization and Detection](https://arxiv.org/abs/2606.27751v1) | audio / sound event model |
| 2026-06-26 | [Class-frequency Guided Noise Schedule for Diffusion Models](https://arxiv.org/abs/2606.27696v1) | diffusion / generation |
| 2026-06-26 | [HunyuanImage 3.0 Technical Report](https://arxiv.org/abs/2509.23951v3) | image generation / multimodal foundation model |
| 2026-06-26 | [ELF: Embedded Language Flows](https://arxiv.org/abs/2605.10938v2) | continuous diffusion language model / progressive distillation |
| 2026-06-26 | [HyLaR: Hybrid Latent Reasoning with Decoupled Policy Optimization](https://arxiv.org/abs/2604.20328v2) | multimodal latent reasoning / SFT and RL |
| 2026-06-26 | [Agent-as-a-Router: Agentic Model Routing for Coding Tasks](https://arxiv.org/abs/2606.22902v3) | LLM routing / coding agent |
| 2026-06-25 | [Qwen-Image-2.0-RL Technical Report](https://arxiv.org/abs/2606.27608v1) | image generation / RLHF |
| 2026-06-25 | [TMP: Tree-structured Mixed-policy Pruning for Large-scale Image Generation and Editing](https://arxiv.org/abs/2606.27089v1) | image generation / pruning |
| 2026-06-25 | [SingGuard: A Policy-Adaptive Multimodal LLM Guardrail with Dynamic Reasoning](https://arxiv.org/abs/2606.22873v3) | multimodal safety LLM / SFT, RL and distillation |
| 2026-06-25 | [ZONOS2 Technical Report](https://arxiv.org/abs/2606.24320v2) | audio / speech model |
| 2026-06-24 | [KRVF: A Source-Aware Semantic Voxel World Representation for Edge Mobile Manipulation](https://arxiv.org/abs/2606.26321v1) | robotics / world model |
| 2026-06-24 | [Causal-rCM: A Unified Teacher-Forcing and Self-Forcing Open Recipe for Autoregressive Diffusion Distillation in Streaming Video Generation and Interactive World Models](https://arxiv.org/abs/2606.25473v1) | video generation / world model |
| 2026-06-24 | [Streaming-dLLM: Accelerating Diffusion LLMs via Suffix Pruning and Dynamic Decoding](https://arxiv.org/abs/2601.17917v3) | diffusion LLM decoding |
| 2026-06-24 | [iFLYTEK-Embodied-Omni Technical Report](https://arxiv.org/abs/2607.02542v1) | embodied foundation model / VLA |
| 2026-06-23 | [LemonHarness Technical Report](https://arxiv.org/abs/2606.24311v1) | agent runtime / benchmark harness |
| 2026-06-23 | [Qwen-AgentWorld: Language World Models for General Agents](https://arxiv.org/abs/2606.24597v1) | agent world model / CPT SFT and RL |
| 2026-06-23 | [Krea 2 Technical Report](https://www.krea.ai/blog/krea-2-technical-report) | image generation foundation model / pretraining and post-training |
| 2026-06-23 | [Cosmos 3: Omnimodal World Models for Physical AI](https://arxiv.org/abs/2606.02800v4) | embodied world model / VLA |
| 2026-06-23 | [Sakana Fugu Technical Report](https://arxiv.org/abs/2606.21228v2) | LLM orchestration / mixture-of-agents |
| 2026-06-22 | [Unlimited OCR Works](https://arxiv.org/abs/2606.23050v1) | OCR / document understanding |
| 2026-06-22 | [Dropstone 1.6: Technical Report](https://blankline.org/research/dropstone-1-6-technical-report) | agent runtime / model routing and serving |
| 2026-06-22 | [Teaching Diffusion to Speculate Left-to-Right](https://arxiv.org/abs/2606.11552v2) | diffusion language model / speculative decoding |
| 2026-06-18 | [Vesta: A Generalist Embodied Reasoning Model](https://arxiv.org/abs/2606.20905v1) | embodied reasoning / foundation model |
| 2026-06-18 | [World Engine: Towards the Era of Post-Training for Autonomous Driving](https://arxiv.org/abs/2606.19836v1) | autonomous driving / post-training |
| 2026-06-17 | [Qwen-RobotManip Technical Report: Alignment Unlocks Scale for Robotic Manipulation Foundation Models](https://arxiv.org/abs/2606.17846v2) | robotics / VLA |
| 2026-06-17 | [Qwen-RobotWorld Technical Report: Unifying Embodied World Modeling through Language-Conditioned Video Generation](https://arxiv.org/abs/2606.17030v3) | embodied world model / VLA |
| 2026-06-16 | [Looped World Models](https://arxiv.org/abs/2606.18208v1) | world model / generative model |
| 2026-06-16 | [Beyond the Sampled Token: Preserving Candidate Support in RLVR](https://arxiv.org/abs/2510.14807v3) | LLM reasoning / RLVR |
| 2026-06-16 | [SubQ-1.1-Small Technical Report](https://subq.ai/docs/subq-1-1-small-model-card.pdf) | long-context / sparse attention |
| 2026-06-16 | [MaineCoon: Pursuing A Real-Time Audio-Visual Social World Model](https://arxiv.org/abs/2606.17800v1) | audio-visual world model / streaming generation |
| 2026-06-16 | [NeuroClaw Technical Report](https://arxiv.org/abs/2604.24696v3) | agent / deep research |
| 2026-06-16 | [TeleStyle V2: Beyond Content-Preserving Style Transfer with Self-Distillation and Distribution-Matching-Distillation](https://arxiv.org/abs/2606.20709v1) | image foundation-model post-training / self-distillation and distribution-matching distillation |
| 2026-06-15 | [ProCUA-SFT Technical Report](https://arxiv.org/abs/2606.17321v1) | GUI agent / computer use |
| 2026-06-15 | [VibeThinker-3B: Exploring the Frontier of Verifiable Reasoning in Small Language Models](https://arxiv.org/abs/2606.16140v1) | small reasoning LM |
| 2026-06-15 | [Olmo Hybrid: From Theory to Practice and Back](https://arxiv.org/abs/2604.03444v4) | LLM pretraining architecture |
| 2026-06-15 | [A Pragmatic VLA Foundation Model](https://arxiv.org/abs/2601.18692v4) | robotics / VLA foundation model |
| 2026-06-15 | [From Detection to Recovery: Operational Analysis on LLM Pre-training with 504 GPUs](https://arxiv.org/abs/2605.09370v5) | LLM pretraining infrastructure |
| 2026-06-14 | [FireRed-Image-Edit-1.0 Technical Report](https://arxiv.org/abs/2602.13344v2) | image generation |
| 2026-06-13 | [Data-Centric Benchmarking of Exploit Generation in LLMs: Understanding the Impact of Fine-Tuning](https://arxiv.org/abs/2606.15123v1) | LLM security / fine-tuning |
| 2026-06-13 | [Ling and Ring 2.6 Technical Report: Efficient and Instant Agentic Intelligence at Trillion-Parameter Scale](https://arxiv.org/abs/2606.15079v1) | agentic LLM / foundation model |
| 2026-06-13 | [SCOPE: Cost-Efficient Model Selection for Compound AI Systems under Quality Constraints](https://arxiv.org/abs/2606.00774v2) | compound AI / model selection |
| 2026-06-12 | [Nemotron 3 Ultra: Open, Efficient Mixture-of-Experts Hybrid Mamba-Transformer Model for Agentic Reasoning](https://arxiv.org/abs/2606.15007v1) | agentic LLM / pretraining and post-training |
| 2026-06-12 | [MiniMax Sparse Attention](https://arxiv.org/abs/2606.13392v2) | long-context / sparse attention |
| 2026-06-11 | [World Tracing: Generative Pixel-Aligned Geometry Beyond the Visible](https://arxiv.org/abs/2606.13652v1) | 3D / world generation |
| 2026-06-11 | [Brick: Spatial Capability Routing for the Mixture-of-Models (MoM) Paradigm](https://arxiv.org/abs/2606.13241v1) | Mixture-of-Models routing |
| 2026-06-11 | [Scaling Inherently Interpretable Language Models](https://www.guidelabs.ai/papers/scaling-inherently-interpretable-language-models/) | interpretable LLM / concept-supervised pretraining |
| 2026-06-11 | [Compressing Image Style Training into a Single Model Forward](https://arxiv.org/abs/2606.13809v1) | image foundation-model adaptation / amortized image-to-LoRA weight prediction |
| 2026-06-10 | [Pythagoras-Prover: Advancing Efficient Formal Proving via Augmented Lean Formalisation](https://arxiv.org/abs/2606.12594v1) | formal proving / reasoning |
| 2026-06-10 | [InternVideo3: Agentify Foundation Models with Multimodal Contextual Reasoning](https://arxiv.org/abs/2606.12195v1) | video multimodal foundation model / long-context SFT and agentic post-training |
| 2026-06-09 | [ARM: An AutoRegressive Large Multimodal Model with Unified Discrete Representations](https://arxiv.org/abs/2606.11188v1) | multimodal / unified representation |
| 2026-06-09 | [ConvMemory v2: A Recall-Preserving Top-10 Evidence Reranker for Conversational Memory Retrieval](https://arxiv.org/abs/2606.10842v1) | memory / retrieval |
| 2026-06-09 | [Kwai Keye-VL-2.0 Technical Report](https://arxiv.org/abs/2606.10651v1) | agent / deep research |
| 2026-06-09 | [Stop Early, Spend Less: Hidden-State Probes as a Practical Recipe for Streaming Moderation of LLM Outputs](https://arxiv.org/abs/2606.10487v1) | LLM safety / streaming moderation |
| 2026-06-09 | [When Generic Prompt Improvements Hurt: Evaluation-Driven Iteration for LLM Applications](https://arxiv.org/abs/2601.22025v2) | LLM app evaluation |
| 2026-06-07 | [Aperon Technical Report: Hierarchical No-Pointer Tangent-Local Search for High-Dimensional Approximate Nearest Neighbors](https://arxiv.org/abs/2606.08813v1) | vector memory / retrieval infrastructure |
| 2026-06-05 | [How Much Dense Attention is Necessary? Oracle-Guided Sparse Prefill for Full/GQA Layers in Hybrid Long-Context Models](https://arxiv.org/abs/2606.07703v1) | long-context / sparse attention |
| 2026-06-05 | [DuMate-DeepResearch: An Auditable Multi-Agent System with Recursive Search and Rubric-Grounded Reasoning](https://arxiv.org/abs/2606.07299v1) | agent / deep research |
| 2026-06-05 | [VoxCPM2 Technical Report](https://arxiv.org/abs/2606.06928v1) | audio / speech model |
| 2026-06-05 | [MOSS-Audio Technical Report](https://arxiv.org/abs/2606.01802v3) | audio / speech model |
| 2026-06-04 | [Queen-Bee Agents: A BeeSpec-Centered Architecture for Governed Enterprise MCP Orchestration](https://arxiv.org/abs/2606.06545v1) | LLM agent orchestration |
| 2026-06-04 | [F3-Tokenizer: Taming Audio Autoencoder Latents for Understanding and Generation](https://arxiv.org/abs/2606.06357v1) | audio tokenizer |
| 2026-06-04 | [OneReason Technical Report](https://arxiv.org/abs/2606.06260v1) | recommendation / reasoning |
| 2026-06-03 | [vLLM Semantic Router: Signal Driven Decision Routing for Mixture-of-Modality Models](https://arxiv.org/abs/2603.04444v4) | LLM routing / inference |
| 2026-06-02 | [HRNN: A Hybrid Graph Index for Approximate Reverse k-Nearest Neighbor Search on High-Dimensional Vectors](https://arxiv.org/abs/2606.03225v1) | retrieval / vector search infrastructure |
| 2026-06-02 | [MAI-Thinking-1: Building a Hill-Climbing Machine](https://microsoft.ai/pdf/mai-thinking-1.pdf) | frontier reasoning LLM / scaling-ladder pretraining and RL post-training |
| 2026-06-02 | [SoulX-Transcriber: A Robust End-to-End Framework for Multi-Speaker Speech Transcription](https://arxiv.org/abs/2606.02400v2) | audio / speech model |
| 2026-06-01 | [Qwen-VLA: Unifying Vision-Language-Action Modeling across Tasks, Environments, and Robot Embodiments](https://arxiv.org/abs/2605.30280v2) | robotics / VLA |
| 2026-06-01 | [Galaxea G0.5 Technical Report](https://opengalaxea.github.io/G05/Galaxea_G0_5.pdf) | robotics VLA / cross-embodiment autoregressive pretraining |
| 2026-06-01 | [Wall-OSS-0.5 Technical Report](https://arxiv.org/abs/2605.30877v2) | robotics / VLA |
| 2026-05-31 | [Step-Audio-R1.5 Technical Report](https://arxiv.org/abs/2604.25719v2) | audio / speech model |
| 2026-05-30 | [Agent-R1: A Unified and Modular Framework for Agentic Reinforcement Learning](https://arxiv.org/abs/2511.14460v2) | agentic RL framework |
| 2026-05-30 | [OCC-RAG: Optimal Cognitive Core for Faithful Question Answering](https://arxiv.org/abs/2606.00683v1) | RAG language model / mid-training and reasoning distillation |
| 2026-05-29 | [Zamba2-VL Technical Report](https://arxiv.org/abs/2606.00390v1) | multimodal / VLM |
| 2026-05-29 | [CRMA: A Spectrally-Bounded Backbone for Modular Continual Fine-Tuning of LLMs](https://arxiv.org/abs/2606.00382v1) | LLM fine-tuning / continual learning |
| 2026-05-29 | [Mellum2 Technical Report](https://arxiv.org/abs/2605.31268v1) | code / software agent |
| 2026-05-29 | [SwanVoice: Expressive Long-Form Zero-Shot Speech Synthesis for Both Monologue and Dialogue](https://arxiv.org/abs/2605.30993v1) | audio / speech model |
| 2026-05-29 | [OrcaRouter: A Production-Oriented LLM Router with Hybrid Offline-Online Learning](https://arxiv.org/abs/2605.30736v1) | LLM routing |
| 2026-05-29 | [GEM-Bench: A Benchmark for Ad-Injected Response Generation within Generative Engine Marketing](https://arxiv.org/abs/2509.14221v3) | LLM agent runtime / retrieval-based advertisement injection and response refinement |
| 2026-05-29 | [COLLEAGUE.SKILL: Automated AI Skill Generation via Expert Knowledge Distillation](https://arxiv.org/abs/2605.31264v1) | LLM agent system / inspectable person-grounded skill generation and lifecycle |
| 2026-05-28 | [SegTune: Structured and Fine-Grained Control for Song Generation](https://arxiv.org/abs/2510.18416v2) | audio / song generation |
| 2026-05-28 | [TabPFN-3: Technical Report](https://arxiv.org/abs/2605.13986v2) | tabular / time-series foundation model |
| 2026-05-28 | [PrecisionCUA: Iterative Visual Refinement for Pixel-Precise Cursor Grounding in Code Editors](https://arxiv.org/abs/2604.13019v3) | GUI agent / computer use |
| 2026-05-28 | [AgentDoG 1.5: A Lightweight and Scalable Alignment Framework for AI Agent Safety and Security](https://arxiv.org/abs/2605.29801v1) | agent safety alignment / lightweight diagnostic guardrail training and runtime monitoring |
| 2026-05-27 | [PEFT-Arena: Understanding Parameter-Efficient Finetuning from a Stability-Plasticity Perspective](https://arxiv.org/abs/2605.28819v1) | PEFT / fine-tuning |
| 2026-05-27 | [Technical Report: Exploring the Emerging Threats of the Agent Skill Ecosystem](https://arxiv.org/abs/2605.28588v1) | agent security |
| 2026-05-27 | [ResearchLoop: An Evidence-Gated Control Plane for AI-Assisted Research](https://arxiv.org/abs/2605.28282v1) | AI-assisted research |
| 2026-05-27 | [ConvMemory: A Lightweight Learned Memory Reranker, a Negative Attribution Result, and a Research-Preview Conflict Editor](https://arxiv.org/abs/2605.28062v1) | memory / retrieval |
| 2026-05-27 | [ABot-OCR Technical Report](https://arxiv.org/abs/2605.27978v1) | OCR / document understanding |
| 2026-05-27 | [Xiaomi Auto World Model: A Joint World Model Integrating Reconstruction and Generation for Autonomous Driving](https://arxiv.org/abs/2605.18137v5) | autonomous driving / world model |
| 2026-05-27 | [Reflective Dialogue between Teacher and Solver Agents for Video Question Answering](https://arxiv.org/abs/2605.27885v1) | video QA / VLM adaptation |
| 2026-05-26 | [Darwin Mobile Agent: A Roadmap for Self-Evolution](https://arxiv.org/abs/2606.20622v1) | GUI agent / self-evolution |
| 2026-05-26 | [Laguna M.1/XS.2 Technical Report](https://arxiv.org/abs/2605.27605v1) | agent / deep research |
| 2026-05-26 | [LongCat-Video-Avatar 1.5 Technical Report](https://arxiv.org/abs/2605.26486v1) | audio-driven video generation |
| 2026-05-26 | [Generalized Range Filtering Approximate Nearest Neighbor Search: Containment and Overlap [Technical Report]](https://arxiv.org/abs/2605.26474v1) | retrieval / filtered ANN infrastructure |
| 2026-05-26 | [MinT: Managed Infrastructure for Training and Serving Millions of LLMs](https://arxiv.org/abs/2605.13779v2) | LLM training / serving infrastructure |
| 2026-05-26 | [RouteProfile: Graph-Based Profiling for Cold-Start LLM Routing](https://arxiv.org/abs/2605.00180v2) | LLM routing |
| 2026-05-25 | [Llamion Technical Report](https://arxiv.org/abs/2605.25676v1) | code / software agent |
| 2026-05-25 | [ERNIE-Image Technical Report](https://arxiv.org/abs/2605.25347v1) | image generation |
| 2026-05-25 | [PowLU: An Activation Function for Stable Pre-Training of LLMs](https://arxiv.org/abs/2605.25704v1) | LLM architecture / stable low-precision pretraining |
| 2026-05-25 | [Agentic Kernel Optimization: Generating State-of-the-Art GPU Kernels Without Hand-Written CUDA](https://arxiv.org/abs/2608.14560v1) | coding agents / autonomous GPU-kernel optimization |
| 2026-05-24 | [Evidence-Linked Radiology Reporting: A Human-Supervised Reference Architecture for Structured Imaging Intelligence](https://arxiv.org/abs/2605.25120v1) | medical AI / radiology reporting |
| 2026-05-24 | [BitCPM-CANN: Native 1.58-Bit Large Language Model Training on Ascend NPU](https://github.com/OpenBMB/MiniCPM/blob/be1efe05c67575628363d925f62c83e938c22274/docs/BitCPM_CANN.pdf) | ternary LLM / quantization-aware training infrastructure |
| 2026-05-23 | [ChronoVAE-HOPE: Beyond Attention -- A Next-Generation VAE Foundation Model for Specialized Time Series Classification](https://arxiv.org/abs/2605.22684v2) | tabular / time-series foundation model |
| 2026-05-23 | [KairosHope: A Next-Generation Time-Series Foundation Model for Specialized Classification via Dual-Memory Architecture](https://arxiv.org/abs/2605.18657v2) | tabular / time-series foundation model |
| 2026-05-22 | [StepAudio 2.5 Technical Report](https://arxiv.org/abs/2605.23463v1) | audio / speech model |
| 2026-05-21 | [Gated DeltaNet-2: Decoupling Erase and Write in Linear Attention](https://arxiv.org/abs/2605.22791v1) | linear attention / architecture |
| 2026-05-21 | [X-OmniClaw Technical Report: A Unified Mobile Agent for Multimodal Understanding and Interaction](https://arxiv.org/abs/2605.05765v2) | robotics / VLA |
| 2026-05-21 | [Joint Communication and Computation Scheduling for MEC-enabled AIGC Services: A Game-Theoretic Stochastic Learning Approach](https://arxiv.org/abs/2605.22277v1) | diffusion-model serving infrastructure / distributed edge offloading and inference-step scheduling |
| 2026-05-20 | [Spatial Gram Alignment for Ultra-High-Resolution Image Synthesis](https://arxiv.org/abs/2605.20808v1) | image synthesis |
| 2026-05-20 | [Lance: Unified Multimodal Modeling by Multi-Task Synergy](https://arxiv.org/abs/2605.18678v2) | unified multimodal model |
| 2026-05-20 | [JoyAI-Image: Awaking Spatial Intelligence in Unified Multimodal Understanding and Generation](https://arxiv.org/abs/2605.04128v2) | unified multimodal / image generation and editing |
| 2026-05-20 | [Sustained 70B-Class AWQ Inference on a Single NVIDIA L20: Throughput, Stability, Energy, and Quality Characterization](https://arxiv.org/abs/2609.05420v1) | LLM inference infrastructure / single-GPU AWQ serving and sustained-load characterization |
| 2026-05-19 | [Mega-ASR: Towards In-the-wild^2 Speech Recognition via Scaling up Real-world Acoustic Simulation](https://arxiv.org/abs/2605.19833v1) | audio / robust ASR post-training |
| 2026-05-19 | [DeepLens Diagnosis Agent: Agentic Workflow Design Lets a Small Reasoning Model Compete with Frontier LLMs](https://arxiv.org/abs/2607.22555v1) | medical LLM agent / RAG workflow |
| 2026-05-19 | [HoloMotion-1 Technical Report](https://arxiv.org/abs/2605.15336v2) | robotics / VLA |
| 2026-05-19 | [Motif-Video 2B: Technical Report](https://arxiv.org/abs/2604.16503v2) | video generation / understanding |
| 2026-05-19 | [TorchUMM: A Unified Multimodal Model Codebase for Evaluation, Analysis, and Post-training](https://arxiv.org/abs/2604.10784v2) | multimodal / post-training |
| 2026-05-18 | [Tongyi DeepResearch Technical Report](https://arxiv.org/abs/2510.24701v3) | agent / deep research |
| 2026-05-18 | [Stable Audio 3](https://arxiv.org/abs/2605.17991v1) | audio generation / latent-diffusion pretraining and adversarial post-training |
| 2026-05-18 | [Protein Autoregressive Modeling via Multiscale Structure Generation](https://arxiv.org/abs/2602.04883v2) | protein autoregressive model |
| 2026-05-17 | [Starchild-1: A real-time multimodal world model](https://starchild.odyssey.ml/starchild-1.pdf) | audio-video world model / causal post-training |
| 2026-05-16 | [EVA01: Unified Native 3D Understanding and Generation via Mixture-of-Transformers](https://arxiv.org/abs/2605.16745v1) | 3D understanding / generation |
| 2026-05-15 | [The Scaling Laws of Skills in LLM Agent Systems](https://arxiv.org/abs/2605.16508v1) | agent / scaling laws |
| 2026-05-15 | [Efficient Image Synthesis with Sphere Latent Encoder](https://arxiv.org/abs/2605.15592v1) | image generation / efficient synthesis |
| 2026-05-15 | [When Latent Geometry Is Not Enough: Draft-Conditioned Latent Refinement for Non-Autoregressive Text Generation](https://arxiv.org/abs/2605.15557v1) | diffusion language model |
| 2026-05-14 | [PhysBrain 1.0 Technical Report](https://arxiv.org/abs/2605.15298v1) | robotics / VLA |
| 2026-05-14 | [MediaClaw: Multimodal Intelligent-Agent Platform Technical Report](https://arxiv.org/abs/2605.14771v1) | agent / deep research |
| 2026-05-14 | [TOPOS: High-Fidelity and Efficient Industry-Grade 3D Head Generation](https://arxiv.org/abs/2605.14594v1) | 3D generation |
| 2026-05-14 | [Learning to Build the Environment: Self-Evolving Reasoning RL via Verifiable Environment Synthesis](https://arxiv.org/abs/2605.14392v1) | reasoning RL |
| 2026-05-14 | [TurboVGGT: Fast Visual Geometry Reconstruction with Adaptive Alternating Attention](https://arxiv.org/abs/2605.14315v1) | visual geometry |
| 2026-05-14 | [Granite Embedding Multilingual R2 Models](https://arxiv.org/abs/2605.13521v2) | multilingual embedding model |
| 2026-05-13 | [Qwen-Image-VAE-2.0 Technical Report](https://arxiv.org/abs/2605.13565v1) | image generation |
| 2026-05-13 | [Achieving Gold-Medal-Level Olympiad Reasoning via Simple and Unified Scaling](https://arxiv.org/abs/2605.13301v1) | reasoning LM |
| 2026-05-12 | [Pion: A Spectrum-Preserving Optimizer via Orthogonal Equivalence Transformation](https://arxiv.org/abs/2605.12492v1) | LLM optimizer |
| 2026-05-12 | [MindMirror: A Local-First Multimodal State-Aware Support System for Digital Workers](https://arxiv.org/abs/2605.11700v1) | local LLM / multimodal support system |
| 2026-05-12 | [DWDP: Distributed Weight Data Parallelism for High-Performance LLM Inference on NVL72](https://arxiv.org/abs/2604.01621v2) | LLM inference infrastructure |
| 2026-05-12 | [Qwen-Scope: Turning Sparse Features into Development Tools for Large Language Models](https://arxiv.org/abs/2605.11887v1) | LLM interpretability / SAE-assisted training and controllable inference |
| 2026-05-11 | [Qwen-Image-2.0 Technical Report](https://arxiv.org/abs/2605.10730v1) | image generation |
| 2026-05-11 | [Phoenix-VL 1.5 Medium Technical Report](https://arxiv.org/abs/2605.10391v1) | multimodal / VLM |
| 2026-05-11 | [Nemotron 3 Nano Omni: Efficient and Open Multimodal Intelligence](https://arxiv.org/abs/2604.24954v2) | multimodal LLM / omni-modal post-training |
| 2026-05-11 | [HiDream-O1-Image: A Natively Unified Image Generative Foundation Model with Pixel-level Unified Transformer](https://arxiv.org/abs/2605.11061v1) | image generation / unified foundation model |
| 2026-05-11 | [AniMatrix: An Anime Video Generation Model that Thinks in Art, Not Physics](https://arxiv.org/abs/2605.03652v3) | video generation |
| 2026-05-11 | [Can Graphs Help Vision SSMs See Better?](https://arxiv.org/abs/2605.11300v1) | visual backbone model family / graph-routed Mamba pretraining and dense-prediction adaptation |
| 2026-05-10 | [Statistical Scouting Finds Debate-Safe but Not Debate-Useful Cases: A Matched-Ceiling Study of Open-Weight LLM Reasoning Protocols](https://arxiv.org/abs/2605.09618v1) | LLM reasoning protocol |
| 2026-05-09 | [UserGPT Technical Report](https://arxiv.org/abs/2605.08766v1) | agent / deep research |
| 2026-05-09 | [Improved Mean Flows: On the Challenges of Fastforward Generative Models](https://arxiv.org/abs/2512.02012v2) | diffusion / generative model |
| 2026-05-09 | [One-step Latent-free Image Generation with Pixel Mean Flows](https://arxiv.org/abs/2601.22158v3) | image generation |
| 2026-05-08 | [ZAYA1-VL-8B Technical Report](https://arxiv.org/abs/2605.08560v1) | multimodal / VLM |
| 2026-05-08 | [Is the Future Compatible? Diagnosing Dynamic Consistency in World Action Models](https://arxiv.org/abs/2605.07514v1) | world action model |
| 2026-05-08 | [CSR: Infinite-Horizon Real-Time Policies with Massive Cached State Representations](https://arxiv.org/abs/2605.07325v1) | robotics / long-context LLM runtime |
| 2026-05-08 | [Xiaomi OneVL: One-Step Latent Reasoning and Planning with Vision-Language Explanation](https://arxiv.org/abs/2604.18486v3) | robotics / VLA |
| 2026-05-07 | [Sparkle: Realizing Lively Instruction-Guided Video Background Replacement via Decoupled Guidance](https://arxiv.org/abs/2605.06535v1) | video background replacement |
| 2026-05-07 | [A Case-Driven Multi-Agent Framework for E-Commerce Search Relevance](https://arxiv.org/abs/2605.05991v1) | e-commerce search agent |
| 2026-05-07 | [Low-Latency Out-of-Core ANN Search in High-Dimensional Space](https://arxiv.org/abs/2605.05787v1) | retrieval / vector search infrastructure |
| 2026-05-06 | [ZAYA1-8B Technical Report](https://arxiv.org/abs/2605.05365v1) | code / software agent |
| 2026-05-06 | [Storage Is Not Memory: A Retrieval-Centered Architecture for Agent Recall](https://arxiv.org/abs/2605.04897v1) | agent memory |
| 2026-05-06 | [InSpatio-WorldFM: An Open-Source Real-Time Generative Frame Model](https://arxiv.org/abs/2603.11911v3) | world model / generative frame model |
| 2026-05-06 | [RLDX-1 Technical Report](https://arxiv.org/abs/2605.03269v2) | robotics / VLA |
| 2026-05-06 | [R3-VAE: Reference Vector-Guided Rating Residual Quantization VAE for Generative Recommendation](https://arxiv.org/abs/2604.11440v3) | recommendation / generative model |
| 2026-05-06 | [Code Broker: A Multi-Agent System for Automated Code Quality Assessment](https://arxiv.org/abs/2604.23088v2) | code / software agent |
| 2026-05-05 | [MiniMind-O Technical Report: An Open Small-Scale Speech-Native Omni Model](https://arxiv.org/abs/2605.03937v1) | audio / speech model |
| 2026-05-05 | [X-Cache: Cross-Chunk Block Caching for Few-Step Autoregressive World Models Inference](https://arxiv.org/abs/2604.20289v2) | world model inference |
| 2026-05-04 | [HY-Himmel Technical Report: Hierarchical Interleaved Multi-stream Motion Encoding for Long Video Understanding](https://arxiv.org/abs/2605.08158v1) | video generation / understanding |
| 2026-05-04 | [ARIS: Autonomous Research via Adversarial Multi-Agent Collaboration](https://arxiv.org/abs/2605.03042v1) | autonomous research agent |
| 2026-05-04 | [Mamoda2.5: Enhancing Unified Multimodal Model with DiT-MoE](https://arxiv.org/abs/2605.02641v1) | unified multimodal / video generation |
| 2026-05-01 | [Agent Brain: A Biologically Inspired Memory System for Autonomous AI Agents in Property Management](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6575360) | agent memory / retrieval and consolidation |
| 2026-05-01 | [MedGemma 1.5 Technical Report](https://arxiv.org/abs/2604.05081v2) | multimodal / VLM |
| 2026-04-30 | [Technical Report: Activation Residual Hessian Quantization (ARHQ) for Low-Bit LLM Quantization](https://arxiv.org/abs/2605.00140v1) | code / software agent |
| 2026-04-30 | [XekRung Technical Report](https://arxiv.org/abs/2605.00072v1) | domain / security / legal LLM |
| 2026-04-30 | [Echo-α: Large Agentic Multimodal Reasoning Model for Ultrasound Interpretation](https://arxiv.org/abs/2604.28011v1) | medical multimodal reasoning |
| 2026-04-30 | [MiniCPM-o 4.5: Towards Real-Time Full-Duplex Omni-Modal Interaction](https://arxiv.org/abs/2604.27393v1) | omnimodal LLM / joint pretraining and full-duplex post-training |
| 2026-04-28 | [A Systematic Post-Train Framework for Video Generation](https://arxiv.org/abs/2604.25427v1) | video generation post-training |
| 2026-04-28 | [MiMo-Embodied: X-Embodied Foundation Model Technical Report](https://arxiv.org/abs/2511.16518v2) | embodied foundation model / VLA |
| 2026-04-28 | [Suiren-1.0 Technical Report: A Family of Molecular Foundation Models](https://arxiv.org/abs/2603.21942v4) | molecular foundation model |
| 2026-04-27 | [GLM-5 Serving Parameter Tuning for OpenClaw: Single-Deployment MaaS Inference Optimization for Long-Context Agent Workloads](https://arxiv.org/abs/2607.02518v1) | LLM serving / long-context agents |
| 2026-04-27 | [X2SAM: Any Segmentation in Images and Videos](https://arxiv.org/abs/2605.00891v1) | segmentation MLLM |
| 2026-04-27 | [GoClick: Lightweight Element Grounding Model for Autonomous GUI Interaction](https://arxiv.org/abs/2604.23941v1) | GUI grounding |
| 2026-04-27 | [GA2-CLIP: Generic Attribute Anchor for Efficient Prompt Tuningin Video-Language Models](https://arxiv.org/abs/2511.22125v2) | video-language model / prompt tuning |
| 2026-04-27 | [VAM: A Multimodal Dynamical Foundation Model for Characterizing Human Aging Dynamics and Enabling Virtual Aging Perturbation](https://doi.org/10.21203/rs.3.rs-9402213/v1) | biomedical foundation model / multimodal pretraining and fine-tuning |
| 2026-04-27 | [Diffusion Templates: A Unified Plugin Framework for Controllable Diffusion](https://arxiv.org/abs/2604.24351v1) | diffusion model systems / composable KV-cache and LoRA control plugins |
| 2026-04-26 | [DeepSeek-V4: Towards Highly Efficient Million-Token Context Intelligence](https://arxiv.org/abs/2606.19348v1) | LLM pretraining / post-training and long context |
| 2026-04-26 | [RefTon: Reference person shot assist virtual Try-on](https://arxiv.org/abs/2511.00956v6) | virtual try-on / diffusion model |
| 2026-04-25 | [A satellite foundation model for improved wealth monitoring](https://arxiv.org/abs/2604.23166v1) | domain foundation model |
| 2026-04-23 | [Flipping Against All Odds: Reducing LLM Coin Flip Bias via Verbalized Rejection Sampling](https://arxiv.org/abs/2506.09998v2) | LLM sampling / calibration |
| 2026-04-23 | [Decoupled DiLoCo for Resilient Distributed Pre-training](https://arxiv.org/abs/2604.21428v1) | distributed LLM pretraining infrastructure |
| 2026-04-23 | [AgentDoG: A Diagnostic Guardrail Framework for AI Agent Safety and Security](https://arxiv.org/abs/2601.18491v2) | agent safety / trajectory-level diagnostic guardrail training and attribution |
| 2026-04-22 | [Seed3D 2.0: Advancing High-Fidelity Simulation-Ready 3D Content Generation](https://arxiv.org/abs/2605.13862v1) | 3D generation |
| 2026-04-22 | [LLaDA2.0-Uni: Unifying Multimodal Understanding and Generation with Diffusion Large Language Model](https://arxiv.org/abs/2604.20796v1) | multimodal diffusion LM |
| 2026-04-21 | [DR-Venus: Towards Frontier Edge-Scale Deep Research Agents with Only 10K Open Data](https://arxiv.org/abs/2604.19859v1) | agent / deep research |
| 2026-04-21 | [VLA Foundry: A Unified Framework for Training Vision-Language-Action Models](https://arxiv.org/abs/2604.19728v1) | robotics / VLA |
| 2026-04-21 | [SmartPhotoCrafter: Unified Reasoning, Generation and Optimization for Automatic Photographic Image Editing](https://arxiv.org/abs/2604.19587v1) | image editing agent |
| 2026-04-21 | [PLaMo 2.1-VL Technical Report](https://arxiv.org/abs/2604.19324v1) | multimodal / VLM |
| 2026-04-21 | [Auditing LLMs for Algorithmic Fairness in Casenote-Augmented Tabular Prediction](https://arxiv.org/abs/2604.19204v1) | LLM evaluation / fairness |
| 2026-04-21 | [MiroThinker: Pushing the Performance Boundaries of Open-Source Research Agents via Model, Context, and Interactive Scaling](https://arxiv.org/abs/2511.11793v3) | agent / deep research |
| 2026-04-21 | [DuQuant++: Fine-grained Rotation Enhances Microscaling FP4 Quantization](https://arxiv.org/abs/2604.17789v2) | LLM quantization |
| 2026-04-21 | [False Security Confidence in Benign LLM Code Generation](https://arxiv.org/abs/2604.17014v2) | agent / deep research |
| 2026-04-21 | [Qwen3.5-Omni Technical Report](https://arxiv.org/abs/2604.15804v2) | multimodal / VLM |
| 2026-04-20 | [Balanced Co-Clustering of Users and Items for Embedding Table Compression in Recommender Systems](https://arxiv.org/abs/2604.18351v1) | recommendation / embedding compression |
| 2026-04-20 | [Train Separately, Merge Together: Modular Post-Training with Mixture-of-Experts](https://arxiv.org/abs/2604.18473v1) | modular post-training / MoE |
| 2026-04-20 | [Training LLM Agents for Spontaneous, Reward-Free Self-Evolution via World Knowledge Exploration](https://arxiv.org/abs/2604.18131v1) | LLM agents / SFT and reinforcement fine-tuning |
| 2026-04-19 | [PoliLegalLM: A Technical Report on a Large Language Model for Political and Legal Affairs](https://arxiv.org/abs/2604.17543v1) | domain / security / legal LLM |
| 2026-04-19 | [Jupiter-N Technical Report](https://arxiv.org/abs/2604.17429v1) | agent / deep research |
| 2026-04-19 | [Knows: Agent-Native Structured Research Representations](https://arxiv.org/abs/2604.17309v1) | AI-assisted research / agent format |
| 2026-04-18 | [GenericAgent: A Token-Efficient Self-Evolving LLM Agent via Contextual Information Density Maximization (V1.0)](https://arxiv.org/abs/2604.17091v1) | agent runtime / memory and self-evolution |
| 2026-04-17 | [DINOv3 Beats Specialized Detectors: A Simple Foundation Model Baseline for Image Forensics](https://arxiv.org/abs/2604.16083v1) | visual foundation model / forensics |
| 2026-04-17 | [Mind DeepResearch Technical Report](https://arxiv.org/abs/2604.14518v2) | agent / deep research |
| 2026-04-16 | [Serving Chain-structured Jobs with Large Memory Footprints with Application to Large Foundation Model Serving](https://arxiv.org/abs/2604.14993v1) | foundation model serving |
| 2026-04-16 | [AIPC: Agent-Based Automation for AI Model Deployment with Qualcomm AI Runtime](https://arxiv.org/abs/2604.14661v1) | agent / deep research |
| 2026-04-16 | [One RL to See Them All: Visual Triple Unified Reinforcement Learning](https://arxiv.org/abs/2505.18129v3) | multimodal RL / VLM post-training |
| 2026-04-16 | [Art3D: Training-Free 3D Generation from Flat-Colored Illustration](https://arxiv.org/abs/2504.10466v2) | 3D generation |
| 2026-04-16 | [XRZero-G0: Pushing the Frontier of Dexterous Robotic Manipulation with Interfaces, Quality and Ratios](https://arxiv.org/abs/2604.13001v2) | dexterous manipulation |
| 2026-04-16 | [cuRoboV2: Dynamics-Aware Motion Generation with Depth-Fused Distance Fields for High-DoF Robots](https://arxiv.org/abs/2603.05493v2) | robotics / motion generation |
| 2026-04-15 | [HY-World 2.0: A Multi-Modal World Model for Reconstructing, Generating, and Simulating 3D Worlds](https://arxiv.org/abs/2604.14268v1) | 3D / world generation |
| 2026-04-15 | [AgentOpt v0.1 Technical Report: Client-Side Optimization for LLM-Based Agent](https://arxiv.org/abs/2604.06296v2) | GUI agent / computer use |
| 2026-04-14 | [FreqFormer: Hierarchical Frequency-Domain Attention with Adaptive Spectral Routing for Long-Sequence Video Diffusion Transformers](https://arxiv.org/abs/2604.22808v1) | video diffusion transformer |
| 2026-04-14 | [Nemotron 3 Super: Open, Efficient Mixture-of-Experts Hybrid Mamba-Transformer Model for Agentic Reasoning](https://arxiv.org/abs/2604.12374v1) | agentic LLM / pretraining and post-training |
| 2026-04-14 | [ABot-M0: VLA Foundation Model for Robotic Manipulation with Action Manifold Learning](https://arxiv.org/abs/2602.11236v2) | robotics / VLA foundation model |
| 2026-04-13 | [SHARE: Social-Humanities AI for Research and Education](https://arxiv.org/abs/2604.11152v1) | domain / social-science LLM |
| 2026-04-13 | [DeepFleet: Multi-Agent Foundation Models for Mobile Robots](https://arxiv.org/abs/2508.08574v3) | robotics / multi-agent foundation model |
| 2026-04-13 | [INSPATIO-WORLD: A Real-Time 4D World Simulator via Spatiotemporal Autoregressive Modeling](https://arxiv.org/abs/2604.07209v2) | interactive world model / video generation |
| 2026-04-13 | [Audio Flamingo Next: Next-Generation Open Audio-Language Models for Speech, Sound, and Music](https://arxiv.org/abs/2604.10905v1) | audio-language model / curriculum pre-, mid- and post-training |
| 2026-04-10 | [WisdomInterrogatory (LuWen): An Open-Source Legal Large Language Model Technical Report](https://arxiv.org/abs/2604.06737v2) | domain / security / legal LLM |
| 2026-04-09 | [EXAONE 4.5 Technical Report](https://arxiv.org/abs/2604.08644v1) | multimodal / VLM |
| 2026-04-09 | [Externalization in LLM Agents: A Unified Review of Memory, Skills, Protocols and Harness Engineering](https://arxiv.org/abs/2604.08224v1) | LLM agent memory / skills |
| 2026-04-09 | [PASK: Toward Intent-Aware Proactive Agents with Long-Term Memory](https://arxiv.org/abs/2604.08000v1) | proactive agents / memory |
| 2026-04-09 | [Timer-S1: A Billion-Scale Time Series Foundation Model with Serial Scaling](https://arxiv.org/abs/2603.04791v3) | time-series foundation model / reasoning |
| 2026-04-09 | [MinerU2.5-Pro: Pushing the Limits of Data-Centric Document Parsing at Scale](https://arxiv.org/abs/2604.04771v2) | document parsing / OCR |
| 2026-04-08 | [Raon-Speech Technical Report](https://arxiv.org/abs/2605.23912v1) | audio / speech model |
| 2026-04-08 | [HY-Embodied-0.5: Embodied Foundation Models for Real-World Agents](https://arxiv.org/abs/2604.07430v1) | embodied foundation model / post-training |
| 2026-04-08 | [Logics-Parsing-Omni Technical Report](https://arxiv.org/abs/2603.09677v3) | OCR / document understanding |
| 2026-04-06 | [StarVLA: A Lego-like Codebase for Vision-Language-Action Model Developing](https://arxiv.org/abs/2604.05014v1) | robotics / VLA |
| 2026-04-06 | [Springdrift: An Auditable Persistent Runtime for LLM Agents with Case-Based Memory, Normative Safety, and Ambient Self-Perception](https://arxiv.org/abs/2604.04660v1) | LLM agent runtime |
| 2026-04-06 | [MedGemma Technical Report](https://arxiv.org/abs/2507.05201v4) | medical multimodal foundation model |
| 2026-04-06 | [Voxtral Realtime](https://arxiv.org/abs/2602.11298v3) | audio / streaming ASR |
| 2026-04-06 | [Embodied-R1: Reinforced Embodied Reasoning for General Robotic Manipulation](https://arxiv.org/abs/2508.13998v2) | embodied foundation model / VLA |
| 2026-04-03 | [JointFM-0.1: A Foundation Model for Multi-Target Joint Distributional Prediction](https://arxiv.org/abs/2603.20266v2) | domain foundation model |
| 2026-04-03 | [Vibe Coding XR: Accelerating AI + XR Prototyping with XR Blocks and Gemini](https://arxiv.org/abs/2603.24591v2) | LLM code-generation system / semantic XR runtime and simulator-to-device prototyping |
| 2026-04-02 | [T5Gemma-TTS Technical Report](https://arxiv.org/abs/2604.01760v1) | audio / speech model |
| 2026-04-02 | [Intern-S1-Pro: Scientific Multimodal Foundation Model at Trillion Scale](https://arxiv.org/abs/2603.25040v2) | scientific multimodal foundation model / RL |
| 2026-04-02 | [Exploring Effective Strategies for Building a User-Configured GPT for Coding Classroom Dialogues](https://arxiv.org/abs/2506.07194v2) | LLM application system / modular GPT classroom-dialogue coding configuration |
| 2026-04-01 | [APEX: Adaptive Precision for Expert Models -- A Novel Layer-Wise Gradient Quantization Method for Mixture-of-Experts Language Models](https://github.com/localai-org/apex-quant/blob/main/paper/APEX_Technical_Report.md) | LLM inference / MoE quantization |
| 2026-03-31 | [X-World: Controllable Ego-Centric Multi-Camera World Models for Scalable End-to-End Driving](https://arxiv.org/abs/2603.19979v2) | driving world model |
| 2026-03-30 | [Synergy: A Next-Generation General-Purpose Agent for Open Agentic Web](https://arxiv.org/abs/2603.28428v1) | general-purpose web agent |
| 2026-03-30 | [MOSS-VoiceGenerator: Create Realistic Voices with Natural Language Descriptions](https://arxiv.org/abs/2603.28086v1) | audio / controllable voice generation |
| 2026-03-30 | [Marco DeepResearch: Unlocking Efficient Deep Research Agents via Verification-Centric Design](https://arxiv.org/abs/2603.28376v1) | deep-research agent / verification-driven post-training |
| 2026-03-30 | [Towards Privacy-Preserving LLM Inference via Covariant Obfuscation (Technical Report)](https://arxiv.org/abs/2603.01499v2) | LLM inference / compression |
| 2026-03-29 | [KAT-Coder-V2 Technical Report](https://arxiv.org/abs/2603.27703v1) | code / software agent |
| 2026-03-29 | [LongCat-Next: Lexicalizing Modalities as Discrete Tokens](https://arxiv.org/abs/2603.27538v1) | multimodal tokenization |
| 2026-03-28 | [Falcon Perception](https://arxiv.org/abs/2603.27365v1) | multimodal perception / detection segmentation and OCR |
| 2026-03-27 | [AMALIA Technical Report: A Fully Open Source Large Language Model for European Portuguese](https://arxiv.org/abs/2603.26511v1) | LLM training / alignment |
| 2026-03-26 | [Composer 2 Technical Report](https://arxiv.org/abs/2603.24477v2) | agent / deep research |
| 2026-03-26 | [StreamingClaw Technical Report](https://arxiv.org/abs/2603.22120v2) | robotics / VLA |
| 2026-03-26 | [SportSkills: Physical Skill Learning from Sports Instructional Videos](https://arxiv.org/abs/2603.25163v1) | visual foundation-model adaptation / sports skill representation learning |
| 2026-03-25 | [Xiaomi-Robotics-0: An Open-Sourced Vision-Language-Action Model with Real-Time Execution](https://arxiv.org/abs/2602.12684v2) | robotics / VLA |
| 2026-03-23 | [Early Discoveries of Algorithmist I: Promise of Provable Algorithm Synthesis at Scale](https://arxiv.org/abs/2603.22363v1) | research agent / algorithm synthesis |
| 2026-03-23 | [AngelSlim: A more accessible, comprehensive, and efficient toolkit for large model compression](https://arxiv.org/abs/2602.21233v3) | audio / speech model |
| 2026-03-22 | [Nemotron-Cascade 2: Post-Training LLMs with Cascade RL and Multi-Domain On-Policy Distillation](https://arxiv.org/abs/2603.19220v2) | agentic LLM / post-training |
| 2026-03-22 | [Causal World Modeling for Robot Control](https://arxiv.org/abs/2601.21998v2) | video-action world model / robot control |
| 2026-03-20 | [Leum-VL Technical Report](https://arxiv.org/abs/2603.20354v1) | multimodal / VLM |
| 2026-03-20 | [BEAVER: A Training-Free Hierarchical Prompt Compression Method via Structure-Aware Page Selection](https://arxiv.org/abs/2603.19635v1) | prompt compression |
| 2026-03-20 | [MOSS-TTSD: Text to Spoken Dialogue Generation](https://arxiv.org/abs/2603.19739v1) | audio / long-form spoken dialogue generation |
| 2026-03-20 | [DLLM Agent: See Farther, Run Faster](https://arxiv.org/abs/2602.07451v3) | diffusion LLM agent / agent-oriented fine-tuning |
| 2026-03-20 | [MOSS-TTS Technical Report](https://arxiv.org/abs/2603.18090v2) | audio / speech model |
| 2026-03-20 | [The Art of Efficient Reasoning: Data, Reward, and Optimization](https://arxiv.org/abs/2602.20945v3) | efficient reasoning |
| 2026-03-19 | [BubbleRAG: Evidence-Driven Retrieval-Augmented Generation for Black-Box Knowledge Graphs](https://arxiv.org/abs/2603.20309v1) | RAG |
| 2026-03-19 | [ClawTrap: A MITM-Based Red-Teaming Framework for Real-World OpenClaw Security Evaluation](https://arxiv.org/abs/2603.18762v1) | agent security / red-teaming |
| 2026-03-19 | [Memento-Skills: Let Agents Design Agents](https://arxiv.org/abs/2603.18743v1) | agent / skill design |
| 2026-03-19 | [Responsible AI Technical Report](https://arxiv.org/abs/2509.20057v4) | AI safety / guardrails |
| 2026-03-19 | [Mobile-VideoGPT: Fast and Accurate Model for Mobile Video Understanding](https://arxiv.org/abs/2503.21782v2) | video understanding / efficient VLM |
| 2026-03-18 | [Memory Bear AI Memory Science Engine for Multimodal Affective Intelligence: A Technical Report](https://arxiv.org/abs/2603.22306v1) | audio / speech model |
| 2026-03-18 | [EDM-ARS: A Domain-Specific Multi-Agent System for Automated Educational Data Mining Research](https://arxiv.org/abs/2603.18273v1) | agent / deep research |
| 2026-03-18 | [CytoSyn: a Foundation Diffusion Model for Histopathology -- Tech Report](https://arxiv.org/abs/2603.18089v1) | histopathology diffusion foundation model |
| 2026-03-18 | [CRE-T1 Preview Technical Report: Beyond Contrastive Learning for Reasoning-Intensive Retrieval](https://arxiv.org/abs/2603.17387v1) | LLM inference / compression |
| 2026-03-18 | [Ruyi2.5 Technical Report](https://arxiv.org/abs/2603.17311v1) | multimodal / VLM |
| 2026-03-17 | [IQuest-Coder-V1 Technical Report](https://arxiv.org/abs/2603.16733v1) | code / software agent |
| 2026-03-16 | [Attention Residuals](https://arxiv.org/abs/2603.15031v1) | attention architecture |
| 2026-03-16 | [Chart-R1: Chain-of-Thought Supervision and Reinforcement for Advanced Chart Reasoner](https://arxiv.org/abs/2507.15509v3) | chart reasoning / VLM |
| 2026-03-16 | [GLM-OCR Technical Report](https://arxiv.org/abs/2603.10910v2) | OCR / document understanding |
| 2026-03-16 | [Covo-Audio Technical Report](https://arxiv.org/abs/2602.09823v2) | audio / speech model |
| 2026-03-16 | [SoulX-Singer: Towards High-Quality Zero-Shot Singing Voice Synthesis](https://arxiv.org/abs/2602.07803v2) | singing voice synthesis |
| 2026-03-14 | [Colon-X: Advancing Intelligent Colonoscopy toward Clinical Reasoning](https://arxiv.org/abs/2512.03667v2) | medical multimodal reasoning |
| 2026-03-14 | [Penguin-VL: Exploring the Efficiency Limits of VLM with LLM-based Vision Encoders](https://arxiv.org/abs/2603.06569v2) | multimodal / VLM |
| 2026-03-14 | [VIBEVOICE-ASR Technical Report](https://arxiv.org/abs/2601.18184v2) | audio / speech model |
| 2026-03-13 | [Uni-Parser Technical Report](https://arxiv.org/abs/2512.15098v4) | OCR / document understanding |
| 2026-03-13 | [Omni-Video: Democratizing Unified Video Understanding and Generation](https://arxiv.org/abs/2507.06119v4) | video generation / unified multimodal model |
| 2026-03-13 | [Omni-Video 2: Scaling MLLM-Conditioned Diffusion for Unified Video Generation and Editing](https://arxiv.org/abs/2602.08820v2) | video generation / editing |
| 2026-03-12 | [OmniStream: Mastering Perception, Reconstruction and Action in Continuous Streams](https://arxiv.org/abs/2603.12265v1) | continuous-stream multimodal model |
| 2026-03-12 | [Tiny Aya: Bridging Scale and Multilingual Depth](https://arxiv.org/abs/2603.11510v1) | multilingual LLM / from-scratch pretraining and regional post-training |
| 2026-03-11 | [FireRedASR2S: A State-of-the-Art Industrial-Grade All-in-One Automatic Speech Recognition System](https://arxiv.org/abs/2603.10420v1) | audio / speech model |
| 2026-03-11 | [Fish Audio S2 Technical Report](https://arxiv.org/abs/2603.08823v2) | audio / speech model |
| 2026-03-10 | [Sabiá-4 Technical Report](https://arxiv.org/abs/2603.10213v1) | Portuguese/legal LLM / continued pretraining and alignment |
| 2026-03-10 | [InternVL-U: Democratizing Unified Multimodal Models for Understanding, Reasoning, Generation and Editing](https://arxiv.org/abs/2603.09877v1) | multimodal / VLM |
| 2026-03-10 | [Covenant-72B: Pre-Training a 72B LLM with Trustless Peers Over-the-Internet](https://arxiv.org/abs/2603.08163v2) | LLM pretraining / decentralized training infrastructure |
| 2026-03-10 | [AlphaApollo: A System for Deep Agentic Reasoning](https://arxiv.org/abs/2510.06261v2) | agentic reasoning system |
| 2026-03-10 | [Scalable Training of Mixture-of-Experts Models with Megatron Core](https://arxiv.org/abs/2603.07685v2) | MoE training infrastructure |
| 2026-03-09 | [IronEngine: Towards General AI Assistant](https://arxiv.org/abs/2603.08425v1) | AI assistant / agent |
| 2026-03-09 | [From Reactive to Map-Based AI: Tuned Local LLMs for Semantic Zone Inference in Object-Goal Navigation](https://arxiv.org/abs/2603.08086v1) | object-goal navigation / LLM |
| 2026-03-09 | [Decomposition-Driven Multi-Table Retrieval and Reasoning for Numerical Question Answering](https://arxiv.org/abs/2603.07950v1) | LLM inference system / multi-table retrieval and programmatic reasoning |
| 2026-03-08 | [VIVECaption: A Split Approach to Caption Quality Improvement](https://arxiv.org/abs/2603.07401v1) | image/video generation data |
| 2026-03-05 | [A Simple Baseline for Unifying Understanding, Generation, and Editing via Vanilla Next-token Prediction](https://arxiv.org/abs/2603.04980v1) | unified multimodal generation |
| 2026-03-05 | [Privacy-Aware Camera 2.0 Technical Report](https://arxiv.org/abs/2603.04775v1) | visual foundation-model system / privacy-preserving edge-cloud perception and reconstruction |
| 2026-03-04 | [Phi-4-reasoning-vision-15B Technical Report](https://arxiv.org/abs/2603.03975v1) | multimodal / VLM |
| 2026-03-04 | [Helios: Real Real-Time Long Video Generation Model](https://arxiv.org/abs/2603.04379v1) | video generation / autoregressive diffusion |
| 2026-03-04 | [Yuan3.0 Ultra: A Trillion-Parameter Enterprise-Oriented MoE LLM](https://github.com/Yuan-lab-LLM/Yuan3.0-Ultra/blob/main/Docs/Yuan3.0_Ultra%20Paper.pdf) | trillion-parameter MoE LLM / pretraining pruning and fast-thinking RL |
| 2026-03-04 | [BOTANIC-0: a series of foundation models for plant genomic data](https://www.biorxiv.org/content/10.64898/2026.02.23.706817v2) | genomic foundation-model pretraining / masked-language training and parameter-efficient adaptation |
| 2026-03-03 | [Kling-MotionControl Technical Report](https://arxiv.org/abs/2603.03160v1) | video generation / understanding |
| 2026-03-03 | [AgentAssay: Token-Efficient Regression Testing for Non-Deterministic AI Agent Workflows](https://arxiv.org/abs/2603.02601v1) | agent testing / evaluation |
| 2026-03-03 | [xLLM Technical Report](https://arxiv.org/abs/2510.14686v2) | LLM inference framework |
| 2026-03-03 | [Quantization-Aware Distillation for NVFP4 Inference Accuracy Recovery](https://arxiv.org/abs/2601.20088v3) | multimodal / VLM |
| 2026-03-02 | [FireRed-OCR Technical Report](https://arxiv.org/abs/2603.01840v1) | OCR / document understanding |
| 2026-03-02 | [TransactionGPT](https://arxiv.org/abs/2511.08939v2) | tabular / transaction foundation model |
| 2026-03-01 | [MM-DeepResearch: A Simple and Effective Multimodal Agentic Search Baseline](https://arxiv.org/abs/2603.01050v1) | multimodal deep research |
| 2026-02-28 | [Qwen3-Coder-Next Technical Report](https://arxiv.org/abs/2603.00729v1) | code / software agent |
| 2026-02-28 | [MiniCPM-SALA: Hybridizing Sparse and Linear Attention for Efficient Long-Context Modeling](https://arxiv.org/abs/2602.11761v2) | long-context / linear attention |
| 2026-02-27 | [Architecture-Aware LLM Inference Optimization on AMD Instinct GPUs: A Comprehensive Benchmark and Deployment Study](https://arxiv.org/abs/2603.10031v1) | LLM inference optimization |
| 2026-02-26 | [Distributed LLM Pretraining During Renewable Curtailment Windows: A Feasibility Study](https://arxiv.org/abs/2602.22760v1) | LLM training / alignment |
| 2026-02-26 | [Ruyi2 Technical Report](https://arxiv.org/abs/2602.22543v1) | multimodal / VLM |
| 2026-02-24 | [AnimeAgent: Is the Multi-Agent via Image-to-Video models a Good Disney Storytelling Artist?](https://arxiv.org/abs/2602.20664v1) | multi-agent video storytelling |
| 2026-02-24 | [AWCP: A Workspace Delegation Protocol for Deep-Engagement Collaboration across Remote Agents](https://arxiv.org/abs/2602.20493v1) | remote agent collaboration protocol |
| 2026-02-24 | [GLM-5: from Vibe Coding to Agentic Engineering](https://arxiv.org/abs/2602.15763v2) | agentic LLM / pretraining and post-training |
| 2026-02-24 | [UI-Venus-1.5 Technical Report](https://arxiv.org/abs/2602.09082v2) | robotics / VLA |
| 2026-02-24 | [SWE-Master: Unleashing the Potential of Software Engineering Agents via Post-Training](https://arxiv.org/abs/2602.03411v2) | agent / deep research |
| 2026-02-23 | [LocateAnything3D: Vision-Language 3D Detection with Chain-of-Sight](https://arxiv.org/abs/2511.20648v2) | 3D detection / VLM |
| 2026-02-23 | [Step 3.5 Flash: Open Frontier-Level Intelligence with 11B Active Parameters](https://arxiv.org/abs/2602.10604v2) | LLM / foundation model |
| 2026-02-22 | [GenesisGeo: Technical Report](https://arxiv.org/abs/2509.21896v2) | geometry reasoning / VLM |
| 2026-02-20 | [Scaling Audio-Text Retrieval with Multimodal Large Language Models](https://arxiv.org/abs/2602.18010v1) | audio-text retrieval / MLLM |
| 2026-02-19 | [Arcee Trinity Large Technical Report](https://arxiv.org/abs/2602.17004v1) | LLM / foundation model |
| 2026-02-17 | [Language and Geometry Grounded Sparse Voxel Representations for Holistic Scene Understanding](https://arxiv.org/abs/2602.15734v1) | 3D scene understanding |
| 2026-02-17 | [LuxMT Technical Report](https://arxiv.org/abs/2602.15506v1) | domain / multilingual LLM |
| 2026-02-16 | [Image Generation with a Sphere Encoder](https://arxiv.org/abs/2602.15030v1) | image generation |
| 2026-02-16 | [PAct: Part-Decomposed Single-View Articulated Object Generation](https://arxiv.org/abs/2602.14965v1) | articulated object generation |
| 2026-02-16 | [EmbeWebAgent: Embedding Web Agents into Any Customized UI](https://arxiv.org/abs/2602.14865v1) | web agent / GUI agent |
| 2026-02-16 | [Frontier AI Risk Management Framework in Practice: A Risk Analysis Technical Report v1.5](https://arxiv.org/abs/2602.14457v1) | frontier AI risk management |
| 2026-02-16 | [The Joy and Pain of Training an LLM from Scratch: A Technical Report on the Development of the Zagreus and Nesso Model Families](https://github.com/mii-llm/zagreus-nesso-slm/blob/49e1b232ffde307e63370842d635e47b4f906452/README.md) | bilingual compact LLM / from-scratch pretraining and instruction post-training |
| 2026-02-15 | [Eureka-Audio: Triggering Audio Intelligence in Compact Language Models](https://arxiv.org/abs/2602.13954v1) | audio / compact audio language model |
| 2026-02-13 | [FiMI: A Domain-Specific Language Model for Indian Finance Ecosystem](https://arxiv.org/abs/2602.05794v2) | domain / multilingual LLM |
| 2026-02-13 | [RynnBrain: Open Embodied Foundation Models](https://arxiv.org/abs/2602.14979v1) | embodied foundation model / multimodal pretraining and post-training |
| 2026-02-13 | [DeepGen 1.0: A Lightweight Unified Multimodal Model for Advancing Image Generation and Editing](https://arxiv.org/abs/2602.12205v2) | unified multimodal / image generation and editing |
| 2026-02-13 | [Nanbeige4.1-3B: A Small General Model that Reasons, Aligns, and Acts](https://arxiv.org/abs/2602.13367v1) | small general LLM / reasoning, alignment and agentic post-training |
| 2026-02-12 | [DeepSight: An All-in-One LM Safety Toolkit](https://arxiv.org/abs/2602.12092v1) | LM safety toolkit |
| 2026-02-12 | [HoloBrain-0 Technical Report](https://arxiv.org/abs/2602.12062v1) | robotics / VLA |
| 2026-02-12 | [ABot-N0: Technical Report on the VLA Foundation Model for Versatile Embodied Navigation](https://arxiv.org/abs/2602.11598v1) | robotics / VLA |
| 2026-02-12 | [MOSS-Audio-Tokenizer: Scaling Audio Tokenizers for Future Audio Foundation Models](https://arxiv.org/abs/2602.10934v2) | audio tokenizer / foundation-model infrastructure |
| 2026-02-12 | [Kelix Technical Report](https://arxiv.org/abs/2602.09843v3) | multimodal / VLM |
| 2026-02-12 | [Singpath-VL Technical Report](https://arxiv.org/abs/2602.09523v2) | multimodal / VLM |
| 2026-02-11 | [Scaling Towards the Information Boundary of Instruction Sets: The Infinity Instruct Subject Technical Report](https://arxiv.org/abs/2507.06968v4) | instruction data / LLM fine-tuning |
| 2026-02-11 | [A.X K1 Technical Report](https://arxiv.org/abs/2601.09200v5) | LLM inference / compression |
| 2026-02-10 | [MOVA: Towards Scalable and Synchronized Video-Audio Generation](https://arxiv.org/abs/2602.08794v2) | video-audio generation |
| 2026-02-10 | [ALIVE: Animate Your World with Lifelike Audio-Video Generation](https://arxiv.org/abs/2602.08682v2) | audio-video generation |
| 2026-02-10 | [Hunyuan-GameCraft-2: Instruction-following Interactive Game World Model](https://arxiv.org/abs/2511.23429v2) | interactive world model / video generation |
| 2026-02-09 | [iGRPO: Self-Feedback-Driven LLM Reasoning](https://arxiv.org/abs/2602.09000v1) | LLM reasoning |
| 2026-02-09 | [Bolmo: Byteifying the Next Generation of Language Models](https://arxiv.org/abs/2512.15586v2) | byte-level LLM / byteification and distillation |
| 2026-02-06 | [Lemon Agent Technical Report](https://arxiv.org/abs/2602.07092v1) | agent / deep research |
| 2026-02-06 | [MeDocVL: A Visual Language Model for Medical Document Understanding and Parsing](https://arxiv.org/abs/2602.06402v1) | medical VLM / document understanding |
| 2026-02-06 | [AgentCPM-Explore: Realizing Long-Horizon Deep Exploration for Edge-Scale Agents](https://arxiv.org/abs/2602.06485v1) | deep-research agent / SFT, model merging and RL |
| 2026-02-06 | [AgentCPM-Report: Interleaving Drafting and Deepening for Open-Ended Deep Research](https://arxiv.org/abs/2602.06540v1) | deep-research agent / SFT and multi-stage RL |
| 2026-02-06 | [Yunjue Agent Tech Report: A Fully Reproducible, Zero-Start In-Situ Self-Evolving Agent System for Open-Ended Tasks](https://arxiv.org/abs/2601.18226v2) | self-evolving agent |
| 2026-02-05 | [Orthogonal Model Merging](https://arxiv.org/abs/2602.05943v1) | model merging |
| 2026-02-05 | [EuroLLM-22B: Technical Report](https://arxiv.org/abs/2602.05879v1) | LLM training / alignment |
| 2026-02-04 | [ARC-AGI-2 Technical Report](https://arxiv.org/abs/2603.06590v1) | symbolic reasoning / transformer system |
| 2026-02-04 | [Locas: Your Models are Principled Initializers of Locally-Supported Parametric Memories](https://arxiv.org/abs/2602.05085v1) | LLM memory / parametric memory |
| 2026-02-04 | [Knowing When to Answer: Adaptive Confidence Refinement for Reliable Audio-Visual Question Answering](https://arxiv.org/abs/2602.04924v1) | audio-visual QA |
| 2026-02-04 | [ERNIE 5.0 Technical Report](https://arxiv.org/abs/2602.04705v1) | multimodal / VLM |
| 2026-02-04 | [OpenOneRec Technical Report](https://arxiv.org/abs/2512.24762v2) | recommendation / generative foundation model |
| 2026-02-04 | [OCRVerse: Towards Holistic OCR in End-to-End Vision-Language Models](https://arxiv.org/abs/2601.21639v2) | OCR / document understanding |
| 2026-02-03 | [Quantization Meets Projection: A Happy Marriage for Approximate k-Nearest Neighbor Search](https://arxiv.org/abs/2411.06158v4) | retrieval / vector search infrastructure |
| 2026-02-03 | [Kimi K2: Open Agentic Intelligence](https://arxiv.org/abs/2507.20534v2) | agentic LLM / MoE |
| 2026-02-03 | [HyperOffload: Graph-Driven Hierarchical Memory Management for Large Language Models on SuperNode Architectures](https://arxiv.org/abs/2602.00748v2) | LLM memory / offload |
| 2026-02-03 | [DuoGen: Towards General Purpose Interleaved Multimodal Generation](https://arxiv.org/abs/2602.00508v2) | multimodal generation |
| 2026-02-01 | [ConsensusDrop: Fusing Visual and Cross-Modal Saliency for Efficient Vision Language Models](https://arxiv.org/abs/2602.00946v1) | efficient VLM |
| 2026-02-01 | [LongCat-Flash-Thinking-2601 Technical Report](https://arxiv.org/abs/2601.16725v2) | agent / deep research |
| 2026-01-31 | [High-Fidelity Generative Audio Compression at 0.275kbps](https://arxiv.org/abs/2602.00648v1) | audio / neural codec |
| 2026-01-30 | [Qwen3-ASR Technical Report](https://arxiv.org/abs/2601.21337v2) | audio / speech model |
| 2026-01-29 | [GeoNorm: Unify Pre-Norm and Post-Norm with Geodesic Optimization](https://arxiv.org/abs/2601.22095v1) | normalization / optimization |
| 2026-01-28 | [Llama-3.1-FoundationAI-SecurityLLM-Reasoning-8B Technical Report](https://arxiv.org/abs/2601.21051v1) | domain / security / legal LLM |
| 2026-01-28 | [Efficient Autoregressive Video Diffusion with Dummy Head](https://arxiv.org/abs/2601.20499v1) | video diffusion |
| 2026-01-28 | [TeleStyle: Content-Preserving Style Transfer in Images and Videos](https://arxiv.org/abs/2601.20175v1) | image/video stylization |
| 2026-01-28 | [Advancing Open-source World Models](https://arxiv.org/abs/2601.20540v1) | interactive world model / video generation |
| 2026-01-27 | [Yunque DeepResearch Technical Report](https://arxiv.org/abs/2601.19578v1) | agent / deep research |
| 2026-01-27 | [Innovator-VL: A Multimodal Large Language Model for Scientific Discovery](https://arxiv.org/abs/2601.19325v1) | scientific-discovery MLLM |
| 2026-01-27 | [Youtu-VL: Unleashing Visual Potential via Unified Vision-Language Supervision](https://arxiv.org/abs/2601.19798v1) | multimodal foundation model / unified vision-language autoregressive training |
| 2026-01-27 | [iFSQ: Improving FSQ for Image Generation with 1 Line of Code](https://arxiv.org/abs/2601.17124v2) | image tokenizer |
| 2026-01-25 | [Masked Depth Modeling for Spatial Perception](https://arxiv.org/abs/2601.17895v1) | visual foundation model / depth perception |
| 2026-01-24 | [C-RADIOv4 (Tech Report)](https://arxiv.org/abs/2601.17237v1) | vision foundation model |
| 2026-01-23 | [Fast, faithful and photorealistic diffusion-based image super-resolution with enhanced Flow Map models](https://arxiv.org/abs/2601.16660v1) | image generation / super-resolution |
| 2026-01-23 | [EvoCUA: Evolving Computer Use Agents via Learning from Scalable Synthetic Experience](https://arxiv.org/abs/2601.15876v2) | computer-use agent / post-training |
| 2026-01-22 | [Qwen3-TTS Technical Report](https://arxiv.org/abs/2601.15621v1) | audio / speech model |
| 2026-01-22 | [Cosmos Policy: Fine-Tuning Video Models for Visuomotor Control and Planning](https://arxiv.org/abs/2601.16163v1) | robotics / world-action policy post-training |
| 2026-01-21 | [Solving the Unsolvable: Inside Acuvity's Prompt Injection and Jailbreak Detection Model](https://acuvity.ai/wp-content/uploads/2026/01/Whitepaper-Solving-the-Unsolvable-Inside-Acuvitys-Prompt-Injection-and-Jailbreak-Detection-Model.pdf) | LLM safety / prompt-injection detection |
| 2026-01-21 | [Human detectors are surprisingly powerful reward models](https://arxiv.org/abs/2601.14037v2) | video generation / reward modeling |
| 2026-01-20 | [RoboBrain 2.5: Depth in Sight, Time in Mind](https://arxiv.org/abs/2601.14352v1) | robotics / VLA |
| 2026-01-20 | [Fun-Audio-Chat Technical Report](https://arxiv.org/abs/2512.20156v4) | audio / speech model |
| 2026-01-20 | [VoiceSculptor: Your Voice, Designed By You](https://arxiv.org/abs/2601.10629v2) | audio / speech model |
| 2026-01-20 | [Logics-STEM: Empowering LLM Reasoning via Failure-Driven Post-Training and Document Knowledge Enhancement](https://arxiv.org/abs/2601.01562v3) | STEM reasoning LLM / failure-driven post-training |
| 2026-01-19 | [Typhoon ASR Real-time: FastConformer-Transducer for Thai Automatic Speech Recognition](https://arxiv.org/abs/2601.13044v1) | audio / speech model |
| 2026-01-19 | [FRoM-W1: Towards General Humanoid Whole-Body Control with Language Instructions](https://arxiv.org/abs/2601.12799v1) | humanoid control / behavior foundation model |
| 2026-01-19 | [Qwen3-VL-Embedding and Qwen3-VL-Reranker: A Unified Framework for State-of-the-Art Multimodal Retrieval and Ranking](https://arxiv.org/abs/2601.04720v2) | multimodal retrieval / embedding and reranking |
| 2026-01-19 | [TranslateGemma Technical Report](https://arxiv.org/abs/2601.09012v3) | multimodal / VLM |
| 2026-01-18 | [QianfanHuijin Technical Report: A Novel Multi-Stage Training Paradigm for Finance Industrial LLMs](https://arxiv.org/abs/2512.24314v2) | finance domain LLM |
| 2026-01-17 | [MuseAgent-1: Interactive Grounded Multimodal Understanding of Music Scores and Performance Audio](https://arxiv.org/abs/2601.11968v1) | music-score/audio multimodal agent |
| 2026-01-17 | [openPangu-VL-7B: A Multi-Modal Large Language Model Designed and Optimized for Ascend NPUs](https://huggingface.co/FreedomIntelligence/openPangu-VL-7B/blob/1688f96fa70952f5a3d5d57af9410b4f8eca8d0a/doc/technical_report.pdf) | multimodal LLM / pretraining, post-training and Ascend infrastructure |
| 2026-01-15 | [STEP3-VL-10B Technical Report](https://arxiv.org/abs/2601.09668v2) | multimodal / VLM |
| 2026-01-14 | [Higher Satisfaction, Lower Cost: A Technical Report on How LLMs Revolutionize Meituan's Intelligent Interaction Systems](https://arxiv.org/abs/2510.13291v2) | LLM application system / agents |
| 2026-01-14 | [When Single-Agent with Skills Replace Multi-Agent Systems and When They Fail](https://arxiv.org/abs/2601.04748v2) | agent systems |
| 2026-01-14 | [Distribution-Aligned Sequence Distillation for Superior Long-CoT Reasoning](https://arxiv.org/abs/2601.09088v1) | LLM post-training / distribution-aligned long-CoT sequence distillation |
| 2026-01-13 | [Ministral 3](https://arxiv.org/abs/2601.08584v1) | small language model / LLM training |
| 2026-01-11 | [Solar Open Technical Report](https://arxiv.org/abs/2601.07022v1) | reasoning LM |
| 2026-01-11 | [LongEmotion: Measuring Emotional Intelligence of Large Language Models in Long-Context Interaction](https://arxiv.org/abs/2509.07403v2) | LLM inference system / long-context emotional reasoning with CoEM RAG and multi-agent enrichment |
| 2026-01-09 | [GR-Dexter Technical Report](https://arxiv.org/abs/2512.24210v2) | robotics / VLA |
| 2026-01-09 | [K-EXAONE Technical Report](https://arxiv.org/abs/2601.01739v2) | agent / deep research |
| 2026-01-08 | [QwenStyle: Content-Preserving Style Transfer with Qwen-Image-Edit](https://arxiv.org/abs/2601.06202v1) | image generation |
| 2026-01-08 | [GDPO: Group reward-Decoupled Normalization Policy Optimization for Multi-reward RL Optimization](https://arxiv.org/abs/2601.05242v1) | RL optimization |
| 2026-01-08 | [THaLLE-ThaiLLM: Domain-Specialized Small LLMs for Finance and Thai -- Technical Report](https://arxiv.org/abs/2601.04597v1) | domain / multilingual LLM |
| 2026-01-08 | [NorwAI's Large Language Models: Technical Report](https://arxiv.org/abs/2601.03034v2) | LLM training / alignment |
| 2026-01-08 | [MiMo-V2-Flash Technical Report](https://arxiv.org/abs/2601.02780v2) | agent / deep research |
| 2026-01-08 | [AMAP Agentic Planning Technical Report](https://arxiv.org/abs/2512.24957v2) | agentic planning LLM |
| 2026-01-07 | [ResTok: Learning Hierarchical Residuals in 1D Visual Tokenizers for Autoregressive Image Generation](https://arxiv.org/abs/2601.03955v1) | visual tokenizer |
| 2026-01-07 | [Back to Basics: Let Denoising Generative Models Denoise](https://arxiv.org/abs/2511.13720v2) | diffusion / generative model |
| 2026-01-07 | [Beyond Scaling: Measuring and Predicting the Upper Bound of Knowledge Retention in Language Model Pre-Training](https://arxiv.org/abs/2502.04066v7) | LLM pretraining / knowledge retention |
| 2026-01-07 | [HONEYBEE: Efficient Role-based Access Control for Vector Databases via Dynamic Partitioning\[Technical Report\]](https://arxiv.org/abs/2505.01538v3) | LLM RAG inference infrastructure / RBAC-aware vector-search partitioning |
| 2026-01-06 | [MMFormalizer: Multimodal Autoformalization in the Wild](https://arxiv.org/abs/2601.03017v1) | multimodal formalization |
| 2026-01-06 | [DoPE: Denoising Rotary Position Embedding](https://arxiv.org/abs/2511.09146v2) | LLM architecture / RoPE |
| 2026-01-05 | [HyperCLOVA X 8B Omni](https://arxiv.org/abs/2601.01792v1) | multimodal / omni LLM |
| 2026-01-05 | [Context-aware Decoding Reduces Hallucination in Query-focused Summarization](https://arxiv.org/abs/2312.14335v3) | RAG / hallucination reduction |
| 2026-01-05 | [Falcon-H1R: Pushing the Reasoning Frontiers with a Hybrid Model for Efficient Test-Time Scaling](https://arxiv.org/abs/2601.02346v1) | reasoning LLM / SFT and RL |
| 2026-01-03 | [HyperCLOVA X 32B Think](https://arxiv.org/abs/2601.03286v1) | reasoning LLM |
| 2026-01-02 | [EXAONE 4.0: Unified Large Language Models Integrating Non-reasoning and Reasoning Modes](https://arxiv.org/abs/2507.11407v2) | multilingual LLM / pretraining, long-context extension and reasoning post-training |
| 2026-01-02 | [EXAONE 3.5: Series of Large Language Models for Real-world Use Cases](https://arxiv.org/abs/2412.04862v3) | bilingual LLM / two-stage pretraining and preference-aligned post-training |
