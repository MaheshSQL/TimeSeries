## About Time Series Forecasting
Demonstrate common approaches for Time Series forecasting task.

## Setup

### OS
Ubuntu 18.04.6 LTS

### 01-TimeSeries-Forecasting.ipynb

#### Environment
conda create --name timeseries python==3.8.3 --yes

conda activate timeseries

conda install notebook ipykernel  --yes

ipython kernel install --name timeseries --display-name "Python 3.8.3 (timeseries)" --user

#### pip packages
pip install requests==2.27.1

pip install plotly==5.6.0

pip install statsmodels==0.13.2

pip install featuretools==1.6.0

#### conda packages
conda install pandas=1.4.1

conda install chardet=4.0.0

conda install scikit-learn=1.0.2

conda install matplotlib=3.5.1

### 02-TimeSeries-Forecasting-PyTorch-Lightning.ipynb

#### Environment
conda create --name timeseriespytorchlight python==3.8.12 --yes

conda activate timeseriespytorchlight

conda install notebook ipykernel  --yes

ipython kernel install --name timeseriespytorchlight --display-name "Python 3.8.12 (timeseriespytorchlight)" --user

#### pip packages

pip install pyarrow==7.0.0


#### conda packages
conda install -c conda-forge ipywidgets

conda install pandas=1.4.1

conda install scikit-learn=1.0.2

conda install matplotlib=3.5.1

conda install pytorch=1.10.2 -c pytorch

conda install pytorch-forecasting=0.9.2 -c conda-forge