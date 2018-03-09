# An Exploration of Neural Network Image Colorization and Processing Techniques

## Abstract

This is an exploration and comparison of different approaches to achieve automatic colorization of an uncolored image (usually a drawn black-and-white sketch) via the use of computer learning algorithms and processes. Traditionally, the coloring of a drawing has been a manual process, involving conscious decisions on behalf of the artist undertaking the task. Such things as color schemes, lighting layouts and textures have been the result of manual, intentional choices made by the human colorer. However, with the advent of advanced computer learning techniques like convolutional neural networks, these decisions can now be made by computers. Furthermore, by training neural networks on examples of art, it is possible to produce an entire colorized image with limited-to-no input from human controllers. We intend to explore and compare the workings of several implementations of computer image colorization, including observing how different training datasets affect their results. We also will explore some other ways in which computer learning and neural networks may be used to assist in creating art.

### 1. [Introduction](Intro.md)
### 2. [Simple Coloring Techniques](Simple.md)
### 3. [Colorization with Neural Networks](Colorization.md)
### 4. [Comparisons](Compare.md)
### 5. [Other Neural Artwork Processes](Other.md)
### 6. Glossary

* **ANN** - Artificial Neural Network: A network of interconnected virtual pseudo-neurons used for computer learning processes.
* **DNN** - Deep Neural Network: An ANN which has one or more "hidden" layers of nodes in between its input and output layers
* **CNN** - Convolutional Neural Network: A type of DNN where nodes apply convolutional operations to their inputs.
* **GAN** - Generative Adversarial Network: A type of CNN that uses two components, a discriminator (or image classifier) and a generator.
* **U-Net** - GAN structure where the generator component consists of an overlapped encoder and decoder structure, linked with skip connections.

### 7. Conclusion

Neural networks are a fascinating area of computer research where progress is constantly still being made. The challenge of applying neural networks to image processing tasks is already considerable, let alone trying to use those neural networks for the purposes of creating art. However, it seems there exists a suite of possible neural network designs and implementations that are ready to be used for these purposes. Convolutional Neural Networks and Conditional Generative Adversarial Networks are capable of taking a grayscale image and producing a fully colorized output; some of these network types have also been used for "super resolution" upscaling of low-resolution images. With the continuous progress being made in this field, it seems inevitable that new designs will come out that beat the performance of these methods. However, CNNs and cGANs already provide thoroughly plausible results and could become important tools for aspiring artists.

### 8. References

 1. Cheng, Zezhou, et al. “Colorization Using Neural Network Ensemble.” *IEEE Transactions On Image Processing*, vol. 26, no. 11, 2017, pp. 5491–5505. *IEEE Xplore*, [doi:10.1109/TIP.2017.2740620](http://ieeexplore.ieee.org/document/8011494/). Accessed 30 Jan. 2018.
 2. Nguyen, Tung, et al. “Image Colorization Using a Deep Convolutional Neural Network.” *Proc. of ASIAGRAPH 2016, Toyama, Japan*, 5-6 Mar. 2016, pp. 49-50. *Cornell University Library*, [arXiv:1604.07904](https://arxiv.org/abs/1604.07904). Accessed 30 Jan. 2018.
 3. Liang, Xiangguo, et al. “Deep Patch-Wise Colorization Model for Grayscale Images.” *SIGGRAPH ASIA 2016 Technical Briefs, Macao*, pp. 1–4. *ACM Digital Library*, [doi:10.1145/3005358.3005375](https://dl.acm.org/citation.cfm?doid=3005358.3005375). Accessed 30 Jan. 2018.
 4. Zhang, Richard, et al. “Real-Time User-Guided Image Colorization with Learned Deep Priors.” *ACM Transactions on Graphics (TOG)*, vol. 36, no. 4, 20 July 2017, pp. 1–11. *ACM Digital Library*, [doi:10.1145/3072959.3073703](https://dl.acm.org/citation.cfm?doid=3072959.3073703). Accessed 30 Jan. 2018.
 5. Dong, Chao, et al. “Image Super-Resolution Using Deep Convolutional Networks.” *IEEE Transactions On Pattern Analysis and Machine Intelligence*, vol. 38, no. 2, 2016, pp. 295–307. *Cornell University Library*, [arXiv:1501.00092](https://arxiv.org/abs/1501.00092). Accessed 30 Jan. 2018.
 6. Isola, Phillip, et al. “Image-to-Image Translation with Conditional Adversarial Networks.” *Cornell University Library*, [arXiv:1611.07004](https://arxiv.org/abs/1611.07004). Accessed 8 Feb. 2018.
 7. Zhang, Lvmin, et al. “Style Transfer for Anime Sketches with Enhanced Residual U-net and Auxiliary Classifier GAN.” *Cornell University Library*, [arXiv:1706.03319](https://arxiv.org/abs/1706.03319). Accessed 8 Feb. 2018.
 8. "Doug's Great Demo: 1968." *Doug Engelbart Institute.* Doug Engelbart Institute, 2018, [www.dougengelbart.org/firsts/dougs-1968-demo.html](http://www.dougengelbart.org/firsts/dougs-1968-demo.html). Accessed 8 Mar. 2018.
 9. Zhu, Jun-Yan, et al. "Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks." *Cornell University Library*, [arXiv:1703.10593](https://arxiv.org/abs/1703.10593]). Accessed 8 Mar. 2018.
 10. Ledig, Christian, et al. "Photo-Realistic Single Image Super-Resolution Using a Generative Adversarial Network." *Cornell University Library*, [arXiv:1609.04802](https://arxiv.org/abs/1609.04802). Accessed 8 Mar. 2018.
 11. Zhang, Richard, et al. "Colorful Image Colorization." *Cornell University Library*, [arXiv:1603.08511](https://arxiv.org/abs/1603.08511). Accessed 8 Mar. 2018.
 12. *Colorful Image Colorization.* Zhang, Richard, et al., 2016, [richzhang.github.io/colorization](https://richzhang.github.io/colorization/). Accessed 8 Mar. 2018.
 13. *Image-to-Image Translation with Conditional Adversarial Networks.* UC Berkeley, 2017, [phillipi.github.io/pix2pix](https://phillipi.github.io/pix2pix/). Accessed 8 Mar. 2018.
 14. *Photo-Realistic Single Image Super-Resolution Using a Generative Adversarial Network.* 2018, [github.com/tensorlayer/srgan](https://github.com/tensorlayer/srgan). Accessed 8 Mar. 2018.
 
