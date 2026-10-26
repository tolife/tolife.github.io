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

Lulu Yao is a assistent professor in [School of Artificial Intelligence at Ningbo University](https://ai.nbu.edu.cn/index.htm). Before that, he was a research scientist in the OS kernel laboratory at Huawei 2012 Lab.

He received his Ph.D. degree in [Computer Science and Technology](https://cs.ustc.edu.cn/main.htm) from the [University of Science and Technology of China (USTC)](https://www.ustc.edu.cn/) in December 2023, where he worked in the [Advanced Data Systems Laboratory (ADSL)](https://adsl.ustc.edu.cn/main.htm), advised by Prof. **Yinlong Xu** and Prof. **[Yongkun Li](http://staff.ustc.edu.cn/~ykli/)**. He received his Bachelor's degree in Computer Science and Technology from Zhengzhou University in June 2018.
His research focuses on **storage systems, cloud computing and system for AI**, particularly memory management and resource management in cloud and AI systems.


<!-- For research discussions and collaborations, please contact me at **[yaolulu@nbu.edu.cn](mailto:yaolulu@nbu.edu.cn)**. You can also find my publications on **[Google Scholar](https://scholar.google.com/citations?user=S85IlTMAAAAJ)**. -->

<!-- ## Research Interests

- **Operating-system memory management:** memory deduplication, large pages and folios, NUMA-aware policies, and memory reclamation.
- **Cloud and virtualized systems:** memory overcommitment, resource allocation, container scheduling, and application performance.
- **Disaggregated memory systems:** memory sharing and reuse, remote memory access, and compute-side collaboration.

<span class="anchor" id="-news"></span> -->

# 🔥 News
- *2026.10:* &nbsp;🎉🎉 Paper **SwiftBaton** appeared at **SIGOPS ATC 2026**.
- *2026.03:* &nbsp;🎉🎉 Paper **Varuna** appeared at arXiv.
- *2026.02:* &nbsp;🎉🎉 Paper **DMTree** appeared at **USENIX FAST 2026**.
- *2025.08:* &nbsp;🎉🎉 He joined the School of Artificial Intelligence at **Ningbo University** as a assitent professor.
- *2024.06:*  &nbsp;🎉🎉 Paper **AdaptMD** appeared in **IEEE Transactions on Computers**.
- *2023.12:* &nbsp;🎉🎉 He received his Ph.D. from **USTC** and joined **Huawei**.


# 📝 Publications 
## Selected Papers

<div class="paper-box publication-card" id="paper-adaptmd">
  <div class="paper-box-image">
    <div class="publication-visual">
      <span class="badge">TC 2024</span>
      <a href="images/papers/adaptmd.png" aria-label="View the adaptmd paper figure">
        <img src="images/papers/adaptmd.png" alt="AdaptMD: Balancing Space and Performance in NUMA Architectures with Adaptive Memory Deduplication — system overview from the original paper" loading="lazy" decoding="async">
      </a>
    </div>
  </div>
  <div class="paper-box-text">
    <h3 class="publication-title"><a href="https://doi.org/10.1109/TC.2024.3375592">AdaptMD: Balancing Space and Performance in NUMA Architectures with Adaptive Memory Deduplication</a></h3>
    <p class="publication-authors"><strong>Lulu Yao</strong>, Yongkun Li, Patrick P. C. Lee, Xiaoyang Wang, and Yinlong Xu.</p>
    <p class="publication-venue"><em>IEEE Transactions on Computers, 73(6): 1588–1602, 2024.</em> <span class="publication-rank">[CCF-A]</span></p>
    <p class="publication-links"><a href="https://doi.org/10.1109/TC.2024.3375592">Paper</a><a href="https://www.cse.cuhk.edu.hk/~pclee/www/pubs/tc24adaptmd.pdf">PDF</a><a href="https://zenodo.org/records/6620339">Code</a><a href="files/bibtex/adaptmd.bib">BibTeX</a></p>
    <p class="publication-summary">NUMA-aware memory deduplication that combines page hotness awareness and similarity-based application placement.</p>
  </div>
</div>

<div class="paper-box publication-card" id="paper-smartmd">
  <div class="paper-box-image">
    <div class="publication-visual">
      <span class="badge">TC 2023</span>
      <a href="images/papers/smartmd.png" aria-label="View the smartmd paper figure">
        <img src="images/papers/smartmd.png" alt="Towards High Performance and Efficient Memory Deduplication via Mixed Pages — system overview from the original paper" loading="lazy" decoding="async">
      </a>
    </div>
  </div>
  <div class="paper-box-text">
    <h3 class="publication-title"><a href="https://doi.org/10.1109/TC.2022.3191742">Towards High Performance and Efficient Memory Deduplication via Mixed Pages</a></h3>
    <p class="publication-authors"><strong>Lulu Yao</strong>, Yongkun Li, Fan Guo, Si Wu, Yinlong Xu, and John C. S. Lui.</p>
    <p class="publication-venue"><em>IEEE Transactions on Computers, 72(4): 926–940, 2023.</em> <span class="publication-rank">[CCF-A]</span></p>
    <p class="publication-links"><a href="https://doi.org/10.1109/TC.2022.3191742">Paper</a><a href="https://www.cse.cuhk.edu.hk/~cslui/PUBLICATION/TC-23.pdf">PDF</a><a href="https://github.com/ustcadsl/SmartMD">Code (SmartMD)</a><a href="files/bibtex/smartmd.bib">BibTeX</a></p>
    <p class="publication-summary">SmartMD and SmartMD+ coordinate memory deduplication with selective large-page splitting and reconstruction.</p>
  </div>
</div>

<div class="paper-box publication-card" id="paper-dmtree">
  <div class="paper-box-image">
    <div class="publication-visual">
      <span class="badge">FAST 2026</span>
      <a href="images/papers/dmtree.png" aria-label="View the dmtree paper figure">
        <img src="images/papers/dmtree.png" alt="DMTree: Towards Efficient Tree Indexing on Disaggregated Memory via Compute-side Collaborative Design — system overview from the original paper" loading="lazy" decoding="async">
      </a>
    </div>
  </div>
  <div class="paper-box-text">
    <h3 class="publication-title"><a href="https://www.usenix.org/conference/fast26/presentation/wei">DMTree: Towards Efficient Tree Indexing on Disaggregated Memory via Compute-side Collaborative Design</a></h3>
    <p class="publication-authors">Guoli Wei, Yongkun Li, Haoze Song, Tao Li, <strong>Lulu Yao</strong>, Yinlong Xu, and Heming Cui.</p>
    <p class="publication-venue"><em>24th USENIX Conference on File and Storage Technologies, 2026.</em> <span class="publication-rank">[CCF-A]</span></p>
    <p class="publication-links"><a href="https://www.usenix.org/conference/fast26/presentation/wei">Paper</a><a href="https://www.usenix.org/system/files/fast26-wei.pdf">PDF</a><a href="https://github.com/muouim/DMTree">Code</a><a href="https://github.com/muouim/aefast26">Artifact</a><a href="files/bibtex/dmtree.bib">BibTeX</a></p>
    <p class="publication-summary">A collaborative compute-side design for tree indexes on disaggregated memory.</p>
  </div>
</div>

<!-- ## Other Publications -->
- `ATC 2026 · Accepted` [SwiftBaton: Dependency-Aware Staged Reconstruction for Live Migration of Stateful Containers](https://sigops.org/s/conferences/atc/2026/accepted.html), Xianzhi Zhu, Gonggu Chen, Yancan Mao, Richard Ma, **Lulu Yao**, Yongkun Li, Yinlong Xu, John C. S. Lui
- `ICPADS 2023` [CARE: A Cost-AwaRe Eviction Strategy for Improving Throughput in Cloud Environments](https://doi.org/10.1109/ICPADS60453.2023.00305), Xiyuan Liang†, **Lulu Yao†**, Si Wu, Yongkun Li, Yinlong Xu
- `ICPP 2023` [On Optimizing Traffic Scheduling for Multi-replica Containerized Microservices](https://doi.org/10.1145/3605573.3605646), Xianzhi Zhu, Yongkun Li, **Lulu Yao**, Zhihao Qi, Yinlong Xu, Pengcheng Wang, Weiguang Wang, Xia Zhu [![](https://img.shields.io/github/stars/sirius8050/OptTraffic?style=social&label=Code+Stars)](https://github.com/sirius8050/OptTraffic)
- `ICPP 2021` [Progressive Memory Adjustment with Performance Guarantee in Virtualized Systems](https://doi.org/10.1145/3472456.3472491), **Lulu Yao**, Yongkun Li, Jiawei Li, Weijie Wu, Yinlong Xu

† Equal contribution.

## Preprints

<div class="paper-box publication-card" id="paper-varuna">
  <div class="paper-box-image">
    <div class="publication-visual">
      <span class="badge preprint">arXiv 2026</span>
      <a href="images/papers/varuna.png" aria-label="View the varuna paper figure">
        <img src="images/papers/varuna.png" alt="Varuna: Enabling Failure-Type Aware RDMA Failover — system overview from the original paper" loading="lazy" decoding="async">
      </a>
    </div>
  </div>
  <div class="paper-box-text">
    <h3 class="publication-title"><a href="https://arxiv.org/abs/2603.28001">Varuna: Enabling Failure-Type Aware RDMA Failover</a></h3>
    <p class="publication-authors">Xiaoyang Wang, Yongkun Li, <strong>Lulu Yao</strong>, Guoli Wei, Longcheng Yang, Yinlong Xu, Weiqing Kong, Weiguang Wang, Peng Dong, and Bingyang Liu.</p>
    <p class="publication-venue"><em>arXiv:2603.28001, 2026. Preprint.</em></p>
    <p class="publication-links"><a href="https://arxiv.org/abs/2603.28001">arXiv</a><a href="https://arxiv.org/pdf/2603.28001">PDF</a><a href="https://github.com/Plasticinew/Varuna">Code</a><a href="files/bibtex/varuna.bib">BibTeX</a></p>
    <p class="publication-summary">Failure-type-aware RDMA failover using completion logs, extended operation status, and lightweight backup connections.</p>
  </div>
</div>

<span class="anchor" id="-honors-and-awards"></span>
# 🎖 Honors and Awards
- *2025.05* Presidential Personal Award (总裁个人奖), Huawei.
- *2024.12* Future Star (明日之星), Huawei.
- *2022.12* Suzhou Yucai Scholarship.
- *2018.06* Outstanding Graduate of Henan Province.
- *2018.06* Outstanding Graduate of Zhengzhou University.
- *2017.12* Yisheng Scholarship.
- *2015.10* National Encouragement Scholarship.

<span class="anchor" id="-educations"></span>
# 📖 Educations
- *2018.09 - 2023.12*, Ph.D. degree, Computer Science and Technology; ADSL lab, University of Science and Technology of China (Advisors: Prof. Yinlong Xu & Prof. [Yongkun Li](http://staff.ustc.edu.cn/~ykli/)).
- *2014.09 - 2018.06*, B.S. degree, Computer Science and Technology; Zhengzhou University. 

<span class="anchor" id="-invited-talks"></span>
# 💬 Invited Talks
- *2026.09*, Invited talk on memory management, **The 32th CCF National
Conference of Information Storage 2026, NCIS 2026**, Tianjin, China. 
- *2023.01*, Invited talk on memory deduplication, **Huawei Cloud**, online.
- *2021.08*, Paper presentation, **ICPP 2021**, online.


<span class="anchor" id="-work-experience"></span>
# 💻 Work Experience
- *2025.08 - now*, Assistent Professor, School of Artificial Intelligence, Ningbo University.
- *2023.12 - 2025.07*, Research Scientist, Huawei 2012 Lab.
- *2021.03 - 2021.06*, Research Intern, Huawei 2012 Lab.
- *2019.03 - 2019.06*, Research Intern, [The Illinois Advanced Research Center at Singapore Ltd. (Illinois ARCS)](https://illinois-arcs.edu.sg).