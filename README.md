# Heterogeneous_Multivariate_Timeseries_data
Welcome to the **Heterogeneous_Multivariate_Timeseries_data repository**! This repository hosts a collection of diverse datasets with multiple time series. These datasets are collected to facilitate the evaluation of heterogenous multivariate time series forecasting models. These datasets are collected to be used for the goal is to determine the models' ability to accurately identify lagged variables importance in heterogenous multivariate time series that include both synthetic nonlinear systems with known dynamics and real-world scenarios.


## Datasets

The repository includes the following datasets in the **data** folder:


## Synthetic Datasets

### Toy_1.csv
- **Description**: This dataset comprises six variables randomly distributed within specific ranges [1]. The target series is generated using a defined equation (Eq.1), enriched with Gaussian white noise.
- **Equation**:  ![Equation 1](https://github.com/sarah-almaghrabi/Heterogeneous_Multivariate_Timeseries_data/blob/main/fig/toy1.png)

 

### Toy_2.csv (Mackey-Glass)
- **Description**: It is also known as Mackey-Glass (MG) time series [2], serves as a benchmark for chaotic time series prediction. It's generated through a nonlinear time-delay differential equation (Eq.2) with distinct parameter values for four independent MG time series.
- **Equation**:  ![Equation 2](https://github.com/sarah-almaghrabi/Heterogeneous_Multivariate_Timeseries_data/blob/main/fig/toy2.png)
 

## Real-World Datasets

### NSW1_df.csv and QLD1_df.csv (Aggregated Solar Power Data)
- **Description**: This dataset features aggregated solar power data from New South Wales (NSW) and Queensland (QLD) states in Australia. It includes the photovoltaic (PV) power generation target series and 13 exogenous weather features. The data spans from 1/1/2019 to 30/11/2021, covering 6:00 to 19:00 daily. In the case of NSW, the data has been aggregated from 12 sites, while for QLD, the aggregation involves 17 sites.
- **Data Source**: Australian Energy Market Operator (AEMO)[3], SOLCAST [4]

### Pollution.csv 
- **Description**: The Pollution Dataset involves pollution levels (PM2.5 concentration) in Beijing. It incorporates the target series as well as seven exogenous variables related to weather conditions. The dataset is based on hourly measurements taken from 1/1/2010 to 31/12/2014.
- **Data Source**: UCI Machine Learning Repository [5]



 
 


**References**:
1. Cao, Z., & Xu, J. (2021). Multi-Attention Mechanism for Multivariate Time Series Forecasting. arXiv preprint arXiv:2109.03596.
2. Bianchi, F. M., Scarselli, F., Gori, M., & Tsoi, A. C. (2017). Recurrent Neural Networks can be Trained to Identify Chaotic and Periodic Dynamics. Nature Communications, 8, 16019.
3. http://www.nemweb.com.au/REPORTS/ARCHIVE/Dispatch\_SCADA/
4. https://solcast.com/
5. https://archive.ics.uci.edu/



## Usage

1. Clone the repository:
<pre>
git clone https://github.com/sarah-almaghrabi/Heterogeneous_Multivariate_Timeseries_data.git
</pre>
2. Navigate to the **data** folder to access the datasets.
3. Select the dataset that aligns with your analysis or modeling goals.
4. Utilise the chosen dataset(s) for your research, analysis, or project as needed.

## Citation

If you use any of these datasets for your projects, please consider citing this repository as:
<pre>
@misc{sarah-almaghrabi,
author = {Sarah Almaghrabi},
title = {Heterogeneous Multivariate Time Series Data Repository},
year = {2023},
publisher = {GitHub},
journal = {GitHub Repository},
howpublished = {\url{https://github.com/sarah-almaghrabi/Heterogeneous_Multivariate_Timeseries_data}},
}

</pre>