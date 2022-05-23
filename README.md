# CO2_emissions_regression
There are a large variety of vehicles on the market, each with different sizes/engines/fuel types. These vehicles all have different levels of fuel consumption and more importantly in terms of global warming, CO2 emissions.

It is possible to accurately predict CO2 emissions based on the vehicle characteristics, as will be shown in this project.

The vehicle data was downloaded from Kaggle (see below) and contains 7385 rows (each of a different vehicle) and 12 columns (each of a different vehicle property). The original data was obtained by the Canadian government and thus contains vehicles available in Canada only.

https://www.kaggle.com/datasets/debajyotipodder/co2-emission-by-vehicles

The project is contained inside the CO2_emissions_regression.ipynb jupyter notebook.  It is laid out as follows:
1. Reading data and explanation of column/value names.
2. Exploratory data analysis.
    - Dataset structure
    - Dataset quality
    - Dataset content and feature engineering
3. Regression and comparison of different models
    - Linear model
    - Random forest
    - Random forest with hyperparameter optimisation
