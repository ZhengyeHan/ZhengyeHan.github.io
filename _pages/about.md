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
  /* 实习卡片容器，增加整体宽度和呼吸感 */
  .internship-cards {
    width: 100%;
    margin-top: 20px;
  }

  /* 单个实习项目卡片 */
  .internship-item {
    display: flex;
    align-items: center; /* 关键：让所有内容在垂直方向上居中对齐 */
    background-color: #f9f9f9; /* 使用一个非常柔和的背景色，极大提升高级感 */
    border-radius: 12px; /* 更大的圆角，更柔和 */
    margin-bottom: 20px; /* 卡片之间的间距 */
    padding: 20px 25px; /* 卡片内边距，给内容呼吸空间 */
    border: 1px solid #e0e0e0; /* 柔和的边框 */
    transition: box-shadow 0.2s ease, transform 0.2s ease; /* 增加简单的 hover 效果，显得有质感 */
  }

  /* 悬停效果：轻微阴影和向上移动 */
  .internship-item:hover {
    box-shadow: 0 5px 15px rgba(0,0,0,0.05);
    transform: translateY(-2px);
  }

  /* 图标容器：大而清晰，且不变形的关键 */
  .logo-box {
    width: 100px; /* 极大地增加图标的最大空间 */
    height: 100px; /* 固定容器高度，确保所有行对齐 */
    margin-right: 30px; /* 图标和文字之间的间距 */
    display: flex;
    align-items: center; /* 垂直居中图标 */
    justify-content: center; /* 水平居中图标 */
    flex-shrink: 0; /* 确保在窄屏下图标不被压缩 */
    overflow: hidden; /* 隐藏溢出部分 */
  }

  /* 真正的图标：保持比例且不变形的关键 */
  .item-logo {
    max-width: 100%;
    max-height: 100%;
    object-fit: contain; /* 核心：在容器内保持比例，永不变形，即使原图比例不同（如美团的长方形） */
  }

  /* 文字内容容器 */
  .content-box {
    flex-grow: 1; /* 占用剩余所有空间 */
  }

  /* 组织名称 */
  .org-title {
    font-size: 1.3rem; /* 字体大一些，更专业 */
    font-weight: 700;
    color: #222;
    margin-bottom: 5px;
  }

  /* 持续时间 */
  .duration-text {
    font-size: 1rem;
    color: #666; /* 使用灰色，让时间不那么抢眼 */
    font-style: italic; /* 斜体增加学术感 */
  }
</style>

Hello, I am Zhengye Han (韩政业), a 1st year PhD student in [New York university](https://www.nyu.edu/), I am advised by Prof.[Quanyan Zhu](https://scholar.google.com/citations?user=Qt2WDh0AAAAJ&hl=en), I got my BS degree in Computer Science from [Beijing Jiaotong University](https://www.bjtu.edu.cn/), where I study under the supervision of Professor [Zhigang Cao](http://en.sem.bjtu.edu.cn/show-910-467.html). Under his guidance, I embarked on my academic journey through the study of game theory.

During my undergraduate studies, I had the privilege to join the Center on Frontiers of Computing Studies ([CFCS](https://cfcs.pku.edu.cn/)) at Peking University, working in the [daGAME](https://dagame.pku.edu.cn/) lab, where I focused on Reinforcement Learning and game theory. I am deeply grateful to Professor [Xiaotie Deng](https://cfcs.pku.edu.cn/english/people/faculty/xiaotiedeng/index.htm) for providing me with invaluable research and internship opportunities during this time. I would also like to extend my sincere thanks to PhD candidate [Zhijian Duan](https://zjduan.github.io/) for his important guidance throughout my time in the lab. 

### Research Interests

My research focuses on the following topics:
* Multi-Agent Systems: Specifically focusing on the integration of game theory and reinforcement learning in multi-agent environments.
* AI Safety: With a special emphasis on the safety of Large Language Models, including topics such as LLM jailbreaking.
* Reinforcement Learning: Including auto-bidding in online advertising, sequential decision-making, and safe reinforcement learning.


# Publications
* <strong>Zhengye Han</strong>, Quanyan Zhu. Toward a Dynamic Stackelberg Game-Theoretic Framework for Agentic AI Defense Against LLM Jailbreaking. In <em>International Conference on Learning Representations (ICLR) AI for Mechanism Design Workshop</em>, 2026.
* Quanyan Zhu, <strong>Zhengye Han</strong>. Split-Merge Dynamics for Shapley-Fair Coalition Formation. <em>arXiv preprint arXiv:2603.17153</em>, 2026.
* Quanyan Zhu, <strong>Zhengye Han</strong>. Learning, Misspecification, and Cognitive Arbitrage in Linear-Quadratic Network Games. <em>arXiv preprint arXiv:2603.17157</em>, 2026.
* Quanyan Zhu, <strong>Zhengye Han</strong>. A Mathematical Programming Approach to Computing and Learning Berk–Nash Equilibria in Infinite-Horizon MDPs. In <em>14th EAI International Conference on Game Theory for Networks (GameNets)</em>, 2026.
* <strong>Zhengye Han</strong>, Yusen Huo, Zhijian Duan, Tianyu Wang, Yeshu Li, Zhilin Zhang, Chuan Yu, Jian Xu, Bo Zheng, Xiaotie Deng. Action Sequence Planner: An Alternative for Offline Reinforcement Learning. 2025. 
* Shuai Dou, Yusen Huo, Zhilin Zhang, Yeshu Li, <strong>Zhengye Han</strong>, Kefan Su, Zongqing Lu, Chuan Yu, Jian Xu, Bo Zheng. Code Contributor to AuctionNet: A Novel Benchmark for Decision-Making in Large-Scale Games. In <em>NeurIPS 2024 Datasets and Benchmarks Track</em> (<span style="color: red;">Spotlight</span>). <a href="https://github.com/alimama-tech/AuctionNet" style="color: blue;">GitHub</a>

# Project
<div class="project">
  <h2><a href="https://zhengyehan.github.io/portfolio/portfolio-2/">NeurIPS 2024 Competition Track: Auto-Bidding in Large-Scale Auctions: Learning Decision-Making in Uncertain and Competitive Games</a></h2>
  <div class="project-images">
    <img src="/images/project1.png" alt="Project 1 Image" class="project-image">
  </div>
 <p>This competition was hosted by the PKU-Alimama Artificial Intelligence Innovation Joint Lab, a collaboration between Alibaba Group and Peking University. As a member of the lab, I was actively involved in organizing the competition. I worked closely with <a href="https://openreview.net/profile?id=~Shuai_Dou1">Shuai Dou</a> and <a href="https://scholar.google.com/citations?user=PYXmSwkAAAAJ&hl=en">Yeshu Li</a> to develop the agents for the competition system, focusing on creating robust models for decision-making in large-scale, competitive auctions.</p>
</div>

<div class="project">
  <h2><a href="https://zhengyehan.github.io/portfolio/portfolio-1/">Intelligent Recognition and Detection Platform for Muck</a></h2>
  <div class="project-images">
    <img src="/images/project2.jpg" alt="Project 2 Image" class="project-image">
  </div>
   <p>This project was a collaboration with the School of Civil Engineering, where we applied deep learning (DL) for image recognition and reinforcement learning (RL) for intelligent optimization. The platform addresses challenges in muck detection and improvement, leading to the creation of a fully functional machine prototype. Our work resulted in a national invention patent and three software copyrights.</p>
</div>

# Internship
For more details, please check my [LinkedIn]([https://www.linkedin.com/in/zhengye-han%EF%BC%88%E9%9F%A9%E6%94%BF%E4%B8%9A%EF%BC%89-a45624235/?originalSubdomain=cn](https://www.linkedin.com/in/zhengye-han-a45624235/)).
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
# Public welfare

<div class="project">
  <h2><a href="https://zhuanlan.zhihu.com/p/4651711566">Democratization of AI</a></h2>
  <div class="project-images">
    <img src="/images/public_welfare1.jpg" alt="Project 1 Image" class="project-image">
    <img src="/images/public_welfare3.jpg" alt="Project 3 Image" class="project-image">
  </div>
  <p>I launched a public welfare campaign in Yulin City, Guangxi, to popularize AI knowledge, extending to high schools for public welfare lectures. The campaign primarily analyzed the impact of AI technology on the wealth gap and promoted the knowledge of using LLM.</p>
</div>

# Miscellaneous
* Hip-hop Dance: Champion of the Small Group Category in the Capital Colleges Dance Competition, Beijing.
* Singing: Campus Musician on NetEase Cloud Music, Participated in a choir performance at a national event on Mango TV.
* Public Speaking: Member of the School Hosting Team.
* Psychology: Deputy Director of the Organizing Department in the School Psychology Association.
* Writing: Passionate about literature, I served as the Deputy Director of the Original Editorial Department for the school's official WeChat account, contributing to creative content and original articles.
