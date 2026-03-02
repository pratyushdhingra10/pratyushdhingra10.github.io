---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
*   **Ph.D. in Computer Engineering**, Washington State University, Pullman, WA, USA, 2022 - Present (Anticipated Graduation: Nov 2026)
    *   CGPA: 4.0
    *   Advisors: Prof. Partha Pratim Pande & Prof. Janardhan Rao Doppa
*   **B.E. in Electronics and Communication Engineering**, Netaji Subhas Institute of Technology, University of Delhi, Delhi, India, 2015 - 2019

Work Experience
======
*   **Research Assistant**, Washington State University, Aug 2022 - Present
    *   **Energy-Efficient ML:** Developed a hybrid training methodology for GNNs that dynamically transitions from a full-parameter phase to a parameter-efficient phase during training, leading to ~5x improvement in energy efficiency by reducing off-chip memory access. Created a framework to accelerate CNN fine-tuning tasks at the edge using low-rank representations.
    *   **Heterogeneous System Design:** Designed a three-dimensional (3D) heterogeneous architecture to accelerate transformer models for the dual purposes of fine-tuning and inference. Developed system-level strategies for optimal resource allocation and pipeline balancing to maximize throughput in heterogeneous systems.
    *   **Processing-in-Memory (PIM) Architectures:** Developed a fault-tolerant algorithm that uses approximate weighted bipartite graph matching to enable reliable on-device training on emerging PIM systems with minimal (~1%) timing overhead.
    *   **System Optimization:** Conducted design space exploration (DSE) for manycore systems, including 2.5D/3D systems, with power, performance, thermal and area as optimization objectives to improve EDAP (Energy-Delay-Area Product). Created an optimization framework to identify pareto-optimal solutions within design spaces containing millions of candidates.

*   **Physical Design – STA Engineer**, Qualcomm India Private Limited, Jul 2019 - Jul 2022
    *   Contributed to subsystem as well as SOC timing closure in Qualcomm Snapdragon 800 series processors (7 nm–4 nm), handling multi-million designs on advanced technology nodes.
    *   Addressed diverse timing challenges across multiple SoC cores (multimedia, CPU, low-power domains, signal processing units, memory) with clock frequencies ranging from 300 MHz to 1.8 GHz.
    *   Developed various utility scripts enhancing productivity and design quality:
        *   Margin aware ECO (Engineering change order) generation.
        *   Identification of bad nets (poor transition or high crosstalk) in the design.
        *   Clock skew fixing in a multi-mode and multi-corner environment using TOOL generated timing reports.
        *   Automated route topology aware TDRC (Testability Rules Checker) fixing to reduce ECO cycles.

*   **Physical Design Intern**, Qualcomm India Private Limited, May 2018 - Jul 2018
    *   Developed a STA dashboard for quick timing analysis capturing summary as well as detailed timing breakdown.

Technical Skills
======
*   **Core Competencies:** HW-SW co-design, Energy-Efficient ML, DRAM, PIM, STA, EDA, ASIC Digital Design
*   **Programming Skills:** Python, C++, Tcl, Verilog, Linux, Data structures & Algorithms
*   **Tools/Packages:** Pytorch, ML libraries, Hardware Simulators, PrimeTime, Tempus, Virtuoso

Publications
======
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}

Talks
======
{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}

Professional and Outreach Activities
======
*   **Invited Talks:**
    *   "ERGO: Energy-Efficient Hybrid Graph Neural Network Training on PIM Architectures" in ESWEEK 2025, Taipei, Taiwan.
    *   "Energy-Efficient hardware Design for LLMs" at LLM workshop in ESWEEK 2024, Rayleigh, USA.
    *   "FARe: Fault-Aware GNN Training on ReRAM-Based PIM Accelerators" at DATE 2024 in Valencia, Spain.
    *   "HeTraX: Energy Efficient 3D Heterogeneous Manycore Architecture for Transformers" at ISLPED 2024 in California.
*   **Awards & Fellowship:**
    *   EECS Outstanding Research Assistant (RA) Award, WSU, 2025.
    *   Harold and Diana Frank Electrical Engineering Fellowship, WSU, 2025.
    *   Mahmoud M. Dillsi Family Graduate Fellowship, 2025
    *   Nakahara Tsuyoshi and Mary Fellow, WSU, 2024.
    *   ACM SIGDA Richard Newton Young Fellow, 2023.
*   **Reviewer:**
    *   Conferences – ICCAD, DAC, DATE, ISLPED, ESWEEK, AAAI.
    *   Journals - IEEE TCAD, IEEE TVLSI, ACM TODAES, ACM TECS, IEEE Design & Test, Microelectronics Reliability.
*   **Instructor and Organizer:**
    *   Summer Internship Program on Microcontroller based Embedded System Design conducted by TI-CEPD, NSIT.
*   **Volunteer:**
    *   S4CE (SUPPORT FOR CHILD EDUCATION), an NGO in the field of educating underprivileged children.
