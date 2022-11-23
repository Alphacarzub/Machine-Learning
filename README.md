#### Machine-Learning
This repository contains codes and datasets only for machine learning projects

- Train.CSV -> Is original dataset downloaded from kaggle, It is based used cars data.
- Updated_dataset.csv -> Is the dataset that is obtained after pre-processing on original dataset. 
                          Only Null values are handled in this dataset. Further pre-processing is necessary to build model.

"Data pre-processing python-notebook" -> contains code that is written to pre-process data of original dataset, specificially to handle null values.


- Following notebooks Contains code that is intended to work on updated_dataset.csv<br>
"dp_part1.ipynb" -> This notebook objective is to experiment with data by applying **"One-Hot-Encoding"** technique on all categorical variables.<br>
"dp_part2.ipynb" -> This notebook objective is to experiment with data by applying **"Label-Encoding"** technique on all categorical variables.<br>
"dp_part3.ipynb" -> This notebook objective is to experiment with data by applying **"Leave-One-Out-Encoding"** technique on all categorical variables.<br>
"dp_part4.ipynb" -> This notebook objective is to experiment with data by applying **"Target-Encoding"** technique on all categorical variables.<br>
"Experiment01.ipynb" -> This notebook objective is to experiment with augmented dataset, excel file is augmented dataset.<br>

Metrics used are **"R2 Score","Adjusted R2 Score","MAE", "MSE","RMSE"**
