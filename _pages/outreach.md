---
layout: single
permalink: /outreach/
title: Outreach
author_profile: false
comments: false
redirect_from: 
  - "/outreach"
---
{% include base_path %}

# Lemonade Stand: A mini-game to understand challenges in data-driven decision-making

This activity is targeted at high-school students. The goal is to introduce the concept of causality via a simple game, where the player operates a lemonade stand. If you are a teacher and would like to use the game and slides, please feel free to do so. 

After moving the files to a folder, in terminal (Mac) or Anaconda command prompt (Windows) run 

`python lemonade_stand_Stage1.py`

for the first stage of the game. In this stage, player observes historical data, and decides whether to give away a Beanie, or Sunglasses as the promotional item to increase the sales. 

Teacher then can go over the slides to reveal the causal structure and why sunglasses is strongly correlated with higher prices, but giving away sunglasses do not increase profit. 

In the second stage, the goal is to use this causal knowledge to come up with the best policy: Look at the customer features, and decide which customers a promotional Beanie should be given to. To start the second phase of the game, run

`python lemonade_stand_Stage2.py`

After allowing students to discover the best policy, the teacher can then go over the remaining slides to explain what was the best policy, reasoning from the causal graph and conclude the activity. 

The code files can be downloaded [here](https://github.com/mkocaoglu/mkocaoglu.github.io/blob/master/files/Lemonade_Stand_Final.zip), the slides can be downloaded [here](https://github.com/mkocaoglu/mkocaoglu.github.io/blob/master/files/LemonadeStand.pdf).


Supported by NSF CAREER grant 2239375.
