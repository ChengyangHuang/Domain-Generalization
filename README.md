# Domain Generalization Review
This repository aims to summarize the papers on domain generalization for non-image/sequence data. A general review on domain generalization can be found in https://github.com/amber0309/Domain-generalization.

## Table of Contents

- [Literatures](#Literatures)
  - [Methods](#Methods)
  - [Pure Computer Vision Methods](#Pure-Computer-Vision-Methods)
- [Datasets](#Datasets)
 
## Literatures

### Methods

- **(MDA) Domain Generalization via Multidomain Discriminant Analysis**   
Shoubo Hu, Kun Zhang, Zhitang Chen, Laiwan Chan. _(UAI 2019)_    
`#classification` `#kernel` `#feature-alignment`    
[[paper]](http://auai.org/uai2019/proceedings/papers/101.pdf)
[[code]](https://github.com/amber0309/Multidomain-Discriminant-Analysis)

- **(CIDG) Domain Generalization via Conditional Invariant Representation**  
Ya Li, Mingming Gong, Xinmei Tian, Tongliang Liu, Dacheng Tao. _(AAAI 2018)_   
`#classification`  `#kernel` `#feature-alignment`     
[[paper]](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/viewFile/16595/16558)
[[code]](https://mingming-gong.github.io/papers/CIDG.zip)

- **(SCA) Scatter Component Analysis: A Unified Framework for Domain Adaptation and Domain Generalization**   
Muhammad Ghifary, David Balduzzi, W. Bastiaan Kleijn, Mengjie Zhang. _(TPAMI 2017)_       
`#classification` `#kernel` `#feature-alignment`    
[[paper]](https://ieeexplore.ieee.org/document/7542175)

- **(MTL) Domain Generalization by Marginal Transfer Learning**   
Gilles Blanchard, Aniket Anand Deshmukh, Urun Dogan, Gyemin Lee, and Clayton Scott. _(arXiv 2017)_   
`#classification` `#regression` `#kernel` `#feature-augmentation`   
[[paper]](https://arxiv.org/abs/1711.07910) 
[[code]](https://github.com/aniketde/DomainGeneralizationMarginal)

- **(DICA) Domain Generalization via Invariant Feature Representation**   
Krikamol Muandet, David Balduzzi, Bernhard Schölkopf _(ICML 2013)_    
`#classification` `#regression` `#kernel` `#feature-alignment`    
[[paper]](http://proceedings.mlr.press/v28/muandet13.html)

- **Generalizing from Several Related Classification Tasks to a New Unlabeled Sample**  
Gilles Blanchard, Gyemin Lee, and Clayton Scott. _(NIPS 2011)_   
`#classification` `#kernel`   
[[paper]](https://papers.nips.cc/paper/2011/hash/b571ecea16a9824023ee1af16897a582-Abstract.html)

### Pure Computer Vision Methods
- **Rethinking Domain Generalization Baselines**    
Francesco Cappio Borlino, Antonio D'Innocente, and Tatiana Tommasi. _(arXiv 2021)_   
`#classification` `#CNN` `#data-augmentation`  
[[paper]](https://arxiv.org/abs/2101.09060) 

- **Domain Generalization via Entropy Regularization**    
Shanshan Zhao, Mingming Gong, Tongliang Liu, Huan Fu, Dacheng Tao. _(NIPS 2020)_   
`#classification` `#CNN` `#feature-alignment` `#adversarial` `#entropy`   
[[paper]](https://proceedings.neurips.cc/paper/2020/hash/b98249b38337c5088bbc660d8f872d6a-Abstract.html)
[[code]](https://github.com/sshan-zhao/DG_via_ER)

- **(GCFN) Generalized Convolutional Forest Networks for Domain Generalization and Visual Recognition**    
Jongbin Ryu, Gitaek Kwon, Ming-Hsuan Yang, Jongwoo Lim. _(ICLR 2020)_   
`#classification` `#CNN` `#ensemble` `#feature-alignment`   
[[paper]](https://iclr.cc/virtual_2020/poster_H1lxVyStPH.html)

- **(CSD) Efficient Domain Generalization via Common-Specific Low-Rank Decomposition**    
Vihari Piratla, Praneeth Netrapalli, Sunita Sarawagi. _(ICML 2020)_   
`#classification` `#CNN` `#decomposition`   
[[paper]](http://proceedings.mlr.press/v119/piratla20a.html)
[[code]](https://github.com/vihari/csd)

- **(CIDDG) Deep Domain Generalization via Conditional Invariant Adversarial Networks**   
Ya Li, Xinmei Tian, Mingming Gong, Yajing Liu, Tongliang Liu, Kun Zhang, Dacheng Tao. _(ECCV 2018)_   
`#classification` `#CNN` `#feature-alignment` `#adversarial`    
[[paper]](https://openaccess.thecvf.com/content_ECCV_2018/html/Ya_Li_Deep_Domain_Generalization_ECCV_2018_paper.html)
[[code]](http://staff.ustc.edu.cn/~xinmei/publications_pdf/2018/code-YaLi.zip)

## Datasets
### Non-Image Datasets
#### Synthetic datasets

### Image Datasets

## TODOes
- https://github.com/amber0309/Domain-generalization
- domain adaption survey https://ieeexplore.ieee.org/document/7078994
- Catergorization
  - Feature Alignment, Meta-Learning, Self-supervised, Data Augmentation (https://arxiv.org/abs/2101.09060)
  - domain erasure, domain perturbed, data augmentation, and meta-learning, Decomposition (https://arxiv.org/pdf/2003.12815.pdf)
- SVM
  - http://people.eecs.berkeley.edu/~tinghuiz/papers/eccv2012.pdf
  - Exploiting low-rank structure from latent domains for domain generalization
- Deep Learning Methods
  - Domain generalization for object recognition with multi-task autoencoders
  - Unified deep supervised domain adaptation and generalization.
  - Domain generalization with adversarial feature learning
  - Deeper, broader and artier domain generalization.
