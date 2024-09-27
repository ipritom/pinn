# Experimental Study on Physics Informed Neural Network

# Introduction
`pinn_build_bactch.ipynb` contains the code for training a neural network which can predict coordinate of a projectile for the given initial velocity, angle, and time. 

`PINNv3_train_gloss.ipynb` contains code which is the extension of the previous experiment. In that experiment, a new loss function is tried to introduce to make the neural network physics informed. We calculate the value of *g* from the predicted output and then calculate the loss with actual *g* value. 

