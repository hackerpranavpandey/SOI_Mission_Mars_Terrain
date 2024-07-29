# SOI_Mission_Mars_Terrain

## MIT License

## Copyright (c) 2024 Pranav Kumar Pandey

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


# Mission Mars Terrain Classification

This repository contains the code and models used for the Mission Mars Terrain Classification project. The goal of this project is to classify different types of terrain on Mars using deep learning models.

## Tech Stack

- **Python**
- **PyTorch**
- **NumPy**
- **Pandas**
- **Matplotlib**
  

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
