## LandCover_Classification
This project compares the performance of two different neural networks: **a custom built CNN** and a **pre-trained ResNET model** on the UC Merced Land Use Dataset.

## Dataset Used
- **Source:** UC Merced Land Use Dataset by Abdul Hasib Uddin  
- **Structure:** 21 classes with 100 RGB TIFF images each, resolution: 256x256  
- **Classes:** airplane, forest, harbor, overpass, buildings, etc.

## Model Specifications
**CNN**
- 2 convolutional layers
- ReLU activation function
- Max pooling
- Fully connected classifier

**ResNET**
- pre-trained
- Residual connections that help mitigate the vanishing gradient problem.

## Results

| Model       | Test Accuracy |
|-------------|---------------|
| Simple CNN  | 47.62%        |
| ResNet18    | 88.89%        |
