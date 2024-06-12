#### Fine-Tuning can Distort Pretrained Features and Underperform Out-of-Distribution



#### DIAGNOSING AND RECTIFYING VISION MODELS USING LANGUAGE, ICLR 2023

可能有用的结论

* cross-model transferability phenomenon of this joint space, use text proxy for image task

#### PromptStyler: Prompt-driven Style Generation for Source-free Domain Generalization

prompt domain generalization -> image domain generalization, without any images. 通过prompt  synthesize other style in vision-language space.

a totally new training paradigm, where we train a classifier using text features while running an inference with the classifier using image features.



## Language_based Detector

[OmniLabel: A Challenging Benchmark for Language-Based Object Detection](https://arxiv.org/abs/2304.11463)

Grounded Language-Image Pre-training(GLIP, CVPR 22)



#### Data Scale

[Scaling Laws of Synthetic Images for Model Training ... for Now](https://arxiv.org/abs/2312.04567)

[StableRep: Synthetic Images from Text-to-Image Models Make Strong Visual Representation Learners](https://arxiv.org/abs/2306.00984)

[Learning Vision from Models Rivals Learning Vision from Data](https://arxiv.org/abs/2312.17742)



#### Composite RM

[Confronting Reward Model Overoptimization With Constrained RLHF](https://openreview.net/attachment?id=gkfUvn0fLU&name=pdf)



#### RM

[Rrhf: Rank responses to align language models with human feedback without tears]

[Scaling laws for reward model overoptimization]

[[Confronting Reward Model Overoptimization with Constrained RLHF](https://openreview.net/forum?id=gkfUvn0fLU)]

[[Improving Generalization of Alignment with Human Preferences through Group Invariant Learning](https://openreview.net/forum?id=fwCoLe3TAX)]

Parrot: Pareto-optimal Multi-Reward Reinforcement Learning Framework for Text-to-Image Generation



#### MoE

[From Sparse to Soft Mixtures of Experts](https://openreview.net/forum?id=jxpsAj7ltE)

Skywork-MoE: A Deep Dive into **Training Techniques** for Mixture-of-Experts Language Models



#### Lora

[LoRaHub: Efficient Cross-Task Generalization via Dynamic LoRa Composition](https://arxiv.org/abs/2307.13269)

[Batched Low-Rank Adaptation of Foundation Models](https://openreview.net/pdf?id=w4abltTZ2f)



SDXL-Lightning: Progressive Adversarial Diffusion Distillation

Self-Correcting Self-Consuming Loops for Generative Model Training



#### RLHF

Aligning Text-to-Image Models using Human Feedback

Training Diffusion Models with Reinforcement Learning(DDPO)

ImageReward: Learning and Evaluating Human Preferences for Text-to-Image Generation

DPOK: Reinforcement Learning for Fine-tuning Text-to-Image Diffusion Models

Better Aligning Text-to-Image Models with Human Preference

Directly Fine-Tuning Diffusion Models on Differentiable Rewards(DRaFT)

PRDP: Proximal Reward Difference Prediction for Large-Scale Reward Finetuning of Diffusion Models

#### DPO and RLHF

Diffusion-DPO

[Statistical Rejection Sampling Improves Preference Optimization](https://arxiv.org/abs/2309.06657)

KTO: Model Alignment as Prospect Theoretic Optimization

[Relative Preference Optimization: Enhancing LLM Alignment through Contrasting Responses across Identical and Diverse Prompts](https://arxiv.org/abs/2402.10958) RPO

ORPO: Monolithic Preference Optimization without Reference Model

From r to Q∗ : Your Language Model is Secretly a Q-Function

IPO:  A general theoretical paradigm to understand learning from human preferences.

[Scaling Laws for Reward Model Overoptimization in Direct Alignment Algorithms](https://arxiv.org/abs/2406.02900)

[Direct Preference Optimization With Unobserved Preference Heterogeneity](https://arxiv.org/abs/2405.15065)

[Adaptive Preference Scaling for Reinforcement Learning with Human Feedback](https://arxiv.org/abs/2406.02764) **Scale DPO**



#### 解耦

MoA: Mixture-of-Attention for Subject-Context Disentanglement in Personalized Image Generation
