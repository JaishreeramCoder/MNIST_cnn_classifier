
# Hand written digit recognistion using CNNs

In this repo I have done image classification on mnist dataset using pytorch. 
- Details about the neural network architecture and training weights can be obtained by uploading [model.onnx](https://github.com/JaishreeramCoder/MNIST_cnn_classifier/blob/temp/model-visualization/model.onnx) file in [Netron](https://netron.app/)
- The loss function used is cross-entropy, and the optimizer is the Adam optimizer. ReLU activation function has been utilized between the layers along with batch normalization.
During inference, the model achieved exceptional performance with the following metrics:
- Test Accuracy: 99.390%

- Precision: 99.410%

- Recall: 99.390%

- F1 Score: 99.399%