**Energy Consumption Prediction in Diverse Smart Buildings**
An Optimized Framework Using Machine Learning
**1.	Project Overview**
This project addresses the rising global concern of energy management in smart buildings. By leveraging the ASHRAE Energy Dataset III, this framework provides a scalable and accurate way to forecast energy consumption across diverse building types, including residential, commercial, and industrial sectors. 
The core of this project is an optimized machine learning pipeline that integrates weather data and temporal trends to overcome common research gaps like inadequate datasets and poor feature integration. 

**2.	Key Contributions**
•	Scalable Framework: Designed to work across multiple building categories beyond    localized university datasets. 
•	Feature Engineering: Incorporates critical variables such as temperature, humidity, and time-based variations (hourly/seasonal). 
•	Computational Efficiency: Uses optimized gradient boosting to achieve high accuracy with lower resource requirements than deep learning models. 

**3. Methodology**
•	Dataset: ASHRAE Energy Dataset III (over 5 million rows with 12 key features). 
•	Preprocessing:
•	**Models Used**: XGBoost, Random Forest, and Long Short-Term Memory (LSTM). 

**4.	Performance Results**
The models were evaluated using MAE, RMSE, and R2 scores. XGBoost emerged as the superior model. 

**Model	        MAE    	RMSE	     R2 Score**
XGBoost	        37.55	  112        	0.9999
Random Forest	  246.04	363	        0.9989
LSTM	          0.0834	0.1264	(Sequential Analysis)

**5.	Future Scope**
•	Integrating real-time prediction capabilities for dynamic monitoring. 
•	Incorporating user behavior analysis and occupancy patterns. 
•	Exploring hybrid models such as XGBoost + Bi-LSTM. 
________________________________________
**6.	How to Run**
1.	Clone the repository:
git clone [https://github.com/fahadtmalik-ctrl/-Energy-Consumption-Prediction.git](https://github.com/fahadtmalik-ctrl/-Energy-Consumption-Prediction.git)
2.	Install dependencies:
3.	pip install -r requirements.txt
4.	Run the analysis:
5.	Open the .ipynb file in VS Code or Jupyter and run all cells.


________________________________________
