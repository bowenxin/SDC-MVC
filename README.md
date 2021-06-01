# SDC-MVC

This open-source repository contains the code of Self-supervised Deep Correlational Multi-view Clustering (SDC-MVC). The proposed MVC algorithm couples multi-view learning with self-supervised deep clustering in an end-to-end deep learning framework, which further facillitates the seperation of clusters. The algorithms were validated on three public datasets outperforming six state-of-the-art correlational MVC algorithms, comprehensively evaluated with NMI, ACC, HOM. 

The algorithm is accepted by International Joint Conference of Neural Network (IJCNN) 2021 in the form of oral presentation. The code will be released soon. 

![image](https://user-images.githubusercontent.com/10879680/120271189-3c068f80-c2ee-11eb-80e6-71340395f65a.png)

# Our contributions
- A novel **Self-supervised Deep Correlational (SDC) loss** function jointly exploits consensus inter-modal information and clustering-oriented discriminative information for multi-view clustering.
- A **Deep Serial Feature-level (DSF) fusion** scheme is investigated to integrate discriminative consensus and view-specific information. 

# Prerequisites
- Python (3.7)
- Sklearn
- Numpy
- Torch
- Scipy

# Citation
Xin B, Huang J, Zhou Y, Lu J, Wang X. Deep Multimodal Fusion for Diagnostic Classification. IJCNN. 2020 (Oral Presentation)
