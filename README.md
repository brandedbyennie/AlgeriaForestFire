# AlgeriaForestFire
Analyzing forest fires in Bejaia &amp; Sidi Bel-abbes regions of Algeria using a dataset from UCI on Algerian Forest Fires (2012). The project aims to predict future fires using machine learning algorithms based on weather, temperature, and environmental data.

INTRODUCTION
Observing forest fire in 2 regions of Algeria, namely the Bejaia region located in the northeast of Algeria and the Sidi Bel-abbes region located in the northwest of algeria.

The dataset I'm using comes from UCI on Algerian Forest Fires --- https://archive.ics.uci.edu/ml/datasets/Algerian+Forest+Fires+Dataset++#

The dataset contains record forest fire occurrence in summer 2012 which spans the period from June 2012 to September 2012.

This project requires the possibility of using machine learning algorithm to predict forest fires in these regions. This is because machine learning can analyse amount of data. Such as, weather patterns, temperature changes and other environmental factors. This can be used to predict when and where a future forest fire might occur using the patterns detected by the machine learning algorithm in these regions.

Data Set Information:
The dataset includes 244 instances that regroup a data of two regions of Algeria,namely the Bejaia region located in the northeast of Algeria and the Sidi Bel-abbes region located in the northwest of Algeria.

122 instances for each region.

The period from June 2012 to September 2012. The dataset includes 11 attributes and 1 output attribute (class) The 244 instances have been classified into fire (138 classes) and not fire (106 classes) classes.

Attribute Information:
Date: (DD/MM/YYYY) Day, month ('june' to 'september'), year (2012) Weather data observations
Temp: temperature noon (temperature max) in Celsius degrees: 22 to 42
RH: Relative Humidity in %: 21 to 90
Ws:Wind speed in km/h: 6 to 29
Rain: total day in mm: 0 to 16.8 FWI Components
Fine Fuel Moisture Code (FFMC) index from the FWI system: 28.6 to 92.5
Duff Moisture Code (DMC) index from the FWI system: 1.1 to 65.9
Drought Code (DC) index from the FWI system: 7 to 220.4
Initial Spread Index (ISI) index from the FWI system: 0 to 18.5
Buildup Index (BUI) index from the FWI system: 1.1 to 68
Fire Weather Index (FWI) Index: 0 to 31.1
Classes: two classes
Steps
Data gathering
Exploratory Data Analysis (EDA)
Feature Selection
Model Building & Selection
Hyperparameter Tuning
Model deployment
