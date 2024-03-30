## Paper

[Imagereward: Learning and evaluating human preferences for text-to-image generation](https://arxiv.org/abs/2304.05977)

[ImagenHub: Standardizing the evaluation of conditional image generation models](https://arxiv.org/abs/2310.01596)

[Measuring the Quality of Text-to-Video Model Outputs: Metrics and Dataset](https://arxiv.org/abs/2309.08009)

[What You See is What You Read? Improving Text-Image Alignment Evaluation](https://arxiv.org/abs/2305.10400)

[EvalCrafter: Benchmarking and Evaluating Large Video Generation Models](https://arxiv.org/abs/2310.11440)

[TIFA: Accurate and Interpretable Text-to-Image Faithfulness Evaluation with Question Answering](https://arxiv.org/abs/2303.11897)

[Imagen Editor and EditBench: Advancing and Evaluating Text-Guided Image Inpainting](https://arxiv.org/abs/2212.06909)

[Toward Verifiable and Reproducible Human Evaluation for Text-to-Image Generation](https://arxiv.org/abs/2304.01816)

[StableVQA: A Deep No-Reference Quality Assessment Model for Video Stability](https://arxiv.org/abs/2308.04904v2)

[Likelihood-Based Text-to-Image Evaluation with Patch-Level Perceptual and Semantic Credit Assignment](https://arxiv.org/abs/2308.08525)

[Let's ViCE! Mimicking Human Cognitive Behavior in Image Generation Evaluation](https://arxiv.org/abs/2307.09416v2)

[Exposing flaws of generative model evaluation metrics and their unfair treatment of diffusion models](https://arxiv.org/abs/2306.04675)

[FETV: A Benchmark for Fine-Grained Evaluation of Open-Domain Text-to-Video Generation](https://arxiv.org/abs/2311.01813)

[Davidsonian Scene Graph: Improving Reliability in Fine-grained Evaluation for Text-to-Image Generation](https://arxiv.org/abs/2310.18235)

[Divide, Evaluate, and Refine: Evaluating and Improving Text-to-Image Alignment with Iterative VQA Feedback](https://arxiv.org/abs/2307.04749)

HRS-Bench: Holistic, Reliable and Scalable Benchmark for Text-to-Image Models



## Improving

[Optimizing Prompts for Text-to-Image Generation](https://arxiv.org/abs/2212.09611)

[Decompose and Realign: Tackling Condition Misalignment in Text-to-Image Diffusion Models](https://arxiv.org/abs/2306.14408)

[Shadows Don’t Lie and Lines Can’t Bend! Generative Models don’t know Projective Geometry...for now]

[Parrot: Pareto-optimal Multi-Reward Reinforcement Learning Framework for Text-to-Image Generation](https://arxiv.org/abs/2401.05675) Story

[Large-scale Reinforcement Learning for Diffusion Models](https://arxiv.org/abs/2401.12244)

[Using Human Feedback to Fine-Tune Diffusion Models Without Any Reward Model](https://arxiv.org/abs/2311.13231)

TagAlign: Improving Vision-Language Alignment with Multi-Tag Classification



## Self-training LLM

[Beyond Human Data: Scaling Self-Training for Problem-Solving with Language Models](https://arxiv.org/abs/2312.06585)



## VQA

#### FAST-VQA: Efficient End-to-end Video Quality Assessment with Fragment Sampling(ECCV 2022)

#### Exploring Video Quality Assessment on User Generated Contents from Aesthetic and Technical Perspectives(ICCV 2023)



1. subjective quality assessment

2. objective quality assessment
   1. full reference(FR)
      * Mean square error, MSE; Mean absolute error, MAE; Root mean square error, RMSE; Standard deviation, STD. 计算复杂度低，和主观评价差距大
      * Peak signal noise ratio, PSNR. 最广泛使用的客观法
      * Structure similarity Index, SSIM. 通过感知结构信息来评价失真更接近人眼
      * Multi scale structure similarity index, MS-SSIM. 相对于单尺度的SSIM能够适应不同分辨率与更广泛的场景
      * Just Noticeable Difference, JND. 符合人眼主观感知
      * VMAF. Netflix. 包括Visual Information Fidelity, VIF; Detail Loss Metric, DLM; Mean Co-Located Pixel Difference, MCPD.
   
   2. reduced reference(RR)
   
   3. no reference(NR)
   
      ![截屏2023-09-12 00.07.59](./VQA.assets/2023-09-12%2000.07.59.png)





##### video caption assessment

![截屏2023-09-12 00.27.07](./VQA.assets/2023-09-12%2000.27.07.png)



Reference method

![截屏2023-09-12 00.28.58](./VQA.assets/2023-09-12%2000.28.58.png)



### Related works

EMScore: Evaluating Video Captioning via Coarse-Grained and Fine-Grained Embedding Matching(CVPR2022)



![截屏2023-09-12 01.15.44](./VQA.assets/2023-09-12%2001.15.44.png)



Positive-Augmented Contrastive Learning for Image and Video Captioning Evaluation(arxiv: 2303.12112)

![截屏2023-09-12 01.32.41](./VQA.assets/2023-09-12%2001.32.41.png)

使用生成模型增强CLIP-Score, 说明生成模型的能力比CLIP要强，我们不能简单地用CLIP去衡量生成质量

类似的结论在如下这篇文章也有: Augmenting CLIP with Improved Visio-Linguistic Reasoning(arxiv: 2307.09233)

![截屏2023-09-12 01.47.16](./VQA.assets/2023-09-12%2001.47.16.png)



可借鉴的文章: TIFA: Accurate and Interpretable Text-to-Image Faithfulness Evaluation with Question Answering(arXiv: 2303.11897)

![截屏2023-09-12 01.53.57](./VQA.assets/2023-09-12%2001.53.57.png)

![截屏2023-09-12 01.56.35](./VQA.assets/2023-09-12%2001.56.35.png)

#### Mean Opinion Score (MOS)

### Data filter

[Data Filtering Networks](https://arxiv.org/abs/2309.17425)

[SIEVE: Multimodal Dataset Pruning Using Image Captioning Models](https://arxiv.org/abs/2310.02110)



### Dataset

HQITP-350M
