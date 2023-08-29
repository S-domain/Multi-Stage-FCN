# Multi-stage fully convolutional network for precise prostate segmentation in ultrasound images
Prostate cancer is one of the most commonly diagnosed non-cutaneous malignant tumors and the sixth major cause of cancer-related death generally found in men globally. Automatic segmentation of prostate regions has a wide range of applications in prostate cancer diagnosis and treatment. It is challenging to extract powerful spatial features for precise prostate segmentation methods due to the wide variation in prostate size, shape, and histopathologic heterogeneity among patients. Most of the existing CNN-based architectures often produce unsatisfactory results and inaccurate boundaries in prostate segmentation, which are caused by inadequate discriminative feature maps and the limited amount of spatial information. To address these issues, we propose a novel deep learning technique called Multi-Stage FCN architecture for 2D prostate segmentation that captures more precise spatial information and accurate prostate boundaries. [Paper link](https://doi.org/10.1016/j.bbe.2023.08.002). 

#  The schematic illustration of the steps involved in the proposed framework
![Framework_TRUS](https://github.com/S-domain/Multi-Stage-FCN/assets/104261511/b8840505-bffa-4132-83ed-b9dcecd6bc43)

#   The overall architecture of Multi-Stage FCN
![model](https://github.com/S-domain/Multi-Stage-FCN/assets/104261511/16ad88b3-6365-4732-b28f-1ce8b4007756)

#  Segmentation results
![Stages_MRI_TRUS](https://github.com/S-domain/Multi-Stage-FCN/assets/104261511/67aaa4ed-4249-4ca2-b445-a5ff3c1ec2b7)

#   Visual comparisons of the proposed method and other CNN-based methods
![Comparism_TRUS](https://github.com/S-domain/Multi-Stage-FCN/assets/104261511/240f55aa-ce98-4017-a412-a3ee8c6987e6)

#   Requirements
Python >= 3.7 
Tensorflow >= 2.0

#   Dataset
[The Multi-site T2-weighted MRI structured dataset](https://github.com/liuquande/SAML).

[The CCH-TRUSPS dataset](https://doi.org/10.1016/j.bbe.2023.08.002).


#   Contact
mecusbans@gmail.com

#   Acknowledgments
The authors thank the patients whose data comprises these datasets (The CCH-TRUSPS dataset and The Multi-site T2-weighted MRI structured dataset) as well as the Chongqing University and Chongqing University Cancer Hospital and support.


#   Citation
Feng Y, Atabansi CC, Nie J, Liu H, Zhou H, Zhao H, Hong R, Li F, Zhou X. Multi-stage fully convolutional network for precise prostate segmentation in ultrasound images. Biocybernetics and Biomedical Engineering. 2023;43(4):586-602



