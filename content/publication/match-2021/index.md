---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Match Plan Generation in Web Search with Parameterized Action Reinforcement
  Learning
subtitle: ''
summary: ''
authors:
- Ziyan Luo
- Linfeng Zhao
- Wei Cheng
- Sihao Chen
- Qi Chen
- Hui Xue
- Haidong Wang
- Chuanjie Liu
- Mao Yang
- Lintao Zhang
tags: [Deep Reinforcement Learning, Information Retrieval, Parameterized
Action Soft Actor-Critic, Search Engine]
categories: [RL]
date: '2020-10-20'
lastmod: 2020-10-13T15:37:31+08:00
featured: false
draft: false

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
publishDate: '2020-10-13T07:37:31.461842Z'
publication_types:
- '1'
abstract: To achieve good result quality and short query response time, search engines
  use specific match plans on Inverted Index to help retrieve a small set of relevant
  documents from billions of web pages. A match plan is composed of a sequence of
  match rules, which contain discrete match rule types and continuous stopping quotas.
  Currently, match plans are manually designed by experts according to their several
  years’ experience, which encounter difficulty in dealing with heterogeneous queries
  and varying data distribution. In this work, we formulate the match plan generation
  as a Partially Observable Markov Decision Process (POMDP) with a discrete-continuous
  hybrid action space, and propose a novel reinforcement learning algorithm Parameterized
  Action Soft Actor-Critic (PASAC) to effectively enhance the exploration in both
  spaces. We also introduce Stratified Prioritized Experience Replay (SPER) to address
  the challenge that the samples with high priority often center on a small range
  of the reward space. We are the first group to generalize this task for all queries
  as a learning problem with zero prior knowledge and successfully apply deep reinforcement
  learning in the real web search environment. Our approach greatly outperforms the
  well designed production match plans by over 70% reduction of index block accesses
  with the quality of documents almost unchanged, and 9% reduction of query response
  time even with model inference cost. Our method also beats the baselines on some
  open-source benchmarks.
publication: '*The Web Conference 2021* (WWW 2021, Accepted)'
url_pdf: files/RL_MatchPlanGen_WWW2021_Proceeding.pdf
url_slides: files/pasac.pdf
url_video: https://www.youtube.com/watch?v=trclQW0uS7U
---
