# Image-Classification

I conducted model training on three distinct datasets, as follows:

- For the MNIST dataset, I utilized Chollet's Notebook code to train the model.

- Moving on to the EMNIST dataset, I applied the same model from Chollet's work, maintaining the same number of layers, but modifying the input and output neurons.

- Data augmentation was then performed on the EMNIST dataset. The newly augmented data was combined with the existing dataset. Subsequently, I trained models on both the augmented and non-augmented data, incorporating hidden convolution layers.

- I conducted an in-depth analysis of the trained models, comparing their accuracy with and without the augmented data.

- Leveraging the model trained on the EMNIST dataset, I employed transfer learning to train the model on the Binary Alpha Digits dataset.

- Following transfer learning, I assessed the model's performance on both the EMNIST and Binary Alpha Digits datasets.
