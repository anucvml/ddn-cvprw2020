<link rel="stylesheet" type="text/css" href="css/bootstrap.min.css">
<link rel="stylesheet" type="text/css" href="css/main.css?1" media="screen,projection">

# Invited Talk: Deep Surface Meshes

<div class="row">
  <div class="col-sm-3">
    <a href="https://icwww.epfl.ch/~fua/" target="_blank">
      <img class="people-pic" src="assets/pfua.jpg">
    </a>
    <div class="people-name text-center">
      <a href="https://icwww.epfl.ch/~fua/" target="_blank">Pascal Fua</a><br>
      EPFL
    </div>
  </div>
    
  <div class="col-sm-9">
    Geometric Deep Learning has recently made striking progress with the advent of Deep Implicit Fields (SDFs). They allow for detailed modeling of watertight surfaces of arbitrary topology while not relying on a 3D Euclidean grid, resulting in a learnable 3D surface parameterization that is not limited in resolution. Unfortunately, they have not yet reached their full potential for applications that require an explicit surface representation in terms of vertices and facets because converting the SDF to such a 3D mesh representation requires a marching-cube algorithm, whose output cannot be easily differentiated with respect to the SDF parameters. In this talk, I will present several approaches to overcoming this limitation and implementing convolutional neural nets that output complex 3D surface meshes while remaining fully-differentiable and end-to-end trainable. I will also present applications of these approaches for applications such as single view reconstruction, physically-Driven Shape Optimization, and bio-medical image segmentation.
  </div>
</div>
