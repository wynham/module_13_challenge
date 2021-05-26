# Module 13 Challenge

This is the repository for my module 13 challenge. In this module challenge, we expanded on our knowledge of machine learning by using neural networks. Our goal was to create a model that predicts whether or not startups would succeed based on a variety of information about each business.

Our first step in this challenge was to prepare the data for use on a neural network model. This involved using tools such as StandardScalar() and OneHotEncoder(), in order to clean our data up and prepare it for the model. 

The second step was to compile and evaluate a binary classification model using a neural network. We used TensorFlow's Keras for this model. We then calculated the model's loss and accuracy.

The final step in this challenge was to 

---

## Technologies

Import the following at the beginning of your jupyter notebook:

```python
import numpy as np
import pandas as pd
from pathlib import Path
from sklearn.metrics import balanced_accuracy_score
from sklearn.metrics import confusion_matrix
from imblearn.metrics import classification_report_imbalanced

import warnings
warnings.filterwarnings('ignore')
```

---

## Example

### This first image shows results for the original data. It shows the accuracy score, confusion matrix, and the classification report.

![original](./readme_images/original.png)


### The next image shows results for the resampled data. It shows the accuracy score, confusion matrix, and the classification report.

![resampled](./readme_images/resampled.png)


---

## Contributors

UCB Fintech Bootcamp, Wynham Guillemot 

---

## License

MIT License

Copyright (c) [2021] [UCB Fintech Bootcamp, Wyham Guillemot]

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
