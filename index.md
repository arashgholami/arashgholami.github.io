---
layout: default
---
<div class="menu-container noselect">
   <table class="content-table">
      <tr>
        <td>
          <img class="left-align image noselect" src="/images/face.png" style="width:100%">
        </td>
        <td>
          <p class="text right-align text-large add-top-margin" style="width:100%;">
              I am currently a Research Fellow in school of Computer Science, Carnegie Mellon University. I received my PhD from the EECS Department at University of California Irvine. I am recipient of 2018 "IEEE Communications Society and Information Theory Society" Joint best Paper Award and 2014 "IEEE Globecom" best paper award. I study probability theory, statistics, information theory, and the interplay between algorithms, classification and learning.
          </p>
        </td>
      </tr>
   </table>
</div>



# Featured Publications
* * *

<div class="menu-container noselect">
   <table class="content-table">
    <col width="500px" />
    <col width="800px" />
      <tr>
        <td>
          <img class="left-align image noselect" src="/images/crowd.jpg" width="1000">
        </td>
        <td>
          <p class="text cright-align text-large add-top-margin" style="width:100%;" align="center">
              <font style="font-size:20px">Aligned image sets under channel uncertainty: Settling conjectures on the collapse of degrees of freedom under finite precision CSIT </font><br>
              <font style="font-size:15px">Arash Gholami Davoodi and Syed Ali Jafar<br>
              <font style="color:red;"> 2019 IEEE Communications Society and Information Theory Society Joint Best Paper Award in Paris, France and 2014 IEEE GLOBECOM Best Paper Award in Austin,Texas </font><br> 
               <font style="font-size:13px">A conjecture made by Lapidoth et al. at Allerton 2005 (also an open problem presented at ITA 2006) states that the degrees of freedom (DoF) of a two user broadcast channel, where the transmitter is equipped with two antennas and each user is equipped with one antenna, must collapse under finite precision channel state information at the transmitter (CSIT). That this conjecture, which predates interference alignment, has remained unresolved, is emblematic of a pervasive lack of understanding of the DoF of wireless networks-including interference and X networks-under channel uncertainty at the transmitter(s). In this paper, we prove that the conjecture is true in all non-degenerate settings (e.g., where the probability density function of unknown channel coefficients exists and is bounded). The DoF collapse even when perfect channel knowledge for one user is available to the transmitter. This also settles a related recent conjecture by Tandon et al. The key to our proof is a bound on the number of codewords that can cast the same image (within noise distortion) at the undesired receiver whose channel is subject to finite precision CSIT, while remaining resolvable at the desired receiver whose channel is precisely known by the transmitter. We are also able to generalize the result along two directions. First, if the peak of the probability density function is √ allowed to scale as O(( √P) α ), representing the concentration of probability density (improving CSIT) due to, e.g., quantized feedback at rate (α/2) log(P), then the DoF is bounded above by 1+α, which is also achievable under quantized feedback. Second, we generalize the result to arbitrary number of antennas at the transmitter, arbitrary number of single-antenna users, and complex channels. The generalization directly implies a collapse of DoF to unity under non-degenerate channel uncertainty for the general K-user interference and M × N user X networks as well. </font><br>
             <a href="https://openreview.net/pdf?id=1uufzxsxfL"><font style="font-size:15px">PDF</font></a>
             </p>
        </td>
      </tr>
   </table>
</div>

* * *

<div class="menu-container noselect">
   <table class="content-table">
    <col width="500px" />
    <col width="800px" />
      <tr>
        <td>
          <img class="left-align image noselect" src="/images/criage.png" width="1000">
        </td>
        <td>
          <p class="text right-align text-large add-top-margin" style="width:100%;" align="center">
            <font style="font-size:20px">Investigating Robustness and Interpretability of Link Prediction via Adversarial Modifications </font><br>
            <font style="font-size:15px">Pouya Pezeshkpour, Yifan Tian, Sameer Singh<br>
            NAACL 2019</font><br>
            <font style="font-size:13px">Representing entities and relations in an embedding space is a well-studied approach for machine learning on relational data. Existing approaches, however, primarily focus on improving accuracy and overlook other aspects such as robustness and interpretability. In this paper, we propose adversarial modifications for link prediction models: identifying the fact to add into or remove from the knowledge graph that changes the prediction for a target fact after the model is retrained. We introduce an efficient approach to estimate the effect of such modifications by approximating the change in the embeddings when the knowledge graph changes. We use these techniques to evaluate the robustness of link prediction models (by measuring sensitivity to additional facts), study interpretability through the facts most responsible for predictions (by identifying the most influential neighbors), and detect incorrect facts in the knowledge base.</font><br>
<font style="font-size:15px"><a href="https://pouyapez.github.io/criage/">Project Page</a>  &nbsp;&nbsp;&nbsp;  <a href="https://arxiv.org/pdf/1905.00563.pdf">PDF</a>  &nbsp;&nbsp;&nbsp;  <a href="https://github.com/pouyapez/criage">Source Code</a>  &nbsp;&nbsp;&nbsp;  <a href="https://www.youtube.com/watch?v=irVqAjt664s">Video on Youtube</a></font>
          </p>
        </td>
      </tr>
   </table>
</div>

* * *
<div class="menu-container noselect">
   <table class="content-table">
    <col width="500px" />
    <col width="800px" />
      <tr>
        <td>
          <img class="left-align image noselect" src="/images/graph.jpg" width="1000">
        </td>
        <td>
          <p class="text right-align text-large add-top-margin" align="center">
            <font style="font-size:20px">Embedding Multimodal Relational Data for Knowledge Base Completion</font><br>
            <font style="font-size:15px">Pouya Pezeshkpour, Liyan Chen, Sameer Singh<br>
            EMNLP 2018</font><br>
            <font style="font-size:13px">Knowledge bases (KB) are an essential part of many computational systems with applications in search, structured data management, recommendations, question answering, and information retrieval. However, KBs often suffer from incompleteness, noise in their entries, and inefficient inference under uncertainty. To address these issues learning relational KBs by representing entities and relations in an embedding space has been a focus of active research. Nevertheless, Knowledge bases in the real-world, contain a wide variety of data types such as text, images, and numerical values which are being ignored by current methodology. We propose multimodal knowledge base embeddings (MKBE) that use different neural encoders for this variety of observed data, and combine them with existing relational models to learn embeddings of the entities and multimodal data. Further, using these learned embedings and different neural decoders, we introduce a novel multimodal imputation model to generate missing multimodal values, like text and images, from information in the knowledge base.</font><br>
<font style="font-size:15px"><a href="https://pouyapez.github.io/mkbe/">Project Page</a>  &nbsp;&nbsp;&nbsp;   <a href="https://arxiv.org/pdf/1809.01341.pdf">PDF</a>  &nbsp;&nbsp;&nbsp;   <a href="https://github.com/pouyapez/mkbe">Source Code</a>  &nbsp;&nbsp;&nbsp;   <a href="https://www.youtube.com/watch?v=Bt5CccdXHUM&t=2s">Video on Youtube</a></font>
          </p>
        </td>
      </tr>
   </table>
</div>

* * *
<div class="menu-container noselect">
   <table class="content-table">
    <col width="500px" />
    <col width="800px" />
      <tr>
        <td>
          <img class="left-align image noselect" src="/images/2014.png"  width="1000">
        </td>
        <td>
          <p class="text right-align text-large add-top-margin"  align="center">
            <font style="font-size:20px">Optimal tradeoff between source and state distortions over a Gaussian channel using single and hybrid digital analog codes</font><br>
            <font style="font-size:15px">Pouya Pezeshkpour, Hamid Behroozi<br>
            IST'2014</font><br>
            <font style="font-size:13px">In this paper, the problem of transmitting an analog Gaussian source over an additive white Gaussian noise (AWGN) channel in the presence of a Gaussian interference known only at the transmitter is investigated. Our goal is to estimate both the analog source and the channel state at the receiver simultaneously. In this work, we present different transmission schemes based on joint source-channel coding. We study hybrid digital-analog (HDA) joint source-channel coding schemes and analyze the region of (mean-squared error) distortion pairs (in estimating the source and the state) that are simultaneously achievable.</font><br>
<font style="font-size:15px"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7000779">PDF</a></font>
          </p>
        </td>
      </tr>
   </table>
</div>



