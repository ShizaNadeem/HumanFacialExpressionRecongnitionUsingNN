# Human Facial Expression Recognition using Neural Networks
## Description
This project focuses on the implementation of Human Facial Expression Recognition (FER) using neural networks. Various optimization techniques such as Adam and RMSprop are employed to train the models. The project includes different configurations:
1. Models trained with weights using Adam optimizer.
2. Models trained with weights using RMSprop optimizer.
3. Models trained without pre-trained weights using Adam optimizer.
4. Models trained without pre-trained weights using RMSprop optimizer.
5. Models with certain layers frozen during training to preserve pre-trained weights while using Adam optimizer.

## Project Structure
- `data/` : Contains the dataset used for training and testing the models.
- `models/` : Directory where trained models and weights are saved.
- `notebooks/` : Jupyter notebooks for training and evaluating the models.
- `src/` : Source code for model architecture, data processing, and training scripts.
- `results/` : Directory for saving results, such as accuracy and loss plots.

## Optimizers and Configurations
1. **With Weights using Adam**
   - Pre-trained weights are loaded, and the Adam optimizer is used for training.

2. **With Weights using RMSprop**
   - Pre-trained weights are loaded, and the RMSprop optimizer is used for training.

3. **Without Weights using Adam**
   - Models are initialized without pre-trained weights, and the Adam optimizer is used for training.

4. **Without Weights using RMSprop**
   - Models are initialized without pre-trained weights, and the RMSprop optimizer is used for training.

5. **With Weights Layers Freeze**
   - Certain layers are frozen to preserve pre-trained weights, and the remaining layers are trained using the Adam optimizer.

## Usage

1. **Training the Models**
   - To train the models, navigate to the `notebooks/` directory and open the respective Jupyter notebooks.
   - Follow the instructions within the notebooks to start the training process.

2. **Evaluating the Models**
   - Use the evaluation scripts in the `src/` directory to test the trained models on the test dataset.
   - Results and performance metrics will be saved in the `results/` directory.

## Results
- The performance of each model is evaluated based on accuracy, loss, and confusion matrices.
- Results are saved in the `results/` directory for comparison and analysis.
