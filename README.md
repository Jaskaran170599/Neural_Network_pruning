# Neural_Network_pruning

## Weight Pruning

Weight pruning: set individual weights in the weight matrix to zero. This corresponds to deleting connections as in the figure above.

Here, to achieve sparsity of k% we rank the individual weights in weight matrix W according to their magnitude (absolute value), and then set to zero the smallest k%.

## Neuron Pruning

set entire columns to zero in the weight matrix to zero, in effect deleting the corresponding output neuron.

Here to achieve sparsity of k% we rank the columns of a weight matrix according to their L2-norm and delete the smallest k%.

