---
# Display name
title: Zhonghao Chen

# Full name (for SEO)
first_name: Zhonghao
last_name: Chen

# Is this the primary user of the site?
superuser: true

# Highlight the author in author lists? (true/false)
highlight_name: true

# Role/position/tagline
role: Ph.D. Student@ECE

# Organizations/Affiliations to display in Biography blox
organizations:
  - name: University of Florida
    url: https://www.ufl.edu/
  - name: University of California, Merced
    url: https://www.ucmerced.edu/

# Social network links
# Need to use another icon? Simply download the SVG icon to your `assets/media/icons/` folder.
profiles:
  - icon: at-symbol
    url: 'mailto:zh.chen@ufl.edu'
    label: E-mail
  - icon: phone
    url: 'tel:+12095043779'
    label: Phone

interests:
  - High-Performance Computing
  - Networking and Communication
  - LLM Training/Inference
  - Federated Learning System
  - AI–HPC Co-design

education:
  - area: Ph.D. in Electrical and Computer Engineering
    institution: University of Florida
    date_start: 2026-01-01
    date_end: ''
    summary: |
      Advisor: Prof. Xiaoyi Lu
  - area: Ph.D. in Electrical Engineering and Computer Science
    institution: University of California, Merced
    date_start: 2024-08-01
    date_end: 2025-12-31
    summary: |
      Advisor: Prof. Xiaoyi Lu  
      Transferring to the University of Florida in January 2026.
  - area: B.E. (with Honors), Computer Science and Technology
    institution: Tianjin University
    date_start: 2020-09-01
    date_end: 2024-07-01

work:
  - position: Graduate Research Assistant (Federated Learning Systems)
    company_name: University of California, Merced
    company_url: 'https://www.ucmerced.edu/'
    company_logo: ''
    date_start: 2024-07-01
    date_end: ''
    summary: |2-
      - Designed a scalable and fault-tolerant modeling and simulation framework for complex federated learning (FL) workflows across cross-silo and cross-device scenarios.
      - Developed a discrete-event simulator on SimGrid to model FL training, communication, and aggregation with heterogeneous compute and network resources.
      - Implemented a communication-centric state machine supporting synchronous, asynchronous, and semi-asynchronous aggregation.
      - Built a user-space, MPI-level long-haul RDMA simulator to compare RDMA vs. TCP/IP for geo-distributed FL workloads, and verified on ESNet testbed.
  - position: Graduate Research Assistant (LLM Reasoning Models on HPC)
    company_name: University of California, Merced
    company_url: 'https://www.ucmerced.edu/'
    company_logo: ''
    date_start: 2024-12-01
    date_end: ''
    summary: |2-
      - Characterized inference and distillation performance of large reasoning models on HPC-scale GPU clusters and interconnects.
      - Scaled model deployment up to 3,840 GPUs using data/tensor/pipeline/expert parallelism, prefill-decode disaggregation, and KV-cache transfer engines.
      - Analyzed pipeline imbalance, communication overhead, and KV-cache bottlenecks to identify efficient configurations for scalable inference.
      - Tools: Python, C/C++, CUDA, MPI/NCCL, DeepSpeed/Megatron, vLLM, VeRL, Ray; profiling with PyTorch Profiler and Nsight Systems.
  - position: Software Engineer Intern (GUI Development)
    company_name: NXP Semiconductors
    company_url: ''
    company_logo: ''
    date_start: 2023-04-01
    date_end: 2023-06-30
    summary: |
      GUI development internship.
  - position: Software Engineer Intern (iOS Backend Development)
    company_name: Tianjin University Software Studio (TWT)
    company_url: ''
    company_logo: ''
    date_start: 2020-11-01
    date_end: 2021-05-31
    summary: |
      iOS backend development internship.

# Skills
# Add your own SVG icons to `assets/media/icons/`
skills:
  - name: Programming
    items:
      - name: Python
        description: ''
        percent: 90
        icon: code-bracket
      - name: C/C++
        description: ''
        percent: 80
        icon: code-bracket
      - name: CUDA
        description: ''
        percent: 70
        icon: code-bracket
  - name: Systems & Tools
    items:
      - name: MPI / NCCL
        description: ''
        percent: 75
        icon: circle-stack
      - name: PyTorch
        description: ''
        percent: 85
        icon: chart-bar
      - name: DeepSpeed / Megatron
        description: ''
        percent: 70
        icon: circle-stack
      - name: vLLM / Ray
        description: ''
        percent: 65
        icon: circle-stack
      - name: SimGrid
        description: ''
        percent: 60
        icon: circle-stack
      - name: Profiling (PyTorch Profiler, Nsight Systems)
        description: ''
        percent: 60
        icon: chart-bar

# Awards.
#   Add/remove as many awards below as you like.
#   Only `title`, `awarder`, and `date` are required.
#   Begin multi-line `summary` with YAML's `|` or `|2-` multi-line prefix and indent 2 spaces below.
awards:
  - title: Student Travel Grant (Q-CORE @ QCE 2025)
    date: '2025-08-01'
    awarder: QCE 2025
    summary: ''
  - title: B.E. with Honors
    date: '2024-07-01'
    awarder: Tianjin University
    summary: ''
  - title: Talent Student in Scientific and Technological Research
    date: '2023-09-01'
    awarder: Tianjin University
    summary: ''
  - title: The 7th Undergraduate Integrated Circuits Innovation and Entrepreneurship Competition
    date: '2023-06-01'
    awarder: Competition
    summary: ''
---

## About Me

I am a Ph.D. student in Electrical and Computer Engineering. My research focuses on high-performance computing and networking, runtime and communication systems, and scalable training/inference of large language models, with a particular interest in distributed and federated learning systems and AI–HPC co-design.
