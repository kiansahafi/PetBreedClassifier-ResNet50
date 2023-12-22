# Oxford-IIIT Pet Dataset Classification Challenge 🐾
## Overview
a computer vision project developed for classifying dog and cat breeds using the **Oxford-IIIT Pet Dataset**. 🐶🐱

## Data Preparation📊
**Dataset:** 37 dog/cat breeds with 200 images each.  
**Augmentation:** Increased robustness through data augmentation, creating a richer dataset for model training.🔄
## Model Development🛠️
**Initial Attempts:** Custom model architectures; trialed VGG-16 and VGG-19.  
**Final Choice:** ResNet50-V2, which significantly improved accuracy.🚀  
**Architecture:** ResNet50-V2 (pre-trained, partially frozen), followed by fully connected layers, dropout, and a final output layer.  
## Training and Evaluation📈  
**Validation Accuracy:** Achieved a high accuracy (specific percentage detailed in the project).✅  
**Optimization:** Used ADAM optimizer for better performance.⚙️  
**Learning Rate Scheduler:** Implemented to optimize training process.📉  
## Results📋  

> [!TIP]
> **Validation Accuracy:** 87%  
> **Validation Loss:** 41%

Keeshond             |  Birman
:-------------------------:|:-------------------------:
  ![alt text](https://github.com/kiansahafi/PetBreedClassifier-ResNet50/blob/main/pictures/sample-1.png) |  ![alt text](https://github.com/kiansahafi/PetBreedClassifier-ResNet50/blob/main/pictures/sample-2.png)

**Confusion Matrix:** Indicates good performance, with some confusion between similar breeds.🧩  
**Sample Outputs:** Showcases the model's breed classification capabilities.👀


## Improvements🌟
**Data Distribution:** Increasing the representation of confused breeds could enhance accuracy. However, dataset limitations restrict this approach.📚  

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/kiansahafi/PetBreedClassifier-ResNet50/blob/main/pictures/confusion%20matrix.jpg">
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/kiansahafi/PetBreedClassifier-ResNet50/blob/main/pictures/confusion%20matrix.jpg">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://github.com/kiansahafi/PetBreedClassifier-ResNet50/blob/main/pictures/confusion%20matrix.jpg">
</picture>  

**Further Tuning:** Optimizing learning rate and further experimenting with model architecture and training strategies.🔧  
## How to Use🖥️
1. Clone the repo.  
2. Install dependencies (list dependencies here).  
3. Run the model (provide command or script).  
## Contributing🤝
Feel free to contribute! Open an issue or submit PRs.  

## License📝
MIT License
