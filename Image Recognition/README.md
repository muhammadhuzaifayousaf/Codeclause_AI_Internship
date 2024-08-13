# Image Recognition using Convolutional Neural Networks (CNN)

This project involves creating an image classifier that can categorize images into predefined classes using a Convolutional Neural Network (CNN) trained on the CIFAR-10 dataset.

## Project Aim

Develop an image classifier using CNN to accurately classify images from the CIFAR-10 dataset.

## Technologies Used

- Python
- TensorFlow
- Google Colab

## Project Structure

- `Image_Recognition.ipynb`: The Jupyter notebook containing the entire project code, from data loading to model training and evaluation.

## Installation

To run this project, you need to have the following dependencies installed:

- TensorFlow
- NumPy
- Matplotlib

You can install the required libraries using pip:

```bash
pip install tensorflow numpy matplotlib
```

## Usage

### Google Colab

1. Open Google Colab.
2. Upload the `Image_Recognition.ipynb` notebook.
3. Run the cells in the notebook to execute the entire project.

### Jupyter Notebook

1. Ensure you have Jupyter Notebook installed. You can install it using Anaconda or pip:
   ```bash
   pip install notebook
   ```
2. Download the `Image_Recognition.ipynb` notebook and place it in your working directory.
3. Open the notebook in Jupyter:
   ```bash
   jupyter notebook Image_Recognition.ipynb
   ```
4. Run the cells in the notebook to execute the entire project.

## Steps to Develop the Image Classifier

1. **Set Up Environment:**
   - Install necessary libraries.
   - Load TensorFlow and other required modules.

2. **Load and Preprocess Dataset:**
   - Utilize the CIFAR-10 dataset.
   - Normalize the images for better training performance.

3. **Build the CNN Model:**
   - Define the architecture with convolutional and pooling layers.
   - Add dense layers for classification.

4. **Compile and Train the Model:**
   - Use appropriate loss functions and optimizers.
   - Train the model over several epochs with validation.

5. **Evaluate the Model:**
   - Assess the model's performance on test data.
   - Visualize training and validation accuracy.

6. **Test with New Images:**
   - Upload and preprocess custom images.
   - Predict the class of new images using the trained model.

## Results

After training, the model achieves satisfactory accuracy on the CIFAR-10 test dataset. The accuracy and loss graphs indicate the model's learning progress over epochs.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/muhammadhuzaifayousaf/Codeclause_AI_Internship/blob/main/LICENSE) file for details.

---

**Note:** For detailed code and step-by-step implementation, refer to the `Image_Recognition.ipynb` notebook.

[Open Image_Recognition.ipynb in Google Colab](https://colab.research.google.com/drive/1qlAf9XBG041A0fzhyKWCUKLCk8Ja2QpT?usp=sharing)
