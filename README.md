# Text Generation - Character level language model - Writing like Shakespeare - Dinosaurus Island

This project aims to develop a **character-level language model** capable of **generating text** in the style of famous literary works. The project leverages deep learning techniques to create a model that can produce coherent and stylistically consistent text snippets.


<div align="center">
<img src="images\shakespeare1.jpg" style="width:450px;"> <br>Designed by Freepik
</div>

![Deep Learning](https://img.shields.io/badge/Skill-Deep%20Learning-yellow)
![Text Generation](https://img.shields.io/badge/Skill-Text%20Generation-brightblue)
![Recurrent Neural Networks](https://img.shields.io/badge/Skill-Recurrent%20Neural%20Networks-blueviolet)
![Natural Language Processing](https://img.shields.io/badge/Skill-Natural%20Language%20Processing-green)
![TensorFlow](https://img.shields.io/badge/Skill-TensorFlow-orange)
![Keras](https://img.shields.io/badge/Skill-Keras-yellow)
![Image Processing](https://img.shields.io/badge/SkillImage%20Processing-brightblue)
![Python Programming](https://img.shields.io/badge/Skill-Python%20Programming-orange)

## Project File Structure

```bash
Dinosaurus_Island_Character_Level_Language_Model/
│
├── Dinosaurus_Island_Character_level_language_model.ipynb    # Main notebook with project code and explanations
├── generateTestCases.py                                      # Script to generate test cases for the model
├── shakespeare.txt                                           # Text data from Shakespeare's works
├── dinos.txt                                                 # Text data with dinosaur names
├── shakespeare_utils.py                                      # Utility functions for processing Shakespeare text
├── test_utils.py                                             # Utility functions for testing the model
├── utils.py                                                  # General utility functions
└── models                                                    # Trained model file
```

## Frameworks and Libraries
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.16.1-orange.svg?style=flat&logo=tensorflow)
![Keras](https://img.shields.io/badge/Keras-3.3.3-red.svg?style=flat&logo=keras)
![NumPy](https://img.shields.io/badge/NumPy-1.26.4-blue.svg?style=flat&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.6.2-green.svg?style=flat&logo=matplotlib)

## Project Architecture

The project utilizes a Recurrent Neural Network (RNN) architecture, specifically Long Short-Term Memory (LSTM) networks, to model the sequence data. The model is trained on a large corpus of text to learn the statistical properties of character sequences, enabling it to generate text in a similar style.

## Key Features
- Text preprocessing for character-level modeling
- Implementation of an `LSTM-based character-level language model`
- Training the model on large text corpora (Shakespeare and dinosaur names)
- Text generation using the trained model

## Usage
**Clone the repository:**
```bash
git clone https://github.com/yourusername/Dinosaurus_Island_Character_Level_Language_Model.git
```
**Navigate to the project directory:**
```bash
cd Dinosaurus_Island_Character_Level_Language_Model
```
**Install the required dependencies:**
```bash
pip install -r requirements.txt
```
**Run the Jupyter Notebook to see the implementation:**
```bash
jupyter notebook Dinosaurus_Island_Character_level_language_model.ipynb
```
## Results

The character-level language model successfully generates text that mimics the style of the training data. The generated text is coherent and stylistically consistent with the works of Shakespeare and the list of dinosaur names, demonstrating the effectiveness of the model in learning and replicating character-level patterns.