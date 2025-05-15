# Improvising PointNet Architecture for 3D Image Classification

## Description
In this project, we enhanced the PointNet architecture for improved fine-grained geometric feature extraction and classification accuracy in 3D point cloud data. Key improvements included introducing the PMFI (Point-based Multi-scale Feature Interaction) module for better local and global feature modeling and exploring self-supervised learning techniques like contrastive learning to reduce dependency on labeled data.

## Point Cloud
![Point Cloud Image](https://github.com/user-attachments/assets/0f0655e1-a555-4493-b80d-6ec7c78764dc)
)
## Enchanced PointNet Architecture With PMFI Integration
![Enchanced PointNet Architecture With PMFI Integration](https://github.com/user-attachments/assets/3d2274d3-c909-4d42-be9d-32fa7351e8f4)

## Key Contributions
- Investigated limitations of the original PointNet in local feature extraction.
- Enhanced PointNet's capabilities with the PMFI module, dynamically modeling local geometry using k-NN graphs and parallel 1D convolutions.
- Applied self-supervised learning (e.g., SimCLR) to pre-train PointNet, learning richer features with minimal manual annotations.
- Achieved a classification accuracy of 90.56%, surpassing the baseline PointNet's performance.

## Applications
- 3D Object Recognition for CAD models and LiDAR scans in autonomous vehicles and robotics.
- Point cloud segmentation for scene understanding.

## Technologies Used
- PointNet Architecture
- KNN Graph Construction
- PMFI Module Integration
- Self-Supervised Learning (Contrastive Learning, SimCLR)

## Challenges & Learnings
- Addressed computational overhead introduced by multi-scale processing and k-NN.
- Balanced accuracy improvement with increased memory usage.

## Collaborators
- Akshat Pratap Singh, Archit Dhakar



