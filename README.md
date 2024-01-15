# Worldquant-capstone-prodect-DC
This is my World Quant University Capstone Project: Regime Change Detection by applying a Directional-change Event approach in the Vietnam stock market

The Directional Change Event is well-written and constructed by Chen and his partner in this famous book:
Chen, J. and Tsang, E.P. Detecting Regime Change in Computational Finance: Data Science, Machine Learning and Algorithmic Trading. CRC Press, 2020.

The idea is to use to Directional Change Event approach to detect Regime Change in market movement. The target is the Vietnam Stock Index - VNINDEX, which the historical data is collected from FiinPro.

The code to calculate the DC Log Return Indicator is modified from Thomas github code:
https://github.com/ThomasWangWeiHong/Time-Series-Directional-Change-Analysis

We them fit the DC Log Return and Normal Log Return into Hidden Markov Model to detect hidden state, then we can identify the normal and abnormal regimes.

We also try impact of different thetas, you can find the result in the different theta folders.


