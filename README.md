# Prediction of the price of rough rice

<h2>Question </h2>
How much is the price of rice influenced by economic factors such as ETFs, CFDs, GDP, and company stocks associated with rice, and by physical factors such as weather patterns, substitutes, and factors of production.
<h2>Hypothesis</h2>
Using a machine learning model in conjunction with the data which were highlighted above, we will predict the price of rice. Next, we will tweak each variable in our dataset to quantify its influence on the ML model we created. We hypothesize that all factors influence the price or rice, but that physical factors play a greater role.
We came up with the idea while brainstorming projects that would satisfy our desire to experiment with prediction for social good. 
“About three-quarters of the world's poorest depend on rice not only for their food and livelihoods, but also because it plays a key role in so many cultures and societies.” - DR. RONALD P. CANTRELL from Open Markets and Global Food Security
We decided that predicting the price of rice could help developing countries assess risks of famine and poverty preemptively and intervene as necessary. 

<h2>Background Information</h2>
Rice is the main source of food in many countries, especially in non-western countries. 
Rice is a staple in the developing world. It feeds more people than any other food source. 
In 2012, nearly half of the world's population or, specifically, more than 3 billion people, relied on rice every day (“Rice as a Crop”). 
Rice is especially important for people in poor countries, and the importance of rice is increasing in the areas in Africa and Latin America. 
Moreover, as human cultivation continues to develop, there are many types of rice these days. 

<h2>Data</h2>


Therefore we need to measure the data from
  - Rough Rice ETF
  - Rough Rice CFD
  - Monsanto Company Stock
  - Wheat ETF´s
  - CORN ETF´s
  - Meat ETF´s
  - Southeast Asia Weather Report 
  - Crude Oil price

The model used for the forecasting is also going to determine the type of dataset used. Due to the nonlinear nature of rice price. (Any stock price). We will need a forecasting model that can adapt to this nature. 
Forthe first iteration

Due to complications with the gathering and processing data of the Southeast Asia Weather Report we only use the other economical factors being:

  - Rough Rice ETF
  - Rough Rice CFD
  - Monsanto Company Stock
  - Wheat ETF´s
  - CORN ETF´s
  - Meat ETF´s
  - Crude Oil price

<h2>To execute</h2>


- To execute Moving Averages Prediction
  - 1 Install libraries and essentials (Look at Installation)
  - 2 Execute "Univariate_EDA_Rice_Price.ipynb" from EDA folder and export the univariate data
  - 3 Execute "MovingAverages.ipynb" from Statistical_Methods folder
  - 4 Look at the results
- To execute LSTM multivariable prediction
  - 1 Install libraries and essentials (Look at Installation)
  - 2 Execute "Multivariate_EDA_Rice_Price.ipynb" and export the univariate data
  - 3 Execute "LSTM_Rice_Prediction.ipynb"
  - 4 Look at the results

<h2>To install</h2>
  - 1 Install Python x3.6
  - 2 Install prefered Notebook (Jupyter notebook, Google colab or other)
