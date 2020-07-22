# Awesome NILM (Non-Intrusive Load Monitoring)[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

![image](https://user-images.githubusercontent.com/28736511/51742581-80aa0c80-20dd-11e9-8ed9-b591a79442a3.png)

A curated list of NILM (also known as Energy Disaggregation or Load Disaggregation) resources. Inspired by [awesome-deep-vision](https://github.com/kjw0612/awesome-deep-vision), [awesome-public-datasets](https://github.com/awesomedata/awesome-public-datasets), [awesome-adversarial-machine-learning](https://github.com/yenchenlin/awesome-adversarial-machine-learning), [awesome-deep-learning-papers](https://github.com/terryum/awesome-deep-learning-papers), [awesome-meta-learning](https://github.com/dragen1860/awesome-meta-learning/) and [awesome-architecture-search](https://github.com/markdtw/awesome-architecture-search).

Curation of papers is generally based on the recent publication in top AI confenrences (NIPS, ICML, ICLR, AAAI, KDD, etc.) or the impactfulness on NILM domain. But the criteria is not strict. Please feel free to [pull requests](https://github.com/ch-shin/awesome-nilm/pulls) or [open an issue](https://github.com/ch-shin/awesome-nilm/issues) if you know awesome NILM resources.


## Papers


### Original paper
- **Nonintrusive appliance load monitoring** (1992), G.W. Hart [[link]](https://ieeexplore.ieee.org/document/192069)


### Reviews
- **Nonintrusive appliance load monitoring: Review and outlook** [[pdf]](https://www.researchgate.net/publication/224225559_Nonintrusive_Appliance_Load_Monitoring_Review_and_Outlook)
  - M Zeifman, K Roth. IEEE transactions on Consumer Electronics, 2011
- **Non-Intrusive Load Monitoring Approaches for Disaggregated Energy Sensing: A Survey** [[pdf]](https://www.mdpi.com/1424-8220/12/12/16838)
  - A Zoha, A Gluhak, M Imran, S Rajasegarar. Sensors, 2012
- **Unsupervised Algorithms for Non-Intrusive Load
Monitoring: an Up-to-Date Overview** [[pdf]](https://www.researchgate.net/profile/Stefano_Squartini/publication/277009814_Unsupervised_Algorithms_for_Non-Intrusive_Load_Monitoring_an_Up-to-Date_Overview/links/55c4eb8208aeca747d6182c5.pdf)
  - R Bonfigli, S Squartini, M Fagiani, F Piazza. 2015 IEEE 15th International …, 2015
- **Non-Intrusive Load Monitoring: A Review and Outlook** [[pdf]](https://arxiv.org/abs/1610.01191)
  - C Klemenjak, P Goldsborough. arXiv preprint arXiv:1610.01191, 2016
- **Machine learning approaches for non-intrusive load monitoring: from qualitative to quantitative comparation, Artificial Intelligence Review** [[pdf]](https://intelligence.csd.auth.gr/publications/machine-learning-approaches-for-non-intrusive-load-monitoring-from-qualitative-to-quantitative-comparation/)
  - C Nalmpantis, D Vrakas. Artificial Intelligence Review, 2019


#### HMM
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


#### Sparse Coding
- **Energy disaggregation via discriminative sparse coding** [[pdf]](http://papers.nips.cc/paper/4054-energy-disaggregation-via-discriminative-sparse-coding.pdf)
  - Zico Kolter, Siddarth Batra, Andrew Ng. *NIPS'10*
- **Contextually Supervised Source Separation with Application to Energy Disaggregation** [[pdf]](http://www.aaai.org/ocs/index.php/AAAI/AAAI14/paper/download/8629/8460)
  - Matt Wytock, Zico Kolter. *AAAI'14*
- **Energy Disaggregation via Learning ‘Powerlets’ and Sparse Coding** [[pdf]](http://www.aaai.org/ocs/index.php/AAAI/AAAI15/paper/download/9791/9306)
  - Ehsan Elhamifar, Shankar Sastry. *AAAI'15*
- **Independent-Variation Matrix Factorization With Application to Energy Disaggregation** [[link]](https://ieeexplore.ieee.org/document/8836542)
  - SImon Henriet, Umut Simsekli, Sergio Dos Santos, Benoit Fuentes, Gaël Richard. *IEEE SPL 2019* & *ICASSP'20*.
  

#### DNN
- **Neural nilm: Deep neural networks applied to energy disaggregation** [[pdf]](http://jack-kelly.com/files/writing/neural_nilm.pdf)
  - Jack Kelly, William Knottenbelt. *BuildSys'15*
- **Sequence-to-point learning with neural networks for non-intrusive load monitoring** [[pdf]](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16623/15980)
  - Chaoyun Zhang, Mingjun Zhong, Zongzuo Wang, Nigel Goddard, Charles Sutton. *AAAI'18*
- **Deep Latent Generative Models For Energy Disaggregation** [[pdf]](https://www.aaai.org/Papers/AAAI/2019/AAAI-BejaranoG.1181.pdf)
  - Gissella Bejarano, David DeFazio, Arti Ramesh. *AAAI'19*
- **Subtask Gated Networks for Non-Intrusive Load Monitoring** [[pdf]](https://arxiv.org/pdf/1811.06692.pdf)
  - Changho Shin, Sunghwan Joo, Jaeryun Yim, Hyoseop Lee, Taesup Moon, Wonjong Rhee. *AAAI'19*
- **Wavenilm: A causal neural network for power disaggregation from the complex power signal** [[pdf]](https://arxiv.org/pdf/1902.08736.pdf)
  - Alon Harell, Stephen Makonin, Ivan V. Bajić. *ICASSP'19*
- **Neural Variational Identification and Filtering for Stochastic Non-linear Dynamical Systems with Application to Non-intrusive Load Monitoring** [[link]](https://ieeexplore.ieee.org/document/8683552)
  - Henning Lange, Mario Berges, Zico Kolter. *ICASSP'19*
- **Multi Label Restricted Boltzmann Machine for Non-intrusive Load Monitoring** [[link]](https://ieeexplore.ieee.org/document/8682860)
  - Sagar Verma, Shikha Singh, Angshul Majumdar. *ICASSP'19*
- **Bayesian-optimized Bidirectional LSTM Regression Model for Non-intrusive Load Monitoring** [[link]](https://ieeexplore.ieee.org/document/8683110)
  - Maria Kaselimi, Nikolaos Doulamis, Anastasios Doulamis, Athanasios Voulodimos, Eftychios Protopapadakis. *ICASSP'19*

#### Others
- **Gemello: Creating a Detailed Energy Breakdown from just the Monthly Electricity Bill** [[pdf]](https://www.kdd.org/kdd2016/papers/files/adp1036-batraA.pdf)
  - Nipun Batra, Amarjeet Singh, Kamin Whitehouse. *KDD'16*
- **Disambiguating Energy Disaggregation: A Collective Probabilistic Approach** [[pdf]](https://www.ijcai.org/proceedings/2017/0398.pdf)
  - Sabina Tomkins, Jay Pujara, Lise Getoor. *IJCAI'17*
- **Matrix Factorisation for Scalable Energy Breakdown** [[pdf]](http://www.aaai.org/ocs/index.php/AAAI/AAAI17/paper/download/14885/14054)
  - Nipun Batra, Hongning Wang, Amarjeet Singh, Kamin Whitehouse. *AAAI'17*
- **Transferring Decomposed Tensors for Scalable Energy Breakdown across Regions** [[pdf]](https://aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16858/15754)
  - Nipun Batra, Yiling Jia, Honging Wang, Kamin Whitehouse. *AAAI'18*

### Papers on Performance Evaluation
- **Nonintrusive load monitoring (NILM) performance evaluation** [[pdf]](https://link.springer.com/article/10.1007/s12053-014-9306-2)
  - S Makonin, F Popowich. Energy Efficiency, 2015
- **Performance evaluation in non-intrusive load monitoring: Datasets, metrics, and tools-A review** [[pdf]](https://www.researchgate.net/publication/325294847_Performance_evaluation_in_non-intrusive_load_monitoring_Datasets_metrics_and_tools-A_review)
  - L Pereira, N Nunes. Wiley Interdisciplinary Reviews: Data Mining and …, 2018
- **Towards Comparability in Non-Intrusive Load Monitoring: On Data and Performance Evaluation** [[pdf]](http://makonin.com/doc/ISGT-NA_2020b.pdf)
  - C Klemenjak, S Makonin, and W Elmenreich. 2020 IEEE Power & Energy Society Innovative
Smart Grid Technologies Conference (ISGT), 2020

## Public Datasets

### Papers on Datasets

- **Position Paper: Electricity Consumption Data Sets: Pitfalls and Opportunities** [[pdf]](http://makonin.com/doc/BuildSys_2019.pdf)
  - C Klemenjak, A Reihardt, L Pereira, S Makoni, M Berges, W Elmenreich. ACM BuildSys. 2019

### Real Datasets

- REDD [[link]](http://redd.csail.mit.edu/)
- UK-DALE [[link]](https://www.nature.com/articles/sdata20157)
- BLUED [[link]](http://portoalegre.andrew.cmu.edu:88/BLUED/)
- GREEND [[link]](https://sourceforge.net/projects/greend/)
- AMPds [[link]](http://ampds.org/)
- ECO [[link]](http://www.vs.inf.ethz.ch/res/show.html?what=eco-data)
- HES [[link]](http://randd.defra.gov.uk/Default.aspx?Menu=Menu&Module=More&Location=None&ProjectID=17359&FromSearch=Y&Publisher=1&SearchText=EV0702&SortString=ProjectCode&SortOrder=Asc&Paging=10#Description)
- Tracebase [[link]](https://github.com/areinhardt/tracebase)
- PLAID [[link]](https://www.nature.com/articles/s41597-020-0389-7)
- ENERTALK [[link]](https://www.nature.com/articles/s41597-019-0212-5)

### Synthetic Datasets

- SHED: [[link]](https://nilm.telecom-paristech.fr/shed/)
- SmartSim: [[link]](https://github.com/sustainablecomputinglab/smartsim)
- SynD: [[link]](https://github.com/klemenjak/SynD/)

## Toolkits
- NILM-Eval [[pdf]]() [[code]](https://github.com/beckel/nilm-eval)
- NILMTK [[pdf]](https://arxiv.org/pdf/1404.3878v1.pdf) [[code]](https://github.com/nilmtk/nilmtk)
  - Recently: NILMTK-Contrib [[pdf]](https://nipunbatra.github.io/papers/batra_buildsys_19.pdf) [[code]](https://github.com/nilmtk/nilmtk-contrib)

## Workshops
- EU NILM Workshop [[website]](http://www.nilm.eu/)
- International NILM Workshop [[website]](http://nilmworkshop.org/)

## Further Material
- NILM wiki [[link]](http://wiki.nilm.eu/)

## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Changho Shin](https://github.com/ch-shin) has waived all copyright and related or neighboring rights to this work.
