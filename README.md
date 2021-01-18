# Iris DAG Test Network
This project aimed to test a Directed Acyclic Graph architecture in a basic classifier neural network, in order to determine potential advantages over linear networks. The Iris flower dataset is used for training and evaluation.

# Conclusion:
After examining post-training weights, the network does not appear to need a DAG weight setup - a standard, linear network would (for this case at least) do the job just as well. A potential application for this architecture could be a use case where static weights or layers impede accurate data forward-propogation, requiring a topological, DAG-like detour.

# Used Resources:
Keras Documentation: https://keras.io/
Iris Dataset: https://archive.ics.uci.edu/ml/datasets/Iris/

# Misc:
Project completed in Fall 2020. Readme updated Jan 18, 2021.
