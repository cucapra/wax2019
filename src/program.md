---
title: "Program"
layout: layout.html
order: 1
---

## WAX 2019 Program

### Saturday, June 22, 2019
### Location TBD

**9:00--9:15am**: Opening and introductions

**9:15--10:15am**: Keynote

**Hardware Efficiency Aware Neural Architecture Search and Model Compression**  
[Song Han][han], MIT

*Abstract:* Efficient deep learning computing requires algorithm and hardware co-design to enable specialization: we usually need to change the algorithm to reduce memory footprint and improve energy efficiency. However, the extra degree of freedom from the algorithm creates a much larger design space: it’s not only about designing the hardware but also about how to change the algorithm to best fit the hardware. Human engineers can hardly exhaust the design space by heuristics. It’s labor consuming and sub-optimal. We propose design automation techniques for efficient neural networks (ref). We investigate automatically designing small and fast models (ProxylessNAS), auto channel pruning (AMC), and auto mixed-precision quantization (HAQ). We demonstrate such learning-based, automated design achieves superior performance and efficiency than rule-based human design. Moreover, we shorten the design cycle by 200× than previous work, so that we can afford to design specialized neural network models for different hardware platforms.

[han]: https://songhan.mit.edu/

**10:15--11:00**: Talks I

Talks for position papers are 10 minutes each. There will be a short period for clarification questions after each talk and a longer, themed discussion period at the end of the session.

- [NAP: Noise-Based Sensitivity Analysis for Programs.][michel]  
  Jesse Michel (Massachusetts Institute of Technology); Sahil Verma (IIT Kanpur); Ben Sherman, Michael Carbin (Massachusetts Institute of Technology).

- [Identifying Optimal Parameters for Approximate Randomized Algorithms.][fernando]  
  Vimuth Fernando, Keyur Joshi, Darko Marinov, Sasa Misailovic (UIUC).

- [Co-Optimization of Optics, Architecture, and Vision Algorithms.][triest]  
  Samual Triest, Daniel Nikolov, Jannick Rolland, Yuhao Zhu (University of Rochester).

**11:00--11:20am**: Break

**11:20--12:30pm**: Talks II

Position paper (10-minute talk):

- [Approximate Checkers.][mahmoud]  
  Abdulrahman Mahmoud, Paul Reckamp, Panqiu Tang, Christopher W. Fletcher, Sarita V. Adve (UIUC).

[fernando]: papers/fernando.pdf
[triest]: papers/triest.pdf
[mahmoud]: papers/mahmoud.pdf
[michel]: papers/michel.pdf

Invited talks (25-minute talks):

**Approximate Computing Across the (Quantum) Stack**  
[Yipeng Huang][huang], Princeton

*Abstract:* Recent advances in prototype quantum computers have led to burgeoning interest in experimenting with quantum algorithms. In order to bridge the gap between quantum algorithm specifications and physical quantum hardware, researchers need tools to aid in the testing and debugging of quantum algorithm implementations. This talk will focus on two aspects of this research area:

The first aspect is in providing debugging tools for programmers. Compared to debugging classical computers, quantum debugging is challenging because we cannot obtain complete information about the program state. We propose using statistical assertions as tests that check for expected values inside quantum programs. Using such assertions we are able to effectively debug several benchmark algorithms, including one for the Shor’s factoring algorithm.

The second aspect is in finding new ways to simulate quantum program runs on classical computers. Surprisingly, quantum simulation can be thought as an extension of probabilistic inference on Bayesian networks, a task that is familiar to researchers in approximate computing. In our ongoing research work, we use knowledge compilation techniques from probabilistic inference for quantum simulation. The most notable advantage of this approach is it leads to more efficient repeated simulations on quantum programs differing in only parameters.

Overall, these two research directions are two examples of taking ideas from approximate, statistical, and probabilistic computing, and applying them the closely related area of quantum computer research.

**Approximation is Bliss: approximate computing in database systems.**  
[Yongjoo Park][park], University of Michigan, Ann Arbor
  
*Abstract:*  Despite advances in computing power, the cost of large-scale data analytics and machine learning remains daunting to small and large enterprises alike. In tackling this issue, sampling-based approximate computing provides an appealing solution: we can offer 100x cheaper data analytics at 0.1% accuracy loss, exploiting the results of asymptotic statistics. In this talk, I discuss what systems limitations are in bringing this attractive benefit to actual data analysts; then, I present our recent effort to overcome them.

[huang]: http://yipenghuang.com/
[park]: https://yongjoopark.com/

**12:30pm--1:30pm**: Lunch

**1:30--2:30pm**: Discussion
