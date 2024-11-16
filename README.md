 GENERATIVE-AI-using-GAN-and-Diffusion-Models

## Abstract
This project investigates the efficacy of Generative Adversarial Networks (GANs) and diffusion models in generating realistic facial images, particularly focusing on the creation of deepfakes. With the increasing concerns surrounding the misuse of synthetic media, understanding the strengths and limitations of these models is paramount. The research begins with an overview of GANs and diffusion models, exploring their architectures and underlying principles. Subsequently, a facial dataset is selected and preprocessed to ensure diversity and representativeness. Different GAN architectures and diffusion models are then implemented for image generation, with a specific emphasis on replicating facial features accurately. The generated images are subjected to thorough analysis, encompassing both visual inspection and quantitative evaluation metrics. Additionally, the detectability of the generated deepfakes is assessed using state-of-the-art detection tools. The findings reveal nuanced differences between GANs and diffusion models in terms of image quality, realism, and detectability. While GANs excel in producing visually appealing images, diffusion models demonstrate superior performance in preserving finer facial details. However, diffusion models are found to be more susceptible to detection by existing deepfake detection algorithms. The project concludes with a comprehensive discussion on the implications of these findings and identifies avenues for future research in the domain of synthetic media generation and manipulation.

## Dataset
Selecting an appropriate facial dataset is crucial for training robust and effective models in various computer vision tasks, including facial recognition, emotion detection, and facial attribute analysis. One commonly used dataset available on Kaggle is the Facial Expression Recognition 2013 (FER 2013) dataset. This dataset comprises facial images annotated with one of seven basic emotions: anger, disgust, fear, happiness, sadness, surprise, and neutral. Each image is grayscale and cropped to focus on the facial region, making it suitable for training convolutional neural networks (CNNs) and other deep learning models.

### GAN LOSS Progression
<img width="331" alt="image" src="https://github.com/BHARATH077/GENERATIVE-AI-using-GAN-and-Diffusion-Models/assets/102033875/d9f78305-77d5-417e-a802-cce0e2ab0e9d">
<img width="339" alt="image" src="https://github.com/BHARATH077/GENERATIVE-AI-using-GAN-and-Diffusion-Models/assets/102033875/ed01a09c-dc8f-4c1f-b043-5805ae886857">

### GAN results after 8 hrs
<img width="468" alt="image" src="https://github.com/BHARATH077/GENERATIVE-AI-using-GAN-and-Diffusion-Models/assets/102033875/f33c22bc-b780-4f58-aae0-f7e4d7b2323e">

### Diffusion Model results after 8 hrs
<img width="426" alt="image" src="https://github.com/BHARATH077/GENERATIVE-AI-using-GAN-and-Diffusion-Models/assets/102033875/ff4b700b-80d5-46a3-9a73-635a660214ea">


## References
[1]	H. Chen et al., “Pre-Trained Image Processing Transformer,” Proceedings of the IEEE Computer Society Conference on Computer Vision and Pattern Recognition, pp. 12294–12305, Dec. 2020, doi: 10.1109/CVPR46437.2021.01212.

[2]	H. Zhang et al., “StackGAN++: Realistic Image Synthesis with Stacked Generative Adversarial Networks,” Oct. 2017, Accessed: May 07, 2024. [Online]. Available: http://arxiv.org/abs/1710.10916

[3]	J. Ho, A. Jain, and P. Abbeel, “Denoising Diffusion Probabilistic Models,” Adv Neural Inf Process Syst, vol. 2020-December, Jun. 2020, Accessed: May 07, 2024. [Online]. Available: https://arxiv.org/abs/2006.11239v2

[4]	I. J. Goodfellow et al., “Generative Adversarial Nets,” Adv Neural Inf Process Syst, vol. 27, 2014, Accessed: May 07, 2024. [Online]. Available: http://www.github.com/goodfeli/adversarial
