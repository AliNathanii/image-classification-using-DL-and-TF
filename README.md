# Dog Breed Classifier

This project builds a Convolutional Neural Network (CNN) to classify images of dogs into different breeds using TensorFlow and Keras. The dataset is divided into training and validation sets, and data augmentation techniques are applied to improve model performance. The model's accuracy is evaluated, and the predictions are visualized.

## Requirements

- TensorFlow
- PIL (Pillow)
- Pandas
- NumPy
- Matplotlib

## Setup

1. **Install Dependencies**:
    ```bash
    pip install tensorflow pillow pandas numpy matplotlib
    ```

2. **Prepare Dataset**:
    - Place the dog breed images in a directory named `images`, structured in subdirectories by breed.

## Code Explanation

### Import Libraries

```python
import tensorflow as tf
from PIL import Image
from tensorflow.keras import layers
from tensorflow.keras.models import Sequential
import pandas as pd
import numpy as np
import itertools
import base64
import io

