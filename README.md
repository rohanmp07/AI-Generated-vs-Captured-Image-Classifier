The proliferation of AI-generated images poses significant challenges in verifying the authenticity of visual content. 
This project focuses on developing a deep learning-based classifier to distinguish between AI-generated images and real-world captured images.
Utilizing the fastai library, we built and trained a convolutional neural network (CNN) to accurately identify the source of an image.
We employed transfer learning (Knowledge Gained by one task is used to improve model performance on another related task) with pre-trained models such as ResNet, fine-tuning (updating pre-trained model with new information) them on a curated dataset of both AI-generated and captured images. 
The fastai library facilitated efficient model training, data augmentation(Generating new data from existing data), and hyperparameter optimization.
To enhance accessibility, we integrated the classifier into an interactive web application using Gradio. 
This application allows users to upload images and receive real-time predictions on whether the images are AI-generated or captured.
The classifier demonstrated high accuracy and robustness, proving effective in distinguishing between the two types of images. 
This project contributes to digital forensics, media authenticity verification, and synthetic media detection, providing a valuable tool to combat the challenges of AI-generated content.

