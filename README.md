# LSTM-GARCH

## Introduction

Volatility plays an important role in financial markets for pricing derivatives, portfolio risk management and hedging strategies. Therefore, being able to correctly predict volatility of stock markets is crucial. This repository contains a Python implementation of a Hybrid LSTM-GARCH model for forecasting volatility. It is based on the following [paper](https://www.sciencedirect.com/science/article/pii/S0957417418301416). The GARCH models are built using PyFlux while the LSTMs are built with TensorFlow and Keras.

## Hybrid LSTM-GARCH model architecture

<table>
<tr>
<td>
  
In econometrics, the autoregressive conditional heteroskedasticity (ARCH) model is a statistical model for time series data that describes the variance of the current error term or innovation as a function of the actual sizes of the previous time periods' error terms; often the variance is related to the squares of the previous innovations. The ARCH model is appropriate when the error variance in a time series follows an autoregressive (AR) model; if an autoregressive moving average (ARMA) model is assumed for the error variance, the model is a generalized autoregressive conditional heteroskedasticity (GARCH) model.

ARCH models are commonly employed in modeling financial time series that exhibit time-varying volatility and volatility clustering, i.e. periods of swings interspersed with periods of relative calm. ARCH-type models are sometimes considered to be in the family of stochastic volatility models, although this is strictly incorrect since at time t the volatility is completely pre-determined (deterministic) given previous values.

Long short-term memory (LSTM) is an artificial neural network used in the fields of artificial intelligence and deep learning. Unlike standard feedforward neural networks, LSTM has feedback connections. Such a recurrent neural network (RNN) can process not only single data points (such as images), but also entire sequences of data (such as speech or video). For example, LSTM is applicable to tasks such as unsegmented, connected handwriting recognition, speech recognition, machine translation, robot control, video games, and healthcare. 

A common LSTM unit is composed of a cell, an input gate, an output gate and a forget gate. The cell remembers values over arbitrary time intervals and the three gates regulate the flow of information into and out of the cell.

<p align="center">
<img src="https://github.com/tlemenestrel/LSTM_GARCH/blob/master/Images/architecture.png" width="700">
</p>

</td>
</tr>
</table>
