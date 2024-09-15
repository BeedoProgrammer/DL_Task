Data Loading:
Load the Breast Cancer dataset from sklearn.datasets.

Select any two features from the Breast Cancer dataset (e.g., mean radius and mean texture). Plot the data points using these two features on a 2D scatter plot. Use different colors to represent the two classes (benign and malignant). Will a linear model work with this data?

Split the dataset into training and test sets (e.g., 80% training, 20% testing).

Model Architecture:
Build a simple neural network using PyTorch.

Think about what layers should your network have? Will it only involve linear layers? Remember activation functions?

Training:

Define a loss function (see BCELoss)
Use an optimizer like SGD or Adam.
Train the model over multiple epochs, adjusting learning rate as needed.
Print out loss and accuracy (for accuracy, see accuracy_score) as you go through your epochs.
Evaluation:

Evaluate the model on the test set.
Report the accuracy see accuracy_score of the model.
Plot train and/or loss vs epochs
