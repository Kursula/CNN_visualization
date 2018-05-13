# Convolutional neural network visualization 

This repo contains two notebooks that show different ways to visualize CNN operation. The CNN_activations notebook describes how to get the intermediate layer outputs as images and plot those. That can be used to analyze how the individual layers work to process the input image. 

The Generate_input_from_activations notebook works exactly the opposite way. In that notebook the selected layer activation are maximized by running a gradient ascent algorithm towards the input image, i.e. the algorithm generates an artificial image that maximizes the selected layer activations. Various combinations and slices of the internal layers can be used in the process, or select just individual "pixel" from internal layer and see what kind of field of view it has in the input image. Set the model include_top=False to use arbitrary image shape if there is no need for the last dense layers. 
