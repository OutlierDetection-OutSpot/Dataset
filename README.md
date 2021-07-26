# Dataset

## introduction

The data set includes data for **200 machines** from 0 to 199, in which each machine has a total of **18 KPIs** from 0 to 17. Each KPI curve shows the situation of the corresponding machine in **45 days**.  

The labeling is for the data of these 200 machines on the **35th day**.

## data

take part of 0.txt (machine 0) for example:

| k0   | k1   | k2   | k3   | k4   | k5   | k6   | k7   | k8   | k9   | k10  | k11  | k12  | k13  | k14  | k15  | k16  | k17  |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| 0.45 | 0.5  | 0.5  | 0.5  | 0.5  | 0.59 | 0.38 | 0.38 | 0.38 | 0.36 | 0.37 | 0.38 | 0.37 | 0.38 | 0.4  | 0.46 | 0.41 | 0.61 |
| 0.51 | 0.5  | 0.5  | 0.5  | 0.5  | 0.59 | 0.36 | 0.36 | 0.38 | 0.35 | 0.36 | 0.37 | 0.36 | 0.37 | 0.39 | 0.46 | 0.4  | 0.62 |
| 0.45 | 0.5  | 0.5  | 0.5  | 0.5  | 0.61 | 0.33 | 0.42 | 0.37 | 0.34 | 0.35 | 0.36 | 0.35 | 0.36 | 0.38 | 0.45 | 0.38 | 0.61 |
| 0.49 | 0.5  | 0.5  | 0.5  | 0.5  | 0.62 | 0.32 | 0.35 | 0.35 | 0.33 | 0.34 | 0.34 | 0.34 | 0.34 | 0.36 | 0.43 | 0.37 | 0.58 |



## labels

| machine | kpi_id | label |
| ------- | ------ | ----- |
| 0       | 0      | 1     |
| 5       | 5      | 0     |
| 7       | 6      | 2     |
| 0       | 17     | 3     |

* 1：normal
* 0：Subsequence outlier
* 2：Aperiodic outlier time series
* 3：periodic outlier time series