# EnergyConsumptionDataset
A project where I perform basic TSA and fit ARIMA/SAMAX, XGBoost model to the data considered

The project is divided into 5 parts:
1)	TDA - where we introduce the dataset, perform basic analysis of the data, resolve NaN values, clean the data from low quality samples, study data statistics etc.
2)	Preprocessing - here we apply finetuned solution from the first step to our data, get the clean version we will work with. Perform data preprocessing quality control. 
3)	Clustering - we apply different common time series clustering techniques, study homogeneity of the data
4)	SARIMAX - tune a SARIMAX model to our data, do some ablations 
5)	XGBoost - create features, run XGBoost autoregressor, compare to SARIMAX baseline
