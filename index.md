<link rel="stylesheet" type="text/css" href="css/bootstrap.min.css">
<link rel="stylesheet" type="text/css" href="css/main.css?1" media="screen,projection">

## Deep Declarative Networks
[CVPR 2020 Workshop](http://cvpr2020.thecvf.com/program/workshops), 14 June, Seattle, Washington, USA

---

[Program](#program) |
[Invited Speakers](#invited-speakers) |
[Submission](#submission) |
[Important Dates](#important-dates) |
[Organizers](#organizers)

Conventional deep learning architectures involve composition of simple feedforward processing functions that are explicitly defined. Recently, researchers have been exploring deep learning models with implicitly defined components. To distinguish these from conventional deep learning models we call them **deep declarative networks**, borrowing nomenclature from the programming languages community ([Gould et al., 2019](https://arxiv.org/abs/1909.04866)).

<center>
<img src="assets/declarative_node2.png" width="70%">
</center>

Processing nodes in deep declarative networks involve solving an optimization problem in the forward pass. End-to-end learning back-propagates gradients through the node, which requires the optimization problem to be differentiable. A few recent works have studied various optimization problem classes and shown how backpropagation is possible even without the knowledge of the algorithm used for solving the problem in the first place ([Agrawal et al., 2019b](http://web.stanford.edu/~boyd/papers/pdf/diff_cvxpy.pdf); [Agrawal et al., 2019a](https://web.stanford.edu/~boyd/papers/pdf/diff_cone_prog.pdf); [Amos, 2019](http://reports-archive.adm.cs.cmu.edu/anon/2019/CMU-CS-19-109.pdf); [Pfau et al. 2019](https://arxiv.org/abs/1806.02215); [Amos and Kotler, 2017](https://github.com/locuslab/optnet); [Gould et al., 2016](https://arxiv.org/abs/1607.05447)). The ideas have been applied to various problems including video classification ([Fernando and Gould, 2016](http://proceedings.mlr.press/v48/fernando16.pdf); [Cherian et al., 2017](http://openaccess.thecvf.com/content_cvpr_2017/papers/Cherian_Generalized_Rank_Pooling_CVPR_2017_paper.pdf), [Wang and Cherian, 2019](https://ieeexplore.ieee.org/document/8812898)), attribute ranking ([Santa Cruz et al., 2018](https://ieeexplore.ieee.org/document/8481554)), and meta-learning ([Lee et al., 2019](http://openaccess.thecvf.com/content_CVPR_2019/papers/Lee_Meta-Learning_With_Differentiable_Convex_Optimization_CVPR_2019_paper.pdf)).

Variants of deep declarative networks have also been studied recently such as methods for imposing hard constraints on the output of neural network models ([Neila et al., 2017](https://infoscience.epfl.ch/record/262884?ln=en)), novel models based on back-propagating through ordinary differential equations ([Chen et al., 2018](https://papers.nips.cc/paper/7892-neural-ordinary-differential-equations.pdf)), approximating maximum satisfiability (MAXSAT) problems ([Wang et al., 2019](https://arxiv.org/abs/1905.12149)), and combinatorial submodular functions ([Tschiatschek et al., 2018](https://las.inf.ethz.ch/files/tschiatschek18submodular-diff.pdf)).

### Topics

This workshop explores the advantages (and potential shortcomings) of declarative networks and their variants, bringing ideas developed in different contexts under the umbrella of deep declarative networks. We will discuss technical issues that need to be overcome in developing such models and applications of these models to computer vision problems that show benefit over conventional approaches. Topics include:
* Declarative end-to-end learnable processing nodes
* Differentiable constrained and unconstrained (non-convex) optimization problems
* Differentiable convex optimization problems
* Imposing hard constraints in deep learning models
* Back-propagation through physical models
* Applications of the above to problems in computer vision such as differentiable rendering, differentiable 3d models, reinforcement learning, action recognition, meta-learning, etc.

## Program

TBA

## Invited Speakers

<div class="row">
  <div class="col-xs-3">
    <a href="http://bamos.github.io/" target="_blank">
      <img class="people-pic" src="assets/bamos.png">
    </a>
    <div class="people-name text-center">
      <a href="http://bamos.github.io/" target="_blank">Brandon Amos</a><br>
      Facebook AI
    </div>
   </div>
   
   <div class="col-xs-3">
    <a href="http://www.cs.toronto.edu/~rtqichen/" target="_blank">
      <img class="people-pic" src="assets/rchen.jpg">
    </a>
    <div class="people-name text-center">
      <a href="http://www.cs.toronto.edu/~rtqichen/" target="_blank">Ricky TQ Chen</a><br>
      University of Toronto
    </div>
  </div>
  
  <div class="col-xs-3">
    <a href="https://ai.stanford.edu/~cbfinn/" target="_blank">
      <img class="people-pic" src="assets/cfinn.jpg">
    </a>
    <div class="people-name text-center">
      <a href="https://ai.stanford.edu/~cbfinn/" target="_blank">Chelsea Finn</a><br>
      Stanford
    </div>
  </div>
</div>

<div class="row">
  <div class="col-xs-3">
    <a href="https://icwww.epfl.ch/~fua/" target="_blank">
      <img class="people-pic" src="assets/pfua.jpg">
    </a>
    <div class="people-name text-center">
      <a href="https://icwww.epfl.ch/~fua/" target="_blank">Pascal Fua</a><br>
      EPFL
    </div>
  </div>  

  <div class="col-xs-3">
    <a href="https://people.cs.umass.edu/~smaji/" target="_blank">
      <img class="people-pic" src="assets/smaji.jpg">
    </a>
    <div class="people-name text-center">
      <a href="https://people.cs.umass.edu/~smaji/" target="_blank">Subhransu Maji</a><br>
      UMass Amherst
    </div>
  </div> 

  <div class="col-xs-3">
    <a href="http://zicokolter.com/" target="_blank">
      <img class="people-pic" src="assets/zkolter.jpg">
    </a>
    <div class="people-name text-center">
      <a href="http://zicokolter.com/" target="_blank">Zico Kolter</a><br>
      CMU
    </div>
  </div> 
</div>

## Accepted Papers

* Zan Gojic, Caifa Zhou, Jan D. Wegner, Leonidas J. Guibas and Tolga Birdal, "*End-to-end globally consistent registration of multiple point clouds*".
* Edward Grefenstette, Brandon Amos, Denis Yarats, Phu Mon Htut, Artem Molchanov, Franziska Meier, Douwe Kiela, Kyunghyun Cho and Soumith Chintala, "*`higher`: A Pytorch Meta-Learning Library*".
* Krishna Murthy Jatavallabhula, Ganesh Iyer, Soroush Saryazdi and Liam Paull, "*&nabla;SLAM: Automagically differentiable SLAM*".
* Bashir Sadeghi, Lan Wang and Vishnu Boddeti, "*Adversarial Representation LearningWith Closed-Form Solvers*".
* Matteo Toso, Neill D. F. Campbell and Chris Russell, "*Fixing Implicit Derivatives: Trust-Region Based Learning of Continuous Energy Functions (Abridged)*".

**PDFs coming soon**

## Submission

We invite paper submissions of up to **four (4) pages** describing work in areas related to the workshop [topics](#topics).

Accepted submissions will be presented as short orals or posters at the workshop and will appear on the workshop website. Authors will be given an opportunity to revise the submission before posting on the website. Papers should follow the CVPR formatting guidelines and emailed as a single PDF to <a href="mailto:cvpr2020@deepdeclarativenetworks.com">cvpr2020@deepdeclarativenetworks.com</a>, with subject line `Paper: <title>`. Submissions are not anonymous (and should include all authors' names and affiliations). References are to be included in the 4-page limit.

### Dual Submissions

We encourage submissions of preliminary or ongoing work. Accepted papers will not appear in the official IEEE proceedings but will be made public on this website. Relevant work that has previously been published or is to be presented at the main conference is also welcome.

### Important Dates

* Submission deadline: ~~1 March 2020~~ 20 March 2020 **(extended)**
* Author notification: 13 April 2020
* Workshop camera-ready deadline: 8 May 2020
* Workshop date: 14 June 2020

## Organizers

<div class="row">
  <div class="col-xs-3">
    <a href="https://cecs.anu.edu.au/people/stephen-gould/" target="_blank">
      <img class="people-pic" src="assets/sgould.jpg">
    </a>
    <div class="people-name text-center">
      <a href="https://cecs.anu.edu.au/people/stephen-gould/" target="_blank">Stephen Gould</a><br>
      ANU
    </div>
  </div>
  <div class="col-xs-3">
    <a href="http://www.merl.com/people/cherian/" target="_blank">
      <img class="people-pic" src="assets/acherian.jpg">
    </a>
    <div class="people-name text-center">
      <a href="http://www.merl.com/people/cherian/" target="_blank">Anoop Cherian</a><br>
      MERL
    </div>
  </div>
  <div class="col-xs-3">
    <a href="https://sites.google.com/view/djcampbell/" target="_blank">
      <img class="people-pic" src="assets/dcampbell.jpg">
    </a>
    <div class="people-name text-center">
      <a href="https://sites.google.com/view/djcampbell/" target="_blank">Dylan Campbell</a><br>
      ANU
    </div>
  </div>
  <div class="col-xs-3">
    <a href="https://cecs.anu.edu.au/people/richard-hartley/" target="_blank">
      <img class="people-pic" src="assets/rhartley.jpg">
    </a>
    <div class="people-name text-center">
      <a href="https://cecs.anu.edu.au/people/richard-hartley/" target="_blank">Richard Hartley</a><br>
      ANU
    </div>
  </div>
</div>
<br>
<p>
Contact: <a href="mailto:cvpr2020@deepdeclarativenetworks.com">cvpr2020@deepdeclarativenetworks.com</a>
</p>
