# Testing

Install Gurobi using the following:

$ conda install -c gurobi gurobi

Go to the gurobi website and get an academic license followed by

$ grbgetkey 0f35dfb6-e001-11ec-98d2-0242ac130003

$ git clone https://github.com/manmeet3591/IP4AncADMG

$ cd src 

$ python LearnLatent.py

# IP4AncADMG
Code for the paper "Integer Programming for Causal Structure Learning in the Presence of Latent Variables" (https://proceedings.mlr.press/v139/chen21c.html)

Results in the paper were generated using Python 3.6.5 and Gurobi 8.1.1

Run src/LearnLatent.py for testing on an example instance
