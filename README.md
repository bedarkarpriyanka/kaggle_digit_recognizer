# mnist_digit_recognizer
Challenge Link  : https://www.kaggle.com/c/digit-recognizer <br><br>
Dataset         : MNIST <br><br>
Framework used  : TensorFlow <br><br>

File1 : working_tf_nn.py <br>
Network Architecture : <br>
input (784) -> hidden1 (50) -> activation1 (tanh) -> hidden2 (50) -> activation2 (sigmoid) -> output (10) -> activation (softmax) <br>
Optimizer : Adam (learning rate = 0.0001) <br>
Mini-batch size : 32 <br>
Number of epochs : 180 <br>
Code Reference : https://www.coursera.org/learn/neural-networks-deep-learning
<br><br>

File2 : network1.py <br>
Network Architecture : <br>
input (784) -> hidden1 (30) -> activation1 (sigmoid) -> output (10) -> activation (softmax) <br>
Optimizer : SGD (learning rate = 3.0) <br>
Mini-batch size : 10 <br>
Number of epochs : 30 <br>
Code Reference : https://github.com/mnielsen/neural-networks-and-deep-learning
