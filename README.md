# Image Classification Project

This project implements a scene classification system using convolutional neural networks (CNNs) and transfer learning. The project is split into two main tasks:
- **Task 1**: Building and training a CNN from scratch (Files: `q2.py`, `q2_1.py`)
- **Task 2**: Transfer learning with a pre-trained model (File: `q3.py`)

## Project Structure

- `q2.py`: Implements the CNN model from scratch using Keras/TensorFlow.
- `q2_1.py`: Contains additional experiments and tuning for the CNN.
- `q3.py`: Implements transfer learning using a pre-trained VGG16 model for scene classification.

### Requirements

To install the required dependencies, run the following command:

```bash
pip install -r requirements.txt


Then you have to place the images folder just in the root directory along with the question files.

After that you can run each file respectively:

```bash
python3 q2.py
python3 q2_1.py
python3 q3.py
python3 extra.py
