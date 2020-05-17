# Responsible Machine Learning
#### GWU DNSC 6290

![A responsible machine learning workingflow](/img/rml_diagram_no_hilite.png)


**Source:** [*Information*, 11(3) (March 2020)](https://www.mdpi.com/2078-2489/11/3)

## Course Outline
* Lecture 1: Interpretable Machine Learning Models
* Lecture 2: Post-hoc Explanation
* Lecture 3: Discrimination Testing and Remediation
* Lecture 4: Machine Learning Security
* Lecture 5: Machine Learning Model Debugging
* Lecture 6: Responsible Machine Learning Best Practices

## Lecture 1: Interpretable Machine Learning Models

### Class Materials
* [Syllabus]()
* [Lecture Notes]()
* Software Examples:

### Suggested Reading

* **Introduction and Background**: 
  * [*Stop Explaining Black Box Machine Learning Models for High Stakes Decisions and Use Interpretable Models Instead*](https://www.nature.com/articles/s42256-019-0048-x) 
  * **[Responsible Artificial Intelligence](https://www.springer.com/gp/book/9783030303709)** - Sections 2.1-2.5, Chapter 7
  
* **Interpretable Machine Learning Techniques**:
  * **Interpretable Machine Learning** - [Chapter 4](https://christophm.github.io/interpretable-ml-book/simple.html)
  * [*Accurate Intelligible Models with Pairwise Interactions*](http://www.cs.cornell.edu/~yinlou/papers/lou-kdd13.pdf)
  * [*This Looks Like That: Deep Learning for Interpretable Image Recognition*](https://arxiv.org/pdf/1806.10574.pdf)
  
## Using Class Software Resources

1. Install [Git](https://git-scm.com/downloads).

2. Clone this repository with the examples

`$ git clone https://github.com/jphall663/GWU_rml.git`

3. Install Anaconda Python 5.1.0 from the [Anaconda archives](https://repo.continuum.io/archive/) and add it to your system path.

4. Change directories into the cloned repository

`$ cd GWU_rml`

5. Create a Python 3.6 virtual environment

`$ virtualenv -p /path/to/anaconda3/bin/python3.6 env_rml`

6. Activate the virtual environment

`$ source env_rml/bin/activate`

7. Install the correct packages for the example notebooks

`$ pip install -r requirements.txt`

8. Start Jupyter

`$ jupyter notebook`
