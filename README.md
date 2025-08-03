# grain-boundary-detection-using-U-net-algorithm
**Overview**

This repository presents an implementation of the U-Net deep learning architecture for image segmentation tasks. U-Net is widely used for biomedical image segmentation but is equally applicable to other image analysis problems where pixel-wise classification is required.
The project includes all the necessary code for training, validating, and evaluating the U-Net model using custom grayscale image datasets and their corresponding segmentation masks.

**Features:**
   **U-Net Architecture:** Encoder-decoder model with skip connections for accurate segmentation.
   **Configurable Training:** Easily adjustable parameters (epochs, batch size, learning rate, etc.).
   **Data Augmentation:** Uses ImageDataGenerator for on-the-fly augmentation.
    **Evaluation Metrics:** Calculates and plots accuracy, loss, confusion matrix, and more.
    **Visualization:** Training history, predictions, and comparison plots included.
    **Model Saving:** Option to save best models with callbacks.
    **Modular Code:** Organized sections for configuration, data loading, model building, training, and evaluation.
