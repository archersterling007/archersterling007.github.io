---
layout: post
layout: post
title: Probabilistic Graphical Models
date: 2023-02-08 11:59:00-0400
description: A Mathematical tool used to represent and reason about the relationships between variables and their dependencies, using a graph-based representation and probability distributions.
tags: ["Probabilistic Graphical Models", "Variational Inference"]
categories: [""]
Probabilistic_Graphical_Models: true
---

Here is two lists of non-exhaustive key concepts and algorithms that you may find very useful:

- [Overview by Sewoong Oh](http://swoh.web.engr.illinois.edu/courses/IE598/handout/summary.pdf)
- [This one by me](/assets/pdf/PGM.pdf)

## Probabilistic Graphical Models

### Probabilistic Graphical Models: Books

- Probabilistic Graphical Models Principles and Techniques by Daphne Koller Nir Friedman
- Probabilistic Graphical Models Principles and Applications by Luis Enrique Sucar
- Reasoning with Probabilistic and Deterministic Graphical Models - Exact Algorithms by Rina Dechter
- An Introduction to Probabilistic Graphical Models by Michael I. Jordan - [Draft Chapters](https://people.eecs.berkeley.edu/~jordan/prelims/)
- Modeling and Reasoning with Bayesian Networks by Adnan Darwich - [Book](https://www.cambridge.org/core/books/modeling-and-reasoning-with-bayesian-networks/8A3769B81540EA93B525C4C2700C9DE6) and [Lectures](https://www.youtube.com/playlist?list=PLlDG_zCuBub6ywAIrM1DfJp8xaeVjyvwx)
- Information Theory, Inference, and Learning Algorithms by David J.C. MacKay - [Book (PDF File)](https://www.inference.org.uk/itprnn/book.pdf)
- Bayesian Reasoning and Machine Learning by David Barber - [Website](http://web4.cs.ucl.ac.uk/staff/D.Barber/pmwiki/pmwiki.php?n=Brml.HomePage) and [Book (PDF File)](http://web4.cs.ucl.ac.uk/staff/D.Barber/textbook/200620.pdf)
- Gaussian Processes for Machine Learning by Carl Edward Rasmussen and Christopher K. I. Williams - [Website](https://gaussianprocess.org/gpml/) and [Book (PDF File)](https://gaussianprocess.org/gpml/chapters/RW.pdf)
- Pattern Recognition and Machine Learning by Christopher M. Bishop - [Book (PDF File)](https://www.microsoft.com/en-us/research/uploads/prod/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf)
- Kevin P. Murphy Books [Website](https://probml.github.io/pml-book/):
  - Machine Learning A Probabilistic Perspective, 2012 - [Book (PDF File)](http://noiselab.ucsd.edu/ECE228/Murphy_Machine_Learning.pdf)
  - Probabilistic Machine Learning - An Introduction, 2022 - [https://probml.github.io/pml-book/book1.html](https://probml.github.io/pml-book/book1.html) and [Draft (PDF File)](https://github.com/probml/pml-book/releases/latest/download/book1.pdf)
  - Probabilistic Machine Learning - Advanced Topics, 2023 - [Website](https://probml.github.io/pml-book/book2.html) and [Final Draft](https://github.com/probml/pml2-book/releases/latest/download/book2.pdf)
- Bayesuvius, a visual dictionary of Bayesian Networks and Causal Inference - [Website](https://qbnets.wordpress.com/2020/11/30/my-free-book-bayesuvius-on-bayesian-networks/), [Book](https://github.com/rrtucci/Bayesuvius/raw/master/main.pdf) and [repo](https://github.com/rrtucci/Bayesuvius)

### Probabilistic Graphical Models: Courses

- University of Notre Dame Probabilistic Graphical Models Spring 2018 - [Website](https://www.zabaras.com/probabilistic-graphical-models) and [Lectures](https://www.youtube.com/playlist?list=PLd-PuDzW85AcV4bgdu7wHPL37hm60W4RM)
- CMU 10-418/10-618  Machine Learning for Structured Data:
  - Fall 2019 - [Website](http://www.cs.cmu.edu/~mgormley/courses/10418-f19/) and [Lectures](https://www.youtube.com/playlist?list=PL4CxkUJbvNVihRKP4bXufvRLIWzeS-ieP)
  - Fall 2022 - [Website](http://www.cs.cmu.edu/~mgormley/courses/10418/)

- CMU 10-708 Probabilistic Graphical Models:
  - Spring 2021 - [Website](http://www.cs.cmu.edu/~mgormley/courses/10708/index.html)
  - Spring 2020 - [Website](https://www.cs.cmu.edu/~epxing/Class/10708-20/) and [Lectures](https://www.youtube.com/playlist?list=PLoZgVqqHOumTqxIhcdcpOAJOOimrRCGZn)
  - Fall 2020 - [Website](http://www.cs.cmu.edu/~pradeepr/courses/708/2020-fall/)
  
- Illinois Institute of Technology CS 583 Probabilistic Graphical Models - Fall 2021 - [Website](https://github.com/CS583pgm/F2021)
- Illinois Institute of Technology IE598 Inference in Graphical Models - [Website](http://swoh.web.engr.illinois.edu/courses/IE598/index.html) and [Handouts](http://swoh.web.engr.illinois.edu/courses/IE598/handout.html)
- Stanford CS 228 - Probabilistic Graphical Models Winter 2021-22 - [Website](https://ermongroup.github.io/cs228/) and [Notes](https://ermongroup.github.io/cs228-notes/)
- University of Washington CSE 515 - Statistical Methods in Computer Science - [website](https://courses.cs.washington.edu/courses/cse515/21wi/schedule/)
- UCL Probabilistic and Unsupervised Learning Approximate Inference and Learning in Probabilistic Models (2022) - [Website](http://www.gatsby.ucl.ac.uk/teaching/courses/ml1/)
- CMSC 691 Graphical and Statistical Models of Learning Spring 2020 — [Website](https://redirect.cs.umbc.edu/~ferraro/teaching/691-s20/)

- University of Arizona :
  - [CSC 380 Probabilistic Graphical Models Fall 2021 (Principles of Data Science)](https://www2.cs.arizona.edu/~pachecoj/courses/csc380_fall21/index.html)
  - [CSC 535 Probabilistic Graphical Models Spring 2022](https://www2.cs.arizona.edu/~pachecoj/courses/csc535_spring22/index.html)
  - [CSC 696H  Probabilistic Graphical Models Fall 2022](https://www2.cs.arizona.edu/~pachecoj/courses/csc696h_fall22/index.html)
- University of Toronto CSC412/2506 Winter 2020 Probabilistic Learning and Reasoning [Website](https://probmlcourse.github.io/csc412/)
- University of Wisconsin CS839 Probabilistic Graphical Models [Website](https://thodrek.github.io/CS839_fall18/)
- University of Montreal IFT 6269 : Probabilistic Graphical Models - Fall 2022 [Website](http://www.iro.umontreal.ca/~slacoste/teaching/ift6269/A22/)
- University of Montreal IFT 6132 : Advanced Structured Prediction and Optimization - Winter 2021 [Website](http://www-labs.iro.umontreal.ca/~slacoste/teaching/ift6132/W21/)
- Mini-course "Learning with Structured Data" - [Lectures](https://www.youtube.com/playlist?list=PLEqoHzpnmTfA0wc1JxjoVVOrJlx8W0rGf)
- CompSci-276 Fall 2021, Reasoning in Graphical Models - [Lectures and Slides](https://www.ics.uci.edu/~dechter/courses/ics-276/fall-2021/)
  
### Probabilistic Graphical Models: Papers

- [Graphical Models, Exponential Families, and Variational Inference by Martin J. Wainwright and Michael I. Jordan](https://people.eecs.berkeley.edu/~wainwrig/Papers/WaiJor08_FTML.pdf)
- [Structured Learning and Prediction in Computer Vision by Sebastian Nowozin and Christoph H. Lampert](http://www.nowozin.net/sebastian/papers/nowozin2011structured-tutorial.pdf)
- Linguistic Structure Prediction by Noah A. Smith
- An Introduction to Conditional Random Fields by Charles Sutton

### Probabilistic Graphical Models: Examples

- [About Collection of probabilistic models and inference algorithms](https://github.com/wiseodd/probabilistic-models)

## Variational Inference in Depth

Inference in probabilistic models is often intractable. There are algorithms that provide approximate solutions to the inference problem (e.g., marginal inference) by using subroutines that involve sampling random variables. Most sampling-based inference algorithms are instances of Markov Chain Monte-Carlo (MCMC); two popular MCMC methods are Gibbs sampling and Metropolis-Hastings. Unfortunately, these sampling-based methods have several important shortcomings. Although they are guaranteed to find a globally optimal solution given enough time, it is difficult to tell how close they are to a good solution given the finite amount of time that they have in practice. In order to quickly reach a good solution, MCMC methods require choosing an appropriate sampling technique (e.g., a good proposal in Metropolis-Hastings). Choosing this technique can be an art in itself.
In this post, we are going to look at an alternative approach to approximate inference called the variational family of algorithms. The main idea of variational methods is to cast inference as an optimization problem.

### Variational Inference: Books

- Kevin P. Murphy Books [Website](https://probml.github.io/pml-book/):
  - Machine Learning A Probabilistic Perspective, 2012 - [Book (PDF File)](http://noiselab.ucsd.edu/ECE228/Murphy_Machine_Learning.pdf)
  - Probabilistic Machine Learning - An Introduction, 2022 - [https://probml.github.io/pml-book/book1.html](https://probml.github.io/pml-book/book1.html) and [Draft (PDF File)](https://github.com/probml/pml-book/releases/latest/download/book1.pdf)
  - Probabilistic Machine Learning - Advanced Topics, 2023 - [Website](https://probml.github.io/pml-book/book2.html) and [Final Draft](https://github.com/probml/pml2-book/releases/latest/download/book2.pdf)
- Pattern Recognition and Machine Learning by Christopher Bishop- [Book (PDF File)](https://www.microsoft.com/en-us/research/uploads/prod/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf)
- [Machine Learning by Jérémy Fix, Hervé Frezza-Buet, Matthieu Geist](https://frezza.pages.centralesupelec.fr/teachml2/Poly/Poly-ML-SDImetz.pdf) and [Older Version with Bayesian Machine Learning](http://sirien.metz.supelec.fr/depot/SIR/CoursML/Poly-ML-SIR.pdf)
- Information Theory, Inference, and Learning Algorithms by David J.C. MacKay - [Book (PDF File)](https://www.inference.org.uk/itprnn/book.pdf)

### Variational Inference: Courses

- MATH 5472. Computer-Age Statistical Inference and its applications - [Website](https://sites.google.com/site/eeyangc/teaching/math-5472-computer-age-statistical-inference-and-its-applications)
- [Meerkat Statistics Youtube Channel](https://www.youtube.com/@MeerkatStatistics/playlists)
- [Probabilistic Machine Learning](https://www.youtube.com/playlist?list=PLISXH-iEM4JlFsAp7trKCWyxeO3M70QyJ)

### Variational Inference: Papers and surveys

- Topics in approximate inference by Yingzhen Li - [Website](http://yingzhenli.net/home/en/?page_id=895) and [Paper](http://yingzhenli.net/home/pdf/topics_approx_infer.pdf)
- [Variational Inference: A Review for Statisticians by David M. Blei, Alp Kucukelbir, Jon D. McAuliffe](https://arxiv.org/abs/1601.00670)
- [Graphical Models, Exponential Families, and Variational Inference by Martin J. Wainwright and Michael I. Jordan](https://people.eecs.berkeley.edu/~wainwrig/Papers/WaiJor08_FTML.pdf)
- [Markov Chain Monte Carlo and Variational Inference: Bridging the Gap by Tim Salimans, Diederik P. Kingma, Max Welling](https://arxiv.org/abs/1410.6460)
- [Black Box Variational Inference Rajesh Ranganath, Sean Gerrish, David M. Blei](https://arxiv.org/abs/1401.0118), [a report](https://miguelbiron.github.io/docs/STAT548_report_1_BBVI.pdf) and [Lecture](https://www.youtube.com/watch?v=-H2N4tVDK7I)
- [Automatic Differentiation Variational Inference by Alp Kucukelbir, Dustin Tran, Rajesh Ranganath, Andrew Gelman, David M. Blei](https://arxiv.org/abs/1603.00788)
- [Auto-Encoding Variational Bayes Diederik P Kingma, Max Welling](https://arxiv.org/abs/1312.6114)
- [Advances in Variational Inference by Cheng Zhang, Judith Butepage, Hedvig Kjellstrom, Stephan Mandt](https://arxiv.org/abs/1711.05597)
- [Expectation Propagation for approximate Bayesian inference by Thomas P. Minka](https://arxiv.org/abs/1301.2294), [A roadmap to research on EP](https://tminka.github.io/papers/ep/roadmap.html) and [Lectures about Approximate Inference](http://videolectures.net/mlss09uk_minka_ai/)
- [Expectation Propagation as a Way of Life: A Framework for Bayesian Inference on Partitioned Data](https://arxiv.org/abs/1412.4869)
- [Amortized Variational Inference: Towards the Mathematical Foundation and Review](https://arxiv.org/abs/2209.10888)
- [Normalizing Flows for Probabilistic Modeling and Inference by George Papamakarios et al.](https://arxiv.org/pdf/1912.02762.pdf)
- [A practical tutorial on Variational Bayes by Minh-Ngoc Tran](https://arxiv.org/abs/2103.01327)
- [Reinforcement Learning and Control as Probabilistic Inference: Tutorial and Review](https://arxiv.org/abs/1805.00909)
- [A General Method for Amortizing Variational Filtering](https://arxiv.org/abs/1811.05090)
- [Iterative Amortized Inference](https://arxiv.org/abs/1807.09356)
- [A unifying tutorial on Approximate Message Passing](https://arxiv.org/pdf/2105.02180.pdf)

### Variational Inference: Tutorials

- NeurIPS 2020 tutorial on approximate inference by Yingzhen Li - [Advances in Approximate Inference Slides](http://yingzhenli.net/home/en/?page_id=1341), [3 hours lecture](https://slideslive.com/38943571/advances-in-approximate-inference)
- [CIRM Bayesian Statistics and Algorithms Week](https://conferences.cirm-math.fr/1619.html)
- Variational Bayes methods and algorithms by Christine KERIBIN - [Slides - Part 1](https://www.cirm-math.fr/ProgWeebly/Renc1619/Keribin1.pdf) and [Lecture](https://www.youtube.com/watch?v=kmz5ujbI9O4), [pt.2](https://www.cirm-math.fr/ProgWeebly/Renc1619/Keribin2.pdf)
- The Expectation-Propagation Algorithm: a tutorial by Simon Barthelmé - [Slides - Part 1](https://www.cirm-math.fr/ProgWeebly/Renc1619/Barthelme_EP1.pdf) and [Lecture](https://www.youtube.com/watch?v=0tomU1q3AdY), [pt.2](https://www.cirm-math.fr/ProgWeebly/Renc1619/Barthelme_EP2.pdf)
- [Tamara Broderick: Variational Bayes and Beyond: Bayesian Inference for Big Data (ICML 2018 tutorial)](https://tamarabroderick.com/tutorial_2018_icml.html)
- [Variational Inference: ELBO, Mean-Field Approximation, CAVI and Gaussian Mixture Models](https://brunomaga.github.io/Variational-Inference-GMM)
- [A Beginner's Guide to Variational Methods: Mean-Field Approximation](https://blog.evjang.com/2016/08/variational-bayes.html)
- [Expectation-maximization: theory and intuition](https://mbernste.github.io/posts/em/)
- [Introduction to Automatic Differentiation Variational Inference](https://luiarthur.github.io/statorial/varinf/introvi/)
- [Bayesian Linear Regression ADVI using PyTorch](https://luiarthur.github.io/statorial/varinf/linregpy/)
- [Theory of variational based inference](https://hiraksarkar.github.io/posts/2021/06/theory-of-vae/)
- [How to derive an EM algorithm from scratch](https://teng-gao.github.io/blog/2022/ems/)
- [High-Level Explanation of Variational Inference](https://www.cs.jhu.edu/~jason/tutorials/variational.html)
- [An Introduction to Control as Inference: Stuffing RL into a graphical model](https://dibyaghosh.com/blog/rl/controlasinference.html)
- [Variational Bayes and Beyond: Foundations of Scalable Bayesian Inference by Tamara broderick](https://tamarabroderick.com/tutorial_2020_smiles.html)
