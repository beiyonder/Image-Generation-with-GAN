# Overview
Model Architecture: 
The DCGAN architecture includes a Generator and a Discriminator. Both are implemented using PyTorch nn.Module.

#### Generator:

###### Consists of transposed convolutional layers (nn.ConvTranspose2d)
###### Uses batch normalization (nn.BatchNorm2d)
###### Uses ReLU activations (nn.ReLU)
#### Discriminator:

###### Consists of convolutional layers (nn.Conv2d)
###### Uses batch normalization (nn.BatchNorm2d)
###### Uses Leaky ReLU activations (nn.LeakyReLU)
#### Training Loop
##### The training loop involves:
###### Defining loss functions (torch.nn.BCELoss)
###### Defining optimizers (Adam optimizer with tuned parameters)
###### Training the Discriminator and Generator in alternating steps

##### Hyperparameters 
###### Learning rate (lr)
###### Batch size
###### Number of epochs
###### Optimizer parameters (e.g., beta1 for Adam)
