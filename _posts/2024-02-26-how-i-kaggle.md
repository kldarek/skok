---
toc: false
layout: post
description: My approach to Kaggle competitions.
categories: [learning, kaggle]
title: How I Kaggle
---

Hyperparameter tuning is a trap!*

In my early Kaggle days, I fell into the trap of tuning hyperparameters on public LB. It's addictive - you make small changes with little effort, and get immediate short term reward. The problem is that this doesn't result in much learning, and is unlikely to bring you private LB success. After rightfully falling on private LB, I learned my lesson and with time adopted different strategies that I want to share in this article. 

## Pick the right competition

My primary motivation when picking a competition is how interesting it is for me. Some competitions feel boring, some feel repetitive, and some are genuinely interesting. 

Here are some characteristics that make an interesting competition for me: 
1. *Meaningful Problem*. Modeling a real, challenging, ambitious problem that is hard to solve. There are plenty of hard problems that humans still need to solve, and I feel good about contributing my time and effort to such competitions. This usually requires significant learning of a new domain, and this makes it even more rewarding for me. I'd rather spend my time trying to predict mRNA structure than predict cryptocurrency prices. 
2. *Novelty*. Ideally, solving an interesting Kaggle challenge requires developing some new methods. It's nice if I can start with a working pipeline and test methods from literature, but the real fun begins when I experiment with new ideas. 
3. *Quirk*. Usually, real problems have quirks that allow approaching them from different angles. I feel at my best when I can try some [unconventional approaches](https://www.kaggle.com/competitions/commonlitreadabilityprize/discussion/244306). 

It's also important for a Kaggle competition to allow for some reliable evaluation of experiments, ideally both on local CV and public LB. It's risky to approach competitions that don't warrant it, but if I can still learn, I will sometimes [take that risk](https://www.kaggle.com/competitions/novozymes-enzyme-stability-prediction/discussion/376369). 

## Choose the Hard Way

While changing a hyperparameter is quick and easy, implementing a novel method is often time consuming and hard. I usually do Kaggle in the night after work and family time, often when I'm tired. It's difficult then to get enough energy to get started on a difficult task. In fact, I'm in a similar situation writing this article now. For me, listening to music helps, and just getting started, counting on flow-state to kick in and carry me forward. It's also nice to wake up and see experiment results. 

## Choose your team wisely

A great perk of Kaggle is the ability to team up and work on competitions with others. When choosing a team, I often look for diversity - this usually gives better results on the leaderboard and also boosts learning. To be able to learn from your team, it's good to allow several weeks for collaboration. I also like to start solo - I think this helps developing original ideas. Of course, integrity of the team is critical, it's important that everybody plays fair and follows the rules. 

## Let your mind work

This tactic worked for me several times: I spend intense time early on during a competition, dig into the problem and try to think about potential solutions and experiment. After the first set of experiments, I take a break for several weeks, and then come back. I feel that my mind keeps working while I'm away from the competition. I spot relevant papers. I think of new methods. When I come back, I have lots of ideas and energy for implementation. 

## Don't follow my advice

Many years ago I heard from a mentor that 50% of things people say are not true. Sometimes it's bad intent, but most often it's wrong intuitions, bad memory, mistakes, or speaking in LLM terms - hallucination. I said at the beginning that hyperparameter tuning is a trap*, but recently Kaggle #1 Philipp Singer said that it's [critical to success](https://twitter.com/ph_singer/status/1757323790277615707). I also realized that when going for the quantity of novel ideas and experiments, I sometimes dropped a perfectly good idea by not giving it enough love - spending more time debugging, refactoring and tuning hyperparameters can be critical to success!

