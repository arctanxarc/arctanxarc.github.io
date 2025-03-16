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

<head>
    <link rel="stylesheet" href="bootstrap.min.css">
    <script>var clicky_site_ids = clicky_site_ids || []; clicky_site_ids.push(101296995);</script>
    <script async src="//static.getclicky.com/js"></script>    
    <style>
	:root {
	  --theme-color: #EC707D; /* 确保这是一个有效的颜色 */
	  --venue-bg-color: rgb(108, 149, 181);
	}
	    
	g {
		color: #aaaaaa
	}

	 pt {
		/* color:chocolate; */
		/* color:#c50e0e; */
		color: var(--title-color);
		/* color:tomato; */
		font-weight: 500;
	}

	 em {
		font-style: italic;
	}

	 venue {
		/* background-color:royalblue; */
		/* background-color:rgb(80, 80, 80); */
		/* background-color: #d1a7a7; */
		/* background-color: #ca3737; */
		background-color: #EC707D;
		/* background-color: rgb(217, 229, 244); */
		/* color: rgb(16, 68, 158); */
		color: #ffffff;
		/* font-family: 'Nunito'; */
		font-size: 70%;
		font-weight: bold;
		line-height: 170%;
		/* padding-left: 1em;
		padding-right: 1em; */
		margin-right: 0.25em;
		width: 5em;
		display:inline-block;
		text-align: center;
		/* border-color: #ffffff; */
		border-width: 0px;
		border-style: none;
		border-radius: 0.1rem;
		/* -webkit-box-shadow:0 2px 5px 0 rgba(0,0,0,0.16),0 2px 10px 0 rgba(0,0,0,0.12);
		box-shadow:0 2px 5px 0 rgba(0,0,0,0.16),0 2px 10px 0 rgba(0,0,0,0.12); */
		/* border-radius: 4px; */
		/* -webkit-box-shadow:inset 0px 0px 0px 0.25em #fff;
	    -moz-box-shadow:inset 0px 0px 0px 0.25em #fff;
	    box-shadow:inset 0px 0px 0px 0.25em #fff; */
		/* border: #ffffff; */
		height: 1.7em;
		vertical-align:text-bottom;
		margin-bottom: 0.1em;
		/* letter-spacing: 0.1cap; */
	}

	 venue1 {
		/* background-color:royalblue; */
		/* background-color:rgb(80, 80, 80); */
		/* background-color: #d1a7a7; */
		/* background-color: #ca3737; */
		background-color: var(--venue-bg-color);
		/* background-color: rgb(217, 229, 244); */
		/* color: rgb(16, 68, 158); */
		color: #ffffff;
		/* font-family: 'Nunito'; */
		font-size: 70%;
		font-weight: bold;
		line-height: 170%;
		/* padding-left: 1em;
		padding-right: 1em; */
		margin-right: 0.25em;
		width: 5em;
		display:inline-block;
		text-align: center;
		/* border-color: #ffffff; */
		border-width: 0px;
		border-style: none;
		border-radius: 0.1rem;
		/* -webkit-box-shadow:0 2px 5px 0 rgba(0,0,0,0.16),0 2px 10px 0 rgba(0,0,0,0.12);
		box-shadow:0 2px 5px 0 rgba(0,0,0,0.16),0 2px 10px 0 rgba(0,0,0,0.12); */
		/* border-radius: 4px; */
		/* -webkit-box-shadow:inset 0px 0px 0px 0.25em #fff;
	    -moz-box-shadow:inset 0px 0px 0px 0.25em #fff;
	    box-shadow:inset 0px 0px 0px 0.25em #fff; */
		/* border: #ffffff; */
		height: 1.7em;
		vertical-align:text-bottom;
		margin-bottom: 0.1em;
		/* letter-spacing: 0.1cap; */
	}
 
	.filter {
		color: var(--color);
		background-color: #fff;
		border: var(--border);
		border-style: solid;
		border-radius: 0.2rem;
		border-width: 1.5px;
		transition: all .3s;
		touch-action: manipulation;
		font-size: 80%;
		line-height: 120%;
		/* width: 5em; */
	}
	
	.filter:focus {
		color: #171e29;
	}
	  
	  .filter:hover {
		border-color: var(--theme-color);
		color: white;
		background-color: var(--theme-color);
		fill: var(--theme-color);
	  }
	  
	  .filter:active {
		border-color: var(--theme-color);
		color: var(--theme-color);
		fill: var(--theme-color);
	  }
	  
	.button-59 {
	  align-items: center;
	  background-color: #fff;
	  border: 1px solid #dadada;
	  box-sizing: border-box;
	  color: #000000;
	  cursor: pointer;
	  display: inline-block; /* 修改为 inline-block */
	  fill: #000;
	  font-family: 'Nunito';
	  font-size: 0.7rem;
	  height: 1.1rem;
	  justify-content: center;
	  line-height: 1.3;
	  min-width: 60px; /* 增加最小宽度 */
	  outline: 0;
	  padding: 0 10px; /* 增加左右内边距 */
	  text-align: center;
	  text-decoration: none;
	  transition: color .3s, background-color .3s, border-color .3s; /* 限制过渡范围 */
	  user-select: none;
	  -webkit-user-select: none;
	  touch-action: manipulation;
	  margin-right: 0.2em;
	  border-radius: 0.2rem;
	}
	
	.button-59:hover {
	  border-color: var(--theme-color);
	  color: #fff;
	  fill: var(--theme-color);
	  background-color: var(--theme-color);
	  text-decoration: none;
	}
	
	.button-59:active {
	  border-color: var(--theme-color);
	  color: #fff;
	  fill: var(--theme-color);
	  background-color: var(--theme-color);
	}
	
	@media (min-width: 768px) {
	  .button-59 {
	    padding-left: 5px;
	    padding-right: 5px;
	  }
	}
    </style>
    <script>
        try{
            if (window.screen.width < 700) {
                setActiveStyleSheet("jemdoc_mobile.css"); 
            } 
            else if(/iPad/i.test(navigator.userAgent)){ 
                setActiveStyleSheet("jemdoc.css"); 
            } 
            else{
                setActiveStyleSheet("jemdoc.css"); 
            } 
        } 
        catch(e){} 
	
        function setActiveStyleSheet(filename){
            document.write("<link href="+filename+" rel=stylesheet>");
        }

        function checkFilter(type, li) {
            if (type == "All") {
                return true
            }
            else if (type == "First-authored") {
                res = li.getAttribute("first_authored")
                return res
            }
            else {
                cate = li.getAttribute("category")
                if (!cate) {
                    return false
                }
                items = cate.split(',')
                for (j = 0; j < items.length; j++) {
                    console.log(items[j])
                    if (type.toUpperCase() == items[j].toUpperCase()) {
                        return true
                    }
                }
                return false
            }
        }

        function filterPub(type) {
            ul = document.getElementById("publications")
            li = ul.getElementsByTagName("li")
            for (i = 0; i < li.length; i++) {
                if (!checkFilter(type, li[i])) {
                    li[i].style.display = "none";
                }
                else {
                    li[i].style.display = ""
                }
            }
            // change the button color
            bts = document.getElementsByClassName("filter")
            for (k = 0; k < bts.length; k++) {
                if (bts[k].textContent == type) {
                    bts[k].style.setProperty("--color", "#000")
                    bts[k].style.setProperty("--border", "#000")
                    // bts[k].style.color = "#000"
                }
                else {
                    bts[k].style.setProperty("--color", "#a0a0a0")
                    bts[k].style.setProperty("--border", "#d3d3d3")
                    // bts[k].style.color = "#a0a0a0"
                }
            }
        }

    </script>

    <script>
        // import data from './bibtex.json' assert { type: 'json' };

        function getBibTex(key) {
            prompt("You can copy the text manually.", data[key]);
        }
    </script>
</head>

<span class='anchor' id='about-me'></span>

# 👤 Biography
Ruichuan An is a senior undergraduate student at **Xi'an Jiaotong University** and I will join **Peking University** as a master, where I am supervised by [Prof. Wentao Zhang](https://zwt233.github.io/) at [AAIS](https://www.aais.pku.edu.cn/). Currently, I serve as a research intern at **Microsoft Research Asia**. Previously, I had a wonderful time doing research at [HMI Lab](https://pku-hmi-lab.github.io/HMI-Web/), where I worked closely with [Prof. Shanghang Zhang](https://www.shanghangzhang.com). More about my experience can be found in [CV](assets/Ruichuan_An_new.pdf).

Many kind people helped me in my journey. If you want to talk more about research or seek advice that I might be able to provide, please no hesitation to reach out. Moreever, feel free to drop me an Email for any form of communication or collaboration!

<div class="highlight-blocks">
  <div class="highlight-block">
    <h3>🔬 AI Researcher</h3>
    <ul>
      <li>Research focus on <strong>Multi-Modality</strong> and <strong>Data-Centric AI</strong></li>
      <li>Multi-Modality: Vision-Language Model, Unified Understanding and Generation, Personalization</li>
      <li>Data-Centric AI: Dataset in learning, Synthetic Data(including other interesting phenomenon about data)</li>
    </ul>
  </div>
  
  <!-- <div class="highlight-block">
    <h3>✍️ Given Credits</h3>
    <ul>
      <li><strong>First</strong> China Association for Science and Technology "<strong>Young Elite Scientist Sponsorship Program (Ph.D.)</strong>", 2025-2027</li>
      <li><a href="https://scholar.google.com/citations?user=R5iSLPQAAAAJ&hl=zh-CN" target="_blank">
  <img src="https://img.shields.io/badge/Google%20Scholar-152%20Citations-9cf?logo=Google%20Scholar&labelColor=f6f6f6&style=flat" alt="Google Scholar Citations">
</a></li>
	<li><a href="https://github.com/RoyZry98" target="_blank">
  <img src="https://img.shields.io/badge/GitHub-Stars%20212-9cf?logo=GitHub&labelColor=f6f6f6&color=EC707D&logoColor=000000&style=flat" alt="GitHub Stars">
</a></li>
    </ul>
  </div> -->
  
  <div class="highlight-block">
    <h3>☎️ Contact Info</h3>
    <ul>
      <li><strong>Address:</strong> <a href="https://www.google.com/maps/place/%E5%BE%AE%E8%BD%AF%E4%BA%9A%E6%B4%B2%E7%A0%94%E7%A9%B6%E9%99%A2/@39.977248,116.3321331,17z/data=!3m1!4b1!4m6!3m5!1s0x35f053f0ab311e9f:0x4a43f1f260da036c!8m2!3d39.977244!4d116.337004!16s%2Fg%2F1tg4jk1c?entry=ttu&g_ep=EgoyMDI1MDMxMi4wIKXMDSoASAFQAw%3D%3D">Microsoft Research Asia, Beijing, China</a></li>
      <li><strong>Phone:</strong> +(86) 187-0689-6777</li>
      <li><strong>Email:</strong> <email>arctanxarc[AT]gmail.com arctanxarc[AT]xjtu.edu.cn</email></li>
      <li><strong>WeChat:</strong> arc2002822</li>
    </ul>
  </div>
</div>

# 🎓 Educations
- <img src="images/pku_.png" style="width: 20px;height: auto;display: inline-block;vertical-align: middle"> **Peking University** (2025.09-2027.09) M.S. in Mathematics
- <img src="images/xjtu_.png" style="width: 20px;height: auto;display: inline-block;vertical-align: middle"> **Xi'an Jiaotong University** (2021.09-2025.06) B.Eng. in Software Engineering
<br>

# 🔥 News
<div id="news" class="w3-container w3-margin-top-2 w3-cursive">
	  <div style="height:200px; width:100%; overflow:auto;">
	    <h4>📌 We have several academic intern positions at DCML Lab (Peking University). We actively work on Data-Centric AI and Multi-modality. If you like what we do, don't hesitate to contact me.</h4>
	    <p>[03.2025] 💼 I joined <strong>Microsoft Research Asia</strong> as a Research Intern.</p>
	    <p>[02.2025] 🎉 One paper <strong>MOVE-KD</strong> was accepted by <strong>CVPR 2025</strong> (CCF-A), congratulations to Jiajun.</p>
	    <p>[12.2024] 🎉 One paper <strong>Draw and Understand</strong> was accepted by <strong>ICLR 2025</strong> (CCF-A), congratulations to Weifeng.</p>
        <p>[09.2024] 🎓 I was offered a M.S. in Mathematics at Peking University supervised by <a class="blue-text" href="https://zwt233.github.io/" target="_blank"><strong>Prof. Wentao Zhang</strong></a>.</p>
        <p>[06.2024] 🎉 One paper <strong>SSD-LLM</strong> was accepted by <strong>ECCV 2024</strong> (CCF-A), I am the co-first author, see you in Milano.</p>
        <p>[05.2024] 🎉 One paper <strong>Can Modifying Data Address Graph Domain Adaptation?</strong> was accepted by <strong>KDD 2024</strong> (CCF-A), congratulations to Renhong.</p>

	    <!-- <p>[12.2024] 🏅 I was named <strong>"Outstanding Ph.D. Candidate"</strong> by NJU.</p>
	    <p>[11.2024] 💰 I was offered <strong>"Bank of Jiangsu"</strong> Scholarship from NJU.</p>
	    <p>[09.2024] 💻 The Panasonic Corporation is integrating the VeCAF (MM'24) into its actual business operations.</p>
	    <p>[08.2024] 💼 I joined the Beijing Academy of Artificial Intelligence supervised by <a class="blue-text" href="https://www.shanghangzhang.com/" target="_blank"><strong>Prof. Shanghang Zhang</strong></a>.</p>
	    <p>[07.2024] 🎉 One paper <strong>VeCAF</strong> was accepted by <strong>ACM Multimedia 2024</strong> (CCF-A) as first author.</p>
	    <p>[07.2024] 🎓 I am offered a dual Ph.D. at The Hong Kong Polytechnic University supervised by <a class="blue-text" href="https://web.comp.polyu.edu.hk/csdwang/" target="_blank"><strong>Prof. Dan Wang</strong></a>.</p>
	    <p>[05.2024] 🎉 One paper <strong>MuPFL</strong> was accepted by <strong>IEEE Transaction on Mobile Computing</strong> (CCF-A) as first author.</p>
	    <p>[04.2024] 📚 Our project: Activation Sparsity via Mixture of Experts for Continual Test Time Adaptation, has been selected as one of the Jiangsu Province Graduate Research and Practical Innovation Project.</p>
	    <p>[03.2024] 💻 The Panasonic Corporation is integrating the MoFME (AAAI'24) into its actual business operations.</p>
	    <p>[01.2024] 🎉 One paper <strong>BEVUDA</strong> was accepted by <strong>IEEE ICRA 2024</strong> (CCF-B) as first author.</p>
	    <p>[12.2023] 🎉 One paper <strong>MoFME</strong> was accepted by <strong>AAAI 2024</strong> (CCF-A) as first author.</p>
	    <p>[08.2023] 🏅 We won 2nd place in the SHIFT Challenge 2023 - Continuous Test-time Adaptation for Semantic Segmentation in the challenges of VCL Workshop, ICCV2023.</p>
	    <p>[06.2023] 🎓 I joined the ISCL lab at Nanjing University and the HMI Lab of the NATIONAL ENGINEERING RESEARCH CENTER OF VISUAL TECHNOLOGY at Peking University as a joint Ph.D. student.</p>
	    <p>[04.2023] 🎉 One paper <strong>RepCaM</strong> was accepted by <strong>ACM NOSSDAV 2023</strong> (CCF-B) as first author.</p>
	    <p>[03.2023] 🎉 One paper <strong>CdFed</strong> was accepted by <strong>IEEE ICME 2023</strong> (CCF-B) as first author.</p>
	    <p>[03.2023] 🎉 One paper <strong>FedFHN</strong> was accepted by <strong>IEEE Network</strong> (CAS-Q2) as first author.</p>
	    <p>[03.2023] 🎉 One paper <strong>FedAB</strong> was accepted by <strong>IEEE Internet of Things Journal</strong> (CAS-Q1).</p>
	    <p>[03.2023] 🎉 Two papers <strong>BEVSAN</strong> and <strong>CDCCA</strong> were accepted by <strong>IEEE CVPR 2023</strong> (CCF-A).</p>
	    <p>[03.2023] 🎓 I received M.Phil. degree from CUHKSZ.</p>
	    <p>[09.2022] 💼 I joined OPPO research as a Research Intern.</p>
	    <p>[08.2021] 🎓 I joined INML lab in CUHKSZ as an M.Phil. student.</p>
         -->
	  </div>
	</div>
 
<br>

# 📝 Publications
## 📒 Selected publications/preprints
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV'2024</div><img src='images/eccv_arc.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**LLM as Dataset Analyst: Subpopulation Structure Discovery with Large Language Model**

- Yulin Luo*, **Ruichuan An\***, Bocheng Zou, Yiming Tang, Jiaming Liu, Shanghang Shang
- European Computer Vision Conference <br><strong>(CCF-A)</strong>, 2024.
- [[Paper]](https://arxiv.org/abs/2405.02363) [[Code]](https://github.com/llm-as-dataset-analyst/SSDLLM)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv'2025</div><img src='images/iccv_arc.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**MC-LLaVA: Multi-Concept Personalized Vision-Language Model**

- **Ruichuan An**, Sihan Yang, Ming Lu, Renrui Zhang, Kai Zeng, Yulin Luo, Ying Chen, Jiajun Cao, Hao Liang, Qi She, Shanghang Zhang, Wentao Zhang
<!-- - Arxiv <br><strong>(CCF-A)</strong>, 2025. -->
- [[Paper]](https://arxiv.org/abs/2411.11706) [[Code]](https://github.com/arctanxarc/MC-LLaVA)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR'2025</div><img src='images/iclr_arc.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Draw-and-Understand: Leveraging Visual Prompts to Enable MLLMs to Comprehend What You Want**

- Weifeng Lin, Xinyu Wei, **Ruichuan An**, Peng Gao, Bocheng Zou, Yulin Luo, Siyuan Huang, Shanghang Zhang, Hongsheng Li
- International Conference on Learning Representations <br><strong>(CCF-A)</strong>, 2025.
- [[Paper]](https://arxiv.org/abs/2403.20271) [[Code]](https://draw-and-understand.github.io/)
</div>
</div>

<!-- ## 📚 Full publications
*: Equal Contribution.<br>
CCF-A/CAS-Q1 as First-author: <venue>AAAI</venue>x 1, <venue>ACM MM</venue>x 1, <venue>TMC</venue>x 1, <venue>TCSVT</venue>x 1 <br><br>

<button class="filter" type="button" onclick="filterPub('All')" style="--color: #000; --border: #000">All</button>&nbsp;
<button class="filter" type="button" onclick="filterPub('First-authored')">First author</button>&nbsp;
<button class="filter" type="button" onclick="filterPub('Efficiency')">Efficiency</button>&nbsp;
<button class="filter" type="button" onclick="filterPub('Generalization')">Generalization</button>&nbsp;

<ul id="publications">
    <li first_authored=true category="Efficiency">
        <venue>AAAI'24</venue><pt>Efficient Deweather Mixture-of-Experts with Uncertainty-aware Feature-wise Linear Modulation</pt><br>
	<b>Rongyu Zhang</b><g>, Yulin Luo, Jiaming Liu, Huanrui Yang, Zhen Dong, Denis Gudovskiy, Tomoyuki Okuno, Yohei Nakata, Kurt Keutzer, Yuan Du, Shanghang Zhang</g><br>
        <p>
            <a href="https://ojs.aaai.org/index.php/AAAI/article/download/29622/31055" class="button-59">PDF</a>
            <a href="https://github.com/RoyZry98/MoFME-Pytorch" class="button-59">Code</a>
	    <img src="https://img.shields.io/github/stars/RoyZry98/MoFME-Pytorch?style=social" class="star-badge" alt="GitHub Stars">
        </p>
    </li>
    <li first_authored=true category="Efficiency">
        <venue>MM'24</venue><pt>VeCAF: Vision-language Collaborative Active Finetuning with Training Objective Awareness</pt><br>
        <b>Rongyu Zhang*</b><g>, Zefan Cai*, Huanrui Yang*, Zidong Liu, Denis Gudovskiy, Tomoyuki Okuno, Yohei Nakata, Kurt Keutzer, Baobao Chang, Yuan Du, Li Du, Shanghang Zhang</g><br />
        <p>
            <a href="https://arxiv.org/pdf/2401.07853" class="button-59">PDF</a>
	    <a href="https://github.com/RoyZry98/VeCAF-Pytorch" class="button-59">Code</a>
	    <img src="https://img.shields.io/github/stars/RoyZry98/VeCAF-Pytorch?style=social" class="star-badge" alt="GitHub Stars">
        </p>
    </li>
    <li first_authored=true category="Generalization">
	<venue>TMC'24</venue><pt>Multi-level Personalized Federated Learning on Heterogeneous and Long-Tailed Data</pt><br>
	<b>Rongyu Zhang</b><g>, Yun Chen, Chenrui Wu, Fangxin Wang, Bo Li</g><br>
	<p>
		<a class="button-59" href="https://arxiv.org/pdf/2405.06413">PDF</a>
		<a class="button-59" href="https://github.com/RoyZry98">Code</a>
	</p>
    </li>
    <li first_authored=true category="Generalization">
        <venue>TCSVT'25</venue><pt>BEVUDA++: Geometric-aware Unsupervised Domain Adaptation for Multi-View 3D Object Detection</pt><br>
        <b>Rongyu Zhang</b><g>, Jiaming Liu, Xiaoqi Li, Xiaowei Chi, Dan Wang, Li Du, Yuan Du, Shanghang Shang</g><br>
        <p>
		<a href="https://ieeexplore.ieee.org/document/10816404" class="button-59">PDF</a>
		<a class="button-59" href="https://github.com/RoyZry98">Code</a>
        </p>
    </li>
    <li first_authored=true category="Efficiency">
        <venue>Network'23</venue><pt>Optimizing Efficient Personalized Federated Learning with Hypernetworks at Edge</pt><br>
        <b>Rongyu Zhang</b><g>, Yun Chen, Chenrui Wu, Fangxin Wang, Jiangchuan Liu</g><br />
        <p>
            <a href="https://arxiv.org/pdf/2211.17126" class="button-59">PDF</a>
            <a href="https://github.com/RoyZry98" class="button-59">Code</a>
        </p>
    </li>
    <li first_authored=true category="Efficiency">
        <venue>Nossdav'23</venue><pt>RepCaM: Re-parameterization Content-aware Modulation for Neural Video Delivery</pt><br>
        <b>Rongyu Zhang*</b><g>, Lixuan Du*, Jiaming Liu*, Congcong Song, Fangxin Wang, Xiaoqi Li, Ming Lu, Yandong Guo, Shanghang Zhang</g><br />
        <p>
            <a href="https://dl.acm.org/doi/pdf/10.1145/3592473.3592567" class="button-59">PDF</a>
            <a href="https://github.com/RoyZry98/RepCaM-Pytorch" class="button-59">Code</a>
	    <img src="https://img.shields.io/github/stars/RoyZry98/RepCaM-Pytorch?style=social" class="star-badge" alt="GitHub Stars">
	    <font color="red">[Oral Presentation]</font>
        </p>
    </li>
    <li first_authored=true category="Efficiency">
        <venue>ICME'23</venue><pt>Cluster-driven GNN-based Federated Recommendation System with Biased Message Dropout</pt><br>
        <b>Rongyu Zhang*</b><g>, Yun Chen*, Chenrui Wu, Fangxin Wang</g><br />
        <p>
            <a href="https://ieeexplore.ieee.org/abstract/document/10219619" class="button-59">PDF</a>
	    <a href="https://github.com/RoyZry98" class="button-59">Code</a>
        </p>
    </li>
    <li first_authored=true category="Generalization">
        <venue>ICRA'24</venue><pt>BEVUDA: Multi-geometric Space Alignments for Domain Adaptive BEV 3D Object Detection</pt><br>
        <g>Jiaming Liu*, </g><b>Rongyu Zhang*</b><g>, Xiaowei Chi, Xiaoqi Li, Ming Lu, Yandong Guo, Shanghang Zhang</g><br />
        <p>
            <a href="https://arxiv.org/pdf/2211.17126" class="button-59">PDF</a>
	    <a href="https://github.com/RoyZry98" class="button-59">Code</a>
        </p>
    </li>
    <li category="Efficiency">
        <venue>AAAI'25</venue><pt>PAT: Pruning-Aware Tuning for Large Language Models</pt><br>
        <g>Yijiang Liu, Huanrui Yang, Youxin Chen, </g><b>Rongyu Zhang</b><g>, Miao Wang, Yuan Du, Li Du</g><br />
        <p>
            <a href="https://arxiv.org/abs/2006.04558" class="button-59">PDF</a>
	    <a href="https://github.com/kriskrisliu/PAT" class="button-59">Code</a>
	    <img src="https://img.shields.io/github/stars/kriskrisliu/PAT?style=social" class="star-badge" alt="GitHub Stars">
        </p>
    </li>
    <li category="Generalization">
        <venue>CVPR'23</venue><pt>Cloud-Device Collaborative Adaptation to Continual Changing Environments in the Real-world</pt><br>
        <g>Yulu Gan, Mingjie Pan, </g><b>Rongyu Zhang</b><g>, Zijian Ling, Lingran Zhao, Jiaming Liu, Shanghang Zhang</g><br />
        <p>
            <a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Pan_Cloud-Device_Collaborative_Adaptation_to_Continual_Changing_Environments_in_the_Real-World_CVPR_2023_paper.pdf" class="button-59">PDF</a>
	    <a href="https://github.com/RoyZry98" class="button-59">Code</a>
        </p>
    </li>
    <li category="Generalization">
        <venue>CVPR'23</venue><pt>BEV-SAN: Accurate BEV 3D Object Detection via Slice Attention Networks</pt><br>
        <g>Xiaowei Chi, Jiaming Liu, Ming Lu, </g><b>Rongyu Zhang</b><g>, Zhaoqing Wang, Yandong Guo, Shanghang Zhang</g><br />
        <p>
            <a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Chi_BEV-SAN_Accurate_BEV_3D_Object_Detection_via_Slice_Attention_Networks_CVPR_2023_paper.pdf" class="button-59">PDF</a>
	    <a href="https://github.com/litwellchi/BEV-SAN" class="button-59">Code</a>
	    <img src="https://img.shields.io/github/stars/litwellchi/BEV-SAN?style=social" class="star-badge" alt="GitHub Stars">
        </p>
    </li>
    <li category="Efficiency">
        <venue>CVPR'23</venue><pt>FedAB: Truthful Federated Learning with Auction-based Combinatorial Multi-armed Bandit</pt><br>
        <g>Chenrui Wu, Yifei Zhu, </g><b>Rongyu Zhang</b><g>, Yun Chen, Fangxin Wang, Shuguang Cui</g><br />
        <p>
            <a href="https://ieeexplore.ieee.org/abstract/document/10092911" class="button-59">PDF</a>
	    <a href="https://github.com/RoyZry98" class="button-59">Code</a>
        </p>
    </li>
    <li first_authored=true category="Generalization">
        <venue1>arXiv'24</venue1><pt>Decomposing the Neural: Activation Sparsity via Mixture of Experts for Continual Test Time Adaptation</pt><br>
        <b>Rongyu Zhang*</b><g>, Aosong Cheng, Yulin Luo, Gaole Dai, Huanrui Yang, Jiaming Liu, Ran Xu, Li Du, Yuan Du, Yanbing Jiang, Shanghang Zhang</g> <br />
        <p>
            <a href="https://arxiv.org/pdf/2405.16486" class="button-59">PDF</a>
            <a href="https://github.com/RoyZry98/MoASE-Pytorch" class="button-59">Code</a>
	    <img src="https://img.shields.io/github/stars/RoyZry98/MoASE-Pytorch?style=social" class="star-badge" alt="GitHub Stars">
        </p>
    </li>
    <li first_authored=true category="Efficiency">
        <venue1>arXiv'24</venue1><pt>Implicit Neural Image Field for Biological Microscopy Image Compression</pt><br>
        <b>Rongyu Zhang*</b><g>, Gaole Dai*, Cheng-Ching Tseng*, Qingpo Wuwu*, Shaokang Wan*, Ming Lu, Tiejun Huang, Yu Zhou, Ali Ata Tuz, Matthias Gunzer, Jianxu Chen, Shanghang Zhang</g> <br />
        <p>
            <a href="http://arxiv.org/abs/2405.19012" class="button-59">PDF</a>
            <a href="https://github.com/RoyZry98/INIF-Pytorch" class="button-59">Code</a>
	    <img src="https://img.shields.io/github/stars/RoyZry98/INIF-Pytorch?style=social" class="star-badge" alt="GitHub Stars">
        </p>
    </li>
    <li first_authored=true category="Efficiency">
        <venue1>arXiv'24</venue1><pt>Intuition-aware Mixture-of-Rank-1-Experts for Parameter Efficient Finetuning</pt><br>
        <g>Yijiang Liu*, </g><b>Rongyu Zhang*</b><g>, Huanrui Yang, Kurt Keutzer, Yuan Du, Li Du, Shanghang Zhang</g> <br />
        <p>
            <a href="https://arxiv.org/pdf/2404.08985.pdf" class="button-59">PDF</a>
            <a href="https://github.com/RoyZry98" class="button-59">Code</a>
        </p>
    </li>
    <li first_authored=true category="Generalization">
        <venue1>arXiv'24</venue1><pt>M2Chat: Empowering VLM for Multimodal LLM Interleaved Text-Image Generation</pt><br>
        <g>Xiaowei Chi*, </g><b>Rongyu Zhang*</b><g>, Zhengkai Jiang, Yijiang Liu, Yatian Wang, Xingqun Qi, Wenhan Luo, Peng Gao, Shanghang Zhang, Qifeng Liu, Yike Guo</g> <br />
        <p>
            <a href="https://arxiv.org/pdf/2311.17963" class="button-59">PDF</a>
            <a href="https://github.com/litwellchi/M2Chat" class="button-59">Code</a>
		<img src="https://img.shields.io/github/stars/litwellchi/M2Chat?style=social" class="star-badge" alt="GitHub Stars">
        </p>
    </li>
    <li category="Generalization">
        <venue1>arXiv'24</venue1><pt>EVA: An Embodied World Model for Future Video Anticipation</pt><br>
        <g>Xiaowei Chi, Hengyuan Zhang, Chun-Kai Fan, Xingqun Qi, </g><b>Rongyu Zhang</b><g>, Aosong Cheng, Yulin Luo, Gaole Dai, Huanrui Yang, Jiaming Liu, Ran Xu, Li Du, Yuan Du, Yanbing Jiang, Shanghang Zhang</g> <br />
        <p>
            <a href="https://arxiv.org/pdf/2405.16486" class="button-59">PDF</a>
            <a href="https://github.com/litwellchi/EmbodiedVideoAnticipator" class="button-59">Code</a>
		<img src="https://img.shields.io/github/stars/litwellchi/EmbodiedVideoAnticipator?style=social" class="star-badge" alt="GitHub Stars">
        </p>
    </li>
    <li category="Generalization">
        <venue1>arXiv'24</venue1><pt>ViML: A Video, Music, Language Unified Dataset for Understanding and Generation</pt><br>
        <g>Xiaowei Chi, Aosong Chen, Pengjun Fang, Yatian Wang, Zeyue Tian, Yingqing He, Zhaoyang Liu, Xingqun Qi, </g><b>Rongyu Zhang</b><g>, Mengfei Li, Jiahao Pan, Yanbing Jiang, Wei Xue, Wenhan Luo, Qifeng Chen, Shanghang Zhang, Qifeng Liu, Yike Guo</g> <br />
        <p>
            <a href="https://arxiv.org/pdf/2407.20962" class="button-59">PDF</a>
            <a href="https://github.com/litwellchi/MMTrail" class="button-59">Code</a>
	    <img src="https://img.shields.io/github/stars/litwellchi/MMTrail?style=social" class="star-badge" alt="GitHub Stars">
        </p>
    </li>
</ul>
  
<br>

<span class='anchor' id='honors-and-awards'></span> -->

# 🥇 Honors and Awards
- *(2024)*: &nbsp;Rising Star of the Year (5/2233) Highest personal honors in college.
- *(2024, 2023, 2022)*: &nbsp;XJTU Outstanding Student*3
- *(2023)*: &nbsp;Huawei Scholarship 10k CNY, only awarded to 3 undergraduate students in XJTU per year.

<span class='anchor' id='services'></span>

# 💼 Services
<!-- #### Journal reviewer
- IEEE Transaction on Mobile Computing
- IEEE Transaction on Computers
- IEEE Transaction on Neural Networks and Learning Systems
- IEEE Internet of Things Journal -->

#### Conference reviewer
- ICCV 2025, ICRA 2025, FM@ICLR 2025

<!-- <span class='anchor' id='internships'></span> -->

<!-- # 💻 Internships
- **Microsoft Research Asia** (2025.03-2025.09) Research Intern -->

<br>

<span class='anchor' id='miscellaneous'></span>

# 😄 Miscellaneous
<!-- <div class="highlight-blocks">
  <div class="highlight-block">
    <h3>❤️ Family</h3>
    <ul>
      <img src="images/qiaoqiao.jpg" alt="family Image" style="display: block; margin: auto; max-width: 100%; height: auto;">
     <br>
	    <li>I have a beautiful girlfriend, <a href='https://scholar.google.com/citations?user=G_BypiwAAAAJ&hl=zh-CN&oi=ao'>Ziqi Qiao</a>, who is also a Ph.D. student at Peking University. We also own an adorable cat 🐱 named QiuQiu. He brings us tremendous fun and happiness.</li>
    </ul>
  </div>
  
  <div class="highlight-block">
    <h3>🧑‍🤝‍🧑 Friends</h3>
    <ul>
	<img src="images/friends.png" alt="friend Image" style="display: block; margin: auto; max-width: 100%; height: auto;">
      <br>
	    <li>Here are some of my closest academic friends: <a href='https://liujiaming1996.github.io/'>Jiaming Liu</a>, <a href='https://scholar.google.com/citations?user=SgeV4NkAAAAJ&hl=zh-CN&oi=ao'>Yulin Luo</a>, <a href='https://gumpest.github.io/'>Yuan Zhang</a>, and Gaole Dai from PKU; <a href='https://scholar.google.com/citations?hl=zh-CN&user=Vl1X_-sAAAAJ'>Xiaowei Chi</a> from HKUST; <a href='https://wuchenrui.github.io/'>Chenrui Wu</a> from ZJU&SFU; <a href='https://yilijin.github.io/'>Yili Jin</a> from McGill.</li>
    </ul>
  </div>
  
  <div class="highlight-block">
    <h3>😄 Hobbies</h3>
    <ul>
	<img src="images/football_new.png" alt="hobby Image" style="display: block; margin: auto; max-width: 100%; height: auto;">
      <br>
	    <li>I am a crazy basketball 🏀 & football ⚽️ fan. I enjoy the games of Kevin Durant 🕷️ and Kyrie Irving 🧙. I also wholeheartedly pledge my allegiance to Chelsea Football Club, KTBFFH! 💙</li>
    </ul>
  </div>
</div>

<br> -->

<!-- <div style="text-align: center;"> -->
<div style="width: 20%; position:relative; left:40%">
  <script type="text/javascript" id="clstr_globe" src="//clustrmaps.com/globe.js?d=TexC6zB_7AOUKNMMshe4U4igIY-rca8pyS5kiQ7N6C8"></script>
    <!-- 地图小部件代码结束 -->
</div>

