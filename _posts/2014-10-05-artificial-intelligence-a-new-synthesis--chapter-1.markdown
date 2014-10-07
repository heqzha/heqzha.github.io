---
layout: post
title: "Artificial Intelligence A New Synthesis - Chapter 1"
date: "2014-10-05"
categories: Blog
tags: [notes, ai, top-down, bottom-up]
comments: true
disqus_identifier: 2014100501
share: true
published: true
---

The chapter 1 mainly discussed definition of AI, the approaches for AI, history of AI and some additional discussions. To facilitate understanding what is AI and what is it used for, this post focuses on the first two parts.

###What Is AI?
> Artificial Intelligence(AI), broadly defined, is concerned with intelligent behavior in artifacts. The intelligent behavior involves perception, reasoning, learning, communicating and acting in complex environments. [Section 1.1]

According to the broad definition, an AI object must satisfies two factors: Firstly, it is manufactured by human or other intelligence organisms(Maybe aliens); Secondly, it must have a ability to perceive the outside world, make logical inferences and react to the outside world, and it also needs the ability to learn from experiences and share its knowledge to other AIs.

The definition of AI still has been surrounded by controversy. A question "Can machine think?" was proposed and interested scientists, engineers, even philosophers. To answer this question, the words "can", "machine" and "think" must be defined first.

1. Can: It is not decided that the human-level thinking machine can be built or not, but the AI progress toward that goal has been steady. The author is optimistic about the success.
2. Machine: According to the physical symbol system hypothesis of [Newell and Simon 1976](http://dl.acm.org/citation.cfm?id=360022), a physical symbol system is a machine which is capable of manipulating symbolic data. That means that it doesn't matter what the physical symbol system is made of.
3. Think: For now, it is almost impossible to define "think". Instead of that, [Turing Test](http://loebner.net/Prizef/TuringArticle.html) is proposed.

###Approaches to Artificial Intelligence
Even though AI has already produced some practically useful systems, it is generally conceded that the ultimate goal of achieving human-level intelligence is still distant. Over the past half century, numbers of different approaches have emerged. These approaches can be separated into two major groups:

1. Top-down approaches: Cognition is treated as a high-level phenomenon that is independent of the low-level details of the implementing mechanism.

2. Bottom-up approaches: Taking an opposite approach and simulate networks of artificial neurons are similar to the neurons in the human brain.

The difference between the two approaches may be illustrated by considering the task of building a system to discriminate between W, say, and other letters. A bottom-up approach could involve presenting letters one by one to a neural network that is configured somewhat like a retina, and reinforcing neurons that happen to respond more vigorously to the presence of W than to the presence of any other letter. A top-down approach could involve writing a computer program that checks inputs of letters against a description of W that is couched in terms of the angles and relative lengths of intersecting line segments. Simply put, the currency of the bottom-up approach is neural activity and of the top-down approach descriptions of relevant features of the task.[Reference](http://www.alanturing.net/turing_archive/pages/reference%20articles/what_is_AI/What%20is%20AI09.html)

Intermediate between the top-down and bottom-up approaches is on based on situated automata of [Kaelbling and Rosenschein 1990](http://www.sciencedirect.com/science/article/pii/S0921889005800272)[Rosenschein and Kaelbling 1995](http://www.sciencedirect.com/science/article/pii/0004370294000567).
