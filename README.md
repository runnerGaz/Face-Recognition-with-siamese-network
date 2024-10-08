
---
![MENU image](https://github.com/runnerGaz/Face-Recognition-with-siamese-network/blob/main/image.png)
# Facial Recognition using Siamese Network



## Overview
This project implements a facial recognition system using a **Siamese Neural Network**. The network compares two face images and determines if they belong to the same person or not.

### Key Concepts:
- **Anchor Image**: The base image used for comparison.
- **Positive Image**: An image of the same person as the anchor.
- **Negative Image**: An image of a different person.

## Setup and Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/facial-recognition-siamese.git
   cd facial-recognition-siamese
   ```

2. **Install Dependencies**:
   ```bash
   pip install tensorflow==2.4.1 tensorflow-gpu==2.4.1 opencv-python matplotlib
   ```

## Data Collection

To collect images using your webcam:
- Run `python collect_images.py`
- Press `a` for anchor images, `p` for positive images, and `q` to quit.

Organize the dataset like this:
```
data/
  ├── anchor/
  ├── positive/
  └── negative/
```

## Training

To train the model:
```bash
python train.py
```

The network will learn to distinguish between images of the same person and different people.

## Usage

After training, you can run the model on new images or webcam input:
```bash
python recognize.py
```

The model will check if two images match based on their facial features.

## License

This project is licensed under the MIT License.

---

You can update the **git clone** link and other details specific to your project, and this will be a concise and easy-to-read README. Let me know if you need further modifications!
