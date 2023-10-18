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
<script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
<script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>
<style>
  .center{
      display:block;
      margin:auto;    
          }
  img[alt="current"]{width:400px;}
  img[alt="ALNS"]{width:400px;}
  img[alt="simulation"]{width:500px;}
  img[alt="architecture"]{width:600px;}
  img[alt="layout"]{width:600px;}
  .image-container {
    display: flex;
    justify-content: center;
  }

  .image-container img {
    margin: 0 20px; /* 可以调整图片之间的间距 */
  }
</style>

<h2><ion-icon name="pricetags-outline"></ion-icon> Current Projects</h2>
-----  
<b><font font size='4.8' color='navy'>Design and Development of Factory Production Simulation Management System</font></b>  
_**2023.06-Present**_  

* By adopting cloud storage and computing technology, we can address the issue of dispersed simulation data resources, achieve centralized data management, and maximize data sharing and reusability.
* We provide modeling process templates and customized libraries for lithium battery workshops to enable parameterized and rapid modeling
* We leverage Git version control and project management technologies to address the challenges of collaborative simulation modeling across multiple individuals and locations for medium to large-scale projects. Additionally, we customize and develop simulation optimization algorithm modules tailored to specific business scenarios, enhancing our capability to solve complex practical problems.
* **Expected Benefit:** improved the efficiency of simulation modelling by 40%, about &#36; 55~63k cost save per year, ROI(0.65)

<img src="../images/Production_Simulation_Project_System_Architecture.png" alt="architecture" class="center">
<center>The architecture of factory production simulation management system</center>
  
<h2><ion-icon name="time-outline"></ion-icon> Past Research</h2>  
-----  
<b><font font size='4.8' color='navy'>Master’s Dissertation: Optimisation of AGV System Guide-path Network Layout Considering Congestion Factors</font></b>  
_**2020.11-2022.06**_  
Based on the current layout of the machining workshop of a customized equipment intelligent manufacturing enterprise, it is proposed to first design an AGV guidance path network with a flexible structure. The aim is to reduce the probability of AGV operation congestion in the workshop during the planning stage, reduce the difficulty and complexity of subsequent AGV scheduling stages, and improve logistics transportation efficiency.  
Establish a mathematical model for the k-arc strongly connected guidance path network in the machining workshop, and first use the existing VNS algorithm to solve its problem. Then, improve the VNS algorithm and propose a solution algorithm based on adaptive large neighborhood search algorithm(ALNS). The experimental results show that the solution performance of this algorithm is better than that of the VNS algorithm.  



<div class="image-container">
  <img src="../images/current_AGV_network.png" alt="current"/>
  <img src="../images/ALNS.png" alt="current"/>
</div>
<center>Comparison of topology of AGV guide-path between current solution and ALNS solution</center>  

<img src="../images/Simulation.png" alt="simulation" class="center">
<center>The simulation model of optimal 2-arc strong connect layout base on ALNS</center>

   

<b><font font size='4.8' color='navy'>Stochastic Flexible Layout optimization of Intelligent Workshop with Unidirectional Multiple Closed Loop AGVs</font></b>  
_**2019.10-2022.01**_  
_Funded by the National Natural Science Foundation of China, No. 51775120_  
_Ning Mao, Qinxin Chen, Huiyu Zhang, Yong Liao, Xuanrui Chen, Rongze Cai_
* **Key responsibilities:** studied the latest theories of workshop layout planning, based on which I optimized the underlying guide-path network topology design of the automated guided vehicle (AGV) to achieve a more flexible workshop.

<b><font font size='4.8' color='navy'>Research and Development of an Intelligent Workshop AGV Dispatching System</font></b>  
_**2020.11-2021.08**_  
_School-enterprise cooperation project_  
_Ning Mao, Rongze Cai, Changwei Hu, Feichuang Fang_
* **Key responsibilities:** lucubrated the AGV charging strategy of the machining workshop, constructed the simulation model of the workshop using the software Plant Simulation, and conducted simulation experiments to verify the model by designing different charging strategies.  
* **Result:** increased the AGV transport efficiency by 30% and reduced the electricity cost by 5%.  

<div class="image-container">
  <img src="../images/AGVcharge.png" alt="current"/>
  <img src="../images/AGVchargerResult.png" alt="current"/>
</div>
<center>Multi AGV Charging Strategy for Job Shop Based on Time of Use Electricity Price Considering Limited Electricity Constraints</center>  


<b><font font size='4.8' color='navy'>Development of Robot Intelligent Factory Layout Designning System</font></b>  
_**2019.12-2020.09**_  
_School-enterprise cooperation project_  
_Ning Mao, Huiyu Zhang, Yong Liao, Xuanrui Chen, Rongze Cai, Ting Deng_  
* **Key responsibilities:** researched the network topology design of AGV guide-path and addressed the AGV congestion problems
* **Result:** A set of workshop layout planning and design systems were created based on the production characteristics of the enterprise in a bid to endow the enterprise with the rapid layout ability  

<img src="../images/Development_of_Robot_Intelligent_Factory_Layout_Designning_System.png" alt="layout" class="center">
<center>Facility layout design with simulation model</center>
