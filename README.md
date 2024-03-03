# Electron Energy Flux Prediction using Deep Learning

Kaggle notebook for EDA: **https://www.kaggle.com/code/sugataghosh/electron-energy-flux-prediction-part-1-eda**

Kaggle notebook for modeling: **https://www.kaggle.com/code/sugataghosh/electron-energy-flux-prediction-part-2-modeling**

- In [**McGranaghan et al. (2021)**](https://doi.org/10.1029/2020SW002684), the authors have considered the problem of modeling _electron particle precipitation_ from the [**magnetosphere**](https://en.wikipedia.org/wiki/Magnetosphere) to the [**ionosphere**](https://en.wikipedia.org/wiki/Ionosphere). They attempted to address it through a new database, using [**machine learning**](https://en.wikipedia.org/wiki/Machine_learning) tools to extract useful information from it.

- Based on that database, we aim to predict _electron total energy flux_, which is a [**continuous variable**](https://en.wikipedia.org/wiki/Continuous_or_discrete_variable#Continuous_variable).

- A detailed [**exploratory data analysis**](https://en.wikipedia.org/wiki/Exploratory_data_analysis) on the dataset is carried out. In particular, we observe that there are clear groups among the feature variables. We investigate the group-wise correlation structure through averaging the pairwise correlation coefficients.

- We use the insights obtained from EDA in the [**data preprocessing**](https://en.wikipedia.org/wiki/Data_Preprocessing) stages, which consists of [**feature extraction**](https://en.wikipedia.org/wiki/Feature_engineering), [**data transformation**](https://en.wikipedia.org/wiki/Data_transformation_(statistics)), [**feature scaling**](https://en.wikipedia.org/wiki/Feature_scaling), and [**principal component analysis**](https://en.wikipedia.org/wiki/Principal_component_analysis).

- We build a [**neural network**](https://en.wikipedia.org/wiki/Neural_network) and [**tune**](https://en.wikipedia.org/wiki/Hyperparameter_optimization) it to predict _electron total energy flux_.

- The final model obtains a [**root mean square error**](https://en.wikipedia.org/wiki/Root-mean-square_deviation) (RMSE) of $1.531904$, a [**mean absolute error**](https://en.wikipedia.org/wiki/Mean_absolute_error) (MAE) of $1.075939$, and a [**coefficient of determination**](https://en.wikipedia.org/wiki/Coefficient_of_determination) $(R^2)$ of $0.699466$ on the test set.
