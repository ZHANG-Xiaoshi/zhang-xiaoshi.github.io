---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


### [Motion simulation of a tensegrity snake-like robot based on the serpenoid curve (Published)](https://iopscience.iop.org/article/10.1088/1742-6596/1965/1/012033/meta)

Abstract: Due to their good motion performance, snake-like robots have been widely studied and researched
for years and still have a lot of research interest. In this paper, we propose a snake-like robot based on tensegrity
structure. Our snake-like robot is driven with cables on both sides, which is different from the serial structure
snake-like robots driving by the motor at the axis of rotation. In order to verify the feasibility of the snake-like
robot motion, we studied its inverse kinematics and performed simulation based on the serpenoid curve

7th International Forum on Manufacturing Technology and Engineering Materials (IFEMMT 2021)



### [Deep Reinforcement Learning for Double Inverted Pendulum Problem(Accepted)]()

Abstract: Double inverted pendulum is a strong non-linear, high-order, unstable system.This paper solves three control tasks of double inverted pendulum: the stablizing control, swinging-up control, and the upper-pendulum-rotating control, with deep reinforcement learning algorithms DDPG and TD3, and then evaluates the control performance with simulation. The control performance and the learning performance of TD3 and DDPG in the 3 control tasks, are compared and analyzed. To be mentioned the results show an anomaly that TD3 performs worse than DDPG in double inverted pendulum problem, which is worth to be further studied.

Accepted by "The 5th International Conference on Machine Learning and Machine Intelligence", however searching for more reputable conferences.




