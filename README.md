# BLP-Exercises-with-BLP-Instruments-and-GH-Instruments

This repository contains Berry-Levinsohn-Pakes (BLP) exercises conducted in BLP (1995) including the logit model (a naive model of demand without the interaction between individual and product characteristics) and the model with interaction without and with BLP instruments. 

Additionally, where I use BLP instruments I add Gandhi-Houde (GH) instruments that were introduced in Gandhi \& Houde (2020) and compare the results.

Please note that this repository only has codes that are intuitive to understand, everything is basically coded up from scratch but does not perform very fast in terms of computational perspective. I'm working on a JIT (Just-In-Time) compilation in Python, which I expect will perform better. 

All of the following exercises use the dataset 'cardata.txt'

The Jupyter notebook, named "BLP-Logit model-basic.ipynb", is a simple logit version of BLP without adding any random coefficient, just for understanding the very basic model and codes. This is in Python. 

The Jupyter notebook, named "BLP_Exercises.ipynb" has everything mentioned above and it's in Julia. 
