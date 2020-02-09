# AVA
---


## Project repo for "Yu et al., AVA: A Financial Service Chatbot based on Deep BidirectionalTransformer, submitted to ACM KDD 2020" 

Welcome!

## Table of Contents

- [Additional Results for the Main Paper](#additional-results-for-the-main-paper)
  - [Histogram of Uncertainties by Dropout Ratios](#histogram-of-uncertainties-by-dropout-ratios)
  - [Uncertainty Curves by Dropout Ratios 5-class vs 381-class](#uncertainty-curves-by-dropout-ratios-5-class-vs-381-class)
  - [Grid Search for Optimal Threshold on Dropout](#grid-search-for-optimal-threshold-on-dropout)  
  - [Optimal Threshold Learning on Dropout 381 classes](#optimal-threshold-learning-on-dropout-381-classes)  

- [BERT Model Scripts](#bert-model-scripts)
  
- [Threshold Optimization Scripts](#threshold-optimization-scripts)

- [Sentence Completion Model Scripts](#sentence-completion-model-scripts)
- [RASA scripts for chatbot](#rasa-scripts-for-chatbot)
- [License](#license)
- [Contributors](#contributors)

## Additional Results for the Main Paper

##### Histogram of Uncertainties by Dropout Ratios
<img src="images/original/dropout_10percent_10iterations.png" width="350"/> <img src="images/original/dropout_10percent_30iterations.png" width="350"  />
<img src="images/original/dropout_20percent_10iterations.png" width="350"/> <img src="images/original/dropout_20percent_30iterations.png" width="350"  />
<img src="images/original/dropout_30percent_10iterations.png" width="350"/> <img src="images/original/dropout_30percent_30iterations.png" width="350"  />
<img src="images/original/dropout_40percent_10iterations.png" width="350"/> <img src="images/original/dropout_40percent_30iterations.png" width="350"  />
<img src="images/original/dropout_50percent_10iterations.png" width="350"/> <img src="images/original/dropout_50percent_30iterations.png" width="350"  />
<img src="images/original/dropout_60percent_10iterations.png" width="350"/> <img src="images/original/dropout_60percent_30iterations.png" width="350"  />
<img src="images/original/dropout_70percent_10iterations.png" width="350"/> <img src="images/original/dropout_70percent_30iterations.png" width="350"  />
<img src="images/original/dropout_80percent_10iterations.png" width="350"/> <img src="images/original/dropout_80percent_30iterations.png" width="350"  />
<img src="images/original/dropout_90percent_10iterations.png" width="350"/> <img src="images/original/dropout_90percent_30iterations.png" width="350"  />

##### Uncertainty Curves by Dropout Ratios 5-class vs 381-class
<img src="images/original/acc_dropout_10epoch.png" width="250"/>  <img src="images/original/acc_dropout_30epoch.png" width="250"  />
<img src="images/original/acc_dropout_10epoch_5class.png" width="250"/> <img src="images/original/acc_dropout_30epoch_5class.png" width="250" /> <img src="images/original/epoch_compare_5class.png" width="250" />

##### Grid Search For Optimal Threshold on Dropout
<img src="images/original/bfsearch.png" width="550"/>

##### Optimal threshold learning on dropout 381 classes

We did more experiments using different \delta values to optimizing the thresholds from Dropout, and results can be found here.

##### Uncertainty comparison 5-class vs 381-class



## License

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

Released 2020 by [Shi Yu](https://github.com/cyberyu) 
