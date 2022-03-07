# MOPED: MOtion PrEdiction for Autonomous Driving in Traffic

**[AdaComp](https://adacomp.comp.nus.edu.sg/), National University of Singapore**

**Are you interested in Autonomous Driving? Do you want to be the brain of the next generation of smart cars?**

![match3](https://user-images.githubusercontent.com/24559595/156965133-415211e4-de5c-43ea-8777-798de7b07079.png)

## Overview

Our Adacomp Lab aims to build robots that think and act like humans. One important application is autonomous driving, especially driving in heavy traffic with heterogeneous agents (illustrated in the video below).

https://user-images.githubusercontent.com/24559595/156963306-826d55e8-5051-44b7-a7d6-f06f54d2989e.mp4


To drive safely and smoothly in such traffic, the smart cars have to **reason about** and **predict** the motion of other nearby vehicles and pedestrians.

https://user-images.githubusercontent.com/24559595/156963315-61e7603f-25a2-48d8-83d2-05c53883edfd.mp4



We identified **motion prediction** as a key challenge of autonomous driving: predicting the future positions of surrounding traffic participants, so that the robot vehicle can decide on its own motion accordingly.

## Background and Motivation of MOPED
There are two general approaches to motion prediction. 

- **Analytical** prediction methods follow a set of handcrafted rules or optimize a handcrafted objective. 
- **Data-driven** methods learn prediction models from trajectory datasets. 
 
They differ significantly in prediction accuracy, computational efficiency, data efficiency for learning, …, and each has strengths and weaknesses. The lack of systematic evaluation and comparison hinders the progress of autonomous driving.  The two common evaluation metrics, average displacement error (ADE) and final displacement error (FDE), seem natural, but may not directly impact driving decisions.


## Project Details

**In this project, we will build an experimental framework (evaluation criteria, datasets, and a simulator) for systematic evaluation of motion prediction methods. We intend to release the experimental framework as open-source software and publish a paper on the findings to report on the state of the art.**

In this summer research project, you will gain experiences in some of the following:

+ Choose representative analytical and data-driven models and conduct a comprehensive study on their performance using a richer set of evaluation metrics.
+ Evaluate the motion prediction models for driving performance in a high-fidelity simulator.
+ Evaluate the prediction models using both real-world datasets, e.g., ArgoVerse, and a real-time driving simulator, e,g, SUMMIT, to compare performance in “canned” and interactive settings.
+ Propose new ideas to improve the prediction and planning methods for autonomous driving. 

The expected duration of the project is 3 months, which may be extended based on mutual agreement. You may participate either on-site or remotely with.

## Contact Us

You are invited to submit the application along with your CV by emailing to [moped](moped_adacomp@googlegroups.com). 
Look forward to working with you on the exciting research!

