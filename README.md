# Forecasting Covid-19 KSA by Confirmed Cases with Facebook Prophet


![a](https://github.com/RahafSh/SDA_DS_FinalProject/blob/main/Images/cover.png "Logo Title Text 1")

 ## Table of Content
- [General Info](#general-Info)
  - [Purpose](#purpose)
  - [Presentation](#presentation)
  - [Data](#data)
- [Results](#results)
- [Technologies](#technologies)


## General Info
 
### Purpose
The Kingdom of Saudi Arabia has dealt excellently with the Covid-19 situation. 
The aim here to explore and extract hidden knowledge to predict the future using time series forecasting Prophet.

### Presentation
 - [One Pager](https://www.overleaf.com/read/ybfzfnzjrzgf)
 - [PowerPoint](https://drive.google.com/file/d/1plUonjINuCCwGkaoi7ghWs8wTFI7aHAT/view?usp=sharing)
 
### Data
The dataset contains detailed for cases and tests in KSA.
 - I used `daily cases` file from [Covid-19 KSA](https://www.kaggle.com/fahdahalalyan/covid19-ksa)

## Results
- First, I wanted to show the cases by regoin 
  ![b](https://github.com/RahafSh/SDA_DS_FinalProject/blob/main/Images/02.PNG)
    - As showen above the higheset confirmed cases. So, I have completed the model with Riyadh region.

- Forecast Plots: 
  ![b](https://github.com/RahafSh/SDA_DS_FinalProject/blob/main/Images/08.PNG)
 
- Component Plots:
  ![b](https://github.com/RahafSh/SDA_DS_FinalProject/blob/main/Images/09.PNG)


- Mean Absolute Error:
  ![b](https://github.com/RahafSh/SDA_DS_FinalProject/blob/main/Images/16.PNG)

## Technologies
 - Tools:
    - Python
    - Google Colab
    - Latex 
    - Jupyter Lab
    
 - Packages:
    - [Seaborn](https://seaborn.pydata.org/index.html#)
    - [Matplotlib](https://matplotlib.org/3.1.0/tutorials/colors/colormaps.html)
    - [Fbprophet](https://facebook.github.io/prophet/docs/quick_start.html)
    - [Pandas](https://pandas.pydata.org/)
    - [Numpy](https://numpy.org/doc/stable/contents.html)
    
