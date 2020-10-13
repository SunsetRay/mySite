---
# Documentation: https://wowchemy.com/docs/managing-content/

title: RLMob - Deep Reinforcement Learning for Successive Mobility Prediction (In submission)
subtitle: ''
summary: ''
authors:
- Ziyan Luo
- Congcong Miao
tags: []
categories: [Mobility, RL]
date: '2021-01-01'
lastmod: 2020-10-13T15:37:32+08:00
featured: false
draft: false
url_code: https://github.com/SunsetRay/RLMob

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2020-10-13T07:37:32.189966Z'
publication_types:
- '1'
abstract: "Human mobility prediction is an important task in the field of spatiotemporal\
  \ sequential data mining and urban computing. Despite the extensive work on mining\
  \ human mobility behavior, little attention was paid to the problem of successive\
  \ mobility prediction. At present, the state-of-the-art methods of human mobility\
  \ prediction are mainly based on traditional machine learning and deep learning.\
  \  To achieve higher predictability and adapt well to the successive mobility prediction,\
  \ there are four key challenges: 1) disability to the circumstance that the optimizing\
  \ target is discrete-continuous hybrid and non-differentiable. In our work, we assume\
  \ that  the user's demands are always multi-targeted and can be modeled as a discrete-continuous\
  \ hybrid function; 2) difficulty to alter the recommendation strategy flexibly according\
  \ to the changes in user needs in real scenarios;  3) error propagation and exposure\
  \ bias issues when predicting multiple points in successive mobility prediction;\
  \ 4) cannot interactively explore user's potential interest that does not appear\
  \ in the history. While previous methods met these difficulties, reinforcement learning\
  \ (RL) is an intuitive answer for this task to settle these issues. To the best\
  \ of our knowledge, this work is the first one to introduce RL to this task. In\
  \ this paper, we formulate this problem as a Markov Decision Process. We further\
  \ propose a framework - RLMob to solve our problem. A simulated environment is carefully\
  \ designed. An actor-critic framework with an instance of Proximal Policy Optimization\
  \ (PPO) is applied to adapt to our scene with a large state space. Experiments show\
  \ that on the task, the performance of our approach  is consistently superior to\
  \ that of the deep-learning-based approaches. "
publication: ''
---
