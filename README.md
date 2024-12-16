# U-Net Segmentation & Denoising

This project demonstrates using a U-Net architecture with PyTorch for image segmentation and denoising tasks. It includes segmenting nuclei in microscopy images and removing noise from natural images.

## **Project Highlights**
- Implemented a U-Net model for both semantic segmentation and image denoising.
- Trained the model on microscopy and natural image datasets.
- Evaluated the model's performance using metrics like Dice Score, F1-Score, and PSNR.
- Visualized results with segmented masks and denoised outputs.

## **Key Strategies**
- **Model Design:** Used a U-Net architecture with skip connections for better feature preservation.
- **Data Augmentation:** Applied transformations like rotation, flipping, and noise injection for robust training.
- **Loss Functions:** Used a combination of Dice Loss and Binary Cross-Entropy for segmentation tasks.
- **Optimization:** Tuned learning rates, batch sizes, and employed early stopping for efficient training.

## **Achievements**
- Accurate segmentation of nuclei in microscopy images.
- Effective denoising of natural images with minimal detail loss.
- Flexible and scalable implementation suitable for various image processing tasks.

Happy Coding!
