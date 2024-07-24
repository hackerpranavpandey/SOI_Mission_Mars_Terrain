# SOI_Mission_Mars_Terrain
# Mission Mars Terrain Classification

This repository contains the code and models used for the Mission Mars Terrain Classification project. The goal of this project is to classify different types of terrain on Mars using deep learning models.

## Tech Stack

- **Python**
- **PyTorch**
- **NumPy**
- **Pandas**

## Project Structure

- `Train_ResNet152.ipynb`: Notebook for training the ResNet152 model.
- `Test_ResNet152.ipynb`: Notebook for testing the ResNet152 model on the test dataset.
- `MissionMarsTerrain_submission.csv`: Final predictions on the test dataset.

## Models Used

The following models were explored during the project:

- Convolutional Neural Networks (CNNs)
- Vision Transformer (ViT)
- DenseNet
- ResNet18
- EfficientNet

After extensive experimentation, **ResNet152** was chosen for the final model due to its high validation accuracy.

## How to Use

1. **Training the Model**: Open `Train_ResNet152.ipynb` and run all cells to train the ResNet152 model.
2. **Testing the Model**: Open `Test_ResNet152.ipynb` and run all cells to test the model on the test dataset.
3. **Final Predictions**: The final predictions can be found in `MissionMarsTerrain_submission.csv`.

## Results

The final model achieved high validation accuracy and the predictions on the test dataset are provided in the `MissionMarsTerrain_submission.csv` file.

## Acknowledgements

- This project uses models and libraries from PyTorch.
- Special thanks to the contributors and the open-source community.
