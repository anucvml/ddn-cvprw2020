## Deep Declarative Networks


[Program](#program) |
[Invited Speakers](#invited-speakers) |
[Submission](#submission) |
[Organizers](#organizers)

Conventional deep learning architectures involve composition of simple feedforward processing functions that are explicitly defined. Recently, researchers have been exploring deep learning models with implicitly defined components. To distinguish these from conventional deep learning models we call them deep declarative networks, borrowing nomenclature from the programming community (Gould et al., 2019).

Processing nodes in deep declarative networks involve solving an optimization problem in the forward pass. End-to-end learning back-propagates gradients through the node, which requires the optimization problem to be differentiable. A few recent works have studied various optimization problem classes and shown how backpropagation is possible even without the knowledge of the algorithm used for solving the problem in the first place (Agrawal, 2019; Amos, 2019; Pfau et al. 2019; Amos and Kolter, 2017; Gould et al., 2016). The ideas have been applied to various problems including video classification (Fernando and Gould, 2017; Cherian et al., 2018, Wang and Cherian, 2019), attribute ranking (Santa Cruz et al., 2018), and meta-learning (Lee et al., 2018).

Variants of deep declarative networks have also been studied recently such as methods for imposing hard constraints on the output of neural network models (Neila et al., 2017) and novel models based on back-propagating through ordinary differential equations (Chen, 2018) and combinatorial submodular functions (Tschiatschek, 2018).

This workshop explores the advantages of declarative networks and their variants. We aim to discuss technical issues that need to be overcome in developing such models and applications of these models to computer vision problems that show benefit over conventional approaches. Topics will include:
Declarative end-to-end learnable processing nodes
Differentiable constrained and unconstrained optimization problems
Imposing hard constraints in deep learning models
Backpropagation through physical models
Applications of above to problems in computer vision

The topic of this workshop generalizes several previous (and forthcoming) workshops at computer vision and machine learning venues. The advantage of this is that it brings together ideas explored in different contexts under the same umbrella of declarative networks. Related workshops include:
Robust Subspace Learning and Applications Workshop, ICCV 2019, which will include sessions on clustering and subspace learning as nodes of a neural network (e.g., deep closed-form subspace learning, Seo et al.)
Statistical Deep Learning in Computer Vision, ICCV 2019, will include topics on statistical meta-learning exploring generalization properties of neural network features.
Smooth Games Optimization and Machine Learning Workshop, NeurIPS 2018, included topics from mathematical programming including bi-level optimization in a Generative Adversarial Network setting.

## Program

TBA

## Invited Speakers

TBA

## Submission

Instructions coming soon...

## Organizers

<div>
<table>
  <tr>
    <td><img src="assets/sgould.jpg" height="100px" width="100px" style="border-radius: 50%;" /></td>
    <td><img src="assets/acherian.jpg" height="100px" width="100px" style="border-radius: 50%;" /></td>
    <td><img src="assets/dcampbell.jpg" height="100px" width="100px" style="border-radius: 50%;" /></td>
    <td><img src="assets/rhartley.jpg" height="100px" width="100px" style="border-radius: 50%;" /></td>
  </tr>
  <tr>
    <td>Stephen Gould</td>
    <td>Anoop Cherian</td>
    <td>Dylan Campbell</td>
    <td>Richard Hartley</td>
  </tr>
</table>
</div>
