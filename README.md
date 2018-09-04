# tensorflow-computation-graph
Tensorflow (tf) is an open source machine learning framework for research, development and production purposes. 
It offers APIs for both desktop and mobile applications.

This repository is intended to provide an understanding of how a computation graph can be created and visualized using tensorflow. 
The ipython notebook containing the python code demonstrates the implementation of following simple arithmetic equations using tf:

1) x = a + b         
2) y = b * c
3) z = y - x

The objective is to compute equation 3) which is in turn dependent on 1) and 2).
Creating a computation graph of these equations using tf would mean that we just need to run equation 3) within the tf session.
Finally, the graph can be saved into a file and can be visualized using tensorboard with the following command in command line:

python -m path/to/tensorboard.main --logdir=path/to/log-directory
