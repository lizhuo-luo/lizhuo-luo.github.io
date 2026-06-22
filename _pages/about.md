---
permalink: /
author_profile: true
stylesheets:
  - /assets/css/home.css
redirect_from: 
  - /about/
  - /about.html
---

About Me
---
I am an incoming Ph.D. student at the College of Computing and Data Science, Nanyang Technological University, supervised by Prof. [Tianwei Zhang](https://personal.ntu.edu.sg/tianwei.zhang/). My research interests lie in efficient AI algorithms and systems. Before that, I received my B.Sc. from the Southern University of Science and Technology (SUSTech).

Feel free to reach out if you are interested in discussing research ideas or potential collaborations!

News
---------------
<div class="news-box">
  <ul class="news-list">
<li><span class="news-date"><em>2026.04</em></span> 🎉🎉 One first-author paper accepted by ICML26, see you in Seoul.</li>
<li><span class="news-date"><em>2025.08</em></span> 🎉🎉 I began my full-time RA at NTU.</li>
  </ul>
</div>

Education
--------------

<div class="experience-container">

  <div class="experience-card">
      <img src="images/NTU.png" alt="NTU" class="experience-logo">
      <div class="experience-info">
          <strong>Nanyang Technological University</strong><br>
          <em>2026.08 - </em><br>
          Full-time Ph.D. at CCDS
      </div>
  </div>

  <div class="experience-card">
      <img src="images/SUSTech.png" alt="SUSTech" class="experience-logo">
      <div class="experience-info">
          <strong>SUSTech</strong><br>
          <em>2021.09 - 2025.06</em><br>
          Major in Data Science and Big Data Technology
      </div>
  </div>
  
</div>

Other Experience
--------------

<div class="experience-container">

  <div class="experience-card">
      <img src="images/NTU.png" alt="NTU" class="experience-logo">
      <div class="experience-info">
          <strong>Nanyang Technologicai University</strong><br>
          <em>2026.05 - 2026.08</em><br>
          Research Assistant at Aumovio-NTU Corporate Lab
      </div>
  </div>

  <div class="experience-card">
      <img src="images/THU.png" alt="thu" class="experience-logo">
      <div class="experience-info">
          <strong>SIGS, Tsinghua University</strong><br>
          <em>2024.08 - 2025.02</em><br>
          Research Intern at MMLab@SIGS
      </div>
  </div>

</div>

Publications
--------------
<button class="pub-button active" onclick="filterPublications(event, 'all')">Core Publications</button>
<button class="pub-button" onclick="filterPublications(event, 'list')">Full Publications List</button>

(* equal contribution · &dagger; corresponding author · &Dagger; project leader)

<div id="core-publications" class="publication-view" data-publication-view="core">
<div class="publication-card" data-category="all"> 
  <div style="display: flex; align-items: center;">
    <div class="pub-media-rotator" data-interval="4000" style="position: relative; width: 320px; height: 180px; margin-right: 20px; border-radius: 8px; overflow: hidden; flex: 0 0 auto;"> 
      <img src="images/DSB.png" alt="dsb" style="width: 320px; height: 180px; object-fit: contain; display: block; margin: 0 auto;"> 
    </div> 
    <div>
      <strong>DSB: Dynamic Sliding Block Scheduling for Diffusion LLMs</strong><br>
      <i style="font-size: 13px;">
        <a href="" target="_blank">
          <strong>Lizhuo Luo*</strong>
        </a>,
        <a href="" target="_blank">
          <strong>Shenggui Li*</strong>
        </a>,
        <a href="" target="_blank">
          <strong>Yonggang Wen</strong>
        </a>,
        <a href="" target="_blank">
          <strong>Tianwei Zhang&dagger;</strong>
        </a>.
      </i><br> 
      Dynamic Sliding Block (DSB), a training-free block scheduling method that uses a sliding block with a dynamic size to overcome the rigidity of the naive block; DSB Cache, a training-free KV-cache mechanism tailored to DSB, improves both generation quality and inference efficiency for dLLMs.
      <br> 
      <b><i style="color:#83a1c7;">ICML 2026 &nbsp;
      </i></b> 
      <a href="https://arxiv.org/abs/2602.05992"><em>[arXiv]</em></a> 
      <a href="https://github.com/lizhuo-luo/DSB"><em>[code]</em></a> 
    </div>
  </div> 
</div>

<div class="publication-card" data-category="all"> 
  <div style="display: flex; align-items: center;">
    <div class="pub-media-rotator" data-interval="4000" style="position: relative; width: 320px; height: 180px; margin-right: 20px; border-radius: 8px; overflow: hidden; flex: 0 0 auto;"> 
      <img src="images/DICE.png" alt="dice" style="width: 320px; height: 180px; object-fit: contain; display: block; margin: 0 auto;"> 
    </div> 
    <div>
      <strong>DICE: Staleness-Centric Optimizations for Parallel Diffusion MoE Inference</strong><br>
      <i style="font-size: 13px;">
        <a href="" target="_blank">
          <strong>Jiajun Luo*</strong>
        </a>,
        <a href="" target="_blank">
          <strong>Lizhuo Luo*</strong>
        </a>,
        <a href="" target="_blank">
          <strong>Jianru Xu*</strong>
        </a>,
        <a href="" target="_blank">
          <strong>Jiajun Song</strong>
        </a>,
        <a href="" target="_blank">
          <strong>Rongwei Lu</strong>
        </a>,
        <a href="" target="_blank">
          <strong>Chen Tang</strong>
        </a>,
        <a href="" target="_blank">
          <strong>Zhi Wang&dagger;</strong>
        </a>.
      </i><br> 
      DICE, an asynchronous expert-parallel framework for MoE-based diffusion models that overlaps communication and computation to realize faster, more scalable multi-GPU inference, achieving up to 1.26× speedup with minimal quality impact.
      <br> 
      <b><i style="color:#83a1c7;">ICCV 2025 &nbsp;
      </i></b> 
      <a href="https://arxiv.org/abs/2411.16786"><em>[arXiv]</em></a> 
      <a href="https://github.com/Cobalt-27/DICE"><em>[code]</em></a> 
    </div>
  </div> 
</div>

</div>


<div id="full-publications" class="publication-view" data-publication-view="list" hidden>
  <ul class="full-publication-list">
    <li>
      <span class="pub-list-badge">ICML 2026</span>
      <span class="pub-list-title">DSB: Dynamic Sliding Block Scheduling for Diffusion LLMs</span><br>
      <span class="pub-list-authors">
        <a href="" target="_blank">
          <strong>Lizhuo Luo*</strong>
        </a>,
        <a href="" target="_blank">
          <strong>Shenggui Li*</strong>
        </a>,
        <a href="" target="_blank">
          <strong>Yonggang Wen</strong>
        </a>,
        <a href="" target="_blank">
          <strong>Tianwei Zhang&dagger;</strong>
        </a>.
      </span>
      <span class="pub-list-note"></span>
      <span class="pub-list-links"><a href="https://arxiv.org/abs/2602.05992">[arXiv]</a><a href="https://github.com/lizhuo-luo/DSB">[code]</a></span>
    </li>
    <li>
      <span class="pub-list-badge">Arxiv 2026</span>
      <span class="pub-list-title">DAWN: Dependency-Aware Fast Inference for Diffusion LLMs</span><br>
      <span class="pub-list-authors">
        <a href="" target="_blank">
          <strong>Lizhuo Luo</strong>
        </a>,
        <a href="" target="_blank">
          <strong>Zhuoran Shi</strong>
        </a>,
        <a href="" target="_blank">
          <strong>Jiajun Luo</strong>
        </a>,
        <a href="" target="_blank">
          <strong>Zhi Wang</strong>
        </a>,
        <a href="" target="_blank">
          <strong>Shen Ren</strong>
        </a>,
        <a href="" target="_blank">
          <strong>Wenya Wang</strong>
        </a>,
        <a href="" target="_blank">
          <strong>Tianwei Zhang&dagger;</strong>
        </a>.
      </span>
      <span class="pub-list-note"></span>
      <span class="pub-list-links"><a href="https://arxiv.org/abs/2602.06953">[arXiv]</a><a href="https://github.com/lizhuo-luo/DAWN">[code]</a></span>
    </li>
    <li>
      <span class="pub-list-badge">Arxiv 2025</span>
      <span class="pub-list-title">FlowSpec: Continuous Pipelined Speculative Decoding for Efficient Distributed LLM Inference</span><br>
      <span class="pub-list-authors">
        <a href="" target="_blank">
          <strong>Xing Liu*</strong>
        </a>,
        <a href="" target="_blank">
          <strong>Lizhuo Luo*</strong>
        </a>,
        <a href="" target="_blank">
          <strong>Ming Tang&dagger;</strong>
        </a>,
        <a href="" target="_blank">
          <strong>Chao Huang</strong>
        </a>,
        <a href="" target="_blank">
          <strong>Xu Chen</strong>
        </a>.
      </span>
      <span class="pub-list-note"></span>
      <span class="pub-list-links"><a href="https://arxiv.org/abs/2507.02620">[arXiv]</a><a href="https://github.com/Leosang-lx/FlowSpec">[code]</a></span>
    </li>
    <li>
      <span class="pub-list-badge">ICCV 2025</span>
      <span class="pub-list-title">DICE: Staleness-Centric Optimizations for Parallel Diffusion MoE Inference</span><br>
      <span class="pub-list-authors">
        <a href="" target="_blank">
          <strong>Jiajun Luo*</strong>
        </a>,
        <a href="" target="_blank">
          <strong>Lizhuo Luo*</strong>
        </a>,
        <a href="" target="_blank">
          <strong>Jianru Xu*</strong>
        </a>,
        <a href="" target="_blank">
          <strong>Jiajun Song</strong>
        </a>,
        <a href="" target="_blank">
          <strong>Rongwei Lu</strong>
        </a>,
        <a href="" target="_blank">
          <strong>Chen Tang</strong>
        </a>,
        <a href="" target="_blank">
          <strong>Zhi Wang&dagger;</strong>
        </a>.
      </span>
      <span class="pub-list-note"></span>
      <span class="pub-list-links"><a href="https://arxiv.org/abs/2411.16786">[arXiv]</a><a href=" https://github.com/Cobalt-27/DICE">[code]</a></span>
    </li>
  </ul>
</div>

<script src="assets/js/show_publications.js"></script>
<script src="assets/js/pub_media_rotator.js"></script>


<!-- Projects
--------
<div class="project-card" data-category="project"> 
  <div style="display: flex; align-items: center;">
    <div class="pub-media-rotator" data-interval="4000" style="position: relative; width: 320px; height: 180px; margin-right: 20px; border-radius: 8px; overflow: hidden; flex: 0 0 auto;">
      <img src="images/2.png" alt="ManiUniCon" style="width: 320px; height: 180px; object-fit: contain; display: block; margin: 0 auto;">
    </div>
    <div> 
      <strong>WowPage</strong><br>
      <i style="font-size: 13px;">
        <a href="https://wd7ang.github.io" target="_blank"><strong>Weidong Tang</strong></a>,
        <a href="https://selen-suyue.github.io/" target="_blank"><strong>Yue Su</strong></a>.
      </i><br>
      In collaboration with Yue Su, I refined and improved his original homepage template. A clean standalone template version is coming soon.
      <br> 
      <b><i style="color:#83a1c7;">Project &nbsp;</i></b> 
      <a href=""><em>[code]</em></a> 
    </div>
  </div> 
</div> -->


Awards
--------
- *2025*, Outstanding Graduation Thesis.



<!-- Services
--------
- *3026.06 – Present*, Chief Coffee Consumption Officer, Midnight Research Lab.
- *3026.01 – Present*, Full-time Debugger of Problems Created by Myself.
- Reviewer for Journal of Unfinished Projects.
- Area Chair for Conference on Last-Minute Submissions (CLMS).
- Volunteer Therapist for Burned-out GPUs. -->



<!-- Talks
--------
- *3026.07*, “How to Finish a Paper 3 Minutes Before Deadline.”
- *3026.05*, “Large Language Models and Large Amounts of Caffeine.”
- *3025.11*, “On the Emotional Stability of GPUs Under Extreme Stress.”
- *3025.08*, “Instant Noodles as Scalable Research Infrastructure.”
- *3025.03*, “Sleep is Temporary, Camera-Ready is Forever.” -->