# Video quality Assessment



#### FAST-VQA: Efficient End-to-end Video Quality Assessment with Fragment Sampling(ECCV 2022)



#### Exploring Video Quality Assessment on User Generated Contents from Aesthetic and Technical Perspectives(ICCV 2023)



1. subjective quality assessment
2. objective quality assessment
   1. Full reference
      * Mean square error, MSE; Mean absolute error, MAE; Root mean square error, RMSE; Standard deviation, STD. 计算复杂度低，和主观评价差距大
      * Peak signal noise ratio, PSNR. 最广泛使用的客观法
      * Structure similarity Index, SSIM. 通过感知结构信息来评价失真更接近人眼
      * Multi scale structure similarity index, MS-SSIM. 相对于单尺度的SSIM能够适应不同分辨率与更广泛的场景
      * Just Noticeable Difference, JND. 符合人眼主观感知
      * VMAF. Netflix. 包括Visual Information Fidelity, VIF; Detail Loss Metric, DLM; Mean Co-Located Pixel Difference, MCPD.