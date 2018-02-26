# keras-salient-object-visualization
[![IMAGE ALT TEXT](https://www.youtube.com/upload_thumbnail?v=bgGEonerPiw&t=3)](http://www.youtube.com/watch?v=https://youtu.be/bgGEonerPiw "Donkey car network visualization based on Nvidia paper")

Keras implementation of nvidia paper 'Explaining How a Deep Neural Network Trained with End-to-End Learning Steers a Car'.
The goal of the visualization is to explain what Donkey Car (https://github.com/wroscoe/donkey) learns and how it makes its decisions. The central idea in discerning the salient objects is finding parts of the image that correspond to
locations where the feature maps of CNN layers have the greatest activations.
