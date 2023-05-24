# DL_imbalanced
Deep learning for collateral evaluation in ischemic stroke with imbalanced data


We developed an automatic and robust collateral assessment method using deep learning to mitigate the issues with the small imbalanced dataset, which can aid in the decision-making of ischemic stroke treatment strategy in clinical settings.

We adapted a pre-trained EfficientNet B0 network through transfer learning to improve collateral evaluation using slice-based and subject-level classification. Our method uses stacking and overlapping of 2D slices from a patient’s 4D computed tomography angiography (CTA) and a majority voting scheme to determine a patient’s final collateral grade based on all classified 2D MIPs. Class imbalance is handled in the evaluation process by using the focal loss with class weight to penalize the majority class.


If this code is useful for you, please consider citing:
Aktar, M., Reyes, J., Tampieri, D. et al. Deep learning for collateral evaluation in ischemic stroke with imbalanced data. Int J CARS 18, 733–740 (2023). https://doi.org/10.1007/s11548-022-02826-6
