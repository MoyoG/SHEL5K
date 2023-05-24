# SHEL5K: An Extended Dataset and Benchmarking for Safety Helmet Detection

<p align="center" width="100%">
    <img width="100%" src="https://github.com/MoyoG/SHEL5K/assets/73123564/7b414a5d-c645-406a-aa82-5cf95d43bb08">
</p>

Wearing a safety helmet is important in construction and manufacturing industrial activities to avoid unpleasant situations. This safety compliance can be ensured by developing an automatic helmet detection system using various computer vision and deep learning approaches. Developing a deep learning-based helmet detection model usually requires an enormous amount of training data. However, there are very few public safety helmet datasets available in the literature, in which most of them are not entirly labeled, and the labeled one contains fewer classes. This paper presents the SHEL5K (Safety HELmet dataset with 5K images) dataset, an enhanced version of the [SHD (Safety Helmet Detection) dataset](https://www.kaggle.com/datasets/andrewmvd/hard-hat-detection). It has 3 classes that numerous objects incompletely label. The main aim of the proposed study is to (1) completed the missing labels, (2) increased the number of classes from 3 to 6.

**The result of YOLOv7 model on SHEL5K dataset**

https://github.com/MoyoG/SHEL5K/assets/73123564/1d1baea2-ac59-4d91-b36d-b07c2186fe12

# Classes
- Helmet
- Head
- Head with helmet
- Person with helmet
- Person without helmet
- Face

# Dataset

- [Click to download the SHEL5K dataset ](https://data.mendeley.com/datasets/9rcv8mm682) 
- [Click to download the paper](https://www.mdpi.com/1424-8220/22/6/2315)

# Experimental results

The proposed dataset is randomly divided into training and testing sets. The training set contains a total of 4000 (80%) images while the testing set contains 1000 (20%) images.

**Result of state-of-the-art models on SHEL5K dataset**
<p align="center" width="100%">
    <img width="100%" src="https://github.com/MoyoG/SHEL5K/assets/73123564/83d9ede8-0b8b-4505-a944-61cc2ae62ff9">
</p>

**The result of k-fold cross-validation on the SHEL5K dataset using the YOLOR model**

<p align="center" width="100%">
    <img width="100%" src="https://github.com/MoyoG/SHEL5K/assets/73123564/c99c99b6-44a4-4749-b1dd-95b7a511cec0">
</p>

# Citation
```bibtex
@article{Otgonbold2022,
  doi = {10.3390/s22062315},
  url = {https://doi.org/10.3390/s22062315},
  year = {2022},
  month = mar,
  publisher = {{MDPI} {AG}},
  volume = {22},
  number = {6},
  pages = {2315},
  author = {Munkh-Erdene Otgonbold and Munkhjargal Gochoo and Fady Alnajjar and Luqman Ali and Tan-Hsu Tan and Jun-Wei Hsieh and Ping-Yang Chen},
  title = {{SHEL}5K: An Extended Dataset and Benchmarking for Safety Helmet Detection},
  journal = {Sensors}
}
