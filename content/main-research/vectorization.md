---
title: "Towards High-Performance and Portable Molecular Docking on CPUs Through Vectorization"
authors:
  - Gianmarco Accordi
  - Jens Domke
  - Theresa Pollinger
  - Davide Gadioli
  - Gianluca Palermo
publisher: "IEEE International Conference on Cluster Computing (CLUSTER)"
year: 2025
badges:
  - HPC
  - Extreme-Scale Virtual Screening
  - CPU
featured:
  name: "Read paper"
  link: "https://doi.org/10.1109/CLUSTER59342.2025.11186493"
links:
  - icon: fas fa-file-pdf
    url: "https://re.public.polimi.it/retrieve/00096c20-8c2c-45ca-8fcd-a00bc265b3a2/pp_cpu_CLUSTER%20%282%29.pdf"
showInHome: true
build:
  render: never
  list: never\
---

Recent trends in the HPC field have introduced new CPU architectures with improved vectorization capabilities that require optimization to achieve peak performance and thus pose challenges for performance portability. The deployment of high-performing scientific applications for CPUs requires adapting the codebase and optimizing for performance. Evaluating these applications provides insights into the complex interactions between code, compilers, and hardware. We evaluate compiler auto-vectorization and explicit vectorization to achieve performance portability across modern CPUs with long vectors. We select a molecular docking application as a case study, as it represents computational patterns commonly found across HPC workloads. We report insights into the technical challenges, architectural trends, and optimization strategies relevant to the future development of scientific applications for HPC. Our results show which code transformations enable portable auto-vectorization, reaching performance similar to explicit vectorization. Experimental data confirms that x86 CPUs typically achieve higher execution performance than ARM CPUs, primarily due to their wider vectorization units. However, ARM architectures demonstrate competitive energy consumption and cost-effectiveness.