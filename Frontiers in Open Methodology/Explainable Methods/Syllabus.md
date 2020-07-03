# Module III: Explainable-Methods

## Open Course Module on explainable methods   
### All Content CC-BY 4.0.  

Part of the "[Frontiers in Open Methodology](https://classroom.google.com/u/1/c/NTg0NTkyMjE0Njda)" course on Google Classroom. Be sure to join the course [Gitter channel](https://gitter.im/OrthogonalLabEd/community) for further discussion.  

### Introduction
Explainable methods (or X-methods) will allow us to avoid engaging in button-pressing exercises or implementing poorly described methodologies. X-methods builds off of explainable AI (X-AI), both of which are a move towards transparency and intuitive (visual) demonstrations of the processes associated with a particular methodology. This enables a wider variety of methods to be used without violations of basic assumptions or other misapplications. The two main principles of X-methods are interpretability and accessibility. This means that for any given model description, we should strive for completeness, interrogability, and transparency. In more practical terms, we should be able to integrate these principles into a data analysis pipeline and the practice of analysis and data science.

Minimum Viable Lesson:  
I) 14 slide lecture.  [Slides](https://github.com/Orthogonal-Research-Lab/Module-III-Explainable-Methods/blob/master/Version%201/explainable-methods.md)  

<p align="center">
  <img width="330" height="183" src="https://user-images.githubusercontent.com/38323286/47579482-b3433e00-d911-11e8-9ad0-26b4a5f2b51d.png"><br>
</p>

II) Interactive notebook walkthrough.  [Sample notebook](https://----)  

<p align="center">
  <img width="330" height="183" src="https://user-images.githubusercontent.com/38323286/49682437-e1bc4900-fa79-11e8-9b7e-f1a8779339b7.png"><br>
</p>

III) Guidelines and Principles:  

  1) model completeness: can we explain the technique used and show how the assumptions are not violated?

  2) model interrogation: can we test models with synthetic controls, pseudo-data, and rival hypotheses?

  3) model transparency: does your public repo include simulation code, tutorials, visualizations, or white (theory) papers?  

  4) model interpretability: how did you arrive at your results and what steps are required to understand them?  
  
IV) Sample Repository (idealized version by directory):  

  1) your favorite method (describe method).  
  
  2) application to data (how is this method applied to data).  
  
  3) competing methods (what methods are similar).  
  
  4) model assumptions (what are the main assumptions of the model).  
  
  5) visualization (how are the results visualized).  
  
  6) digital notebook (with tutorials).  
  
  7) technical papers and associated manuscripts (further reading).  
  
<p align="center">
  <img width="246" height="261" src="https://user-images.githubusercontent.com/38323286/47579321-3a43e680-d911-11e8-84f8-c5af9d3fde50.png"><br>
Practically implemented version for the paper "Morphogenetic processes as data: Quantitative structure in the *Drosophila* eye imaginal disc", BioSystems, doi:10.1016/j.biosystems.2018.10.005. [open access link](https://www.biorxiv.org/content/early/2018/08/19/395640)
</p>

V) References:

Patrick Ferris, [An introduction to explainable AI](https://medium.freecodecamp.org/an-introduction-to-explainable-ai-and-why-we-need-it-a326417dd000), and why we need it. FreeCode Camp (Medium).

Lenny Teytleman, [No more excuses for non-reproducible methods](https://www.nature.com/articles/d41586-018-06008-w). Nature WorldView.

Karthik Ram, [How To Make Your Data Analysis Notebooks More Reproducible](https://github.com/karthik/rstudio2019). Github.

Dirk Brockmann, [Complexity Explorables](https://www.complexity-explorables.org/explorables). Website.  

Mennatallah El-Assady, Duen Horng (Polo) Chau, Adam Perer, Hendrik Strobelt, Fernanda Viegas, [Workshop on Visualization for AI Explainability](http://visxai.io/). IEEE VIS Website.  

Brandon Thorpe, [The ReproRubric: evaluation criteria for the reproducibility of computational analyses](https://osf.io/thvef/). OSF Preprints, [doi:10.31219/osf.io/thvef](https://osf.io/thvef/)

VI) Potential exercises (one or more can be chosen by the learner):
  
   1) choose a method and create an explainable framework.
     
* repository of pseudo-data, simulations, graphs. Submit as a link in a Markdown file.
   
* create a pipeline for analysis and/or diagram the method of your choice. Submit as a link in a Markdown file, an image file, or an interactive notebook.
     
* push assignment to the [Push Assignments Here](https://github.com/Orthogonal-Research-Lab/Module-III-Explainable-Methods/tree/master/Push%20Assignments%20Here) folder in this directory. Format for file name: FirstName_LastName.foo

   2) what are the assumptions of your method, and how does this relate to your use of the model? Submit as text (with images if necessary) in a Markdown file.
     
* are the results replicable, or is there variation? How does model respond to various degrees of noise? Submit as text (with images if necessary) in a Markdown file.
   
* expected outcomes: what is deterministic, and what is stochastic? Submit as text (with images if necessary) in a Markdown file.

* push assignment to the [Push Assignments Here](https://github.com/Orthogonal-Research-Lab/Module-III-Explainable-Methods/tree/master/Push%20Assignments%20Here) folder in this directory. Format for file name: FirstName_LastName.foo
