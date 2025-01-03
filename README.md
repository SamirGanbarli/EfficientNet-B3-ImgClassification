# EfficientNet-B3-ImgClassification
Image Classifition with EfficientNet B3 model 
This project focuses on image classification using the EfficientNet-B3 model and data preprocessing techniques to enhance model performance. Key steps include:

Data Preprocessing:
Images resized to 224x224 pixels.
Normalization applied for stable model training.
Synthetic images generated using Autoencoder to balance underrepresented classes (Generated images are similar to the ones that belong to the corresponding class).

Model Architecture:
Pretrained EfficientNet-B3 model fine-tuned for the dataset.
Additional fully connected layers added for classification.
Selective retraining of MBConv block weights.

Training:
Optimizer: Adam, Learning Rate: 0.001.
Loss Function: CrossEntropy.
Training conducted over 15 epochs using an NVIDIA RTX 3050 GPU

Evaluation:
F1 Score and Classification Report highlight model performance.
Challenges with data quality and underrepresented classes noted.
References include EfficientNet papers, Autoencoder tutorials, and PyTorch documentation
