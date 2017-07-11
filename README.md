## Character-level Intra Attention Network
Implementation of the Character-level Intra Attention Network (CIAN) as a master thesis project in [Universitat Politècnica de Catalunya · BarcelonaTech](http://www.upc.edu/). 

Task description can be seen at [RepEval 2017](https://repeval2017.github.io/shared/). 

Architecture of the model: 
<p align="center"><img src="https://github.com/yanghanxy/CIAN/blob/master/figure/architecture.png" height="387" width="459"></p>

### How to run
Dataset should be be put in folder ./data

To run the model, use '''python ./model.py'''

The result and log file will be saved in ./log folder. 

### Requirements
Code is written in python 2.7 and requires [Keras 2](https://github.com/fchollet/keras).

### Data
Dataset could be downloaded at [MultiNLI](http://www.nyu.edu/projects/bowman/multinli/) and [SNLI](http://nlp.stanford.edu/projects/snli/). 

### Result
<p align="center"><img src="https://github.com/yanghanxy/CIAN/blob/master/figure/training.png" height="428" width="783"></p>

### Visualization of Attention
PairID 192997e, label Entailment
<p align="center"><img src="https://github.com/yanghanxy/CIAN/blob/master/figure/PairID_192997e.PNG" height="764" width="594"></p>

PairID 254941e, label Entailment
<p align="center"><img src="https://github.com/yanghanxy/CIAN/blob/master/figure/PairID_254941e.PNG" height="760" width="603"></p>

### Reference
[1] [Character-Aware Neural Language Models](https://github.com/jarfo/kchar)

[2] [Intra Attention Mechanism](https://gist.github.com/cbaziotis/7ef97ccf71cbc14366835198c09809d2)
