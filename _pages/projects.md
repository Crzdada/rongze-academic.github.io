---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

<!-- {% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->

-----  
<b><font font size='4.8' color='navy'>Master’s Dissertation: Optimisation of AGV System Guide-path Network Layout Considering Congestion Factors</font></b>  
_2020.11-2022.06_  
Based on the current layout of the machining workshop of a customized equipment intelligent manufacturing enterprise, it is proposed to first design an AGV guidance path network with a flexible structure. The aim is to reduce the probability of AGV operation congestion in the workshop during the planning stage, reduce the difficulty and complexity of subsequent AGV scheduling stages, and improve logistics transportation efficiency.  
Establish a mathematical model for the k-arc strongly connected guidance path network in the machining workshop, and first use the existing VNS algorithm to solve its problem. Then, improve the VNS algorithm and propose a solution algorithm based on adaptive large neighborhood search algorithm(ALNS). The experimental results show that the solution performance of this algorithm is better than that of the VNS algorithm.  

<style>
  .center{
      display:block;
      margin:auto;    
          }
  img[alt="current"]{width:400px;}
  img[alt="ALNS"]{width:400px;}
  img[alt="simulation"]{width:500px;}
  .image-container {
    display: flex;
    justify-content: center;
  }

  .image-container img {
    margin: 0 20px; /* 可以调整图片之间的间距 */
  }
</style>

<div class="image-container">
  <img src="../images/current_AGV_network.png" alt="current"/>
  <img src="../images/ALNS.png" alt="current"/>
</div>
<center>Comparison of topology of AGV guide-path between current solution and ALNS solution</center>  

<img src="../images/Simulation.PNG" alt="simulation" class="center">
<center>The simulation model of optimal 2-arc strong connect layout base on ALNS</center>

   

<b><font font size='4.8' color='navy'>Stochastic Flexible Layout optimization of Intelligent Workshop with Unidirectional Multiple Closed Loop AGVs</font></b>  
_2019.10-2022.01_  
_Funded by the National Natural Science Foundation of China, No. 51775120_  
_Ning Mao, Qinxin Chen, Huiyu Zhang, Yong Liao, Xuanrui Chen, Rongze Cai_
* **Key responsibilities:** studied the latest theories of workshop layout planning, based on which I optimized the underlying guide-path network topology design of the automated guided vehicle (AGV) to achieve a more flexible workshop.

<b><font font size='4.8' color='navy'>Research and Development of an Intelligent Workshop AGV Dispatching System</font></b>  
_2020.11-2021.08_  
_School-enterprise cooperation project_  
_Ning Mao, Rongze Cai, Changwei Hu, Feichuang Fang_
* **Key responsibilities:** lucubrated the AGV charging strategy of the machining workshop, constructed the simulation model of the workshop using the software Plant Simulation, and conducted simulation experiments to verify the model by designing different charging strategies.  
* **Result:** increased the AGV transport efficiency by 30% and reduced the electricity cost by 5%.  

<b><font font size='4.8' color='navy'>Development of Robot Intelligent Factory Planning System</font></b>  
_2019.12-2020.09_  
_School-enterprise cooperation project_  
_Ning Mao, Huiyu Zhang, Yong Liao, Xuanrui Chen, Rongze Cai, Ting Deng_  
* **Key responsibilities:** researched the network topology design of AGV guide-path and addressed the AGV congestion problems
* **Result:** A set of workshop layout planning and design systems were created based on the production characteristics of the enterprise in a bid to endow the enterprise with the rapid layout ability
