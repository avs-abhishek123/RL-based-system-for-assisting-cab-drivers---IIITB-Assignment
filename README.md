# RL based system for assisting cab drivers - IIITB Assignment [![](https://img.shields.io/badge/Prateek-Ralhan-brightgreen.svg?colorB=ff0000)](https://prateekralhan.github.io/)


Developed by:
1. [Deepa Kushwaha](https://github.com/deepakush)
2. [Prateek Ralhan](https://github.com/prateekralhan)

### Problem Statement
We are hired as Sr. Machine Learning Er. at SuperCabs, a leading app-based cab provider in a large Indian metro city. In this highly competitive industry, retention of good cab drivers is a crucial business driver, and we believe that a sound RL-based system for assisting cab drivers can potentially retain and attract new cab drivers. Cab drivers, like most people, are incentivised by a healthy growth in income. The goal of this project was to build an RL-based algorithm which can help cab drivers maximise their profits by improving their decision-making process on the field.

##### The Need for Choosing the 'Right' Requests
Most drivers get a healthy number of ride requests from customers throughout the day. But with the recent hikes in electricity prices (all cabs are electric), many drivers complain that although their revenues are gradually increasing, their profits are almost flat. Thus, it is important that drivers choose the 'right' rides, i.e. choose the rides which are likely to maximise the total profit earned by the driver that day.
&nbsp;
For example, say a driver gets three ride requests at 5 PM. The first one is a long-distance ride guaranteeing high fare, but it will take him to a location which is unlikely to get him another ride for the next few hours. The second one ends in a better location, but it requires him to take a slight detour to pick the customer up, adding to fuel costs. Perhaps the best choice is to choose the third one, which although is medium-distance, it will likely get him another ride subsequently and avoid most of the traffic. 
There are some basic rules governing the ride-allocation system. If the cab is already in use, then the driver won’t get any requests. Otherwise, he may get multiple request(s). He can either decide to take any one of these requests or can go ‘offline’, i.e., not accept any request at all. 

### Objective(s):
In this project, you need to create the environment and an RL agent that learns to choose the best request. You need to train your agent using vanilla Deep Q-learning (DQN) 

#### Goals
* Create the environment
* Build an agent that learns to pick the best request using DQN and create a final DQN model.
* Check for the convergance of Q-values by sampling a few state-action pairs and plotting their Q-values along episodes

### Installation:
Run ***pip install -r requirements.txt*** to install all the dependencies.

### Usage:
Simply execute the command : ***jupyter notebook*** in your console/terminal to launch the Jupyter code and follow accordingly.

### Results:
![1](https://user-images.githubusercontent.com/29462447/92985720-d7db3b80-f4d2-11ea-8852-b5cb410eca03.png)
![2](https://user-images.githubusercontent.com/29462447/92985721-d9a4ff00-f4d2-11ea-909b-e17904cfdb0a.png)

