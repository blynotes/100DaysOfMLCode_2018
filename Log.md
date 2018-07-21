# 100 Days Of ML - LOG

## Day 0 : July 10, 2018
 
**Today's Progress** : Plan what to work on for first few weeks.

**Thoughts** : I'm looking forward to becoming more familiar with NumPy and gaining practice learning CNN's, RNN's, GAN's, and Deep Reinforcement Learning.


## Day 1 : July 11, 2018

**Today's Progress** : 
- Complete most of Topic 1 in my [Learning Plan](https://github.com/blynotes/100DaysOfMLCode_2018/blob/master/LearningPlan.md).
- Build a basic feedforward network with backpropagation using NumPy. This is based off of [Trask's Neural Network in 11 Lines of Python](https://iamtrask.github.io/2015/07/12/basic-python-network/)
- Modify my basic feedforward network to handle dynamic number of layers.

**Thoughts** : 
- It was a good refresher. I am feeling more comfortable with NumPy.
- I will move onto Topic 2 tomorrow and slowly continue reading the Deep Learning Book Part 1.

**Link of Work:**
- [Commit of basic FeedForward Network - Fixed number of layers](https://github.com/blynotes/NumPy-FeedForward-Network/commit/8c8dd48feed2ae2aff5e715a5ac770813f2154a2)
- [Commit of FeedForward Network - Dynamic number of layers](https://github.com/blynotes/NumPy-FeedForward-Network/commit/80fb5c8726fa3246be89825931f829283e23adb9)


## Day 2 : July 12, 2018

**Today's Progress** :
- Install Tensorflow on laptop
- Explore Tensorboard
- Read CS20 Tensorflow overview
- Read CS20 Tensorflow Operations

**Thoughts** :
- Tensorflow looks powerful.  I'm looking forward to writing some test programs tomorrow and playing with Tensorboard more.

**Link of Work:**
- None today


## Day 3 : July 13, 2018

**Today's Progress** : 
- Read CS20 (Tensorflow for Deep Learning Research) lectures and slides

**Thoughts** : 
- There is a lot of information in these slides.  I will start to play with Tensorflow and then come back in a few weeks to understand them better.

**Link of Work:**
- None today


## Day 4 : July 14, 2018

**Today's Progress** : 
- Completed 2 tutorials on the Tensorflow website:
  - Basic Classification Tutorial
  - Text Classification Tutorial

**Thoughts** : 
- It is very helpful to follow the tutorials.  It helps me understand how to write Tensorflow and Keras code.

**Link of Work:**   
- Basic Classification Tutorial [Commit](https://github.com/blynotes/Tensorflow-Tutorials/blob/master/1-FirstNN-BasicClassification.ipynb)
- Text Classification Tutorial [Commit](https://github.com/blynotes/Tensorflow-Tutorials/blob/master/2-ClassifyMovieReviews.ipynb)


## Day 5 : July 15, 2018

**Today's Progress** : 
- Finished Tensorflow Regression tutorial
- Researched hard drives, RAM, motherboard, and case for deep learning PC

**Thoughts** : 
- Hoping to finish picking parts for deep learning PC and order them tomorrow.

**Link of Work:**   
- Regression Tutorial [Commit](https://github.com/blynotes/Tensorflow-Tutorials/blob/master/3-BostonHousingPrices.ipynb)


## Day 6 : July 16, 2018

**Today's Progress** : 
- Picked out almost all of my Deep Learning computer's parts.
- Watched Siraj Raval's [Reinforcement Learning for Stock Prediction Video](https://www.youtube.com/watch?v=05NqKJ0v7EE)

**Thoughts** : 
- Hope to pick out the rest of the computer parts tomorrow.

**Link of Work:**   
- None today


## Day 7 : July 17, 2018

**Today's Progress** : 
- Found all parts for Deep Learning PC. I was planning on using fans to cool, but realized I needed to do water cooling to sufficiently cool the 2 Nvidia Titan XP Collector's Edition graphics cards.

**Thoughts** : 
- I will begin researching water cooling tomorrow.

**Link of Work:**   
- [Current list of parts... it may change as I bring in watercooling](https://pcpartpicker.com/list/Z7kDJ8)


## Day 8 : July 18, 2018

**Today's Progress** : 
- Researched watercooling.  Found other people that watercooled Titan XP Collector's Editions and began researching their parts.
- Found [EK Fluid Gaming parts](https://www.ekfluidgaming.com/)
- Found an [interesting article saying that evolutionary algorithms are able to outperform deep-learning at video games](https://www.technologyreview.com/s/611568/evolutionary-algorithm-outperforms-deep-learning-machines-at-video-games/)

**Thoughts** : 
- The concept of watercooling is simple, I just need to determine exactly which parts I need to sufficiently cool my PC.
- I will write a simple evolution algorithm tomorrow

**Link of Work:**   
- None today


## Day 9 : July 19, 2018

**Today's Progress** : 
- Completed a genetic algorithm to solve the Traveling Salesman Problem.
- Emailed EK Fluid Gaming's help desk to find out what components I needed to cool my Deep Learning PC. After talking with them, I determined I needed:
  1. [A360G kit (I won't use the pump that comes with it though)](https://www.ekfluidgaming.com/ek-kit-a360g)
  2. [D5 pump](https://www.ekfluidgaming.com/ek-acr-revo-d5-mx)
  3. [EK-AC GEFORCE GTX Water Block](https://www.ekfluidgaming.com/ek-ac-titan-x)
  4. [Vertical pump mount (to mount the pump combo in my case to a fan or radiator so I don't have ot drill holes)](https://www.ekfluidgaming.com/ek-uni-pump-bracket-120mm-fan-vertical)
  5. [Multi-GPU kit](https://www.ekfluidgaming.com/ek-ac-gpu-connector-kit)
  6. [EK-FG 360 Expansion Pack to get a second radiator (one radiator would not sufficiently cool the CPU and 2 GPUs)](https://www.ekfluidgaming.com/ek-fg-360-expansion-pack)
  7. [Colored fluid (if I want it). The kit comes with clear fluid](https://www.ekfluidgaming.com/parts/)

**Thoughts** : 
- The genetic algorithm was interesting to implement. I plan to revisit this more after I do some reinforcement learning to compare the results.
- The help desk at EK Fluid Gaming was very helpful and I am understanding better the parts needed and what they do.
- I need to find a case that will fit my motherboard (it is SSI CEB form factor... I may try to find a different motherboard as well), 2 radiators, and all of the watercooling components.

**Link of Work:**   
- Genetic Algorithm - Traveling Salesman Problem [Commit](https://github.com/blynotes/GeneticAlgorithmTSP/blob/master/Traveling%20Salesman%20-%20Genetic%20Algorithm.ipynb)


## Day 10 : July 20, 2018

**Today's Progress** : 
- My Jupyter Notebook stopped working, so I had to troubleshoot and ended up re-installing it.
- Finished Tensorflow tutorial on Overfitting and Underfitting
- Watched YouTube videos by [Steve Brunton on using Genetic Programming to optimize the structure and parameters of an effective control law](https://www.youtube.com/watch?v=CZE86BPDqCI)

**Thoughts** : 
- I plan to finish the Tensorflow tutorials this weekend, and start something larger before the end of the weekend.
- I want to play with Genetic Algorithms more on future projects.  I find them really interesting.
- I also plan to finalize my computer parts (hopefully finding a computer case tomorrow) and order the parts before Monday.

**Link of Work:**   
- Tensorflow Tutorial - Overfitting and Underfitting [Commit](https://github.com/blynotes/Tensorflow-Tutorials/blob/master/4-Overfitting%20and%20Underfitting.ipynb)


<!--
## Day 11 : July 21, 2018

**Today's Progress** : 
- TODO

**Thoughts** : 
- TODO

**Link of Work:**   
- TODO [Commit](https://github.com/LordSomen/100DaysOfML/commit/a09148256d1561f5f9e5544ff3f64aacf0d24f43)

-->
