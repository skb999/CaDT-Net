# CaDT-Net : A Cascaded Deformable Transformer Network for Multiclass Breast Cancer Histopathological Image Classification

<p align="justify"> This paper proposes a cascaded deformable transformer network (CaDT-Net) for breast cancer 
histopathological image classification. the CaDT-Net architecture primarily consists of three parts: a pre-trained 
MaxViT as a backbone, a cascaded deformable transformer layer (CDTL), and a classification layer for multiclass 
classification of breast cancer as shown in figure below. </p>
<img src="RDTNet.jpg" alt="Architecture of CaDT-Net">
<p align="justify"> At first the histopathological image undergoes an initial passage through a backbone transformer network, 
resulting in the extraction of hierarchical feature maps F. Subsequently, these feature maps are fed into the proposed
CDTL to model wide-range feature dependencies. The CDTL introduces a cascaded deformable self-attention (CDSA) module
which leverages the extraction of salient and category-specific features from the crucial regions of the histopathological 
images. In addition, it utilizes skip connections for better feature flow within the network. The resultant feature are finally 
fed to a classification layer to classify the image into eight breast tumor types. </p>

This repository contains the CaDT-Net code. Experiments were carried out on widely used publicly available dataset: [BreaKHis](https://web.inf.ufpr.br/vri/databases/breast-cancer-histopathological-database-breakhis/)
