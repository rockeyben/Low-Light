# Low-Light
Low light &amp; Unpair training


## Traditional

- BIMEF(北大深研院)：A Bio-Inspired Multi-Exposure Fusion Framework for Low-light Image Enhancement [Project](https://github.com/baidut/BIMEF)

- Ying：A New Image Contrast Enhancement Algorithm Using Exposure Fusion Framework [Project](https://github.com/AndyHuang1995/Image-Contrast-Enhancement)

- LIME：Low-light IMage Enhancement via Illumination Map Estimation [Project](https://sites.google.com/view/xjguo/lime)

- NPE：Naturalness Preserved Enhancement Algorithm for Non-Uniform Illumination Images 
[Project](https://shuhangwang.wordpress.com/2015/12/14/naturalness-preserved-image-enhancement-using-a-statistical-lightness-variation-prior/)

- SRIE：A weighted variational model for simultaneous reflectance and illumination estimation
[Project](https://xueyangfu.github.io/)

- MF：A Fusion-based Enhancing Method for Weakly Illuminated Images
[Projetc](https://xueyangfu.github.io/)

## Deep Learning

- Deep Retinex Decomposition for Low Light Enhancement **(BMVC18)**
[Paper](https://arxiv.org/abs/1808.04560)

- MBLLEN: Low Light Image/Video Enhancement using CNNs **(BMVC18)**
[Paper](http://bmvc2018.org/contents/papers/0700.pdf)

- Learning to see in the dark **(CVPR18)**
[Paper](https://arxiv.org/abs/1805.01934)
[Code](https://github.com/cchen156/Learning-to-See-in-the-Dark)


## Unpair learning

- Deep Photo Enhancer **(CVPR18)**
[Paper](https://www.cmlab.csie.ntu.edu.tw/project/Deep-Photo-Enhancer/CVPR-2018-DPE.pdf)

- CycleGAN : Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks **(CVPR18)**
[Paper](https://arxiv.org/abs/1703.10593)
[Code](https://github.com/vanhuyz/CycleGAN-TensorFlow)

- AugCGAN: Augmented CycleGAN 
[Paper](https://arxiv.org/pdf/1802.10151.pdf)

- WISPE: Weakly Supervised Photo Enhancer for Digital Cameras **(CVPR18)**
[Paper](https://arxiv.org/pdf/1709.01118.pdf)

# Denoise

- Image Blind Denoising With Generative Adversarial Network Based Noise Modeling **(CVPR18)**
[Paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Chen_Image_Blind_Denoising_CVPR_2018_paper.pdf)




# Dataset

- NEXET vehicle dataset

  - [link](https://www.getnexar.com/challenge-2/#)
  - quantity: Training 50K, Testing 41K
  - resolution: 1280x720
  - ratio: Day - Night (about 50% each)
  - scene: road, car

  | Night                                                        | Day                                                          |
  | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | ![](.\images\frame_05c3e17847ff03feac36c558ae4899f2_10bf5f7edad1d53ef9e4e78c21bb8631_0-1280_720.jpg) | ![](.\images\frame_35a791b1-a5b8-4a69-877e-663e7c0540f7_00011-1280_720.jpg) |

- KAIST dataset

  - [link](https://soonminhwang.github.io/rgbt-ped-detection/data/)
  - quantity: Training 50K, Testing 45K
  - ratio: Day - Night (about 60% - 40%)
  - resolution: 640x512
  - feature: with extra **thermal** annotation
  - scene: road, campus, downtown

  | Night                    | Thermal                          | Day                      |
  | ------------------------ | -------------------------------- | ------------------------ |
  | ![](.\images\I00011.jpg) | ![](.\images\I00011_thernal.jpg) | ![](.\images\I00275.jpg) |

- Adobe 5K

  - [link](https://data.csail.mit.edu/graphics/fivek/)
  - quantity: 5K
  - ratio: Day(100%)
  - resolution: 4000x2000
  - feature: high resolution, high quality day time pictures

  | Day                                         | Day                                        |
  | ------------------------------------------- | ------------------------------------------ |
  | ![](.\images\蜂蜜浏览器_a0006-IMG_2787.jpg) | ![](.\images\蜂蜜浏览器_a0025-kme_298.jpg) |