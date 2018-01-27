## Structure of IRR

### Abstract

### Table of Contents

### 1. Introduction

* Identification of topic.
* Current problems and hypothesises.
* What is machine learning?
* Structure of the remainder of the paper.

### 2. Background

How does Image Classification fit into the domains of artificial intelligence and machine learning? This could potentially go into the introduction.

#### 2.1. Classification

#### 2.1. OR.. Image Classification

Take inspiration from ML book.

#### 2.2. The History of Image Classification

Identifying a single point of time in history as the birth of artificial intelligence (AI) is difficult because most definitions of AI include the notion of a digital computer [insert reference here]. However, the notion of an intelligent agent dates to the ancient Greeks with the writings of Homer in the Iliad [insert reference here]. Furthermore, ideas surrounding the creation of automata are well established within the literature and predate the 1700s [insert reference here].

Other interesting points that can be added as footnotes:

1. Wittgenstein's Duck. Mentioned by Voltaire and Goethe.
2. Turing and his intelligence test, shifts to a more philosophical question: why does it matter.. Reference Turing and/or Lucadio Floridi.

It is claimed that learning is one requirement that an agent must be able to perform in order to be deemed as intelligent. [Reference: P. Norvig  AI] It follows that in order for a machine to be intelligent, it must be capable of learning, hence the term machine learning.

During the early days of modern, digital artificial intelligence a war was being waged between two rivalry approaches to solving the problem of artificial intelligence:

1. The symbolic manipulation approach (symbolic AI)
2. The connectionist approach (inspired by the brain)

It turns out that the two approaches work very well for solving different sorts of artificial intelligence problems.


#### Previously Written by me:

Whilst we’re on the subject of history, it may also be worth considering the situation regarding academic funding for connectionist approaches to solving artificial intelligence problems, as apposed to the ‘good old fashioned artificial intelligence’ (GOFAI) approach.

Here is a direct extract from the notes belonging to a lecture series (available via Audible) titled ‘Philosophy of Mind: Brains, Consciousness, and Thinking Machines’:

“In 1962, Frank Rosenblatt developed the perceptron, a feed-forward neural network consisting of two connected layers: inputs and outputs. For any pattern a perceptron could instantiate, Rosenblatt’s learning rule could train it to that pattern. Marvin Minsky and Seymour Papert attacked neural nets, showing that perceptrons could not instantiate certain patterns, such as exclusive or. Minsky and Papert convinced the field that Connectionism could not succeed. Grants for research on neural nets dried up.

Neural nets were reborn in the mid-1980s through the work of David Rumelhart, Jay McClelland, and the Parallel Distributed Processing Research Group. A new learning rule, backpropagation of errors, allowed the training of multilayer nets. Neural nets are good at pattern recognition, the kind of task that stumped GOFAI. Garrison Cottrell’s face-recognition net offers a good example.”

Interestingly, Minksy and Papert recognised and described this situation as a kind of fairy tale, describing the two approaches as: ‘two sisters’. “One sister was natural, with features inherited from the study of the brain” (connectionism), “The other was artificial, related from the beginning to the use of computers” (GOFAI). They declared themselves as “two staunch followers of the artificial sister” and described their attack on connectionism as “the bloody work”.

You can read more about this in: ‘Artificial Intelligence and Education: Principles and case studies’, by Robert W. Lawler, Masoud Yazdani.

To conclude, in my humble opinion, you could1 characterise backpropagation as revolutionary because it allowed for increased confidence in connectionism (perhaps, even a revival of the connectionist approach) and with it an influx of academic funding2, eventually leading to the kinds of technology and scientific theory that we have today.


##### Footnotes:

It may not be completely unreasonable to characterise backpropagation as revolutionary, but what is genuinely revolutionary are the kinds of technologies that have resulted from a combination of things: increased availability of data, storage capacity, compute power and so forth - only one of those things is the discovery and application of the backpropagation algorithm.
Although this was only temporary, funding was cut again during the 90's. But since then we have seen other impactful breakthroughs in artificial intelligence, for example: Hinton et al. AlexNet (2012) - I am sure there are many others, but this is the first one that came to mind - and so the funding has returned.

##### ^ I believe the above can be adapted to include the McCullon & Pitts implementation of a neuron. Then change the kind of 'flow' of the text to lead into Neural Networks such as ImageNet challange 2012 / AlexNet whatever it's called. That would bring us nicely into modern approaches... BUT, we do need to associate neural networks with image recognition

#### 2.3. Modern Approaches

### 3. Neural Network Architectures

#### 3.1. Multilayered Perceptron (MLP)

#### 3.1.1. Deep Networks

Networks with multiple layers. There's some literature somewhere (I think it's ImageNet 2012 hinton) that basically says that more layers are better.

#### 3.2. Training

* Backpropagation
* Backpropagation with Momentum
* Hybrid Methods (genetic algorithms)
* Dropout

#### 3.3. Types of Layers

* Fully Connected
* Convolutional
* Recurrent
* LSTM (?) Do we really need to go this deep?

### 4. Data

#### 4.1. Collection and labelling

* Done mainly via humans.. Need to read into this.

#### 4.2. Representation of pre-processing

* Normalisation (Zero Mean, and unit variance)
* Batch Normalisation
* Clustering Pre-processing

### 5. Evaluation Metrics (Image / Object recognition)

#### 5.1. Error Metrics

#### 5.2. Accuracy

Example: CIFAR top-5 and CIFAR top-1, etc.

#### 5.3. Other measures

Examples such as co-variance matrix.. I think? Look this up in literature.

### 6. Conclusion

Summary goes here

#### 6.1. Conclusions Reached (need to sub this out for some other heading)

#### 6.2. Future Work

### 7. References