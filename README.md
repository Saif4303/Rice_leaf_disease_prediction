# Rice Leaf Disease Detection using CNN

This project focuses on utilizing Convolutional Neural Networks (CNN) to detect various diseases in rice leaves. The dataset comprises 120 images, with 40 images each for Bacterial leaf blight, Brown spot, and Leaf smut disease.

## Dataset
The dataset consists of labeled images of rice leaves affected by different diseases. Each category (Bacterial leaf blight, Brown spot, Leaf smut disease) contains 40 images, totaling 120 images.

## Models and Results

### 1. Main CNN Model
- **Accuracy:** 73%

### 2. Hyperparameter Tuning Model
- **Learning Rate:** 0.0001
- **Accuracy:** 84%
- **Observation:** Accuracy deteriorates with an increase in learning rate.

### 3. Data Augmentation Model
- **Accuracy:** 68%
- **Observation:** Data augmentation didn't significantly improve accuracy compared to the main CNN model.

### 4. Multilayer Perceptron (MLP)
- **Observation:** MLP was unable to accurately classify all disease categories.

## Conclusion
- Among the models tested, the CNN with Hyperparameter Tuning yielded the highest accuracy of 84%.
- The main CNN model provides a baseline accuracy of 73%.
- Data augmentation showed some improvement but not as significant as hyperparameter tuning.
- The MLP model wasn't effective in identifying all disease classifications.
- Therefore, the CNN with hyperparameter tuning is recommended for accurate rice leaf disease detection.
