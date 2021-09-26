---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
  - /resume
---
* [Learning Robot Exploration Strategy with Deep Reinforcement Learning (12.2020 -- 07.2021)](#anchor6)

* [Efficient Heuristic Generation for Robot Path planning (07.2020 -- 10.2020)](#anchor5)

* [A sampled-based trajectory planning method for urban autonomous vehicles (07.2019 -- 01.2020)](#anchor)

* [Path planning for a laser scanning robot system (02.2019 -- 06.2019)](#anchor2)

* [Intelligent operation of robot arm (09.2018 -- 01.2019)](#anchor3)

* [Smart car competition (10.2017 -- 08.2018)](#anchor4)

### <span id = "anchor6">Learning Robot Exploration Strategy with Deep Reinforcement Learning</span>
* Advisor: Max Q.-H. Meng , IEEE Fellow and Professor in Department of Electrical and Electronic Engineering, SUSTech

<center><img src='/images/RAL2021.png' width="45%" height="45%" /></center>
  
Being able to explore unknown environments is a requirement for fully autonomous robots. Many learning-based methods have been proposed to learn an exploration strategy. In the frontier-based exploration, learning algorithms tend to learn the optimal or near-optimal frontier to explore. Most of these methods represent the environments as fixed size images and take these as inputs to neural networks. However, the size of environments is usually unknown, which makes these methods fail to generalize to real world scenarios. To address this issue, we present a novel state representation method based on 4D point-clouds-like information, including the locations, frontier, and distance information. We also design a neural network that can process these 4D point-clouds-like information and generate the estimated value for each frontier. Then this neural network is trained using the typical reinforcement learning framework. We test the performance of our proposed method by comparing it with other five methods and test its scalability on maps that are much larger than maps in the training set. The experiment results demonstrate that our proposed method needs shorter average traveling distances to explore whole environments and can be adopted in maps with arbitrarily sizes. 


### <span id = "anchor5">Efficient Heuristic Generation for Robot Path planning </span>
* Advisor: Max Q.-H. Meng , IEEE Fellow and Professor in Department of Electrical and Electronic Engineering, SUSTech

<center><img src='/images/FrameworkICRA2021.png' width="45%" height="45%" /></center>
  
Robot path planning is difficult to solve due to the contradiction between the optimality of results and the complexity of algorithms, even in 2D environments. To find an optimal path, the algorithm needs to search all the state space, which costs many computation resources. To address this issue, we present a novel recurrent generative model (RGM), which generates efficient heuristic to reduce the search efforts of path planning algorithms. This RGM model adopts the framework of general generative adversarial networks (GAN), which consists of a novel generator that can generate heuristic by refining the outputs recurrently and two discriminators that check the connectivity and safety properties of heuristic. We test the proposed RGM module in various 2D environments to demonstrate its effectiveness and efficiency. The results show that, compared with a model without recurrence, the RGM successfully generates appropriate heuristic in both seen and new unseen maps with higher accuracy, demonstrating the good generalization ability of the RGM model. We also compare the rapidly-exploring random tree star (RRT*) with generated heuristic and the conventional RRT* in four different maps, showing that the generated heuristic can guide the algorithm to efficiently find both initial and optimal solutions in a faster and more efficient way.


### <span id = "anchor">A sampled-based trajectory planning method for urban autonomous vehicles</span>
* Advisor: Masayoshi Tomizuka , IEEE Fellow and Professor of Mechanical Engineering, UC Berkeley

<center><img src='/images/DEB work flow.png' width="75%" height="75%" /></center>
  
In this project, we designed a motion planning method for urban autonomous vehicles. This method have the advantages of fast sampling speed, time-bounded collison-free path generation and sampling-based decision making method. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/O0E2lmW-gVM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<iframe width="448" height="252" src="https://www.youtube.com/embed/5IC28z9ZNMo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


### <span id = "anchor2">Path planning for a laser scanning robot system</span>
* Advisor: Huijun Gao , IEEE Fellow and Professor of Department of Automation, Harbin Institute of Technology
<center><img src='/images/results2.png' width="33%" height="33%" /><img src='/images/scan_result05.png' width="33%" height="33%" /></center>

Laser scanning has been widely used in the industrial manufacturing, especially in reverse engineering, quality control and surface defect detection. Achieving automatic scanning can succeed in reducing production costs and increasing production efficiency. In our project, we proposed an automatic intelligent scanning system based on ROS, including robot arm, RGBD camera and line laser scanner.



<iframe width="560" height="315" src="https://www.youtube.com/embed/BE4FbGaB_Kc" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### <span id = "anchor3">Intelligent operation of robot arm</span>
* Advisor: Huijun Gao , IEEE Fellow and Professor of Department of Automation, Harbin Institute of Technology
  * Employed the linear-quadratic-Gaussian regulator (LQG) to make the UR10 robot arm move to a designated position.
  * Modified the guided policy search method (a policy search method in reinforcement learning) in executing simulated robotic manipulation tasks.
  * Used position control with guided policy search method to train the UR10 robot arm move to a designatedposition without using inverse kinematics
<iframe width="560" height="315" src="https://www.youtube.com/embed/CcBsTdofb0o" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


### <span id = "anchor4">Smart car competition</span>

During the second year at university, I attended the 13th Chinese national NXP CUP smart car competition, which is one of the most famous competitions in China.

<center><img src='/images/smartcar03.jpg' width="25%" height="25%" /><img src='/images/smartcar04.jpg' width="40%" height="40%" /></center>
<center><img src='/images/smartcar01.png' width="50%" height="50%" /><img src='/images/smartcar02.png' width="36%" height="36%" /></center>


<iframe width="560" height="315" src="https://www.youtube.com/embed/_3HYpM_5XqU" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
