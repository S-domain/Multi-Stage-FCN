# Multi-stage fully convolutional network for precise prostate segmentation in ultrasound images
Prostate cancer is one of the most commonly diagnosed non-cutaneous malignant tumors and the sixth major cause of cancer-related death generally found in men globally. Automatic segmentation of prostate regions has a wide range of applications in prostate cancer diagnosis and treatment. It is challenging to extract powerful spatial features for precise prostate segmentation methods due to the wide variation in prostate size, shape, and histopathologic heterogeneity among patients. Most of the existing CNN-based architectures often produce unsatisfactory results and inaccurate boundaries in prostate segmentation, which are caused by inadequate discriminative feature maps and the limited amount of spatial information. To address these issues, we propose a novel deep learning technique called Multi-Stage FCN architecture for 2D prostate segmentation that captures more precise spatial information and accurate prostate boundaries. [Paper link](https://doi.org/10.1016/j.bbe.2023.08.002). 

#  The schematic illustration of the steps involved in the proposed framework
![Framework_TRUS](https://github.com/S-domain/Multi-Stage-FCN/assets/104261511/b8840505-bffa-4132-83ed-b9dcecd6bc43)

#   The overall architecture of Multi-Stage FCN
[model.pdf](https://github.com/S-domain/Multi-Stage-FCN/files/12461350/model.pdf)

#  Segmentation results
![Stages_MRI_TRUS](https://github.com/S-domain/Multi-Stage-FCN/assets/104261511/67aaa4ed-4249-4ca2-b445-a5ff3c1ec2b7)

#   Visual comparisons of the proposed method and other CNN-based methods
![Comparism_TRUS](https://github.com/S-domain/Multi-Stage-FCN/assets/104261511/240f55aa-ce98-4017-a412-a3ee8c6987e6)

#   Requirements
Python >= 3.7 
Tensorflow >= 2.0

#   Dataset
[The Multi-site T2-weighted MRI structured dataset](https://pages.github.com/).


#   Contact
mecusbans@gmail.com

#   Acknowledgments
The authors thank the patients whose data comprises this dataset (The CCH-TRUSPS dataset and The Multi-site T2-weighted MRI structured dataset) as well as the Chongqing University and Chongqing University Cancer Hospital and support.


#   Citation
@article{feng2023multi,
title={Multi-stage fully convolutional network for precise prostate segmentation in ultrasound images},
author={Feng, Yujie and Atabansi, Chukwuemeka Clinton and Nie, Jing and Liu, Haijun and Zhou, Hang and Zhao, Huai and Hong, Ruixia and Li, Fang and Zhou, Xichuan},
journal={Biocybernetics and Biomedical Engineering},
volume={43},
pages={586–602},
year={2023},
publisher={Elsevier}
}

[Uploading @article{FENG2023586,
title = {Multi-stage fully convolutional network for precise prostate segmentation in ultrasound images},
journal = {Biocybernetics and Biomedical Engineering},
volume = {43},
number = {3},
pages = {586-602},
year = {2023},
issn = {0208-5216},
doi = {https://doi.org/10.1016/j.bbe.2023.08.002},
url = {https://www.sciencedirect.com/science/article/pii/S0208521623000402},
author = {Yujie Feng and Chukwuemeka Clinton Atabansi and Jing Nie and Haijun Liu and Hang Zhou and Huai Zhao and Ruixia Hong and Fang Li and Xichuan Zhou},
}S0208521623000402.bib…]()
