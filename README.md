# Fire Detection Using Convolutional Neural Networks and Image Processing
## Overview
This project leverages advanced AI techniques, including Convolutional Neural Networks (CNNs), transfer learning, and Large Language Models (LLMs), to develop an efficient and accurate fire detection system. The model aims to enhance safety systems by providing real-time, precise fire detection using image-based data.  



## Features
CNN-based Fire Detection: Achieved 96.88% validation accuracy and an F1 score of 0.9688.  


Comparison with LLMs:  
Llama2-7B and GPT-4 Mini achieved 100% accuracy in fire detection.  
Applications: Real-world integration in smart systems for residential, commercial, and forest fire monitoring.  



## Dataset
Size: 2,000 images (1,500 fire, 500 non-fire).
Sources: Public datasets, Google Photos, Roboflow Universe.
Diversity: Varied backdrops, lighting conditions, and fire intensity levels.


## Methodology
## Data Preprocessing:
Resized images to 256x256 pixels.
Data augmentation using TensorFlow's ImageDataGenerator (flips, brightness adjustment, etc.).

## Modeling:
Used VGG16 pre-trained model for feature extraction.
Added custom fully connected layers with ReLU activation.
Fine-tuned with Adam optimizer and a learning rate of 0.001.

## LLM Integration:
Evaluated Llama2-7B and GPT-4 Mini for fire detection.
Both achieved 100% accuracy, showcasing the potential of generative AI in complex classification tasks.

## Results
CNN Performance:
Validation Accuracy: 96.88%
F1 Score: 0.9688
LLM Performance:
Llama2-7B: 100% accuracy.
GPT-4 Mini: 100% accuracy.

## Applications
Fire safety in residential and commercial spaces.
Forest fire monitoring using drones.
Integration with IoT devices for smart alerts.

## Future Work
Enhance CNN models with more complex datasets and hyperparameter tuning.
Improve computational efficiency of LLMs for deployment on edge devices.
Explore advanced architectures (e.g., transformers) for further accuracy improvements.

## References
Roboflow Universe Dataset.
Research papers on CNN and fire detection (see References in the repository).
