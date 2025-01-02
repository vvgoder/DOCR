# DOCR: Data-efficient Object Detection on Construction Sites with Reweighting and Contrastive Learning

[![Paper](https://img.shields.io/badge/Paper-PDF-red)](xxx)

DOCR is a data-efficient object detection framework specifically designed for construction site monitoring. Through innovative reweighting mechanisms and cross-batch contrastive learning, it achieves state-of-the-art performance (56.6% mAP) while maintaining real-time inference capabilities.

## Overview

Our framework addresses three critical challenges in construction site object detection:
1. Limited labeled training data availability
2. Complex spatial arrangements leading to severe occlusions
3. Similar visual appearances between different construction elements

## Key Innovations

### 1. Reweighting Mechanism
- Dual-stage reweighting strategy
- Proposal reweighting for handling partially visible objects
- Refinement reweighting for improving localization accuracy
- Enhanced spatial relationship modeling

### 2. Cross-batch Contrastive Learning
- Memory bank-based feature management
- Enhanced feature discrimination
- Efficient negative sample utilization
- Improved separation between visually similar categories

### 3. Data-efficient Architecture
- CenterNet2-based lightweight design
- Optimized for limited training data scenarios
- Real-time performance 
- Balanced accuracy and computational efficiency

## Performance Highlights

- **Detection Accuracy**: 56.6% mAP
- **Data Efficiency**: High performance with limited training samples
- **Real-time Capability**: Practical for construction site deployment


## Code Availability & Technical Details

Our implementation is built upon [Detectron2](https://github.com/facebookresearch/detectron2) (version 0.2.1). We are currently in discussions with our project stakeholders regarding the release of certain core module implementations. 

### Technical Framework
- Based on Detectron2 (v0.2.1)
- Extended with custom modules for reweighting and contrastive learning
- Optimized for construction site scenarios

### Important Notes
- Due to ongoing research projects and industrial collaborations, certain components are currently under patent application processes
- We are working to strike a balance between intellectual property protection and academic transparency
- Future code releases will focus on key algorithmic components that do not compromise intellectual property rights

### Dependencies
- Detectron2 (v0.2.1)
  - Higher versions may not be compatible
  - Please follow [Detectron2's installation instructions](https://detectron2.readthedocs.io/en/latest/tutorials/install.html) for the correct version

**Stay Updated**: Follow this repository for potential future releases and technical discussions.

---
**Note**: While we work towards making certain implementations publicly available, we welcome academic discussions and technical inquiries through the repository's issue system.



## Citation

If you find this work useful in your research, please consider citing:

```bibtex
@article{DOCR2025,
  title={Data-efficient Object Detection on Construction Sites Using Reweighting Mechanism and Cross-batch Contrastive Learning},
  author={xxx},
  journal={xxx},
  year={2025}
}
```

## Contact

For technical discussions and academic inquiries:
- Create an issue in this repository
- Email: [vvgod@seu.edu.cn]

## Acknowledgments

This work is supported by our research partners and funding agencies. Due to ongoing research projects and industrial collaborations, certain components are currently under patent application processes. We are committed to contributing to the research community while respecting intellectual property constraints.

---
**Note**: This repository currently serves as a project page. Code implementations will be gradually released as they become available. Thank you for your understanding and interest in our work.
