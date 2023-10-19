## Paper

#### [Imagereward: Learning and evaluating human preferences for text-to-image generation](https://arxiv.org/abs/2304.05977)

#### [ImagenHub: Standardizing the evaluation of conditional image generation models](https://arxiv.org/abs/2310.01596)

#### [Measuring the Quality of Text-to-Video Model Outputs: Metrics and Dataset](https://arxiv.org/abs/2309.08009)

#### [What You See is What You Read? Improving Text-Image Alignment Evaluation](https://arxiv.org/abs/2305.10400)



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



想法：先搞一个image的，然后拓展到video和3D上

video 注重和文本的匹配度和本身的一致性