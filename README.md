# LipNet: : End-to-End Sentence-level Lipreading

This project is a machine learning model that can predict text based on the lip movements of a video without audio. It can be used for applications such as speech recognition for individuals with hearing impairments, or as a tool for analyzing video footage without audio.

# Model architecture

The lip reading model is based on a deep convolutional neural network (CNN) architecture. The input to the model is a sequence of video frames, and the output is a sequence of characters representing the predicted text. The model consists of several layers of convolutional and recurrent neural networks, with a final output layer that produces a probability distribution over the character set.

The model was trained using the CTC (Connectionist Temporal Classification) loss function, which is commonly used for sequence prediction tasks. 

# Sample Input

https://user-images.githubusercontent.com/95428432/235194337-b9d92034-a83d-40f5-9825-af2f415b7ab2.mp4

# Refrences
~  Yannis M. Assael, Brendan Shillingford, Shimon Whiteson, Nando de Freitas 2016 "LipNet: End-to-End Sentence-level Lipreading" <a href="https://arxiv.org/abs/1611.01599"> Link <a/>
  <br/>
~ <a href="https://github.com/nicknochnack"> @nicknochnack <a/>



