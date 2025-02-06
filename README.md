🖼️ Image Classification with EfficientNet-B3

This project focuses on image classification using the EfficientNet-B3 model, incorporating data preprocessing and synthetic image generation to enhance model performance.

🏗️ Key Features:

Pretrained EfficientNet-B3 fine-tuned for classification.
MBConv block retraining for better feature extraction.
Additional fully connected layers for improved classification.

🔄 Data Preprocessing:

Images resized to 224x224 pixels.
Normalization applied for stable model training.
Synthetic image generation via Autoencoder to balance underrepresented classes.

🚀 Training Setup:

Optimizer: Adam (LR = 0.001)
Loss Function: CrossEntropy
Hardware: NVIDIA RTX 3050 GPU
Epochs: 15

📊 Evaluation:

F1 Score & Classification Report for performance analysis.
Challenges: Data quality and class imbalance noted.
References: EfficientNet papers, Autoencoder tutorials, PyTorch documentation.
