# Module 13

## Instructions
As a risk management associate at Alphabet Soup, a venture capital firm. Alphabet Soup’s business team receives many funding applications from startups every day. This team has asked you to help them create a model that predicts whether applicants will be successful if funded by Alphabet Soup.

The business team has given you a CSV file containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. The CSV file contains a variety of information about each business, including whether or not it ultimately became successful. With your knowledge of machine learning and neural networks, you decide to use the features in the provided dataset to create a binary classifier model that will predict whether an applicant will become a successful business.

## Objective

To predict whether Alphabet Soup funding applicants will be successful, you will create a binary classification model using a deep neural network.

This challenge consists of three technical deliverables. You will do the following:

- Preprocess data for a neural network model.

- Use the model-fit-predict pattern to compile and evaluate a binary classification model.

- Optimize the model.

## Alternative Models

### Original
- **Total Hidden Layers:** 1
- **Total Hidden Nodes for Layer 1:** 9
- **Total Hidden Nodes for Layer 2:** 6
- **Activation Function:** linear
- **Loss**: binary_crossentropy
- **Epochs**: 50
- #### Accuracy: 0.7251312136650085

### Alternative 1
- **Total Hidden Layers:** 1
- **Total Hidden Nodes:** 20
- **Activation Function:** linear
- **Loss**: binary_crossentropy
- **Epochs**: 100
- #### Accuracy: 0.7308454513549805

### Alternative 2
- **Total Hidden Layers:** 3
- **Total Hidden Nodes for Layer 1:** 12
- **Total Hidden Nodes for Layer 2:** 9
- **Total Hidden Nodes for Layer 3:** 6
- **Activation Function:** sigmoid
- **Loss**: binary_crossentropy
- **Epochs**: 50
- #### Accuracy: 0.7328279614448547

### Alternative 3
*Feature SPECIAL_CONSIDERATIONS was removed*
- **Total Hidden Layers:** 2
- **Total Hidden Nodes for Layer 1:** 12
- **Total Hidden Nodes for Layer 2:** 9
- **Activation Function:** sigmoid
- **Loss**: binary_crossentropy
- **Epochs**: 100
- #### Accuracy: 0.7302623987197876
---

## Installation Guide
1. Clone this project using git with the following command: `git clone git@github.com:galcivar/module_13.git`
2. Install Python you should follow this instructions depending on you OS: https://realpython.com/installing-python/

---

## Usage
You can use this program by opening the file: `GC_venture_funding_with_deep_learning.ipynb` in the Google Colab.

---

## Contributors
Gabriel Alcivar
[Email](mailto:galcivar@galgomedia.com) - [LinkedIn](https://www.linkedin.com/in/gabriel-alcivar-aa83a710b/) - [GitHub](https://github.com/galcivar/)

---

## MIT License

Copyright (c) [2022] [Gabriel Alcivar]

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
