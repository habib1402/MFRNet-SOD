MFRANet: Multi-Scale Feature Refinement with Optimal Dual Attention-Driven Network for Salient Object Detection
This repository will contain the implementation of MFRANet, a novel network designed for salient object detection (SOD), once our paper is accepted and published. MFRANet leverages multiscale feature extraction, contextual spatial feature attention, channel-optimized dilated attention, and progressive feature fusion to achieve state-of-the-art (SOTA) performance in saliency detection tasks.
# Overview
In our work, we present MFRANet, which integrates EfficientNet-B7 as the backbone to extract multiscale feature maps across six reduction stages. This allows the network to provide a balanced representation of salient objects with detailed low-level and rich high-level features. Key modules include:

## Contextual Spatial Feature Attention (CSFA) Module: 
Refines spatial features while preserving edge awareness, enhancing the accuracy and precision of saliency maps.
## Channel-Optimized Dilated Attention (CODA) Module: 
Utilizes dilated convolutions with optimized dilation rates to capture multi-scale contextual information and refine channels for improved detection performance.
## Progressive Feature Fusion: 
Combines high-level semantic information and low-level spatial details through multiple skip connections, ensuring robust feature representation and effective gradient backpropagation.

To enhance the network's robustness, we train MFRANet with augmented data featuring adjustments for both high and low brightness levels, thereby improving its ability to handle diverse lighting conditions.
## Experimental Results
Extensive experiments were conducted on three benchmark datasets—ECSSD, HKU-IS, and PASCAL-S—to validate the effectiveness of our integrated modules. The results demonstrate superior accuracy and robustness compared to existing SOTA methods in the domain of salient object detection.
## Future Availability
The complete implementation of MFRANet, including code, pretrained models, and detailed usage instructions, will be made available in this repository upon acceptance and publication of our paper. We appreciate your interest and patience.
## Citation
Once our paper is published, we will provide the appropriate citation information here for referencing our work.
## Contact
For questions regarding the research or future code release, please contact Habib Khan.

