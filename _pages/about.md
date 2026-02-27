---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a fourth-year Ph.D. candidate in the School of Computer Science at Peking University, advised by Professor [Guojie Luo](https://ceca.pku.edu.cn/people/faculty/lgj/) at PKU-DASYS Group (Design Automation for Next-generation Computing Systems). My current research interests include computer architecture, AI systems and compilers, electronic design automation (EDA). I have published 9 papers with total <a href='https://scholar.google.com/citations?user=-31YAP4AAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>. [[English CV]](files/English_CV.pdf) [[中文简历]](files/Chinese_CV.pdf)

I obtained my B.S. in Computer Science in 2022 from the School of EECS at Peking University. I have been affiliated with the PKU-DASYS Group with Professor Guojie Luo since 2019. I also worked as a research intern at Carnegie Mellon University and National Institute of Informatics (Japan). During my undergraduate studies and Ph.D. pursuit, I mainly focused on efficent LLM algorithm and system, electronic design automation, and domain-specific accelerator design.


# 📝 Publications

## Conferences

\[C7\] UltraSketchLLM: Sub-1-Bit LLM Compression via Sketch and Hardware-Friendly Operators, **Sunan Zou**, Xueting Sun, Ziyun Zhang, and Guojie Luo. in the Proceedings of the 63rd Design Automation Conference (**DAC**), 2026 (To Appear).

\[C6\] [MuSA: Multi-Sketch Accelerator with Hybrid Parallelism and Coalesced Memory Organization](https://ieeexplore.ieee.org/document/10817985), **Sunan Zou**, Bizhao Shi, Ziyun Zhang, and Guojie Luo. in the Proceedings of the 42nd International Conference on Computer Design (**ICCD**), Nov, 2024.

\[C5\] [AceRoute: Adaptive Compute-Efficient FPGA Routing with Pluggable Intra-Connection Bidirectional Exploration](https://dl.acm.org/doi/10.1145/3676536.3676709), Xinming Wei, Ziyun Zhang, **Sunan Zou**, Kaiwen Sun, Jiahao Zhang, Jiaxi Zhang, Ping Fan, and Guojie Luo. in the Proceedings of the 43rd IEEE/ACM International Conference on Computer-Aided Design (**ICCAD**), 2024.

\[C4\] [ImageMap: Enabling Efficient Mapping from Image Processing DSL to CGRA](https://link.springer.com/chapter/10.1007/978-3-031-69577-3_5), Bizhao Shi, Tuo Dai, **Sunan Zou**, Xinming Wei, and Guojie Luo. in the Proceedings of the 30th International European Conference on Parallel and Distributed Computing (**Euro-Par**), Aug, 2024.

\[C3\] [PONO: Power Optimization with Near Optimal SMT-based Sub-circuit Generation](https://dl.acm.org/doi/10.1145/3649329.3655904), **Sunan Zou** and Guojie Luo. in the Proceedings of the 61st Design Automation Conference (**DAC**), Jun, 2024.

\[C2\] [Incremental SAT-based Exact Synthesis](https://dl.acm.org/doi/10.1145/3649476.3658739), **Sunan Zou**, Jiaxi Zhang, and Guojie Luo. in the Proceedings of the 34th Great Lakes Symposium on VLSI (**GLSVLSI**), 2024. <span style="color: red">**\[Best Paper Award\]**</span>

\[C1\] [BESWAC: Boosting Exact Synthesis via Wiser SAT Solver Call](https://ieeexplore.ieee.org/document/10546591/), **Sunan Zou**, Jiaxi Zhang, Bizhao Shi, and Guojie Luo. in the Proceedings of 2024 Design Automation and Test in Europe (**DATE**), Mar, 2024.


## Journals

\[J2\] [Large Circuit Models: Opportunities and Challenges](https://link.springer.com/article/10.1007/s11432-024-4155-7), Lei Chen, Yiqi Chen, Zhufei Chu, Wenji Fang, Tsung-Yi Ho, et al, and **Sunan Zou** (Alphabetical Order). in Science China Information Sciences, Volume 67, 2024.

\[J1\] [PowerSyn: A Logic Synthesis Framework with Early Power Optimization](https://ieeexplore.ieee.org/document/10186351), **Sunan Zou**, Jiaxi Zhang, Bizhao Shi, and Guojie Luo. in the IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (**TCAD**), Vol: 43, Issue: 1, Jan 2024, pp. 203-216.


# 🏆 Honors and Awards
- **2024** - Honors for Merit Student (**三好学生**), Peking Unniversity
- **2024** - BYD Scholarship (**北京大学比亚迪奖学金**), Peking University
- **2024** - Best Paper Award, 34th Great Lakes Symposium on VLSI (**GLSVLSI**)
- **2024** - ISFPGA FPGA Routing Contest Third Place, ISFPGA Committee
- **2021** - Principal's Fund for Undergraduate Research Training (Natural Science), Peking University
- **2018** - Freshman Scholarship (**新生奖学金**), Peking University
- **2018** - Freshman Scholarship (**院长新生奖学金**), School of EECS, Peking University


# 🎓 Educations
- *2022.09 - 2027.06 (Expected)*, Ph.D. Student, School of Computer Science, Peking University.
- *2018.09 - 2022.07*, B.S. in Computer Science, School of EECS, Peking University.


# 💼 Experiences
- *2025.10 - 2026.04 (Expected)*, National Institute of Informatics (NII), Tokyo, Japan. Advised by Prof. Junichi Yamagishi. Violin Audio Model.
- *2021.03 - 2021.09*, Carnegie Mellon University (Remote). Advised by Prof. Lawrence Pileggi. GNN and Logic Locking.
- *2019.07 - 2022.01*, PKU-DASYS Group, Peking University, Beijing, China. Advised by Prof. Guojie Luo. RL and logic optimization.


# 📚 Services
- Reviewer: IEEE TCAD 2025, 2026
- Teaching Assistant: Introduction to Parallel and Distributed Computing, 2022 Spring & 2023 Spring

# ⚙️ Skills
- Programming: C/C++, Python (PyTorch), FPGA HLS, Verilog, CUDA, LaTeX
- Tools: Git, Docker/Apptainer
- Languages: Chinese (Native), English (Working Proficiency), Japanese (Conversational)
