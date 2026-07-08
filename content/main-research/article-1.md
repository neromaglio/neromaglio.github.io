---
title: "mARGOt: A Dynamic Autotuning Framework for Self-Aware Approximate Computing"
authors:
  - Davide Gadioli
  - Emanuele Vitali
  - Gianluca Palermo
  - Cristina Silvano
publisher: "IEEE Transactions on Computers"
year: 2019
badges:
  - Autonomic Computing
  - Self-Optimization
  - Approximate Computing
featured:
  name: "Read paper"
  link: "https://doi.org/10.1109/TC.2018.2883597"
links:
  - icon: fas fa-file-pdf
    url: "https://re.public.polimi.it/retrieve/e0c31c0f-278d-4599-e053-1705fe0aef77/mARGOt_GreenOpenAccess.pdf"
showInHome: true
build:
  render: never
  list: never\
---

In the autonomic computing context, the system is perceived as a set of autonomous elements capable of self-management, where end-users define high-level goals and the system shall adapt to achieve the desired behaviour. Runtime adaptation creates several optimization opportunities, especially if we consider approximate computing applications, where it is possible to trade off the accuracy of the result and the performance. Given that modern systems are limited by the power dissipated, autonomic computing is an appealing approach to increase the computation efficiency. In this paper, we introduce mARGOt, a dynamic autotuning framework to enhance the target application with an adaptation layer to provide self-optimization capabilities. The framework is implemented as a C++ library that works at function-level and provides to the application a mechanism to adapt in a reactive and a proactive way. Moreover, the application is capable to change dynamically its requirements and to learn online the underlying application-knowledge. We evaluated the proposed framework in three real-life scenarios, ranging from embedded to HPC applications. In the three use cases, experimental results demonstrate how, thanks to mARGOt, it is possible to increase the computation efficiency by adapting the application at runtime with a limited overhead.