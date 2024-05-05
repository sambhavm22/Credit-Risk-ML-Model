**Credit Risk Modeling Machine Learning Project** 

***Introduction***

The goal is to create a machine learning model that can precisely segregate customers into class of giving credit based on past financial data and other pertinent borrower characteristics which allow financial institutions to determine the risk of lending to them. Such models can help thenm identify and measure their total risk exposure, set appropriate risk limits, and make informed investment decisions.


**Dependencies**

Python 3, sklearn, numpy, XGBoost, scipy, pandas and matplotlib


**Work Flow Diagram**

			<img width="467" alt="image" src="https://github.com/sambhavm22/Credit-Risk-ML-Model/assets/58766591/ed5872fe-0d85-4767-b1f4-3656ead1d60e">

**Target Variable Distribution**

			<img width="467" alt="image" src="https://github.com/sambhavm22/Credit-Risk-ML-Model/assets/58766591/1d9eafdc-fbfa-4a50-8dd7-f8d2a4b71110">

**Final ML Model**

First, train the data on random forest algorithm (accuracy-76%)and then we train the model on XGBoost classifer algorithm (accuracy - 77%). With hyperparameter tuning of XGBoost classifer, the accuracy is 78%.


**F1 Score for each class**

		<img width="400" alt="image" src="https://github.com/sambhavm22/Credit-Risk-ML-Model/assets/58766591/fc047618-68f6-4b43-beba-e499ed385aeb">

For detailed documentation of this project visit [

https://medium.com/@sambhavm22/credit-risk-model-3120b99073c4
