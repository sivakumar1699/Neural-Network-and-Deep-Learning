# Neural-Network-and-Deep-Learning

Student Name: Siva Kumar Choutametla
Student id: 700765371
Submission: Tensor Manipulations, Loss Functions, Neural Network Training

Tensor Manipulations & Reshaping
1)Created a random tensor of shape (4, 6).
2)Printed its rank and shape using TensorFlow functions.
3)Reshaped tensor to (2, 3, 4) and transposed it to (3, 2, 4).
4)Applied broadcasting by adding a smaller tensor of shape (1, 4).
5)Explained broadcasting: TensorFlow automatically expands smaller tensors along missing dimensions to match larger tensors.

Printed all shapes, ranks, and tensor values after each operation.

Loss Functions & Hyperparameter Tuning
1)Defined true values (y_true) as one-hot encoded vectors.
2)Created two sets of predictions (y_pred_1 and y_pred_2) to simulate prediction adjustments.
Calculated:
2.a)Mean Squared Error (MSE)
2.b)Categorical Cross-Entropy (CCE)
Compared loss values before and after modifying predictions.
3)Visualized the comparison using Matplotlib bar chart.
4)Demonstrated how different loss functions respond to prediction changes.

Train a Neural Network and Log to TensorBoard
1)Loaded MNIST dataset and normalized the data.
2)Built a simple neural network:
3)Flatten -> Dense(128, ReLU) -> Dense(10, Softmax)

4)Trained the model for 5 epochs.

4.a)Enabled TensorBoard logging at logs/fit/ directory.

4.b)After training, TensorBoard shows training and validation accuracy/loss curves.

4.c)Evaluated final test accuracy: 97.04%.

4.d)Addressed and fixed TensorFlow warning by adding explicit Input(shape=(28, 28)) layer.

