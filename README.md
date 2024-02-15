# uwb_hand_gesture_classifier
This repository implements a hand gesture recognition system using ultra-wideband (UWB) technology. It provides:

Data loading and preprocessing from the UWB_dataset_2.
Label encoding for categorical gesture classes.
Training-validation-test data splitting.
A deep learning model architecture with a Squeeze-and-Excitation block for attention.
Model training and evaluation (functionality needs to be added based on your code).

**Model Architecture**
The core of the model incorporates a Squeeze-and-Excitation (SE) block, a neural network component designed to enhance model interpretability and performance. The SE block is added to capture channel-wise dependencies and improve feature representation.

**Training**
The model is trained using TensorFlow/Keras. Training details, including the training history, are logged using a CSV logger. The training script (train.ipynb) can be run to train the model on the provided dataset.

**Model Evaluation**
After training, the model is evaluated on a separate test set. Accuracy is computed and reported as a performance metric.

**Dependencies**
NumPy
TensorFlow
Matplotlib
Scikit-learn
