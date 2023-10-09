---
layout: splash
title: "Research"
permalink: /research/
author_profile: false
---

### Distributed Optimization and Learning

{: .text-justify style="font-size: 15pt" reversed="reversed"}
**Estimating tolerable communication delays for distributed optimization problems in control of heterogeneous multi-agent systems**

{: .text-justify style="font-size: 12pt" reversed="reversed"}
| <img src="/assets/images/opt1.png" width="2800px" alt="TV_network"> | This study addresses the problem of distributed optimization in control of heterogeneous linear multi-agent systems. Instead of assuming a perfect communication medium as in many existing approaches, we consider two important issues arising from communication networks. First, we assume the existence of communication delays when each agent receives information from its neighbors. Second, since communication networks are generally unreliable, we assume that each agent interacts with other agents through random digraphs. Finally, we derive delay-dependent sufficient conditions in the form of linear matrix inequalities (LMIs) to prove convergence to optimal solutions. |

{: .text-justify style="font-size: 15pt" reversed="reversed"}

{: .text-justify style="font-size: 15pt" reversed="reversed"}
**Online Optimization with Infrequent Feedback**

{: .text-justify style="font-size: 12pt" reversed="reversed"}
| <img src="/assets/images/Infrequent.png" width="3500px" alt="Infrequent"> | The avilability of data has become a challenge to overcome when we develop algorithms that depend on measurements at each instance of time. [Here](https://arxiv.org/pdf/2109.06343.pdf), we focused on a data-based online projected gradient algorithm where: the input-output map of the system is replaced by measurements of the output whenever available; and the unknown function is learned based on functional evaluations that may occur infrequently. i.e., we are dealing with a feedback-based online algorithm that operates in a regime with inexact gradient knowledge and with random updates. We provided error bounds in expectation and in high-probability, and also we stablished results in terms of input-to-state stability. Gaussian Processes is used as an example to estimate the uncertanties on the cost function. |

### Online Optimization and Learning for Power Systems

{: .text-justify style="font-size: 15pt" reversed="reversed"}
**Learning-Based Demand Response in Buildings**

{: .text-justify style="font-size: 12pt" reversed="reversed"}
| We developed a model-free predictive controller for a grid-interactive multi-zone building where the temperature dynamics are learned via Gaussian Process (GP) regression. We investigated the development of a learning predictive control with two main objectives: (i) continuously learn the temperature dynamics of the building based on data; and, (ii) use the learned dynamics to solve a multi-objective predictive control problem to guarantee occupants comfort and energy efficiency during normal conditions and demand response events. In this work a numerical case in a standard five-zone commercial building is presented. | <img src="/assets/images/GP-PC.png" width="3500px" alt="GP-PC_bar"> |

{: .text-justify style="font-size: 15pt" reversed="reversed"}
**Personalized Demand Response via Online Learning**

{: .text-justify style="font-size: 12pt" reversed="reversed"}
| <img src="/assets/images/GP_ex.png" width="2800px" alt="GP_ex"> | Demand response strategies are key to increase the flexibility and efficiency of power systems by allowing controllable devices to provide services at various time-scales. Nowadays, users have a high level of interaction with most of the controllable devices at the distribution level, therefore, we can have access to feedback from the user at different time intervals. In this context, we formalize a demand response task as an optimization problem featuring a known time-varying engineering cost - associated with the network- and an unknown (dis)comfort function -relative to the users-. One example of this setting is presented in this [paper](https://ieeexplore.ieee.org/document/9303020). | <img src="/assets/images/SHGP_ex.png" width="2800px" alt="SHGP_ex"> | 

{: .text-justify style="font-size: 15pt" reversed="reversed"}
**Estimation of Matrix Sensitivity**

{: .text-justify style="font-size: 12pt" reversed="reversed"}
| <img src="/assets/images/Fig_intro_R1_1.png" width="2800px" alt="sensitivity"> | Perfect knowledge of power systems parameters is a complex and expensive task, but it is vital to guarantee the proper performance of many systems that interact with the network. In this line of work, we focus on the estimation of sensitivity matrices in electrical transmission systems. We proposed an online proximal-gradient method to estimate sensitivities on-the-fly from real-time measurements by leveraging a nuclear norm minimization approach, as well as sparsity-promoting regularization functions. This [pre-print](https://arxiv.org/pdf/2006.16346.pdf) is our first approach on that direction. | <img src="/assets/images/Fig_9_BC_LSE_LR.png" width="2800px" alt="9bus_LSE_LR"> |
