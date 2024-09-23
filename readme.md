# Movie Recommendation System

This project implements a neural network-based movie recommendation system using PyTorch. It uses the MovieLens ml-latest-small dataset to train a model that predicts user ratings for movies.

## Table of Contents

- [Dataset](#dataset)
- [Requirements](#requirements)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Model Architecture](#model-architecture)
- [Training](#training)
- [Evaluation](#evaluation)
- [Contributing](#contributing)
- [License](#license)

## Dataset

This project uses the MovieLens ml-latest-small dataset, which contains 100,000 ratings and 3,600 tag applications applied to 9,000 movies by 600 users. You can find more information about the dataset [here](https://grouplens.org/datasets/movielens/latest/).

## Requirements

- Python 3.9+
- PyTorch
- pandas
- numpy
- scikit-learn


## Installation

1. Clone this repository:
   ```
   git clone https://github.com/your-username/movie-recommendation-system.git
   cd movie-recommendation-system
   ```

2. Create a virtual environment and activate it:
   ```
   conda create -n mrs python=3.9
   conda activate mrs
   ```

## Model Architecture

The recommendation model is implemented as a neural network in PyTorch. It uses embedding layers for users and movies, followed by fully connected layers to predict ratings.

## Training

The model is trained using stochastic gradient descent (SGD) with mean squared error (MSE) as the loss function. The training process includes:

- Data loading and preprocessing
- Model initialization
- Training loop with batch processing
- Periodic logging of training progress

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.