# Pulse_Recognition
Python code for classifying pulses that come from 2 different sources/channels. The archive Channel_Recognition holds a code that allows to compare the accuracy of the model,
as function of its parameters (trainning data, complexity of model, etc.). The pulses are already labeled, so the comparison is a contrast between the model prediction and
the original label.
Pytorch is used for a neural network and the model LSTM. Future work implies training the model to recognize pulse baseline, total charge (area under the curve) and decay time. 
