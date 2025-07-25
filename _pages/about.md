---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I'm a second-year graduate student at the [School of Automation](https://automation.seu.edu.cn/), [Southeast University](https://www.seu.edu.cn/). My research interests include computer vision, 3D vision, and embodied AI, with a current focus on 3D hand-object interaction and physics-based grasping.

I am very fortunate to be advised by [Prof. Yangang Wang](https://www.yangangwang.com/). Before that, I received my bachelor's degree from the [University of Electronic Science and Technology of China (UESTC)](https://www.uestc.edu.cn/).

[Email](mailto:wendysun0107@gmail.com) / [Github](https://github.com/wendysun2001)

<h1>Publications</h1>

<div style="display: flex; align-items: flex-start;">
  <div style="flex: 1;">
    <img src="images/NPHand_0.jpg" alt="Paper image" style="max-width: 100%; height: auto;">
  </div>
  <div style="flex: 3; padding-left: 15px;">
    <strong>NP-Hand: Novel Perspective Hand Image Synthesis Guided by Normals</strong><br>
    Binghui Zuo,<strong>Wenqian Sun</strong>, Zimeng Zhao, Xiaohan Yuan, Yangang Wang<br>
    <i>IEEE Transactions on Image Processing (<strong>TIP</strong>), 2025</i><br>
<!--     2015-10-01<br><br> -->
    [<a href="https://ieeexplore.ieee.org/document/10689328">Paper</a>]
  </div>
</div>

---

<div style="display: flex; align-items: flex-start;">
  <div style="flex: 1;">
    <img src="images/NP.png" alt="Paper image" style="max-width: 100%; height: auto;">
  </div>
  <div style="flex: 3; padding-left: 15px;">
    <strong>GraspDiff: Grasping Generation for Hand-Object Interaction With Multimodal Guided Diffusion</strong><br>
    Binghui Zuo, Zimeng Zhao, <strong>Wenqian Sun</strong>, Xiaohan Yuan, Zhipeng Yu and Yangang Wang<br>
    <i>IEEE Transactions on Visualization and Computer Graphics (<strong>TVCG</strong>), 2024</i><br>
<!--     2015-10-01<br><br> -->
    [<a href="https://ieeexplore.ieee.org/document/10689328">Paper</a>]
  </div>
</div>

---

<div style="display: flex; align-items: flex-start;">
  <div style="flex: 1;">
    <img src="images/pose.png" alt="Paper image" style="max-width: 100%; height: auto;">
  </div>
  <div style="flex: 3; padding-left: 15px;">
    <strong>Accurate and Real-time Variant Hand Pose Estimation Based on Gray Code Bounding Box Representation</strong><br>
    Yangang Wang, <strong>Wenqian Sun</strong>, and Ruting Rao<br>
    <i>IEEE Sensors Journal, 2024</i><br>
<!--     2010-10-01<br><br> -->
    [<a href="https://ieeexplore.ieee.org/document/10506333">Paper</a>]
  </div>
</div>

---

<div style="display: flex; align-items: flex-start;">
  <div style="flex: 1;">
    <img src="images/Interprior.png" alt="Paper image" style="max-width: 100%; height: auto;">
  </div>
  <div style="flex: 3; padding-left: 15px;">
    <strong>Reconstructing Interacting Hands with Interaction Prior from Monocular Images</strong><br>
    Binghui Zuo, Zimeng Zhao, <strong>Wenqian Sun</strong>, Wei Xie, Zhou Xue and Yangang Wang<br>
    <i>IEEE/CVF International Conference on Computer Vision (<strong>ICCV</strong>), 2023</i><br>
<!--    The key idea is first to construct a two-hand interaction prior and recast the interaction reconstruction task as the conditional sampling from the prior.<br><br> -->
    [<a href="https://arxiv.org/abs/2308.14082">Paper</a>] [<a href="https://www.yangangwang.com/papers/iccv2023_interprior/BinghuiZuo-ICCV2023_InterPrior.html">Project Page</a>] [<a href="https://github.com/binghui-z/InterPrior_pytorch">Code [comming soon]</a>]
  </div>
</div>

---

<h1>Projects</h1>
<div class="container" style="display: flex; align-items: flex-start;">
    <div class="image" style="flex: 1;">
        <video controls autoplay muted style="max-width: 100%; height: auto;">
            <source src="images/handcollb_1.mp4" type="video/mp4">
            Your browser does not support the video tag. Please <a href="http://path-to-your-demo-video.mp4">click here to watch the video</a>.
        </video>
    </div>
    <div class="content" style="flex: 3; padding-left: 15px;">
        <strong>Motion Synthesis Framework for Hand-Object Interaction</strong> (First-author Under Review)<br>
        This project addresses <strong>hand-object interaction</strong> and proposes a two-stage motion synthesis framework with diffusion for <strong>two hands and articulated objects</strong>.<br>
       [<a href="https://github.com/wendysun2001">Code</a>] 
    </div>
</div>

---

<div class="container" style="display: flex; align-items: flex-start;">
    <div class="image" style="flex: 1;">
        <video controls autoplay muted style="max-width: 100%; height: auto;">
            <source src="images/atom.mp4" type="video/mp4">
            Your browser does not support the video tag. Please <a href="http://path-to-your-demo-video.mp4">click here to watch the video</a>.
        </video>
    </div>
    <div class="content" style="flex: 3; padding-left: 15px;">
        <strong>Task to Atom Action Segmentation</strong><br>
        This project focuses on segmenting and decomposing 3D hand-object interaction motion to identify the atom actions, facilitating data processing to further assist in robotic skill learning.<br>
       [<a href="https://github.com/wendysun2001/task2key2atom">Code</a>]
    </div>
</div>

---

<div class="container" style="display: flex; align-items: flex-start;">
    <div class="image" style="flex: 1;">
        <video controls autoplay muted style="max-width: 100%; height: auto;">
            <source src="images/pybullet.mp4" type="video/mp4">
            Your browser does not support the video tag. Please <a href="http://path-to-your-demo-video.mp4">click here to watch the video</a>.
        </video>
    </div>
    <div class="content" style="flex: 3; padding-left: 15px;">
        <strong>Dexterous Manipulation Transfer</strong><br>
        PyBullet Implementation <a href="https://meowuu7.github.io/QuasiSim/">QuasiSim</a> (<i>ECCV 2024</i>)<br>
        This project replicates the ECCV paper <i>QuasiSim</i>. We have implemented the single-hand object grab tracking task in PyBullet and are expanding to two-hand and multi-object tracking, with plans for migration to the Isaac Gym platform.<br>
    </div>
</div>






