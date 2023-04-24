# Super Image Resolution

### Abstract:
Image super-resolution, the task of generating high-resolution images from low-resolution input, is a challenging problem in computer vision. Traditional methods often rely on paired training data, which requires high-resolution images and their corresponding low-resolution versions for supervised learning. However, obtaining such paired data can be time-consuming and labor-intensive. In this project, we propose a unique approach for image super-resolution using deep image priors and unsupervised learning.

The main idea behind this project is to use the architecture of a deep neural network itself as a prior for image restoration tasks, instead of directly training the network using paired data. The approach is based on the concept of Deep Image Prior, where a randomly initialized neural network is optimized with input noise to restore the high-resolution image from a low-resolution input. This allows for image super-resolution without the need for paired training data, making the approach more flexible and generalizable to different image restoration tasks.

The proposed method is based on unsupervised learning, where no ground truth high-resolution images are used during training. Instead, the optimization process is guided by image quality metrics, such as peak signal-to-noise ratio (PSNR), to iteratively refine the restored image. The code for this project is open source and available on GitHub, providing a framework for image super-resolution as well as other image restoration tasks, such as denoising, inpainting, and deblurring.

Experimental results show that the proposed method achieves state-of-the-art performance in terms of image quality metrics, outperforming traditional methods and other deep learning-based methods. The ability to achieve high-quality restoration results with limited training data and the flexibility to adapt to different tasks make this project unique and innovative in the field of image super-resolution research.

Keywords: Image super-resolution, deep image prior, unsupervised learning, deep neural networks, image restoration, open source.

<img width="723" alt="Screenshot 2023-04-24 at 3 18 33 PM" src="https://user-images.githubusercontent.com/68138315/233962004-5bce122a-f312-44b2-8491-96d859a0a4dc.png">
