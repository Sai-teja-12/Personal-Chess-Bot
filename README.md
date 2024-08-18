# Personal Chess Bot

## Overview

This repository contains the code for a personal chess bot. It includes scripts for training a model and making predictions on chess moves. The project uses PyTorch for model training and TensorFlow for predictions.

## Getting Started

Follow these instructions to set up and run the project on your local machine.

### Prerequisites

- Python 3.x
- `pip` for installing dependencies
- Jupyter Notebook for running the `.ipynb` files

### Setup

1. **Clone the Repository**

   Clone the repository to your local machine:

   ```bash
   git clone https://github.com/Sai-teja-12/Personal-Chess-Bot.git
   cd Personal-Chess-Bot

2. **Install Dependencies**
   
    Install the required Python packages using requirements.txt:

    ```
    pip install -r requirements.txt
    ```
3. **Prepare Data**

   Place your PGN files in the data/pgn/ directory. Make sure the directory structure looks like this:
```
    Personal-Chess-Bot/
    ├── data/
    │   └── pgn/
    │       └── your_pgn_files.pgn
    ├── engine/
    │   └── torch/
    │       ├── chess_model.py
    │       ├── dataset.py
    │       ├── utils.py
    │       ├── predict.ipynb
    │       └── train.ipynb
    ├── models/
    │   ├── TORCH_100EPOCHS.pth
    │   └── info.txt
    ├── requirements.txt
    └── README.md
```
**Training the Model**
1. Open the train.ipynb notebook in Jupyter Notebook:

```
jupyter notebook engine/torch/train.ipynb
```
Follow the instructions in the notebook to train the model. Ensure that you have placed your PGN files in the data/pgn/ directory before starting the training process.

**Testing the Model**
- Open the predict.ipynb notebook in Jupyter Notebook:

Follow the instructions in the notebook to test the model. The notebook will use the trained model to make predictions based on the provided chess positions.



