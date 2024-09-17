[Searching Priors Makes Text-to-Video Synthesis Better](https://arxiv.org/abs/2406.03215)

​	Improving performance of motion dynamics by RAG, but no much improvement from its demo

[ShareGPT4Video: Improving Video Understanding and Generation with Better Captions](https://arxiv.org/abs/2406.04325)

​	Opensora's solution for better captioning: caption each video clip by sliding-indow and then summarize

#### DiT & Base-model:

[CogVideoX: Text-to-Video Diffusion Models with An Expert Transformer](https://arxiv.org/abs/2408.06072)

[Lumina-Next: Making Lumina-T2X Stronger and Faster with Next-DiT](https://arxiv.org/pdf/2406.18583)

[Lumina-T2X: Transforming Text into Any Modality, Resolution, and Duration via Flow-based Large Diffusion Transformers](https://arxiv.org/abs/2405.05945)

[Latte: Latent Diffusion Transformer for Video Generation](https://arxiv.org/abs/2401.03048) 

[VD3D: Taming Large Video Diffusion Transformers for 3D Camera Control](https://arxiv.org/pdf/2407.12781)

[Scaling Diffusion Transformers to 16 Billion Parameters](https://arxiv.org/pdf/2407.11633)

​	propose DiT-MoE, which is scalable and competitive with dense networks while exhibiting highly optimized inference. 

#### Pioneer Base model & UNet

[Video Diffusion Models](https://arxiv.org/abs/2204.03458)

​	3D UNet factorized over space and time

​	Insert temporal attention layer that attends across the temporal dimension

[Make-A-Video: Text-to-Video Generation without Text-Video Data](https://arxiv.org/abs/2209.14792)

​	Training video without text. The model captures video motion from unsupervised video data.

[Stable Video Diffusion: Scaling Latent Video Diffusion Models to Large Datasets](https://arxiv.org/abs/2311.15127)

​	Curated Training Data Improves Performance; Frame Interpolation to obtain smooth videos at high frame rates

[VideoCrafter2: Overcoming Data Limitations for High-Quality Video Diffusion Models](https://arxiv.org/abs/2401.09047)



#### Controllable generation & Adapter

[SparseCtrl: Adding Sparse Controls to Text-to-Video Diffusion Models](https://arxiv.org/abs/2311.16933#)

​	controlnet

[AnimateDiff: Animate Your Personalized Text-to-Image Diffusion Models without Specific Tuning](https://arxiv.org/abs/2307.04725)

​	motion lora

[DisCo: Disentangled Control for Realistic Human Dance Generation](https://arxiv.org/abs/2307.00040)

​	Enable arbitrary compositionality of human subjects, backgrounds, and poses by disentangling the control from all three conditions. 

[HumanVid: Demystifying Training Data for Camera-controllable Human Image Animation](https://arxiv.org/pdf/2407.17438)

​	synthetic data

[InVi: Object Insertion In Videos Using Off-the-Shelf Diffusion Models](https://arxiv.org/abs/2407.10958)

[VideoTetris: Towards Compositional Text-to-Video Generation](https://arxiv.org/abs/2406.04277)

[Cinemo: Consistent and Controllable Image Animation with Motion Diffusion Models ](https://arxiv.org/pdf/2407.15642) 

​	learn motion residuals

#### Long video generation

[NUWA-XL: Diffusion over Diffusion for eXtremely Long Video Generation](https://arxiv.org/abs/2303.12346)

​	a coarse-to-fine process, first generate the keyframes and then recursively fill in the content between nearby frames.

[SEINE: Short-to-Long Video Diffusion Model for Generative Transition and Prediction](https://openreview.net/forum?id=FNq3nIvP4F)

​	from discrete scene images generate transition videos

[StreamingT2V: Consistent, Dynamic, and Extendable Long Video Generation from Text](https://arxiv.org/abs/2403.14773)

[Video-Infinity: Distributed Long Video Generation](https://arxiv.org/abs/2406.16260)

​	GPU distributed generation

#### Video&Image story generation

[MovieDreamer: Hierarchical Generation for Coherent Long Visual Sequence](https://arxiv.org/abs/2407.16655)

​	MLLM generates keyframes, and SVD generates consistent video from keyframes

[DreamStory: Open-Domain Story Visualization by LLM-Guided Multi-Subject Consistent Diffusion](https://arxiv.org/abs/2407.12899v1)

​	LLM generates subject and scene descriptions from scripts, and then directly generates long videos from descriptions by strong T2V models. (the demo's T2V model is Kling)

[Make-A-Storyboard: A General Framework for Storyboard with Disentangled and Merged Control](https://arxiv.org/abs/2312.07549)

​	Disentangle subjects and scenes then do controllable generation

[Boosting Consistency in Story Visualization with Rich-Contextual Conditional Diffusion Models](https://arxiv.org/abs/2407.02482)

​	firstly generate the first frame, then generate 2-M frames conditioned on the first frame and all captions

[Intelligent Grimm - Open-ended Visual Storytelling via Latent Diffusion Models](https://arxiv.org/abs/2306.00973)

​	 use text prompts and previous visual-language contexts as conditions to generate a coherent image sequence.

[StoryDiffusion: Consistent Self-Attention for Long-Range Image and Video Generation](https://arxiv.org/abs/2405.01434)

​	Generate consistent images from prompts, then generate consistent videos from images

[VideoDirectorGPT: Consistent Multi-scene Video Generation via LLM-Guided Planning](https://arxiv.org/abs/2309.15091)

​	Very similar plan

[VideoDrafter: Content-Consistent Multi-Scene Video Generation with LLM](https://arxiv.org/abs/2401.01256)

[Compositional 3D-aware Video Generation with LLM Director](https://arxiv.org/abs/2409.00558)

#### Evaluate

[VIDEOPHY: Evaluating Physical Commonsense for Video Generation](https://arxiv.org/abs/2406.03520)

​	Evaluate physical commonsense in generated videos

[T2V-CompBench: A Comprehensive Benchmark for Compositional Text-to-video Generation](https://arxiv.org/abs/2407.14505) 

[VBench: Comprehensive Benchmark Suite for Video Generative Models](https://arxiv.org/abs/2311.17982) 

#### Dataset

[Openstory++: A Large-scale Dataset and Benchmark for Instance-aware Open-domain Visual Storytelling](https://arxiv.org/abs/2408.03695)

[OpenVid-1M: A Large-Scale High-Quality Dataset for Text-to-video Generation](https://arxiv.org/abs/2407.02371)

[VidGen-1M: A Large-Scale Dataset for Text-to-video Generation](https://arxiv.org/abs/2408.02629)

[Panda-70M: Captioning 70M Videos with Multiple Cross-Modality Teachers](https://arxiv.org/abs/2402.19479) 



[ReconX: Reconstruct Any Scene from Sparse Views with Video Diffusion Model](https://arxiv.org/abs/2408.16767)
[Generative Inbetweening: Adapting Image-to-Video Models for Keyframe Interpolation](https://arxiv.org/abs/2408.15239)
[xGen-VideoSyn-1: High-fidelity Text-to-Video Synthesis with Compressed Representations](https://www.arxiv.org/abs/2408.12590)