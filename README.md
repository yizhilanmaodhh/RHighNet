# RHighNet
The code for the paper "Relation-Aware High-Order Interaction Network for Remote Sensing Image Change Detection"

#PyTorch implementation of Relation-aware High-order Interaction Network for Remote Sensing Image Change Detection
- **DOI**: [10.1109/TGRS.2025.3604400]

## 📝 Introduction
Remote sensing image change detection plays a vital role in ecological monitoring, urban planning, and infrastructure assessment. However, accurately identifying changes in high-resolution remote sensing imagery remains challenging due to multi-temporal imaging variations and complex backgrounds. A key limitation of existing methods is their inadequate modeling of spatio-temporal relationships, which restricts their ability to distinguish meaningful changes from irrelevant variations. To alleviate  this limitation, we propose a Relation-aware High-order Spatial Interaction Network (RHighNet), which enhances spatio-temporal feature learning through spatial, channel, and high-order relation modeling across bi-temporal images.
The proposed RHighNet consists of two key components: (1) A Temporal Relationship-Aware Module (TRAM) that captures bi-temporal dependencies via a dual-branch attention mechanism, effectively highlighting change-related features in both spatial and channel dimensions. (2) A High-Order Spatio-Temporal Interaction Module (HOSTIM) that employs recursive gated convolutions to model higher-order feature interactions, enabling robust representation of complex changes beyond two-order interactions in self-attention. Additionally, a multi-stage loss optimization strategy is introduced to stabilize training and refine feature learning progressively.
Extensive experiments on four benchmark datasets—LEVIR-CD, WHU-CD, SYSU, and CDD—demonstrate the effectiveness and superiority of our method in remote sensing image change detection.

## 🚀 Installation
Our code is implemented in **PyTorch** .

### Train and Test
```
python main_zl.py
```

For any questions, please contact: Email: hhdongxd@163.com
