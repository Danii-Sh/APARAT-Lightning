# APARAT-Lightning

This work was one the contributions to my thesis, develpoing an LSTM based network metric prediction model
That monitored the network QoS metrics on `APARAT.com` the alternative for youtube in iran as access to youtube is restricted.
A dataset consisting of different attainable metrics was collected for 2 months, and after undergoing a heavy preprocessing phase, it was fed 
to a Long short term memory (LSTM) neural network.

#### A sample line of stored and processed dataset
![alt text](https://github.com/Danii-Sh/APARAT-Lightning/blob/fc760c37e88fb6b2a1cb727e34b5160dd44f7a64/Sample%20Output/Screenshot%202023-07-27%20224606.png)

The LSTM model provided insight on network and server behaviour. an example output for 
a small time slot is presented:
#### A sample prediction

![alt text](https://github.com/Danii-Sh/APARAT-Lightning/blob/fc760c37e88fb6b2a1cb727e34b5160dd44f7a64/Sample%20Output/Picture2.png)

As any information on Network status can open opportunities for a better management, we used QoS metrics like ping and congestion to devise a better
caching mechanism, that took into account a server that was going to become more heavily loaded. The idea can be greatly expanded into different 
types of network control and resource allocation.
#### Our new caching problem

![alt text](https://github.com/Danii-Sh/APARAT-Lightning/blob/fc760c37e88fb6b2a1cb727e34b5160dd44f7a64/Sample%20Output/Picture1.jpg)
