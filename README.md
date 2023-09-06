<img src="https://github.com/mahyarmohammadimatin/Grapevine_Leaves_Classification/blob/main/pic.PNG">

This project aims to classify five classes of grapevine leaves using pre-trained models and transfer learning techniques.
By leveraging the power of autoencoders, we explore the impact of dimensionality reduction and data enhancement by image generation on classification accuracy.
The evaluation metric used is 10-fold cross-validation.

## Libraries and Frameworks

PIL: Python Imaging Library for image manipulation

pandas: Data manipulation and analysis library

numpy: Numerical computing library

tensorflow: Deep learning framework

matplotlib: Data visualization library

scikit-learn: Machine learning library

keras: Deep learning library

seaborn: Statistical data visualization library

## main sections

Data Preparation: Loading the grapevine leaves dataset, organizing the data, and creating a dataframe.

Data Augmentation: Augmenting the images using various transformations to increase the diversity of the training data.

Autoencoder Implementation: Constructing an autoencoder model with multiple layers for dimensionality reduction.

Model Training: Training pre-trained models (VGG19, ResNet50, EfficientNetB3) using transfer learning and the grapevine leaves dataset.

Model Evaluation: Evaluating the trained models using 10-fold cross-validation and measuring accuracy.

Results Analysis: Analyzing the performance of the models using confusion matrices and visualizations.

Image generation & test again: Generate more sample for our models.

## Models Accurecy
VGG19: 69%

ResNet50: 69%

EfficientNetB3: 76%

EfficientNetB3 after using image generation: 92%
