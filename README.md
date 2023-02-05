# Awesome Medical Vision Language Learning



## Contents
* [Datasets](#datasets)
* [Papers](#papers)

## Datasets

| Dataset                                                            | Year | Modality | Images |  Text     |
|--------------------------------------------------------------------|------|----------|--------|-----------|
| MIMIC-CXR[[data](https://mimic.mit.edu/docs/iv/modules/cxr/)][[paper](https://arxiv.org/pdf/1901.07042.pdf)]| 2019 | Chest X-ray | 377,110 | 227,827 |
| CheXpert[[data](https://stanfordmlgroup.github.io/competitions/chexpert)][[paper](https://arxiv.org/pdf/1901.07031.pdf)]| 2019 | Chest X-ray | 224,316 | 224,316 |
| ROCO [[data](https://github.com/razorx89/roco-dataset)][[paper](https://labels.tue-image.nl/wp-content/uploads/2018/09/AM-04.pdf)]                   | 2018 | CT, Ultrasound, X-Ray, Fluoroscopy, PET, <br> Mammography, MRI, Angiography, PET-CT | 81,825 | 81,825 |
| MedICaT[[data](https://github.com/allenai/medicat)][[paper](https://arxiv.org/pdf/2010.06000v1.pdf)]                     | 2020 | CT, Ultrasound, X-Ray, Fluoroscopy, PET, <br> Mammography, MRI, Angiography, PET-CT | 217,060 | 217,060 |




## Survey

- VLP: A Survey on Vision-Language Pre-training. arxiv 2022. [[paper](https://arxiv.org/pdf/2202.09061.pdf)]

- Vision-Language Pre-training: Basics, Recent Advances, and Future Trends. arxiv 2022. [[paper](https://arxiv.org/pdf/2210.09263.pdf)]

- Beyond Medical Imaging: A Review of Multimodal Deep Learning in Radiology. techrxiv 2022. [[paper](https://www.researchgate.net/profile/Jan-Egger-2/publication/358581125_Beyond_Medical_Imaging_A_Review_of_Multimodal_Deep_Learning_in_Radiology/links/620a1e5a7b05f82592ea5bda/Beyond-Medical-Imaging-A-Review-of-Multimodal-Deep-Learning-in-Radiology.pdf)]


## Tutorial

- Vision-Language Pretraining: Current Trends and the Future. ACL 2022.  [[link](https://vlp-tutorial-acl2022.github.io/)]

- Recent Advances in Vision-and-Language Pre-training. CVPR 2022. [[link](https://vlp-tutorial.github.io/2022/)]

## Vision Language Pretraining

### Text Encoder

| Text Encoder                                                       | Year |  Corpus                      |
|--------------------------------------------------------------------|------|------------------------------|
| [BioBERT](https://github.com/dmis-lab/biobert)                     | 2020 | PubMed                       |
| [ClinicalBERT](https://arxiv.org/abs/1904.05342)                   | 2019 | MIMIC-III                    |
| [PubMedBERT](https://dl.acm.org/doi/10.1145/3458754)               | 2022 | PubMed                       |
| [CXR-BERT](https://arxiv.org/abs/2204.09817)                       | 2022 | PubMed+MIMIC-III/CXR         |
 

### How to Train

**2023**

- [MRM] Advancing Radiograph Representation Learning with Masked Record Modeling. ICLR 2023. [[paper](https://openreview.net/forum?id=w-x7U26GM7j)][[code](https://github.com/RL4M/MRM-pytorch)]

- [BioViL-T] Learning to Exploit Temporal Structure for Biomedical Vision–Language Processing. arxiv 2023. [[paper](https://arxiv.org/pdf/2301.04558.pdf)]

- MedKLIP: Medical Knowledge Enhanced Language-Image Pre-Training. arxiv 2023. [[paper](https://arxiv.org/pdf/2301.02228.pdf)] [[code](https://chaoyi-wu.github.io/MedKLIP/)]

**2022**

- [MGCA] Multi-Granularity Cross-modal Alignment for Generalized Medical Visual Representation Learning. NIPS 2022. [[paper](http://arxiv.org/abs/2210.06044)][[code](https://github.com/fuying-wang/MGCA)]

- MedCLIP: Contrastive Learning from Unpaired Medical Images and Text. EMNLP 2022. [[paper](https://arxiv.org/pdf/2210.10163.pdf)][[code](https://github.com/RyanWangZf/MedCLIP)]
  
- [M3AE] Multi-Modal Masked Autoencoders for Medical Vision-and-Language Pre-Training. MICCAI 2022. [[paper](https://arxiv.org/pdf/2209.07098.pdf)][[code](https://github.com/zhjohnchan/M3AE)]

- Breaking with Fixed Set Pathology Recognition through Report-Guided Contrastive Training. MICCAI 2022. [[paper](https://arxiv.org/pdf/2205.07139.pdf)]

- Align, Reason and Learn: Enhancing Medical Vision-and-Language Pre-training with Knowledge. MM 2022. [[paper](https://arxiv.org/pdf/2209.07118.pdf)][[code](https://github.com/zhjohnchan/ARL)]

- [MedViLL] Multi-Modal Understanding and Generation for Medical Images and Text via Vision-Language Pre-Training. JHBI 2022. [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9894658)][[code](https://github.com/SuperSupermoon/MedViLL)]

- [REFERS] Generalized radiograph representation learning via cross-supervision between images and free-text radiology reports. Nature Machine Intelligence 2022. [[paper](https://arxiv.org/abs/2111.03452)][[code](https://github.com/funnyzhou/REFERS)]

- [BioViL] Making the Most of Text Semantics to Improve Biomedical Vision–Language Processing. ECCV 2022. [[paper](https://arxiv.org/pdf/2204.09817.pdf)]

- [LoVT] Joint learning of localized representations from medical images and reports. ECCV 2022. [[paper](https://link.springer.com/chapter/10.1007/978-3-031-19809-0_39)]

**2021**

- [Local-MI] Multimodal Representation Learning via Maximization of Local Mutual Information. MICCAI 2021. [[paper](https://link.springer.com/chapter/10.1007/978-3-030-87196-3_26)]

- GLoRIA: A Multimodal Global-Local Representation Learning Framework for Label-efficient Medical Image Recognition. ICCV 2021. [[paper](https://ieeexplore.ieee.org/document/9710099/)]

- Self-supervised Image-text Pre-training With Mixed Data In Chest X-rays. arxiv 2021. [[paper](https://arxiv.org/pdf/2103.16022.pdf)]


**2020**

- [ConVIRT] Contrastive Learning of Medical Visual Representations from Paired Images and Text. MLHC 2022. [[paper](http://arxiv.org/abs/2010.00747)][[code](https://github.com/yuhaozhang/convirt)]


**2018**

- Unsupervised Multimodal Representation Learning across Medical Images and Reports. NIPS workshop 2018. [[paper](https://arxiv.org/pdf/1811.08615.pdf)]


### How to Use

**2022**

- Medical Image Understanding with Pretrained Vision Language Models: A Comprehensive Study. arxiv 2022. [[paper](https://arxiv.org/pdf/2209.15517.pdf)]

- Adapting Pretrained Vision-Language Foundational Models to Medical Imaging Domains. NIPS workshop 2022. [[paper](http://arxiv.org/abs/2210.04133)]

**2021**

- [PubMedCLIP] Does CLIP Benefit Visual Question Answering in the Medical Domain as Much as it Does in the General Domain. arxiv 2021. [[paper](https://arxiv.org/pdf/2112.13906.pdf)][[code](https://github.com/sarahESL/PubMedCLIP)]


## Vision Language Task

Refer to [Awesome-Multimodal-Applications-In-Medical-Imaging](https://github.com/Richard88888/awesome-multimodal-in-medical-imaging) for more papers

### Segmentation

- LViT: Language meets Vision Transformer in Medical Image Segmentation. arxiv 2022. [[paper](http://arxiv.org/abs/2206.14718)]


### Generation


- RoentGen: Vision-Language Foundation Model for Chest X-ray Generation. arxiv 2022. [[paper](http://arxiv.org/abs/2211.12737)]

