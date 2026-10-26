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

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. Suspendisse condimentum, libero vel tempus mattis, risus risus vulputate libero, elementum fermentum mi neque vel nisl. Maecenas facilisis maximus dignissim. Curabitur mattis vulputate dui, tincidunt varius libero luctus eu. Mauris mauris nulla, scelerisque eget massa id, tincidunt congue felis. Sed convallis tempor ipsum rhoncus viverra. Pellentesque nulla orci, accumsan volutpat fringilla vitae, maximus sit amet tortor. Aliquam ultricies odio ut volutpat scelerisque. Donec nisl nisl, porttitor vitae pharetra quis, fringilla sed mi. Fusce pretium dolor ut aliquam consequat. Cras volutpat, tellus accumsan mattis molestie, nisl lacus tempus massa, nec malesuada tortor leo vel quam. Aliquam vel ex consectetur, vehicula leo nec, efficitur eros. Donec convallis non urna quis feugiat.

My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).


# 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

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
    <p class="publication-links"><a href="https://doi.org/10.1109/TC.2024.3375592">Paper</a><a href="https://www.cse.cuhk.edu.hk/~pclee/www/pubs/tc24adaptmd.pdf">PDF</a><a href="files/bibtex/adaptmd.bib">BibTeX</a></p>
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

## Other Publications
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


# 🎖 Honors and Awards
- *2025.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2018.09 - 2023.12*, Ph.D. degree, Computer Science and Technology; ADSL lab, University of Science and Technology of China (Advisors: Prof. Yinlong Xu & Prof. [Yongkun Li](http://staff.ustc.edu.cn/~ykli/)).
- *2014.09 - 2018.06*, B.S. degree, Computer Science and Technology; Zhengzhou University. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Work Experience
- *2025.08 - now:*, Assistent Professor, School of Artificial Intelligence, Ningbo University.
- *2023.12 - 2025.07:*, Research Scientist, Huawei 2012 lab.
- *2021.03 - 2021.06:*, Research Intern, Huawei 2012 Lab.
- *2019.03 - 2019.06:*, Research Intern, [The Illinois Advanced Research Center at Singapore Ltd. (Illinois ARCS)](https://illinois-arcs.edu.sg).