# Brain-Tumor-Segmentation-using-DDPM

Diffusion models have recently surfaced as a highly effective group of deep generative models, achieving unprecedented success in various applications such as image synthesis, video creation, and molecular design. In this study, we introduce an innovative semantic segmentation technique based on diffusion models. By altering the training and sampling approach, we demonstrate the capability of diffusion models in performing segmentation within medical imagery. To produce image-specific segmentation, we train the model using ground truth segmentation and incorporate the image as a prior during both training and each step of the sampling process. The given stochastic sampling procedure enables us to generate a range of segmentation masks, allowing us to compute pixel-wise uncertainty maps for segmentation and facilitating an implicit ensemble of segmentations, enhancing segmentation performance. Our method is evaluated using the Brain MRI dataset for brain tumor segmentation. our technique not only delivers impressive segmentation results but also provides comprehensive uncertainty maps.