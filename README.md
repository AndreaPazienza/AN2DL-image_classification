# Time Series Classification Challenge

Challenge project for the Artificial Neural Networks and Deep Learning course at Politecnico di Milano. The project addresses a multivariate time series classification task using recurrent neural networks (RNNs), implemented in a Jupyter Notebook (primarily run on Google Colab). The repository contains the notebook and the challenge report.

---

## Overview

The goal of this project was to correctly classify time series samples by designing, training, and evaluating RNN-based architectures on the dataset provided for the course challenge. The notebook includes data exploration, preprocessing, model definition, training, and evaluation, as well as a discussion of the results.  
The final solution was submitted to the official Kaggle challenge associated with the course, achieving a leaderboard position of 17th out of 193 teams.

---

## Project Structure

- `Models/`: Contains the Jupyter Notebooks implementing and evaluating the models used in the challenge.
  - `GRU.ipynb`: Implements a baseline GRU model for multivariate time series classification.
  - `BaggedGRU.ipynb`: Implements an ensemble model obtained by bagging 5 GRU networks to improve robustness and performance.
  - `AttentionCNNLSTM.ipynb`: Implements a hybrid model combining convolutional layers, LSTM units, and an attention mechanism for time series classification.
- `Deliverables/`: Contains the project report.

---

## How to Run the Project

1. Open the main notebook in Google Colab.
2. Install the required dependencies as specified in the course instructions or at the top of the notebook (for Colab, follow the setup cells provided).
3. Follow the instructions inside the notebook to download or access the Kaggle challenge dataset, then execute the cells from top to bottom.

At the moment, the dataset is not included in this repository and will be uploaded at a later time.

---

## Documentation

- [Challenge report](Deliverables/Report.pdf)

---

## Technologies

- Python  
- Google Colab  
- RNN for time series classification

---

## License

This project is released under the MIT License.

---

## Notes

This project was developed as part of a university course in artificial neural networks and deep learning. The code and report are provided for educational purposes.

---

## Acknowledgements

This project was developed in collaboration with Francesco Conte and Tito Maraz Galassi.
