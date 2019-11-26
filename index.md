## Deep Declarative Networks

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

[Program](#program)
[Invited Speakers](#invited-speakers)
[Submission](#submission)
[Organizers](#organizers)

## Program
## Invited Speakers
## Submission
## Organizers



### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/anucvml/ddn-workshop/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
