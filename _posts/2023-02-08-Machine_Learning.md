---
layout: post
title: Machine Learning
date: 2023-02-08 11:59:00-0400
description: The process of using algorithms and statistical models to enable computers to learn from data and make decisions without explicit programming.
tags: ["Learning Theory", "Statistical Learning", "Machine Learning", "Machine Learning Theory", "Mathematics of Machine Learning"]
categories: [""]
Machine_Learning: true
---

## Mathematics of Machine Learning

- EE 290: Mathematics of Data Science, University of California Berkeley, Jiantao Jiao, Fall 2019
- Introduction to Applied Linear Algebra – Vectors, Matrices, and Least Squares by Stephen Boyd and Lieven Vandenberghe - [Website](https://web.stanford.edu/~boyd/vmls/), [Book (PDF File)](https://web.stanford.edu/~boyd/vmls/vmls.pdf) and [Stanford Lectures](https://www.youtube.com/playlist?list=PLoROMvodv4rMz-WbFQtNUsUElIh2cPmN9)
- Interactive Linear Algebra - [Wwebsite](https://textbooks.math.gatech.edu/ila/) and [PDF Version](https://textbooks.math.gatech.edu/ila/ila.pdf)
- COS 302 / SML 305 / ECE 305: Mathematics for Numerical Computing and Machine Learning - [Website](https://www.cs.princeton.edu/courses/archive/fall22/cos302/) and [Lectures](https://www.youtube.com/playlist?list=PLCO4cUaBLHFEHo42HVIVWaSOvbAiH30uc)

## Learning Theory and Online Learning

Learning theory is a branch of machine learning that deals with the mathematical analysis of algorithms and their performance. It aims to understand the fundamental limits of what can be learned from data, and to identify the best algorithms for a given problem. It provides a set of mathematical tools to reason about generalization error, sample complexity, and the trade-offs between them. PAC (probably approximately correct) learning and the VC (Vapnik-Chervonenkis) dimension are concepts from learning theory that are used to analyze the sample complexity of machine learning algorithms. In PAC learning, the goal is to learn a concept or function from a finite set of examples, with a guarantee of a certain degree of accuracy and confidence. The VC dimension is a measure of the complexity of a concept class, which is the set of all possible hypotheses that the algorithm could consider. The smaller the VC dimension, the less data is required to learn the concept class.

Online learning and multi-armed bandits are both types of learning algorithms that are used in situations where data is generated sequentially, as opposed to being available all at once. In online learning, the algorithm makes predictions based on the data it has seen so far and updates its model as new data becomes available. Multi-armed bandits are a type of online learning where the algorithm must choose among a number of different actions (the "arms" of the bandit), with the goal of maximizing a reward signal. The algorithm learns from the feedback it receives after taking each action, and uses this information to guide its future choices. Online learning and multi-armed are used in many real-world applications, such as web search, recommendation systems, and real-time control systems.

In summary, Learning theory is the branch of Machine Learning that is concerned with the theoretical aspects and the mathematical foundation of learning. Whereas online learning is specific type of Machine Learning that deals with learning from streaming data. While Online learning is a subset of learning theory and it is more specific to the case where data comes in a stream.

### Learning Theory and Online Learning: Courses

- STATS 231C: Theories of Machine Learning - [Website](http://www.stat.ucla.edu/~arashamini/teaching/231c) and [Lectures](https://www.youtube.com/playlist?list=PLN_qg0-2-0SxKyZLv_FotPDED5ET_rQmo)
- Stanford STATS214 / CS229M: Machine Learning Theory - Fall 2021 - [Website](https://web.stanford.edu/class/stats214/) and [Lectures](https://www.youtube.com/playlist?list=PLoROMvodv4rP8nAmISxFINlGKSK4rbLKh)
- Learning Theory from First Principles by Francis Bach - [Website](https://www.di.ens.fr/~fbach/ltfp/) and [Notes (PDF File)](https://www.di.ens.fr/~fbach/ltfp_book.pdf).
- [Machine Learning by Jérémy Fix, Hervé Frezza-Buet, Matthieu Geist](https://frezza.pages.centralesupelec.fr/teachml2/Poly/Poly-ML-SDImetz.pdf) and [Older Version with Bayesian Machine Learning](http://sirien.metz.supelec.fr/depot/SIR/CoursML/Poly-ML-SIR.pdf)
- Mathematical Foundations of Machine Learning by Michael M. Wolf - [Notes (PDF File)](https://www-m5.ma.tum.de/foswiki/pub/M5/Allgemeines/MA4801_2021S/ML.pdf)
- Geometric Aspects of Statistical Learning Theory — A Preliminary Draft by Shahar Mendelson - [Book (PDF File)](https://www.esi.ac.at/uploads/11053b15-f227-4623-9f14-64a7b634f7b5.pdf)
- CMU 10716 Advanced Machine Learning: Theory and Methods Spring 2019 - [Website](http://www.cs.cmu.edu/~pradeepr/courses/716/2019-spring/)
- MIT 18.657 Mathematics of Machine Learning - [Website](https://ocw.mit.edu/courses/18-657-mathematics-of-machine-learning-fall-2015/pages/lecture-notes/)
- University of Notre Dame Advanced Topics in Machine Learning Spring 2021 - [Lecture notes and videos](https://www.zabaras.com/machine-learning)
- Reproducing Kernel Hilbert Spaces in Machine Learning:
  - Machine learning with kernel methods, Spring 2022 - [Website](https://mva-kernel-methods.github.io/course-2021-2022/schedule/)
  - Machine learning with kernel methods, Spring 2021 - [Website](https://members.cbio.mines-paristech.fr/~jvert/svn/kernelcourse/course/2021mva/index.html), [Lectures](https://www.youtube.com/playlist?list=PLD93kGj6_EdrkNj27AZMecbRlQ1SMkp_o)
  - Gaussian Processes and Kernel Methods (G8325) Fall 2015 by John P. Cunningham - [Course Syllabus](https://stat.columbia.edu/~cunningham/syllabi/STAT_G8325_2015fall_syllabus.pdf) and [Slides](https://stat.columbia.edu/~cunningham/teaching/G8325/)
  - UCL CS Advanced Topics in Machine Learning: Reproducing kernel Hilbert spaces in Machine Learning - [Slides and notes](http://www.gatsby.ucl.ac.uk/~gretton/coursefiles/rkhscourse.html). More short courses by ARTHUR GRETTON [Website](http://www.gatsby.ucl.ac.uk/~gretton/teaching.html)
  - From Basic Machine Learning models to Advanced Kernel Learning - [Website](https://kernel-learning.github.io/)
- University of Toronto CSC 2532 Winter 2022: Statistical Learning Theory - [Website](https://erdogdu.github.io/csc2532/)
- Princeton University COS 511: TML-2022 Theoretical Machine Learning by Elad Hazan - [Website](https://sites.google.com/view/cos-511-tml-2022/home?authuser=0)
- University of Maryland CMSC828U Algorithms in Machine Learning: Guarantees and Analyses - [Website](http://www.cs.umd.edu/class/fall2020/cmsc828u//schedule/)
- STAT928 Statistical Learning Theory and Sequential Prediction Spring 2014 - [Website](https://www.mit.edu/~rakhlin/courses/stat928/) and [Statistical Learning and Sequential Prediction (PDF File)](https://www.mit.edu/~rakhlin/courses/stat928/stat928_notes.pdf)
- 6.883: Online Methods in Machine Learning Theory and Applications - [Website](https://www.mit.edu/~rakhlin/6.883/)
- IDS.160/9.521/18.656: Mathematical Statistics: A Non-Asymptotic Approach by Sasha Rakhlin - [Lecture Notes](https://www.mit.edu/~rakhlin/courses/mathstat/rakhlin_mathstat_sp22.pdf)
- [Computational Learning Theory](https://www.cs.ox.ac.uk/people/varun.kanade/teaching/CLT-MT2022/lectures/)
- [CSC 665: Online Learning and Multi-armed Bandits - Spring 2020](https://kwangsungjun.github.io/teach/20.1.csc665/index.html)
- [18.409: Algorithmic Aspects of Machine Learning](http://people.csail.mit.edu/moitra/409.html) and [Lecture Notes](https://people.csail.mit.edu/moitra/docs/bookexv2.pdf)
- [CSE 599, Winter 2020 Interactive Learning](https://courses.cs.washington.edu/courses/cse599i/20wi/)
- [CSC 588: Machine Learning Theory - Spring 2022](https://kwangsungjun.github.io/teach/23.1.csc588/index.html)
- [ECE434/COS434: Machine Learning Theory](https://sites.google.com/view/cjin/ece434cos434?authuser=0)
- [AM207 - Stochastic Methods for Data Analysis, Inference and Optimization](https://onefishy.github.io/am207/)
- [CSS.314.1 Online Algorithms](https://www.youtube.com/playlist?list=PLTtM9ThZ2L-c638AjqTskivmXwVTzTYnl)
- [MIT 9.520/6.860: Statistical Learning Theory and Applications](https://www.mit.edu/~9.520/fall19/) and [Lectures](https://www.youtube.com/playlist?list=PLyGKBDfnk-iB4Xz_EAJNEgGF5I-6OzRNI)
- [Harvard CS 181: Machine Learning](https://harvard-ml-courses.github.io/cs181-web/), [repo](https://github.com/harvard-ml-courses/cs181-web) and [A Textbook](https://github.com/harvard-ml-courses/cs181-textbook)
  
### Learning Theory and Online Learning: Books

- Understanding Machine Learning: From Theory to Algorithms By Shai Shalev-Shwartz and Shai Ben-David - [Website](https://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/) and [book (PDF File)](https://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/understanding-machine-learning-theory-algorithms.pdf)
- Foundations of Machine Learning by Mehryar Mohri, Afshin Rostamizadeh, and Ameet Talwalkar - [Free book and Slides](https://cs.nyu.edu/~mohri/mlbook/)
- [Statistical Inference via Convex Optimization by Anatoli Juditsky and Arkadi Nemirovski](https://www2.isye.gatech.edu/~nemirovs/StatOptPUPWeb)
- Mathematics for Machine Learning - [Website](https://mml-book.github.io/) and [Free book and Slides](https://mml-book.github.io/book/mml-book.pdf)
- The Elements of Statistical Learning - [Website](https://hastie.su.domains/ElemStatLearn/) and [book](https://hastie.su.domains/Papers/ESLII.pdf)
- An Introduction to Statistical Learning - [Website](https://www.statlearning.com/) and [Book](https://hastie.su.domains/ISLR2/ISLRv2_website.pdf)
- Applied Predictive Modeling - [Website](http://appliedpredictivemodeling.com/toc)
- Introduction to Machine Learning Fourth Edition by Ethem Alpaydın - [3rd edition (PDF File)](https://dl.matlabyar.com/siavash/ML/Book/Ethem%20Alpaydin-Introduction%20to%20Machine%20Learning-The%20MIT%20Press%20(2014).pdf) and [some slides](https://www.cmpe.boun.edu.tr/~ethem/i2ml3e/)
- Mathematical Foundations of Data Sciences by Gabriel Peyré - [Website](https://mathematical-tours.github.io/book/) and [Book](https://mathematical-tours.github.io/book-sources/FundationsDataScience.pdf)
- Introduction to Machine Learning by Alex Smola and S.V.N. Vishwanathan - [Website](https://alex.smola.org/teaching/cmu2013-10-701/index.html) and [Book](https://alex.smola.org/drafts/thebook.pdf)
- Exercises in Machine Learning by Michael U. Gutmann - [File](https://arxiv.org/pdf/2206.13446.pdf)
- Artificial Intelligence: A Textbook by Charu C. Aggarwal
- Artificial Intelligence: A Modern Approach, 4th Edition by Stuart Russell and Peter Norvig
- Mathematics for Artificial Intelligence by Christophe Giraud - [Book (PDF File)](https://www.imo.universite-paris-saclay.fr/~christophe.giraud/Orsay/MIA.pdf)
- [Algorithmic Aspects of Machine Learning](https://www.cambridge.org/core/books/algorithmic-aspects-of-machine-learning/165FD1899783C6D7162235AE405685DB)
- [Introduction to Online Convex Optimization by Elad Hazan](https://sites.google.com/view/intro-oco/)
- Bandit Algorithms Tor Lattimore and Csaba Szepesvari - [Website](https://banditalgs.com/), [Book (PDF File)](https://tor-lattimore.com/downloads/book/book.pdf) and [Solutions to Selected Exercises](https://tor-lattimore.com/downloads/book/solutions.pdf)
- Bayesian models of perception and action - [Website](http://www.cns.nyu.edu/malab/bayesianbook.html) and [book (PDF File)](http://www.cns.nyu.edu/malab/static/files/Bayesian_models_of_perception_and_action_v3.pdf)
- PATTERNS, PREDICTIONS, AND ACTIONS A story about machine learning by Moritz Hardt and Benjamin Recht - [Website](https://mlstory.org/index.html) and [book (PDF File)](https://mlstory.org/pdf/patterns.pdf)

### Learning Theory and Online Learning: Papers and Surveys

- [Online Learning: A Comprehensive Survey](https://arxiv.org/abs/1802.02871)
- [Online Learning and Online Convex Optimization By Shai Shalev-Shwartz](https://www.cs.huji.ac.il/~shais/papers/OLsurvey.pdf)
- [Optimization for Machine Learning by Elad Hazan](https://arxiv.org/abs/1909.03550)
- [A Modern Introduction to Online Learning](https://arxiv.org/abs/1912.13213)
- [Introduction to Multi-Armed Bandits](https://arxiv.org/abs/1904.07272)
- [Regret Analysis of Stochastic and Nonstochastic Multi-armed Bandit Problems](https://arxiv.org/abs/1204.5721)

## Applied Machine Learning

- Courses by University of Tuebingen:
  - Introduction to Machine Learning by Dmitry Kobak, Winter Term 2020/21 - [Lectures](https://www.youtube.com/playlist?list=PL05umP7R6ij35ShKLDqccJSDntugY4FQT) and [Slides](https://dkobak.github.io)
  - Statistical Machine Learning by Ulrike von Luxburg, Summer Term 2020 - [Lectures](https://www.youtube.com/playlist?list=PL05umP7R6ij2XCvrRzLokX6EoHWaGA2cC) and [Slides](http://www.tml.cs.uni-tuebingen.de/teaching/2022_statistical_learning/)
  - Probabilistic Machine Learning by Philipp Hennig, Summer Term of 2020 - [Lectures](https://www.youtube.com/playlist?list=PL05umP7R6ij1tHaOFY96m5uX3J21a6yNd) and [Sldies](https://uni-tuebingen.de/en/fakultaeten/mathematisch-naturwissenschaftliche-fakultaet/fachbereiche/informatik/lehrstuehle/methoden-des-maschinellen-lernens/lehre/probabilistic-machine-learning/)
  - Numerics of Machine Learning by Philipp Hennig - [Lectures](https://www.youtube.com/playlist?list=PL05umP7R6ij2lwDdj7IkuHoP9vHlEcH0s) and [Slides](https://github.com/philipphennig/NumericsOfML)

  - Related Courses:
    - Essential Statistics by Philipp Berens, 2020/21 - [Lectures](https://www.youtube.com/playlist?list=PL05umP7R6ij0Gw5SLIrOA1dMYScCx4oXT)
    - Data Compression With Deep Probabilistic Models Course by Prof. Robert Bamler - [Website](https://robamler.github.io/teaching/compress21/) and [Lectures](https://www.youtube.com/playlist?list=PL05umP7R6ij0Mp1dW2HuXlb-UQIYnv8xK)
    - Math for Deep Learning (MaDL) A Short Guided Tour on Linear Algebra and Probability Theory by Prof. Andreas Geiger - [Lectures](https://www.youtube.com/playlist?list=PL05umP7R6ij0bo4UtMdzEJ6TiLOqj4ZCm) and [Slides](https://uni-tuebingen.de/de/241678)
    - Deep Learning by Andreas Geiger - [Lectures](https://www.youtube.com/playlist?list=PL05umP7R6ij3NTWIdtMbfvX7Z-4WEXRqD) and [Slides](https://uni-tuebingen.de/fakultaeten/mathematisch-naturwissenschaftliche-fakultaet/fachbereiche/informatik/lehrstuehle/autonomous-vision/lectures/deep-learning/)
    - Neural Data Science — Philipp Berens, 2021 - [Lectures](https://www.youtube.com/playlist?list=PL05umP7R6ij3SxudmSWFL_zGh0BMrRdrx) and [Notebooks](https://github.com/berenslab/neural_data_science)
    - Computer Vision by Prof. Andreas Geiger - [Lectures](https://www.youtube.com/playlist?list=PL05umP7R6ij35L2MHGzis8AEHz7mg381_) and [Course Website with Slides, Lecture Notes, Problems and Solutions](https://uni-tuebingen.de/fakultaeten/mathematisch-naturwissenschaftliche-fakultaet/fachbereiche/informatik/lehrstuehle/autonomous-vision/lectures/computer-vision/)
    - Self-Driving Cars by Prof. Andreas Geiger - [Lectures](https://www.youtube.com/playlist?list=PL05umP7R6ij321zzKXK6XCQXAaaYjQbzr) and [Course Website with Slides, Lecture Notes, Problems and Solutions](https://uni-tuebingen.de/fakultaeten/mathematisch-naturwissenschaftliche-fakultaet/fachbereiche/informatik/lehrstuehle/autonomous-vision/lectures/self-driving-cars/)

- Courses by UvA:
  - [Machine Learning 1](https://uvaml1.github.io/), [Lectures](https://www.youtube.com/playlist?list=PL8FnQMH2k7jzhtVYbKmvrMyXDYMmgjj_n) and [Lecture Notes](https://staff.fnwi.uva.nl/r.vandenboomgaard/MachineLearning/index.html)
  - [Machine Learning 2](https://datanose.nl/Course/Manual/77340/Machine%20Learning%202/2019) and [Lecture Notes](https://staff.fnwi.uva.nl/j.m.mooij/edu/ML2/ML2_lecture_notes.pdf)
  - [MACHINE LEARNING](https://mlvu.github.io/) and [Lectures](https://www.youtube.com/@riskone1/playlists)
  - [Machine Learning Theory](https://homepages.cwi.nl/~wmkoolen/MLT_2022/)

  - Related Courses:
    - [UvA Deep Learning I Course](https://uvadlc.github.io/) and [2020 Lectures](https://www.youtube.com/playlist?list=PLdlPlO1QhMiDlES3Vck6oQwO3TMYbdZDk)
    - [UvA Deep Learning II Course](https://uvadl2c.github.io/) and [Lectures](https://www.youtube.com/@deeplearningii8059/playlists)
    - [Tutorials for Both Courses](https://uvadlc-notebooks.readthedocs.io/en/latest/) and [Tutorials Lectures](https://www.youtube.com/playlist?list=PLdlPlO1QhMiAkedeu0aJixfkknLRxk1nA) and [Prracticals](https://github.com/uvadlc)
    - [Group Equivariant Deep Learning](https://uvagedl.github.io/) and [Lectures](https://www.youtube.com/playlist?list=PL8FnQMH2k7jzPrxqdYufoiYVHim8PyZWd)
    - [Lightning Tutorials](https://devblog.pytorchlightning.ai/lightning-tutorials-in-collaboration-with-the-university-of-amsterdam-uva-2499eaa0caad)

- Courses by Stanford University:
  - CS221: Artificial Intelligence: Principles and Techniques - [Website](https://stanford-cs221.github.io/autumn2022/), [Autumn 2019 Lectures](https://www.youtube.com/playlist?list=PLoROMvodv4rO1NB9TD4iUZ3qghGEGtqNX)/[Autumn 2021 Lectures](https://www.youtube.com/playlist?list=PLoROMvodv4rOca_Ovz1DvdtWuz8BfSWL2) and [Cheatsheets](https://stanford.edu/~shervine/teaching/cs-221/)
  - EE104: Introduction to Machine Learning - [Website](https://ee104.stanford.edu/) and [Lectures](https://www.youtube.com/playlist?list=PLoROMvodv4rN_Uy7_wmS051_q1d6akXmK)
  - CS229: Machine Learning - [Website](https://cs229.stanford.edu/), [Summer 2019 Lectures](https://www.youtube.com/playlist?list=PL4YhK0pT0ZhVf4nIsEjcRT5K47K7WH76P)/[Autumn 2018 Lectures](https://www.youtube.com/playlist?list=PLRQmQC3wIq9wl4WtUEA1PJoqw14ouro9m) and [Cheatsheets](https://stanford.edu/~shervine/teaching/cs-229/)
  - STATS214 / CS229M: Machine Learning Theory - [Website](https://web.stanford.edu/class/stats214/) and [Lectures](https://www.youtube.com/playlist?list=PLoROMvodv4rP8nAmISxFINlGKSK4rbLKh)
  - CS 329S: Machine Learning Systems Design - [Website](https://stanford-cs329s.github.io/syllabus.html) and [Stanford MLSys Seminar](https://www.youtube.com/watch?v=OEiNnfdxBRE&list=PLSrTvUm384I9PV10koj_cqit9OfbJXEkq)
  - CS224W: Machine Learning with Graphs - [Website](http://web.stanford.edu/class/cs224w/), [Lectures](https://www.youtube.com/playlist?list=PLoROMvodv4rPLKxIpqhjhPgdQy7imNkDn) and [Tutorials](https://medium.com/stanford-cs224w)
  - CS 329P: Practical Machine Learning - [Website](https://c.d2l.ai/stanford-cs329p/) and [Lectures](https://www.youtube.com/playlist?list=PLuQUxYHEVjGmekUNx8OySHpD9-x5GJt0N)
  - Related Courses:
    - CS 230: Deep Learning - [Website](https://cs230.stanford.edu/), [Lectures](https://cs230.stanford.edu/lecture/) and [Cheatsheets](https://stanford.edu/~shervine/teaching/cs-230/)
    - CS231n: Deep Learning for Computer Vision - [Website](http://cs231n.stanford.edu/) and [2017 Lectures](https://www.youtube.com/playlist?list=PL3FW7Lu3i5JvHM8ljYj-zLfQRF3EO8sYv)
    - CS234: Reinforcement Learning | Winter 2019 - [Lectures](https://www.youtube.com/playlist?list=PLoROMvodv4rOSOPzutgyCTapiGlY2Nd8u)
    - CS 330: Deep Multi-Task and Meta Learning:
      - [Fall 2019](http://cs330.stanford.edu/fall2019/index.html) and [Lectures](https://www.youtube.com/playlist?list=PLoROMvodv4rMC6zfYmnD7UG3LVvwaITY5)
      - [Autumn/Fall 2020](http://cs330.stanford.edu/fall2020/index.html) and [Lectures](https://www.youtube.com/playlist?list=PLoROMvodv4rOxuwpC_raecBCd5Jf54lEa)
      - [Autumn/Fall 2021](http://cs330.stanford.edu/fall2021/index.html) and [Lectures](https://www.youtube.com/playlist?list=PLoROMvodv4rMIJ-TvblAIkw28Wxi27B36)
      - [Fall 2022: No material on reinforcement learning and meta-reinforcement learning](https://cs330.stanford.edu/)
    - CS224U: Natural Language Understanding - [Website](http://web.stanford.edu/class/cs224u/) and [Lectures](https://www.youtube.com/playlist?list=PLoROMvodv4rPt5D0zs3YhbWSZA8Q_DyiJ)
    - CS224N: Natural Language Processing with Deep Learrning - [Website](http://web.stanford.edu/class/cs224n/) and [Spring 2021 Lectures](https://www.youtube.com/playlist?list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z)
    - CS25: Transformers United - [2023](https://web.stanford.edu/class/cs25/) - [2021](https://web.stanford.edu/class/cs25/prev_years/2021_fall/) and [Lectures](https://www.youtube.com/playlist?list=PLoROMvodv4rNiJRchCzutFw5ItR_Z27CM)
    - CS324 - Large Language Models - [Website](https://stanford-cs324.github.io/winter2022/)

- Courses by University of Toronto:
  - [STA 314 Fall 2021: Statistical Methods for Machine Learning I](https://www.cs.toronto.edu/~cmaddis/courses/sta314_f21/)
  - [CSC 2515 Fall 2021: Introduction to Machine Learning](https://amfarahmand.github.io/IntroML-Fall2021/) and [Lectures](https://www.youtube.com/playlist?list=PLCveiXxL2xNZRg7PVp-JM4teSmaBETksy) - [Winter 2021](https://subercui.github.io/csc2515/index.html) - [Fall 2020](https://www.cs.toronto.edu/~rgrosse/courses/csc311_f20/)
  - [CSC 2532 Winter 2022: Statistical Learning Theory](https://erdogdu.github.io/csc2532/)
  - [CSC412 Winter 2022: Probabilsitic Machine Learning](https://erdogdu.github.io/csc412/) - [Winter 2020](https://probmlcourse.github.io/csc412/)
  - [STA414 Winter 2023: Statistical Methods for Machine Learning II](https://erdogdu.github.io/sta414/) - [Winter 2022:](https://duvenaud.github.io/sta414/) - [Winter 2020I](https://probmlcourse.github.io/sta414/)
  - [JSC370 and JSC470: Data Science II and III](https://jsc370.github.io/)
  - Current Topics in Machine Learning Methods in 3D and Geometric Deep Learning - [Website](https://www.pair.toronto.edu/csc2547-w21/) and [Lectures](https://www.youtube.com/playlist?list=PLki3HkfgNEsLrbI_r2iqNogmL5DW6HJXF)

- Courses by University of Berkeley:
  - CS 189/289A Introduction to Machine Learning by Jonathan Shewchuk Spring 2022 - [Website](https://people.eecs.berkeley.edu/~jrs/189/)
  - CS 189/289A Introduction to Machine Learning Fall 2022 - [Website](https://www.eecs189.org/)
  - EE290-2 Hardware for Machine Learning - [Website](https://inst.eecs.berkeley.edu/~ee290-2/sp21/)
  - CS 182/282A | Deep Neural Networks - [Fall 2022](https://inst.eecs.berkeley.edu/~cs182/fa22/) - [Spring 2021](https://cs182sp21.github.io/) and [Lectures](https://www.youtube.com/playlist?list=PLki3HkfgNEsK1PNSxxPi1YuUKi2cvz5S5)
  - CS 285: Deep Reinforcement Learning Fall - [Website](https://rail.eecs.berkeley.edu/deeprlcourse/) and [Lectures](https://www.youtube.com/playlist?list=PL_iWQOsE6TfX7MaC6C3HcdOf1g337dlC9)

- Courses by UW-Madison
  - CS540: Introduction to Artificial Intelligence - [Fall 2022](https://pages.cs.wisc.edu/~kandasamy/courses/22fall-cs540/index.html), [Spring 2022](https://pages.cs.wisc.edu/~sharonli/courses/cs540_spring2022/index.html)
  - CS750: Machine Learning - [Fall 2022](http://www.iliasdiakonikolas.org/teaching/Fall22/index.html), [Spring 2022](https://danielpimentel.github.io/teaching.html)
  - CS 839 Advanced Machine Learning Systems, Spring 2022 - [Website](https://pages.cs.wisc.edu/~shivaram/cs839-sp22/)

- Courses by University of California:
  - CS161 Winter 2022 Fundamentals of Artificial Intelligence - [website](https://uclaml.github.io/CS161-Winter2022/)
  - CS260 Fall 2021 Machine Learning Algorithms - [Website](https://uclaml.github.io/CS260-Fall2022/)

- Courses by University of Notre Dame:
  - Statistical Computing for Scientists and Engineers - [Website](https://www.zabaras.com/statistical-computing) and [Lectures](https://www.youtube.com/playlist?list=PLZBswPA7UFR8pUkCNPgoaT0diXyX6b_e9)
  - Advanced Topics in Machine Learning - [Website](https://www.zabaras.com/machine-learning) and [Lectures](https://www.youtube.com/playlist?list=PLd-PuDzW85AeKg3S0UDWevofQqrBLCLnz)
  - Probabilistic Graphical Models - [Website](https://www.zabaras.com/probabilistic-graphical-models) and [Lectures](https://www.youtube.com/playlist?list=PLd-PuDzW85AcV4bgdu7wHPL37hm60W4RM)
  
- Courses by University of Pennsylvania:
  - CIS 419/519 : Applied Machine Learning - [Website](https://www.seas.upenn.edu/~cis5190/fall2020/index.html) and [Lectures](https://www.youtube.com/playlist?list=PLQcasX5-oG91lbjiHzQAxEQgsDOCjgZEs)
  - CIS 620 - Learning in Few-Labels Settings - [Website](https://www.seas.upenn.edu/~cis6200/)  
  - CIS 700 - Reasoning for Natural Language Understanding - [Website](https://www.seas.upenn.edu/~cis7000a/Spring20/)

- Courses by University of Washington:
  - CSE416: Introduction to Machine Learning - [Summer 2022](https://courses.cs.washington.edu/courses/cse416/22su/) - [Spring 2022](https://courses.cs.washington.edu/courses/cse416/22sp/) - [Spring 2019](https://courses.cs.washington.edu/courses/cse416/19sp/)
  - CSE446: Machine Learning - [Winter 2022](https://courses.cs.washington.edu/courses/cse446/22wi/) and [Previous Versions](http://courses.cs.washington.edu/courses/cse446/)
  - EE511 - Advanced Introduction to Machine Learning - Spring Quarter, 2020 - Spring Quarter, 2020 - [Website](https://people.ece.uw.edu/bilmes/classes/ee511/ee511_spring_2020/)
  - EE563 - Submodular Functions, Optimization, and Applications to Machine Learning, Fall Quarter, 2020 - [Website](https://people.ece.uw.edu/bilmes/classes/ee563/ee563_fall_2020/)

- Courses by Caltech:
  - CS/CNS/EE 155 Machine Learning & Data Mining Winter 2022 - [Website](https://sites.google.com/view/cs155caltech2022/home?authuser=0)
  - [Advanced Topics in Machine Learning](http://www.yisongyue.com/teaching.php)
    - Spring 2022: Representation Learning for Science
    - Spring 2021: Predictive Control & Neural Network Theory
    - Spring 2020: Data-Driven Algorithm Design
    - Spring 2019: Deep Probabilistic Models
    - Spring 2018: Imitation Learning and Reinforcement Learning
    - Spring 2017: Machine Learning for Structured Prediction
    - Spring 2016: Online Learning, Interactive Machine Learning, and Learning from Human Feedback

- NYU CENTER FOR DATA SCIENCE:
  - [Mathematical Tools for Data Science](https://cds.nyu.edu/math-tools/)
  - [MACHINE LEARNING](https://nyu-ds1003.github.io/spring2022/#home)
  - Yann LeCun’s Deep Learning Course - [Website](https://cds.nyu.edu/deep-learning/), [Material](https://atcold.github.io/NYU-DLSP21/) and [Lecturres](https://www.youtube.com/playlist?list=PLLHTzKZzVU9e6xUfG10TkTWApKSZCzuBI)

- Other Courses:
  - INF8245E - Machine Learning - [WWebsite](https://chandar-lab.github.io/INF8245E/) and [Lectures](https://www.youtube.com/playlist?list=PLImtCgowF_ETupFCGQqmvS_2nqErZbifm)
  - Statistical methods for machine learning by Nicolò Cesa-Bianchi - [Website](https://cesa-bianchi.di.unimi.it/MSA/)
  - Advanced Machine Learning by Emilie CHOUZENOUX, Frédéric PASCAL - [Website](http://www-syscom.univ-mlv.fr/~chouzeno/ECPml/index.htm)
  - Machine Learning by Nando de Freitas - [Website](https://www.cs.ox.ac.uk/people/nando.defreitas/machinelearning/) and [Lectures](https://www.youtube.com/playlist?list=PLE6Wd9FR--EfW8dtjAuPoTuPcqmOV53Fu)
  - UCLA Machine Learning for Beginners - [Website](http://www.stat.ucla.edu/~ywu/teaching.html)
  - 36-708 Statistical Methods for Machine Learning by Larry Wasserman - [Website](https://www.stat.cmu.edu/~larry/=sml/)
  - [Machine Learning UVa CS 6316 (Spring 2022)](http://yangfengji.net/uva-ml-course/) and [Undergraduate Version](https://qiyanjun.github.io/2022sp-UVA-CS-MachineLearningDeep/)
  - CS8850: Advanced Machine Learning - [Website](https://splis.gsucreate.org/classes/advancedml/) and [Lectures](https://www.youtube.com/playlist?list=PLzERW_Obpmv_cdvD5kHnH7R_Rpdr7NyUx)
  - Intuition for the Algorithms of Machine Learning by Cynthia Rudin - [Website](https://users.cs.duke.edu/~cynthia/teaching.html) and [Lectures](https://www.youtube.com/playlist?list=PLNeXFnYrCJneoY_rKtWJy833YiMrCRi5f)
  - Cornell Tech CS 5787 Applied Machine Learning - [Course Materials](https://github.com/kuleshov/cornell-cs5785-2020-applied-ml) and [Lectures](https://www.youtube.com/playlist?list=PL2UML_KCiC0UlY7iCQDSiGDMovaupqc83)
  - CS 7641: Machine Learning Course - [Website](https://omscs.gatech.edu/cs-7641-machine-learning-course-videos)
  - Mathematical Foundations of Machine Learning - [Course Materials and Lectures](https://willett.psd.uchicago.edu/teaching/mathematical-foundations-of-machine-learning-fall-2021/)
  - MATH 4432 Statistical Machine Learning - [Website](https://sites.google.com/site/eeyangc/teaching/math-4432-statistical-machine-learning) and [Tutorials](https://github.com/statwangz/MATH-4432-Statistical-Machine-Learning)
  - Marc Toussaint AI-lectures - [Website](https://www.user.tu-berlin.de/mtoussai/teaching/) and [repo](https://github.com/MarcToussaint/AI-lectures)
  - [CSC 580: Principles of Machine Learning (Fall 2022)](https://zcc1307.github.io/courses/csc580fa22/index.html)
  - [Machine Learning - A First Course for Engineers and Scientists](http://smlbook.org/)
  - [Statistical Machine Learning 1RT700 11808 HT2022](https://uppsala.instructure.com/courses/65587)
  - [COMP 451: Fundamentals of Machine Learning](https://www.siamak.page/courses/COMP451F22/index.html) and [Practicals](https://github.com/mravanba/comp451)
  - [COMP 551: Applied Machine Learning - Winter 2023](http://www.reirab.com/Teaching/AML23/index.html) and [Practicals](https://github.com/mravanba/comp551-notebooks)

## Bayesian Machine Learning (A.k.a Probabilstic)

### Bayesian Machine Learning: Courses

- Bayesian machine learning Roadmap by Roger Grosse - [Website](https://metacademy.org/roadmaps/rgrosse/bayesian_machine_learning)
- CSE 515T: Bayesian Methods in Machine Learning – Fall 2019 by Roman Garnett - [Website](https://www.cse.wustl.edu/~garnett/cse515t/fall_2019/) and [Bayesian Optimization Book](https://bayesoptbook.com/)
- Bayesian methods for machine learning course at CentraleSupélec - [Github repo](https://github.com/sleglaive/BayesianML)
- Bayeisan Machine Learning textbook - [Github repo](https://github.com/wbasener/BayesianML) and [Textbook](https://github.com/wbasener/BayesianML/blob/main/BasenerBrownBML_1_31_2022.pdf)
- Lecture Notes by Frezza-Buet Herve - [Website](http://sirien.metz.supelec.fr/spip.php?article91)
- Bayesian machine learning at ENS Paris-Saclay and Univ Lille - [Course Material](https://github.com/rbardenet/bml-course/)
- Bayesian Machine Learning and Information Processing (5SSD0) - [Website](https://biaslab.github.io/teaching/bmlip/) and [Lectures](https://www.youtube.com/@biaslab730/playlists)
- Managing Uncertainty by Frederic Pennerath - [Website](http://www.metz.supelec.fr/metz/personnel/pennerath/Cours/ManagingUncertainty/)
- University of Cambridge LE49 Probabilistic Machine Learning by Damon Wischik - [Website](https://www.cl.cam.ac.uk/teaching/2122/LE49/materials.html) and [Lectures](https://www.youtube.com/playlist?list=PLknxdt7zG11O5BV8ipHD30dnupEk-tKjn)
- University of Cambridge 4f13 Probabilistic Machine Learning - [Website](http://mlg.eng.cam.ac.uk/teaching/4f13/2223/) and [a more structured version](http://mlg.eng.cam.ac.uk/teaching/4f13/2223/chunks.html)
- MATH 5472 Computer-Age Statistical Inference and its applications - [Website](https://sites.google.com/site/eeyangc/teaching/math-5472-computer-age-statistical-inference-and-its-applications)
- [Meerkat Statistics Youtube Channel](https://www.youtube.com/@MeerkatStatistics/playlists)
- [Probabilistic Machine Learning](https://www.youtube.com/playlist?list=PLISXH-iEM4JlFsAp7trKCWyxeO3M70QyJ)

### Bayesian Machine Learning: Books

- Kevin P. Murphy Books [Website](https://probml.github.io/pml-book/):
  - Machine Learning A Probabilistic Perspective, 2012 - [Book (PDF File)](http://noiselab.ucsd.edu/ECE228/Murphy_Machine_Learning.pdf)
  - Probabilistic Machine Learning - An Introduction, 2022 - [https://probml.github.io/pml-book/book1.html](https://probml.github.io/pml-book/book1.html) and [Draft (PDF File)](https://github.com/probml/pml-book/releases/latest/download/book1.pdf)
  - Probabilistic Machine Learning - Advanced Topics, 2023 - [Website](https://probml.github.io/pml-book/book2.html) and [Final Draft](https://github.com/probml/pml2-book/releases/latest/download/book2.pdf)
- Pattern Recognition and Machine Learning by Christopher Bishop - [Book (PDF File)](https://www.microsoft.com/en-us/research/uploads/prod/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf)
- [Machine Learning by Jérémy Fix, Hervé Frezza-Buet, Matthieu Geist](https://frezza.pages.centralesupelec.fr/teachml2/Poly/Poly-ML-SDImetz.pdf) and [Older Version with Bayesian Machine Learning](http://sirien.metz.supelec.fr/depot/SIR/CoursML/Poly-ML-SIR.pdf)
- [Bayesian models of perception and action](http://www.cns.nyu.edu/malab/bayesianbook.html)
- Bayesian Reasoning and Machine Learning by David Barber - [Website](http://web4.cs.ucl.ac.uk/staff/D.Barber/pmwiki/pmwiki.php?n=Brml.HomePage) and [Book (PDF File)](http://web4.cs.ucl.ac.uk/staff/D.Barber/textbook/200620.pdf)
- Gaussian Processes for Machine Learning by Carl Edward Rasmussen and Christopher K. I. Williams - [Website](https://gaussianprocess.org/gpml/) and [Book (PDF File)](https://gaussianprocess.org/gpml/chapters/RW.pdf)

### Bayesian Machine Learning: Papers

- [The Bayesian Learning Rule by Mohammad Emtiyaz Khan, Håvard Rue](https://arxiv.org/abs/2107.04562)

### Bayesian Machine Learning: Related Topics

- [Probabilistic Graphical Models](https://yabdellah.github.io/blog/probabilistic_graphical_models/)
- [Bayesian Statistics and Monte Carlo Methods](https://yabdellah.github.io/blog/bayesian_statistics_and_monte-carlo_methods/)

## MultiModal Machine Learning

- CMU 11-777 MultiModal Machine Learning - [Website](https://cmu-multicomp-lab.github.io/mmml-course/fall2022/) and [Fall 2020 Lectures](https://www.youtube.com/playlist?list=PL-Fhd_vrvisNup9YQs_TdLW7DQz-lda0G)
- CMU 11-877 Advanced Topics in MultiModal Machine Learning - [Website](https://cmu-multicomp-lab.github.io/adv-mmml-course/spring2022/)
- Tutorial on Multimodal Machine Learning - [CVPR 2022](https://cmu-multicomp-lab.github.io/mmml-tutorial/cvpr2022/), [NAACL 2022](https://cmu-multicomp-lab.github.io/mmml-tutorial/naacl2022/)
- [Reading List for Topics in Multimodal Machine Learning](https://github.com/pliang279/awesome-multimodal-ml)
- [Foundations and Recent Trends in Multimodal Machine Learning: Principles, Challenges, and Open Questions](https://arxiv.org/abs/2209.03430)

## Machine Learning for Tabular Data

- [TABULAR DATA: DEEP LEARNING IS NOT ALL YOU NEED](https://arxiv.org/abs/2106.03253)
- [Deep Neural Networks and Tabular Data: A Survey](https://arxiv.org/abs/2110.01889)
- [A Short Chronology Of Deep Learning For Tabular Data](https://sebastianraschka.com/blog/2022/deep-learning-for-tabular-data.html)
- [XGBoost: Scalable and Flexible Gradient Boosting](https://xgboost.ai/)
- [NVTabular](https://github.com/NVIDIA-Merlin/NVTabular)
- [LightGBM: Light Gradient Boosting Machine](https://github.com/microsoft/LightGBM)
- [scikit-learn](https://scikit-learn.org/stable/)
- Bojan Tunguz:
  - [Tabular Benchmarks](https://github.com/tunguz/TabularBenchmarks)
  - [ML/AI/DS resources](https://github.com/tunguz/ML_Resources)
  - [Twitter Account](https://twitter.com/tunguz)

## Blog Posts

- [On the Bias-Variance Tradeoff: Textbooks Need an Update](https://www.bradyneal.com/bias-variance-tradeoff-textbooks-update)
