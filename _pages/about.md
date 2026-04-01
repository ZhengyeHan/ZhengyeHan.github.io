---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  .internship-cards {
    width: 100%;
    margin-top: 20px;
  }

  .internship-item {
    display: flex;
    align-items: center; 
    background-color: #f9f9f9; 
    border-radius: 12px; 
    margin-bottom: 20px; 
    padding: 20px 25px; 
    border: 1px solid #e0e0e0; 
    transition: box-shadow 0.2s ease, transform 0.2s ease; 
  }


  .internship-item:hover {
    box-shadow: 0 5px 15px rgba(0,0,0,0.05);
    transform: translateY(-2px);
  }

  
  .logo-box {
    width: 100px; 
    height: 100px; 
    margin-right: 30px; 
    display: flex;
    align-items: center;
    justify-content: center; 
    flex-shrink: 0; 
    overflow: hidden; 
  }


  .item-logo {
    max-width: 100%;
    max-height: 100%;
    object-fit: contain; 
  }


  .content-box {
    flex-grow: 1; 
  }


  .org-title {
    font-size: 1.3rem; 
    font-weight: 700;
    color: #222;
    margin-bottom: 5px;
  }


  .duration-text {
    font-size: 1rem;
    color: #666; 
    font-style: italic; 
  }
</style>

<style>
  .hero-section {
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 30px;
    margin-bottom: 25px;
    padding-top: 10px;
  }
  
  .hero-text {
    flex: 1;
    font-size: 1.05em; /* 字体稍微放大一点点，更有气场 */
    line-height: 1.6;
  }
  
  .hero-text p {
    margin: 0;
  }

  .hero-logo {
    flex-shrink: 0;
    width: 100px; 
    transition: transform 0.3s ease;
  }

  .hero-logo:hover {
    transform: scale(1.05); 
  }

  .hero-logo img {
    width: 100%;
    height: auto;
    object-fit: contain;
  }

  @media (max-width: 768px) {
    .hero-section {
      flex-direction: column-reverse;
      align-items: center;
      text-align: center;
    }
    .hero-logo {
      width: 90px;
      margin-bottom: 20px;
    }
  }
</style>

<div class="hero-section">
  <div class="hero-text">
    <p>Hello, I am Zhengye Han (韩政业), a 1st year PhD student at <a href="https://www.nyu.edu/">New York University</a>, advised by Prof. <a href="https://scholar.google.com/citations?user=Qt2WDh0AAAAJ&hl=en">Quanyan Zhu</a>. I received my BS degree in Computer Science from <a href="https://www.bjtu.edu.cn/">Beijing Jiaotong University</a>, where I studied under the supervision of Professor <a href="http://en.sem.bjtu.edu.cn/show-910-467.html">Zhigang Cao</a>. Under his guidance, I embarked on my academic journey through the study of game theory.</p>
  </div>
  <div class="hero-logo">
    <a href="https://www.nyu.edu/" target="_blank">
      <img src="/images/nyu_logo.png" alt="New York University Logo">
    </a>
  </div>
</div>

During my undergraduate studies, I had the privilege to join the Center on Frontiers of Computing Studies ([CFCS](https://cfcs.pku.edu.cn/)) at Peking University, working in the [daGAME](https://dagame.pku.edu.cn/) lab, where I focused on Reinforcement Learning and game theory. I am deeply grateful to Professor [Xiaotie Deng](https://cfcs.pku.edu.cn/english/people/faculty/xiaotiedeng/index.htm) for providing me with invaluable research and internship opportunities during this time. I would also like to extend my sincere thanks to Dr.[Zhijian Duan](https://zjduan.github.io/) for his important guidance throughout my time in the lab. 

My research focuses on the following topics:
* Multi-Agent Systems: Exploring the integration of game theory and Reinforcement Learning in multi-agent environments.
* AI Safety: With a special emphasis on the safety of Large Language Models, including topics such as LLM jailbreaking.
* Reinforcement Learning: Including auto-bidding in online advertising, sequential decision-making, and Safe Reinforcement Learning.

<h3>🔥 News</h3>
<ul style="list-style-type: none; padding: 0; margin: 0;">
  <li style="margin-bottom: 16px; display: flex; align-items: flex-start;">
    <span style="background-color: #f1f3f5; color: #495057; padding: 3px 8px; border-radius: 4px; font-weight: 600; font-size: 0.85em; margin-right: 15px; white-space: nowrap; min-width: 80px; text-align: center;">Mar 2026</span>
    <span style="line-height: 1.5; color: #333;">🎉 Our paper <i>"Toward a Dynamic Stackelberg Game-Theoretic Framework for Agentic AI Defense Against LLM Jailbreaking"</i> has been accepted by the ICLR 2026 Workshop on AI for Mechanism Design and Strategic Decision Making!</span>
  </li>
  <li style="margin-bottom: 16px; display: flex; align-items: flex-start;">
    <span style="background-color: #f1f3f5; color: #495057; padding: 3px 8px; border-radius: 4px; font-weight: 600; font-size: 0.85em; margin-right: 15px; white-space: nowrap; min-width: 80px; text-align: center;">Sep 2025</span>
    <span style="line-height: 1.5; color: #333;">🗽 I officially started my Ph.D. journey at the ECE Department of New York University (NYU)!</span>
  </li>
  <li style="margin-bottom: 16px; display: flex; align-items: flex-start;">
    <span style="background-color: #f1f3f5; color: #495057; padding: 3px 8px; border-radius: 4px; font-weight: 600; font-size: 0.85em; margin-right: 15px; white-space: nowrap; min-width: 80px; text-align: center;">Jun 2024</span>
    <span style="line-height: 1.5; color: #333;">🏆 Co-organized the NeurIPS 2024 Competition: <i>"Auto-Bidding in Large-Scale Auctions"</i> and open-sourced <a href="https://github.com/alimama-tech/AuctionNet" style="font-weight: 600;">AuctionNet</a> as a core code contributor.</span>
  </li>
</ul>

# Internship
For more details, please check my [LinkedIn](https://www.linkedin.com/in/zhengye-han-a45624235/).

<div class="internship-cards">
  <div class="internship-item">
    <div class="logo-box">
      <img src="/images/alibaba_logo.png" alt="Alibaba Group Logo" class="item-logo">
    </div>
    <div class="content-box">
      <div class="org-title">Alibaba Group</div>
      <div class="duration-text">03/2024 - 12/2024</div>
    </div>
  </div>

  <div class="internship-item">
    <div class="logo-box">
      <img src="/images/pku_logo.png" alt="PKU Logo" class="item-logo">
    </div>
    <div class="content-box">
      <div class="org-title">Center on Frontiers of Computing Studies, Peking University</div>
      <div class="duration-text">02/2023 - 12/2024</div>
    </div>
  </div>

  <div class="internship-item">
    <div class="logo-box">
      <img src="/images/meituan_logo.png" alt="Meituan Logo" class="item-logo">
    </div>
    <div class="content-box">
      <div class="org-title">Meituan</div>
      <div class="duration-text">10/2023 - 01/2024</div>
    </div>
  </div>

  <div class="internship-item">
    <div class="logo-box">
      <img src="/images/BOC_logo.png" alt="BOC Logo" class="item-logo">
    </div>
    <div class="content-box">
      <div class="org-title">BOC International (China) Co., Ltd</div>
      <div class="duration-text">06/2022 - 09/2022</div>
    </div>
  </div>
</div>


# Publications
* Quanyan Zhu, <strong>Zhengye Han</strong>. Performative Scenario Optimization. Under review in <em>IEEE Conference on Decision and Control (CDC) 2026</em>. <a href="https://arxiv.org/abs/2603.29982" style="color: blue;">[arXiv]</a>
* <strong>Zhengye Han</strong>, Quanyan Zhu. Toward a Dynamic Stackelberg Game-Theoretic Framework for Agentic AI Defense Against LLM Jailbreaking. In <em>International Conference on Learning Representations (ICLR) AI for Mechanism Design Workshop</em>, 2026. <a href="https://arxiv.org/abs/2507.08207" style="color: blue;">[arXiv]</a>
* Quanyan Zhu, <strong>Zhengye Han</strong>. Split-Merge Dynamics for Shapley-Fair Coalition Formation. Under review in <em>International Symposium on Mathematical Theory of Networks and Systems 2026</em>. <a href="https://arxiv.org/abs/2603.17153" style="color: blue;">[arXiv]</a>
* Quanyan Zhu, <strong>Zhengye Han</strong>. Learning, Misspecification, and Cognitive Arbitrage in Linear-Quadratic Network Games. Under review in <em>International Symposium on Mathematical Theory of Networks and Systems 2026</em>. <a href="https://arxiv.org/abs/2603.17157" style="color: blue;">[arXiv]</a>
* Quanyan Zhu, <strong>Zhengye Han</strong>. A Mathematical Programming Approach to Computing and Learning Berk–Nash Equilibria in Infinite-Horizon MDPs. In <em>14th EAI International Conference on Game Theory for Networks (GameNets)</em>, 2026. <a href="https://arxiv.org/abs/2603.13641" style="color: blue;">[arXiv]</a>
* <strong>Zhengye Han</strong>, Yusen Huo, Zhijian Duan, Tianyu Wang, Yeshu Li, Zhilin Zhang, Chuan Yu, Jian Xu, Bo Zheng, Xiaotie Deng. Action Sequence Planner: An Alternative for Offline Reinforcement Learning. Under review in <em>ICLR 2025</em>. <a href="https://openreview.net/forum?id=MtjPIDWyWK" style="color: blue;">[OpenReview]</a>
* Shuai Dou, Yusen Huo, Zhilin Zhang, Yeshu Li, <strong>Zhengye Han</strong>, Kefan Su, Zongqing Lu, Chuan Yu, Jian Xu, Bo Zheng. Code Contributor to AuctionNet: A Novel Benchmark for Decision-Making in Large-Scale Games. In <em>NeurIPS 2024 Datasets and Benchmarks Track</em> (<span style="color: red;">Spotlight</span>). <a href="https://github.com/alimama-tech/AuctionNet" style="color: blue;">[GitHub]</a>


<style>
  /* 全宽优化卡片样式定义 */
  .fullwidth-card {
    display: flex;
    flex-direction: column; /* 强行恢复上下布局 */
    gap: 15px;
    margin-bottom: 35px;
    padding: 20px;
    border-radius: 12px;
    background-color: #fcfcfc;
    border: 1px solid #eef0f2;
    transition: transform 0.2s ease, box-shadow 0.2s ease;
  }
  
  /* 鼠标悬停时的浮动阴影效果 */
  .fullwidth-card:hover {
    transform: translateY(-3px);
    box-shadow: 0 10px 20px rgba(0,0,0,0.06);
  }

  .fullwidth-images {
    width: 100%; /* 图片容器全宽 */
    display: flex;
    flex-direction: column;
    gap: 12px;
  }

  /* 针对多张图片做横向排列适配 */
  .fullwidth-images.row-layout {
    flex-direction: row;
  }
  
  .fullwidth-images img {
    width: 100%; /* 图片占满容器宽度 */
    border-radius: 8px;
    object-fit: cover;
    border: 1px solid #eee;
  }

  .fullwidth-content {
    display: flex;
    flex-direction: column;
  }

  .fullwidth-title {
    font-size: 1.25em;
    font-weight: 700;
    margin-top: 0;
    margin-bottom: 12px;
    line-height: 1.4;
  }

  .fullwidth-title a {
    color: #2c3e50; /* 更沉稳的标题颜色 */
    text-decoration: none;
    border-bottom: 2px solid transparent;
    transition: border-color 0.2s ease, color 0.2s ease;
  }

  .fullwidth-title a:hover {
    color: #0366d6;
    border-bottom: 2px solid #0366d6;
  }

  .fullwidth-desc {
    font-size: 0.95em;
    color: #555;
    line-height: 1.6;
    margin: 0;
  }
</style>

# Project
<div class="fullwidth-card">
  <div class="fullwidth-images">
    <img src="/images/project1.png" alt="Auto-Bidding in Large-Scale Auctions">
  </div>
  <div class="fullwidth-content">
    <h2 class="fullwidth-title">
      <a href="https://github.com/alimama-tech/AuctionNet" target="_blank">NeurIPS 2024 Competition Track: Auto-Bidding in Large-Scale Auctions</a>
    </h2>
    <p class="fullwidth-desc">
      This competition was hosted by the PKU-Alimama Artificial Intelligence Innovation Joint Lab, a collaboration between Alibaba Group and Peking University. As a member of the lab, I was actively involved in organizing the competition. I worked closely with <a href="https://openreview.net/profile?id=~Shuai_Dou1" target="_blank">Shuai Dou</a> and <a href="https://scholar.google.com/citations?user=PYXmSwkAAAAJ&hl=en" target="_blank">Yeshu Li</a> to develop the agents for the competition system, focusing on creating robust models for decision-making in large-scale, competitive auctions.
    </p>
  </div>
</div>

# Public welfare
<div class="fullwidth-card">
  <div class="fullwidth-images">
    <img src="/images/public_welfare1.jpg" alt="Public Welfare Lecture 1">
  </div>
  <div class="fullwidth-content">
    <h2 class="fullwidth-title">
      <a href="https://zhuanlan.zhihu.com/p/4651711566" target="_blank">Democratization of AI</a>
    </h2>
    <p class="fullwidth-desc">
      I launched a public welfare campaign in Yulin City, Guangxi, to popularize AI knowledge, extending to high schools for public welfare lectures. The campaign primarily analyzed the impact of AI technology on the wealth gap and promoted the knowledge of using LLM.
    </p>
  </div>
</div>

# Miscellaneous
* Public Speaking: NYU PhD live! top 8 PhD speaker, member of the School Hosting Team in BJTU.
* Singing: Campus Musician on NetEase Cloud Music, Participated in a choir performance at a national event on Mango TV.
* Hip-hop Dance: Champion of the Small Group Category in the Capital Colleges Dance Competition, Beijing.
* Writing: Passionate about literature, I served as the Deputy Director of the Original Editorial Department for the school's official WeChat account, contributing to creative content and original articles.
