# Terrain_Identification_Team91

This project aims to identify different types of terrains (such as forest, mountains, desert, etc.) using LSTM (Long Short-Term Memory) neural networks.

#Team Members: 
- Chetana Chunduru, cchetan2@ncsu.edu
- Rohith Aki, raki@ncsu.edu
- Sai Niranjan Karthik Mulugu, smulugu@ncsu.edu


## Prerequisites

- Python 3.x
- TensorFlow
- NumPy
- Pandas

## Dataset

The dataset used in this project is obtained from [source] and contains images of various terrains. The images are labeled and split into train and test sets.

## Getting Started

1. Clone this repository.

2. Install the required dependencies.


## Results

The results of the Terrain Identification using LSTM model are evaluated based on the model's ability to correctly classify the terrain type of a given terrain dataset.

The model's accuracy is one of the primary metrics used to evaluate the model's performance. It measures the proportion of correctly predicted terrain types out of all the terrain samples used for testing. Higher accuracy values indicate better performance.

Other performance metrics used to evaluate the model include precision, recall, and F1 score. Precision measures the percentage of true positive predictions out of all positive predictions, while recall measures the percentage of true positive predictions out of all actual positives in the dataset. The F1 score is the harmonic mean of precision and recall and provides a more balanced measure of performance.

Additionally, the confusion matrix is used to evaluate the model's performance. It is a table that summarizes the number of correctly and incorrectly predicted terrain types. The confusion matrix can be used to calculate performance metrics such as precision and recall for each terrain type, providing more detailed insights into the model's performance for each class.

Overall, the results of the Terrain Identification using LSTM model should be interpreted with consideration for all of these metrics to ensure that the model's performance is well-rounded and reliable.

## Future Work

- Improve the accuracy of the model by using more advanced techniques.
- Expand the dataset to include more terrains and images.
- Build a web or mobile app to classify terrains in real-time using the trained model.


## Acknowledgments

- The LSTM model architecture used in this project was inspired by the paper "Deep learning for remote sensing image classification: A survey" by Cheng et al. (2019).

- The code implementation for the LSTM model was adapted from the Keras documentation (https://keras.io/examples/timeseries/).

- The code for visualizing the results was adapted from the Matplotlib documentation (https://matplotlib.org/3.3.3/index.html).







