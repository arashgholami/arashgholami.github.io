---
layout: default
---
<div class="menu-container noselect">
   <table class="content-table">
      <tr>
        <td>
          <p class="text right-align text-large add-top-margin" style="width:100%;">
              I am currently a Research Fellow in school of Computer Science, Carnegie Mellon University. I received my PhD from the EECS Department at University of California Irvine. I am recipient of 2018 "IEEE Communications Society and Information Theory Society" Joint best Paper Award and 2014 "IEEE Globecom" best paper award. I study Probability Theory, Information Theory, Statistics and Algorithms.
          </p>
        </td>
      </tr>
   </table>
</div>



# Featured Publications


<div class="menu-container noselect">
   <table class="content-table">
    <col width="500px" />
    <col width="800px" />
      <tr>
        <td>
          <img class="left-align image noselect" src="/images/ALS.png" width="1000">
        </td>
        <td>
          <p class="text cright-align text-large add-top-margin" style="width:100%;" align="center">
              <font style="font-size:20px">Aligned image sets under channel uncertainty: Settling conjectures on the collapse of degrees of freedom under finite precision CSIT </font><br>
              <font style="font-size:15px">Arash Gholami Davoodi and Syed Ali Jafar<br>
                 IEEE Transactions 2016</font><br>
              <font style="color:red;"> 2019 IEEE Communications Society and Information Theory Society Joint Best Paper Award in Paris, France and 2014 IEEE GLOBECOM Best Paper Award in Austin,Texas </font><br> 
               <font style="font-size:13px">A conjecture made by Lapidoth et al. at Allerton 2005 (also an open problem presented at ITA 2006) states that the degrees of freedom (DoF) of a two user broadcast channel, where the transmitter is equipped with two antennas and each user is equipped with one antenna, must collapse under finite precision channel state information at the transmitter (CSIT). That this conjecture, which predates interference alignment, has remained unresolved, is emblematic of a pervasive lack of understanding of the DoF of wireless networks-including interference and X networks-under channel uncertainty at the transmitter(s). In this paper, we prove that the conjecture is true in all non-degenerate settings (e.g., where the probability density function of unknown channel coefficients exists and is bounded). The DoF collapse even when perfect channel knowledge for one user is available to the transmitter. This also settles a related recent conjecture by Tandon et al. The key to our proof is a bound on the number of codewords that can cast the same image (within noise distortion) at the undesired receiver whose channel is subject to finite precision CSIT, while remaining resolvable at the desired receiver whose channel is precisely known by the transmitter. We are also able to generalize the result along two directions. First, if the peak of the probability density function is √ allowed to scale as O(( √P) α ), representing the concentration of probability density (improving CSIT) due to, e.g., quantized feedback at rate (α/2) log(P), then the DoF is bounded above by 1+α, which is also achievable under quantized feedback. Second, we generalize the result to arbitrary number of antennas at the transmitter, arbitrary number of single-antenna users, and complex channels. The generalization directly implies a collapse of DoF to unity under non-degenerate channel uncertainty for the general K-user interference and M × N user X networks as well. </font><br>
             <a href="https://ieeexplore.ieee.org/abstract/document/7502087"><font style="font-size:15px">PDF</font></a>
             


<div class="menu-container noselect">
   <table class="content-table">
    <col width="500px" />
    <col width="800px" />
      <tr>
        <td>
          <img class="left-align image noselect" src="/images/figs.png" width="1000">
        </td>
        <td>
          <p class="text right-align text-large add-top-margin" style="width:100%;" align="center">
            <font style="font-size:20px">Sum-set inequalities from aligned image sets: Instruments for robust GDoF bounds </font><br>
            <font style="font-size:15px">Arash Gholami Davoofi and Syed Ali Jafar</font><br>
              IEEE Transactions 2020</font><br>
            <font style="font-size:13px">Sum-set inequalities specialized to the generalized degrees of freedom (GDoF)
framework are presented in this paper. These are information theoretic lower bounds on the entropy of bounded density
linear combinations of discrete, power-limited dependent random variables in terms of the joint
entropies of arbitrary linear combinations of new random variables that are obtained by power
level partitioning of the original random variables. These bounds generalize the aligned image
sets approach, and are useful instruments to obtain GDoF characterizations for wireless networks, especially with multiple antenna nodes, subject to arbitrary channel strength and channel
uncertainty levels. To demonstrate the utility of these bounds, we consider a non-trivial instance
of wireless networks – a two user interference channel with different number of antennas at each
node, and different levels of partial channel knowledge available to the transmitters. We obtain tight GDoF characterization for specific instance of this channel with the aid of sum-set
inequalities.</font><br>
<font style="font-size:15px"> <a href="https://arxiv.org/pdf/1703.01168.pdf">PDF</a> </font>
          </p>
        </td>
      </tr>
   </table>
</div>


<div class="menu-container noselect">
   <table class="content-table">
    <col width="500px" />
    <col width="800px" />
      <tr>
        <td>
          <img class="left-align image noselect" src="/images/fig2.png" width="1000">
        </td>
        <td>
          <p class="text right-align text-large add-top-margin" align="center">
            <font style="font-size:20px">ForestDSH: A Universal Hash Design for Discrete Probability Distributions</font><br>
            <font style="font-size:15px">Arash Gholami Davoodi, Sean Chang, Hyun Gon Yoo, Anubhav Baweja, Mihir Mongia and Hosein Mohimani<br>
            AISTATS 2020</font><br>
            <font style="font-size:13px">In this paper, we consider the problem of classification of $M$ high dimensional queries $y^1,\cdots,y^M\in \mathcal{B}^S$ to  $N$ high dimensional classes  $x^1,\cdots,x^N\in \mathcal{A}^S$ where $\mathcal{A}$ and $\mathcal{B}$ are discrete alphabets and the probabilistic model that relates data to the classes $\mathbb{P}(x,y)$ is known. This problem has applications in various fields including the database search problem in mass spectrometry. The problem is analogous  to the  nearest neighbor search problem, where the goal is to find the data point in a database that is the most similar to a query point. The state of the art method for solving an approximate version of the nearest neighbor search problem in high dimensions is locality sensitive hashing (LSH). LSH is based on designing hash functions that map near points to the same buckets with a probability higher than random (far) points. To solve our high dimensional classification problem, we introduce distribution sensitive hashes that map jointly generated pairs $(x,y)\sim \mathbb{P}$  to the same bucket with probability higher than random pairs $x\sim {\mathbb{P}}^{\mathcal{A}}$ and $y\sim {\mathbb{P}}^{\mathcal{B}}$, where  $ {\mathbb{P}}^{\mathcal{A}}$ and ${\mathbb{P}}^{\mathcal{B}}$ are the marginal probability distributions of $\mathbb{P}$. We design distribution sensitive hashes using a forest of decision trees and we show that the complexity of search grows with $O(N^{\lambda^*({\mathbb{P}})})$ where $\lambda^*({\mathbb{P}})$ is expressed in an analytical form. {\color{red}We further show that the proposed hashes perform faster than state of the art approximate nearest neighbor search methods for a range of probability distributions, in both theory and simulations.} Finally, we apply our method to the spectral library search problem in mass spectrometry, and show that it is an order of magnitude faster than the state of the art methods.</font><br>

          </p>
        </td>
      </tr>
   </table>
</div>




