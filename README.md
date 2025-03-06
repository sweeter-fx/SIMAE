### Style-Invariant Multi-axis Attentive Embedding for Visible-Infrared Person Re-Identification

Authors: [kai Yuan](), [Shidu Dong*](),[Qiyue Ran]()，[Ting wen]()

### Abstract:

Visible-Infrared Person Re-identification (VI-ReID) is a challenging cross-modal retrieval task due to the significant modality discrepancies between heterogeneous images. Existing methods primarily focus on embedding modality-shared information into a common space to bridge the modality gap. However, the extracted modality-shared features are often insufficient, leading to limited identity-related discriminative power. To address these issues, we propose a novel Style-Invariant Multi-axis Attentive Embedding framework (SIMAE) for VI-ReID. SIMAE learns style-invariant modality-shared features by incorporating an Enhanced Styleinvariant Feature module (ESF), which leverages style-invariant weight maps to guide channel and spatial attention. Furthermore, a Multi-axis Attentive Embedding module (MAE) is introduced to collaboratively embed the style-invariant features into a shared space, modeling multi-axis information across height, width, and channel dimensions. Comprehensive experiments on the SYSU-MM01 and RegDB datasets demonstrate that SIMAE outperforms most state-of-the-art methods, achieving robust performance and high accuracy in VI-ReID tasks.

![image](https://github.com/sweeter-fx/SIMAE/blob/main/images/framework.png)

### Environmental requirements:

python==3.8

PyTorch == 1.13.0

ignite == 0.2.1

torchvision == 0.4.0

### Results:
SYSU-MM01:
![image](https://github.com/sweeter-fx/SIMAE/blob/main/images/Result_1.png)
