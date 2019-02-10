# Awesome NILM (Non-Intrusive Load Monitoring)[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

![image](https://user-images.githubusercontent.com/28736511/51742581-80aa0c80-20dd-11e9-8ed9-b591a79442a3.png)

A curated list of NILM (also known as Energy Disaggregation) resources. Inspired by [awesome-deep-vision](https://github.com/kjw0612/awesome-deep-vision), [awesome-public-datasets](https://github.com/awesomedata/awesome-public-datasets), [awesome-adversarial-machine-learning](https://github.com/yenchenlin/awesome-adversarial-machine-learning), [awesome-deep-learning-papers](https://github.com/terryum/awesome-deep-learning-papers), [awesome-meta-learning](https://github.com/dragen1860/awesome-meta-learning/) and [awesome-architecture-search](https://github.com/markdtw/awesome-architecture-search).

Curation of papers is generally based on the recent publication in top AI confenrences (NIPS, ICML, ICLR, AAAI, KDD, etc.) or the impactfulness on NILM domain. But the criteria is not strict. Please feel free to [pull requests](https://github.com/ch-shin/awesome-nilm/pulls) or [open an issue](https://github.com/ch-shin/awesome-nilm/issues) if you know awesome NILM resources.


## Papers
### Original paper
- **Nonintrusive appliance load monitoring** (1992), G.W. Hart [[link]](https://ieeexplore.ieee.org/document/192069)

### HMM
- **Unsupervised Disaggregation of Low Frequency Power Measurements** [[pdf]](http://hanj.cs.illinois.edu/pdf/sdm11_hkim.pdf)
  - Hyungsul Kim, Manish Marwah, Martin Arlitt, Geoff Lyon, Jiawei Han. *SDM'11*
- **Approximate inference in additive factorial hmms with application to energy disaggregation** [[pdf]](http://proceedings.mlr.press/v22/zico12/zico12.pdf)
  - Zico Kolter, Tommi Jaakkola. *AISTATS'12*
- **Non-intrusive load monitoring using prior models of general appliance types** [[pdf]](https://www.aaai.org/ocs/index.php/AAAI/AAAI12/paper/view/4809/5163)
  - Oliver Parson, Siddhartha Ghosh, Mark Weal, Alex Rogers. *AAAI'12*
- **Bayesian Nonparametric Hidden Semi-Markov Models** [[pdf]](http://www.jmlr.org/papers/volume14/johnson13a/johnson13a.pdf)
  - Matthew Johnson, Alan Willsky. *JMLR'14*
- **Signal Aggregate Constraints in Additive Factorial HMMs, with Application to Energy Disaggregation** [[pdf]](http://papers.nips.cc/paper/5526-signal-aggregate-constraints-in-additive-factorial-hmms-with-application-to-energy-disaggregation.pdf)
  - Mingjun Zhong, Nigel Goddard, Charles Sutton. *NIPS'14*
- **Latent Bayesian melding for integrating individual and population models** [[pdf]](http://papers.nips.cc/paper/5756-latent-bayesian-melding-for-integrating-individual-and-population-models.pdf)
  - Mingjun Zhong, Nigel Goddard, Charles Sutton. *NIPS'15*
- **SDP Relaxation with Randomized Rounding for Energy Disaggregation** [[pdf]](https://papers.nips.cc/paper/6555-sdp-relaxation-with-randomized-rounding-for-energy-disaggregation.pdf)
  - Kiarash Shaloudegi, Andräs György, Csaba Szepesvari, Wilsun Xu. *NIPS'16*


### Sparse Coding
- **Energy disaggregation via discriminative sparse coding** [[pdf]](http://papers.nips.cc/paper/4054-energy-disaggregation-via-discriminative-sparse-coding.pdf)
  - Zico Kolter, Siddarth Batra, Andrew Ng. *NIPS'10*
- **Contextually Supervised Source Separation with Application to Energy Disaggregation** [[pdf]](http://www.aaai.org/ocs/index.php/AAAI/AAAI14/paper/download/8629/8460)
  - Matt Wytock, Zico Kolter. *AAAI'14*
- **Energy Disaggregation via Learning ‘Powerlets’ and Sparse Coding** [[pdf]](http://www.aaai.org/ocs/index.php/AAAI/AAAI15/paper/download/9791/9306)
  - Ehsan Elhamifar, Shankar Sastry. *AAAI'15*

### DNN
- **Neural nilm: Deep neural networks applied to energy disaggregation** [[pdf]](http://jack-kelly.com/files/writing/neural_nilm.pdf)
  - Jack Kelly, William Knottenbelt. *BuildSys'15* 
- **Sequence-to-point learning with neural networks for non-intrusive load monitoring** [[pdf]](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16623/15980)
  - Chaoyun Zhang, Mingjun Zhong, Zongzuo Wang, Nigel Goddard, Charles Sutton. *AAAI'18*
- **Subtask Gated Networks for Non-Intrusive Load Monitoring** [[pdf]](https://arxiv.org/pdf/1811.06692.pdf)
  - Changho Shin, Sunghwan Joo, Jaeryun Yim, Hyoseop Lee, Taesup Moon, Wonjong Rhee. *AAAI'19*

### Others
- **Gemello: Creating a Detailed Energy Breakdown from just the Monthly Electricity Bill** [[pdf]](https://www.kdd.org/kdd2016/papers/files/adp1036-batraA.pdf)
  - Nipun Batra, Amarjeet Singh, Kamin Whitehouse. *KDD'16*
- **Disambiguating Energy Disaggregation: A Collective Probabilistic Approach** [[pdf]](https://www.ijcai.org/proceedings/2017/0398.pdf)
  - Sabina Tomkins, Jay Pujara, Lise Getoor. *IJCAI'17*
- **Matrix Factorisation for Scalable Energy Breakdown** [[pdf]](http://www.aaai.org/ocs/index.php/AAAI/AAAI17/paper/download/14885/14054)
  - Nipun Batra, Hongning Wang, Amarjeet Singh, Kamin Whitehouse. *AAAI'17*
- **Transferring Decomposed Tensors for Scalable Energy Breakdown across Regions** [[pdf]](https://aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16858/15754)
  - Nipun Batra, Yiling Jia, Honging Wang, Kamin Whitehouse. *AAAI'18*

## Public Datasets
- REDD [[link]](http://redd.csail.mit.edu/)
- UK-DALE [[link]](https://www.nature.com/articles/sdata20157)
- BLUED [[link]](http://portoalegre.andrew.cmu.edu:88/BLUED/)
- GREEND [[link]](https://sourceforge.net/projects/greend/)
- AMPds [[link]](http://ampds.org/)
- ECO [[link]](http://www.vs.inf.ethz.ch/res/show.html?what=eco-data)
- HES [[link]](http://randd.defra.gov.uk/Default.aspx?Menu=Menu&Module=More&Location=None&ProjectID=17359&FromSearch=Y&Publisher=1&SearchText=EV0702&SortString=ProjectCode&SortOrder=Asc&Paging=10#Description)
- Tracebase [[link]](https://github.com/areinhardt/tracebase)

## Toolkits
- NILM-Eval [[codes]](https://github.com/beckel/nilm-eval)
- NILMTK [[paper]](https://arxiv.org/pdf/1404.3878v1.pdf) [[codes]](https://github.com/nilmtk/nilmtk)

## ETC.
- NILM wiki [[link]](http://wiki.nilm.eu/)

## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Changho Shin](https://github.com/ch-shin) has waived all copyright and related or neighboring rights to this work.
