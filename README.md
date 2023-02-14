# Backpropagation
Build an Artificial Neural Network by implementing the Backpropagation algorithm and test the same using appropriate data sets.

Each training example is a pair of the form (𝑥⃗ →,𝑡→ ), where (𝑥→ ) is the vector of network input values, (𝑡→ ) and is the vector of target network output values.
ƞ is the learning rate (e.g., .05). ni, is the number of network inputs, nhidden the number of units in the hidden layer, and nout the number of output units.
The input from unit i into unit j is denoted xji, and the weight from unit i to unit j is denoted wji.


•	Create a feed-forward network with ni inputs, nhidden hidden units, and nout output units.

•	Initialize all network weights to small random numbers.

•	Until the termination condition is met, Do

 
•	For each (xi→,𝑡→ ), in training examples, Do
Propagate the input forward through the network:

Propagate the errors backward through the network.
![image](https://user-images.githubusercontent.com/86374358/218832076-d09d0705-4564-4eb5-964f-6d1449be6d3a.png)


 

