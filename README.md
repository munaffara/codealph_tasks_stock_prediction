**Meta Stock Price Prediction**

This repository contains a Jupyter Notebook for predicting the stock prices of Meta (formerly Facebook) using an LSTM (Long Short-Term Memory) model. The notebook demonstrates the entire process, from loading the dataset to training the model and making predictions.

**Introduction**

This project aims to predict the stock prices of Meta using historical stock price data. The model utilizes LSTM, a type of recurrent neural network (RNN), to capture temporal dependencies in the data. The Jupyter Notebook includes data preprocessing, model training, and visualization of the predictions.

**Requirements**

To run this notebook, you need the following libraries:

numpy

pandas

matplotlib

scikit-learn

keras


You can install these libraries using pip:

	pip install numpy pandas matplotlib scikit-learn keras
    
    
**Usage**

Clone this repository:

	git clone https://github.com/yourusername/meta-stock-price-prediction.git
  
Navigate to the repository directory:

	cd meta-stock-price-prediction
  
Open the Jupyter Notebook:

	jupyter notebook Meta_Stock_Price_Prediction.ipynb
  
Run the notebook cells sequentially to execute the code.


**Dataset**

The dataset used in this project is the Meta Stock Price Dataset. It contains historical stock prices. 
Ensure the dataset is named Meta_Stock_Price_Dataset.csv and is located in the same directory as the notebook.

**Model Architecture**

The LSTM model architecture consists of:


Four LSTM layers with Dropout layers to prevent overfitting

An output Dense layer with one unit

The model is compiled using the Adam optimizer and the mean squared error loss function.


**Results**

The notebook provides visualizations of the actual vs. predicted stock prices. The plot shows how well the model's predictions align with the actual stock prices.

**Conclusion**

This project demonstrates the use of LSTM for stock price prediction. The model captures the temporal dependencies in the data and provides reasonably accurate predictions. Future improvements could include tuning hyperparameters, using additional features, and experimenting with different model architectures.
