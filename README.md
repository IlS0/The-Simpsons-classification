# The-Simpsons-classification

Training a Convolutional Neural Network to recognize The Simpson TV Show characters. The model is made using __PytTorch__ framework. Final metric-value (f-measure) is about 93%. To have more detailed explanations, see the blog articles on Medium [Part 1](https://medium.com/alex-attia-blog/the-simpsons-character-recognition-using-keras-d8e1796eae36) and [Part 2](https://medium.com/alex-attia-blog/the-simpsons-characters-recognition-and-detection-part-2-c44f9d5abf37).

## Files description

1. `simpsons.ipynb`: the notebook with CNN architecture, model training and testing;
2. `simpsons_model.pth`: trained model.

## Build

### Cloning

Clone the repository from github by running the command in the terminal:
`git clone https://github.com/IlS0/The-Simpsons-classification.git`.

### Requirements

Unzip the archive, navigate to the directory and install the requirements by running the following command:
`pip install -r requirements.txt`.

### Downloading the dataset

[Download](https://www.kaggle.com/datasets/alexattia/the-simpsons-characters-dataset) the dataset containing pictures of 42 Simpsons characters from Kaggle.

## Run

To run the notebook, the `simpsons.ipynb` file and the dataset must be in the same directory. Also make sure you have Jupyter Notebook installed. You can see the installation guide [here](https://docs.jupyter.org/en/latest/install/notebook-classic.html#installing-jupyter-using-anaconda-and-conda). 

