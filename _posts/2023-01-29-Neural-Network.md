---
layout: post
title:  Pullquotes
categories: [HTML,Code]
excerpt: The history of Neural Networks is quite fascinating! #ArtificialIntelligence #DeepLearning #MachineLearning
---


The Seminal models: 
- 1894 Linear regression by Galton: https://galton.org/books/natural-inheritance/pdf/galton-nat-inh-1up-clean.pdf
- 1838 Logistic regression by Verhulst (https://books.google.com/books?id=8GsEAAAAYAAJ&printsec=frontcover#v=onepage&q&f=false) and 1920 by Pear (http://math.bu.edu/people/mak/MA565/Pearl_Reed_PNAS_1920.pdf)
- 1958 the Multi Layer Perceptron by Rosenblatt: https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.335.3398&rep=rep1&type=pdf

The optimization methods
- 1671 by Newton and then Ralphson in 1690 for the Newton-Ralphson method: https://archive.org/details/bub_gb_4nlbAAAAQAAJ/mode/2up
- 1805(?) Least Square Method by Legendre or Gauss(?): https://www.york.ac.uk/depts/maths/histstat/legendre.pdf, https://projecteuclid.org/journals/annals-of-statistics/volume-9/issue-3/Gauss-and-the-Invention-of-Least-Squares/10.1214/aos/1176345451.full
- 1847 Cauchy develops the Gradient descent algorithm: https://cs.uwaterloo.ca/~y328yu/classics/cauchy-en.pdf
- 1960 Kelley discovers the Backpropagation algorithm (Kelley: https://www.gwern.net/docs/statistics/decision/1960-kelley.pdf) but is popularized by Hinton in 1986 (https://www.iro.umontreal.ca/~vincentp/ift3395/lectures/backprop_old.pdf) 

The silver age: 
- 1989-1998 first Convolutional NN trained with Gradient descent by LeCun (LeNet-5): https://proceedings.neurips.cc/paper/1989/file/53c3bce66e43be4f209556518c2fcb54-Paper.pdf, http://vision.stanford.edu/cs598_spring07/papers/Lecun98.pdf
- 1997 The LSTM Network by Hochreiter: http://www.bioinf.jku.at/publications/older/2604.pdf
- 2006 Hinton creates "deep" learning with a deep architecture of Restricted Boltzmann machines: http://www.cs.toronto.edu/~hinton/absps/fastnc.pdf

The golden Age for computer vision:
- 2012 AlexNet by Krizhevsky (Hinton's student): https://proceedings.neurips.cc/paper/2012/file/c399862d3b9d6b76c8436e924a68c45b-Paper.pdf
- 2014 InceptionNet by Google: https://arxiv.org/pdf/1409.4842v1.pdf
- 2015 VGG16 by Simonyan: https://arxiv.org/pdf/1409.1556.pdf
- 2015 ResNet by Microsoft researchers: https://arxiv.org/pdf/1512.03385.pdf

The golden age for Natural Language Processing:
- 2017 Google researchers create the Attention Mechanism to replace LTSM: https://arxiv.org/abs/1706.03762
- 2018 Google researchers create BERT: https://arxiv.org/pdf/1810.04805.pdf
- 2020 OpenAI creates GPT-3: https://arxiv.org/pdf/2005.14165.pdf

The golden age (?) for Deep Reinforcement Learning:
- 2013-2015 RL algorithms reach human level performance on video games with Mnih at DeepMind: https://www.cs.toronto.edu/~vmnih/docs/dqn.pdf, https://web.stanford.edu/class/psych209/Readings/MnihEtAlHassibis15NatureControlDeepRL.pdf 

So much work in the field that it was impossible to fit everything! I am looking forward to seeing what comes next!

----
Subscribe to learn something new in Machine Learning every week: https://TheAiEdge.io/
#machinelearning #datascience #artificialintelligence


[What Makes a Dialog Agent Useful?](https://huggingface.co/blog/dialog-agents)
[How Digital Twins Enable Intelligent Cities](https://e.huawei.com/fr/eblog/industries/insights/2020/how-digital-twins-enable-intelligent-cities)
[Massive Language Models Can Be Accurately Pruned in One-Shot](https://arxiv.org/abs/2301.00774)
[Neural Image Compression with a Diffusion-Based Decoder](https://arxiv.org/abs/2301.05489)
[Data2vec 2.0: Highly efficient self-supervised learning for vision, speech and text](https://ai.facebook.com/blog/ai-self-supervised-learning-data2vec/?utm_source=linkedin&utm_medium=organic_social&utm_campaign=blog&utm_content=other_research)
[TRL - Transformer Reinforcement Learning](https://huggingface.co/docs/trl/index)
[Why we focus on AI and to what end](https://ai.google/our-focus/)

Your data can tell you a lot about the type of ML you could do, the type of hardware you should invest in and the people you should hire. Here is a simple guide:

Text Data (build chatbots for customer service, …):
- Lots of data: can make use of Deep Learning. A robust data engineering infrastructure around the data should be designed. Modeling requires highly specialized people in the domain. GPU machines should increase modeling speed
- Small amount of data: Should probably explore first pre-trained DL models. Engineering infrastructure is less important. Modeling could be performed by a less specialized workforce. GPU machines may not be necessary

Image Data (face recognition for security systems, augmented reality systems, ...):
- Lots of data: DL will probably generate performance beyond anything traditional techniques could produce. A robust data engineering infrastructure around the data should be designed. Modeling requires highly specialized people. GPU machines are a must.
- Small amounts of data: Pre-trained DL Models could yield satisfactory results but should possibly question investing in ML in general for Computer Vision applications. Engineering infrastructure around the data is less important. Modeling could be performed by a less specialized workforce. GPU machines remain important for improved modeling speed.

Time Series Data (sales forecast, stock price prediction, ...):
- Lots of data: Traditional methods like XGBoost will generally yield greater performance in time series data. A robust data engineering infrastructure around the data should be designed. Modeling could be performed by generalist data scientists. GPU (for Transformers or LSTM for example) and CPU machines could be leveraged.
- Small amounts of data: It is potentially not a problem to be solved with ML techniques. Engineering infrastructure around the data is less important. Modeling could be performed by a less specialized workforce. GPU machines are most likely unnecessary.

Tabular Data (product recommendation, customer churn prediction, ...):
- Lots of data: traditional ML techniques usually outperform Deep Learning. However, in the case of recommendation engines with very sparse variables, DL has proven to bring superior performance. A robust data engineering infrastructure around the data should be designed. Modeling could be performed by generalist data scientists. GPU may not be very useful as Deep Learning is less relevant in this case (apart from in the case of Rec Engines).
- Small amount of data: It is probably not a problem to be solved with ML. Should possibly reconsider investing in advanced analytics. A robust data engineering infrastructure around the data is less important. Modeling could be performed by a less specialized workforce. GPU machines are most likely unnecessary.
----
Subscribe to learn something new in Machine Learning every week: https://TheAiEdge.io/
#machinelearning #datascience #artificialintelligence


From Zero to AI Research Scientist Full Resources Guide

GitHub : https://github.com/ahmedbahaaeldin/From-0-to-Research-Scientist-resources-guide

#ArtificialIntelligence #DeepLearning #MachineLearning

