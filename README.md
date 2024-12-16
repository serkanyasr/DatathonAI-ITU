
---

# DatathonAI  Challenge



## Challenge Overview
This repository contains the code and resources for participating in the DatathonAI qualification round, a competition focused on classifying Google Street View images to determine which Turkish city they belong to.

### Challenge Details
Participants in this challenge are tasked with developing AI models to classify images into three of Turkey's most prominent cities:

- **Istanbul**: The transcontinental metropolis bridging Europe and Asia
- **Ankara**: The modern capital city
- **Izmir**: The pearl of the Aegean Sea

This competition tests participants' abilities to identify distinct architectural styles, urban planning patterns, and geographical features that make each city unique.

### Competition Structure
This is a qualification round where the top 30 performing teams will advance to the physical finals at the Istanbul Technical University (ITU) campus.

### Objective
Your goal is to develop a model capable of accurately classifying street view images into the three target cities: Istanbul, Ankara, and Izmir.

## Getting Started

### Dataset

kaggle: https://www.kaggle.com/competitions/datathon-ai-qualification-round

The dataset contains Google Street View images of Istanbul, Ankara, and Izmir. The images are organized into training and test sets.

### Model Architecture
The project utilizes a deep learning model based on EfficientNetV2M architecture for image classification. The model is fine-tuned on the Google Street View images of the three cities. Key components include:

- **Data Augmentation**: Techniques like random cropping, resizing, flipping, brightness and contrast adjustment.
- **Transfer Learning**: Pre-trained weights from ImageNet to initialize the model, followed by custom dense layers for classification.
- **Regularization**: Techniques such as L2 regularization and dropout to prevent overfitting.

### Results
- **Training Loss**: The model's training and validation loss over epochs can be visualized in the training history plots.
- **Accuracy**: Model's performance metrics, including accuracy and validation accuracy, are tracked during training.

### Submission
After training, the model's predictions are used to generate a submission file in the required format for evaluation on the leaderboard. The predictions are formatted into a CSV file that maps filenames to predicted city labels.


## Acknowledgements
Special thanks to the DatathonAI ITU AI Club for organizing this challenge.


