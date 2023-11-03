
# Concrete Crack Detection using Image Processing and Deep Learning

This repository contains code for detecting cracks in concrete using image processing and deep learning techniques. It includes Python code, a pre-trained model, and instructions for testing the model.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Testing New Images](#testing-new-images)
- [Results](#results)
- [Gradio Web Interface](#gradio-web-interface)

## Installation

1. Clone this repository to your local machine:

git clone https://github.com/your-username/concrete-crack-detection.git


2. Install the required Python libraries by running:

pip install -r requirements.txt


## Usage

1. Navigate to the repository directory:

cd concrete-crack-detection


2. Train the model (optional):

   If you want to train the model with your own dataset, you can use the provided code to prepare your data and train the model. Make sure to organize your dataset and update the data loading code accordingly.

3. Evaluate the pre-trained model:

   Run the following command to evaluate the pre-trained model on the test dataset:

python evaluate_model.py


This will display the test loss, accuracy, a confusion matrix, and a classification report.

## Testing New Images

To test the model with new images, you can use the Gradio web interface:

1. Launch the Gradio interface:

python gradio_interface.py


2. Open a web browser and navigate to the provided URL.

3. Upload an image containing concrete to check for cracks. The model will predict whether the concrete has cracks or not.

## Results

The results of the model evaluation and testing are provided in the README.

## Gradio Web Interface

The Gradio web interface allows you to interact with the model and test it with new images through a user-friendly web interface.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This project uses the Gradio library for building the web interface. (https://gradio.app/)

