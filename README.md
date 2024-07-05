# MFRANet: Multi-Scale Feature Refinement with Optimal Dual Attention-Driven Network for Salient Object Detection

This repository contains the implementation of MFRANet, a novel network designed for salient object detection (SOD). MFRANet leverages multiscale feature extraction, contextual spatial feature attention, channel-optimized dilated attention, and progressive feature fusion to achieve state-of-the-art (SOTA) performance in saliency detection tasks.

## Overview

In this paper, we present MFRANet, which integrates EfficientNet-B7 as the backbone to extract multiscale feature maps across six reduction stages. This allows the network to provide a balanced representation of salient objects with detailed low-level and rich high-level features. Key modules include:

- **Contextual Spatial Feature Attention (CSFA) Module:** Refines spatial features while preserving edge awareness, enhancing the accuracy and precision of saliency maps.
  
- **Channel-Optimized Dilated Attention (CODA) Module:** Utilizes dilated convolutions with optimized dilation rates to capture multi-scale contextual information and refine channels for improved detection performance.
  
- **Progressive Feature Fusion:** Combines high-level semantic information and low-level spatial details through multiple skip connections, ensuring robust feature representation and effective gradient backpropagation.

To enhance the network's robustness, we train MFRANet with augmented data featuring adjustments for both high and low brightness levels, thereby improving its ability to handle diverse lighting conditions.

## Experimental Results

Extensive experiments were conducted on three benchmark datasets—ECSSD, HKU-IS, and PASCAL-S—to validate the effectiveness of our integrated modules. The results demonstrate superior accuracy and robustness compared to existing SOTA methods in the domain of salient object detection.

## Usage

### Requirements

- Python 3
- PyTorch
- Other dependencies as specified in `requirements.txt`

### Installation

1. Clone the repository:

2. Install dependencies:

### Training

To train the MFRANet on your own dataset or the provided benchmarks, modify the training script accordingly and run:

### Evaluation

To evaluate the pretrained MFRANet on test data:

### Pretrained Models

Pretrained models on ECSSD, HKU-IS, and PASCAL-S datasets are available [here](link_to_pretrained_models).

## Citation

If you find MFRANet or this repository useful for your research, please consider citing our paper:

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Mention any acknowledgments here, such as funding sources, inspiration from other projects, etc.

## Contact

For questions or issues regarding the code, please contact [Your Name](mailto:youremail@example.com).

