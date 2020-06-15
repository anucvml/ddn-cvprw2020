<link rel="stylesheet" type="text/css" href="css/bootstrap.min.css">
<link rel="stylesheet" type="text/css" href="css/main.css?1" media="screen,projection">

# Invited Talk: Deep equilibrium models and monotone operators

<div class="row">
  <div class="col-sm-3">
    <a href="http://zicokolter.com/" target="_blank">
      <img class="people-pic" src="assets/zkolter.jpg">
    </a>
    <div class="people-name text-center">
      <a href="http://zicokolter.com/" target="_blank">Zico Kolter</a><br>
      CMU
    </div>
  </div>
    
  <div class="col-sm-9">
    This talk will introduce our recent work on the Deep Equilibrium (DEQ) Model. Instead of stacking nonlinear layers, as is common in deep learning, this approach finds the equilibrium point of the repeated iteration of a single non-linear layer, then backpropagates through the layer directly using the implicit function theorem. The resulting method achieves or matches state of the art performance in many domains (while consuming much less memory), and can theoretically express any "traditional" deep network with just a single layer. However, existing work in DEQs leave open the question of the existence and uniqueness of these fixed points and attempts to compute them largely through heuristic methods. In the second part of the talk, we will thus introduce a new class of DEQ models based upon monotone operator theory. We illustrate how we can parameterize these networks such that they are guaranteed to have a unique equilibrium point, and show how to apply operator splitting methods to efficiently find these fixed points. We show that these monotone operator equilibrium networks can far outperform existing implicit models where solutions are similarly guaranteed to exist.
  </div>
</div>
<p/>

## Video

<iframe src="https://www.youtube.com/embed/NxPhV1G0Cl0" 
    width="560" 
    height="315"
    frameborder="0" 
    allowfullscreen>
</iframe>
<p/>

[back](https://anucvml.github.io/ddn-cvprw2020/#program)
