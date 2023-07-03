# Toxicity Classification Interface
This repository contains code for a toxicity scoring interface that utilizes a pre-trained model to predict the toxicity of text comments. The interface allows users to input a comment and receive a toxicity score for various categories.

## Note: Interface is currently available for `toxicity-classification.ipynb` only

# Prerequisites
Make sure you have the following dependencies installed:

`TensorFlow
numpy
pandas
gradio`

You can install them using pip:
`pip install tensorflow numpy pandas gradio`

# Usage
Clone the repository
Navigate to the project directory:

Download the pre-trained model weights:
Update the vectorizer function in the code to match your text vectorization approach. Make sure it produces a vector representation for a given input text.

Run the script:

python main.py
Open your web browser and go to http://localhost:7860 to access the interface.

Enter a comment in the text box provided and click the "Score" button. The interface will display the predicted toxicity scores for different categories.
