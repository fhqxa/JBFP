#JBFP: Joint Background-Foreground Perception for Fine-grained Few-shot Learning

#Abstrast
Fine-grained Few-shot Learning (FFL) aims to tackle the challenge of classifying categories with scarce labeled data and nuanced inter-class distinctions.
However, most FFL models exhibit a bias towards readily available background
Shortcut Learning (SL) knowledge and lack attention to indistinguishable foreground object within Regions of Interest (ROI). In this paper, we present a Joint
Background-Foreground Perception (JBFP) approach to address these two challenges. First, we present the Background Shortcut Learning Mitigating (BSLM)
data augmentation submodule to alleviate the reliance on background SL knowledge. BSLM assesses and eliminates redundant background SL areas by utilizing
3D depth maps and semantic complexity information from the data. Second, we
propose the Foreground in Region of Interest Promoting (FRIP) spatial attention
submodule to enhance the model attention on foreground ROI knowledge. FRIP
localizes the ROI areas and assigns higher weight to foreground object local features by employing object detection and spatial attention methods. Our experiments evaluate the effectiveness of JBFP on three widely used FFL classification
benchmarks. Specifically, JBFP achieves at least 2.1%, 1.4%, and 1.0% improvements over other models on CUB-200-2011, Stanford Dogs, and Stanford Cars at
5-way 1-shot setting. The code is available at https://github.com/fhqxa/JBFP.
[Model.pdf](https://github.com/user-attachments/files/15622071/Model.pdf)

#Acknowledgement 
This repo benefits from SOD,MobileNet-SSD,and RENet. Thanks for thier works.
