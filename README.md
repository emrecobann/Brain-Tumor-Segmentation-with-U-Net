# U-Net for Brain Tumor Segmentation

## Overview

This project explores the application of the U-Net architecture for automating brain tumor segmentation from MRI images. It includes a detailed study on model implementation, evaluation metrics, and results.

## Key Points

- **Objective**: Automate brain tumor segmentation to improve diagnostic accuracy and efficiency.
- **Method**: Utilize the U-Net deep learning architecture.
- **Evaluation**: Assess performance using recall, precision, and Dice coefficient metrics.
- **Outcome**: Provide reliable tumor segmentations for clinical use.


## Conclusion

In our study using the U-Net model for brain tumor segmentation, we optimized several parameters. 
Increasing the image size to 224x224 pixels improved segmentation accuracy, with a batch size of 16 chosen for efficient computation.
Data augmentation, initially explored, was excluded due to negative effects on segmentation performance. The step scheduler effectively stabilized training and improved precision.
Integrating Dice coefficient with Binary Cross-Entropy (BCE) consistently outperformed BCE alone, emphasizing the importance of shape similarity metrics.
These findings highlight our approach's potential to enhance clinical outcomes in brain tumor diagnosis and treatment planning.
