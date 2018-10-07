---
layout: default
---

I am a postgraduate student in University of Edinburgh. I have completed all the courses and the dissertation, and will graduate in Nov. 2018. I am interested in Machine Learning & Artifical Intelligence.

Contact: s1719186@ed.ac.uk

# Education

## University of Edinburgh, UK
*   Sep. 2017 to Nov. 2018
*   **Master of Science with Distinction**
*   Data Science @ School of Informatics
*   GPA: 78/100
*   Core Courses: Machine Learning and Patter Recognition (69/100), Machine Learning Practical (84/100), Probabilistic Modelling and Reasoning (90/100), Data Mining and Exploration (80/100), etc.

## Shandong University, China (985 & 211 project)
*   Sep. 2013 to Jun. 2017
*   **Bachelor of Science**
*   Mathematics and Applied Mathematics @ Hua Luogeng Class (National Mathematical Training Base) in School of Mathematics
*   GPA: 85/100 or 4.3/5.0
*   Related Courses: Probability Theory (89/100), Mathematical Statistics (95/100), Applied Statistics (88/100), etc.


# Projects

## TensorFlow Applied to Neural Language Models
- Jun. 2018 to Aug. 2018
- **MSc thesis**, supervised by _Ben Allison_ (Amazon) and _Tania Bakhos_ (Amazon).
- Contents:
  - Implement Neural Language Models with Mixture of Softmaxes using TensorFlow to solve the Softmax bottleneck;
  - Optimize hyperparameters mainly by specific Random Search; explore the influence of different LSTM implementations and the number of Softmax components.
  - Speed up training by: training models in parallel on multiple GPUs; weight tying; weight matrix factorization; Gradient Clipping.
  - The final model has lower validation and test perplexities as well as higher speed, compared with the original model.
  - Compare the final TensorFlow model with the same model implemented using PyTorch.
- Get access to [pdf](./dissertation.pdf) and [code](https://github.com/dreamlh/MoStfmodels).

## Marketing: Predicting Customer Behaviors
- Mar. 2018 to Apr. 2018
- Coursework in Data Mining and Exploration, with _Yi Wei_, _Wen Jia_ and _Jiayu Li_.
- Contents:
  - Preprocess the large and dirty dataset provided by KDD Cup 2009 competition using pandas, making it clean enough to feed neural networks.
  - Clip variables with large amounts of missing data; fill in the missing data; encode categorical data by one hot; reduce dimensions by linear or unlinear methods including PCA, Isomap & LLE.
  - Predict bahaviors by deep models; optimize hyperparameters; evaluate the result by AUC scores.
  - In terms of customer churn, one of the three behaviors, the prediction AUC exceeds the first place of the competition.
- Get access to [pdf](./DME_report.pdf).

## Instance Segmentation of Nucleus Images
- Feb. 2018 to Apr. 2018
- Coursework in Machine Learning Practical, with _Yi Wei_ and _Zhengjun Yue_, supervised by _Steve Renals_.
- Contents:
  - Segment nucleus instances from nucleus images acquired in different microscopy systems, which is provided by Kaggle 2018 Data Science Bowl.
  - In the baseline experiments, use fully convolutional networks with VGG16 backbone to semantically segment nuclei from the background, and use open operation to separate individual nuclei.
  - In the contrast experiments, apply Mask RCNN to direct segment nucleus instances. Extract features by ResNet101 with Feature Pymarid Networks; select regions of interest by Region Proposal Networks; semantically segment the nuclei in all regions by fully convolutional networks.
  - Implement the two models and pretrain them on COCO datasets; implement evaluation criteria by mean average procision; carefully tune hyperparameters. Mask RCNN significantly (0.401) outperforms the baseline model (0.229).
- Get access to [pdf](./mlp-final-report.pdf).

# Awards
*    Informatics International Masters Scholarship in Nov. 2017
*    Hua Luogeng Schorlarship in Dec. 2016
*    Honorable Mention @ Interdisciplinary Contest in Modeling (US) in Apr. 2016
*    First Prize @ Shandong Province Mathematics Competitions (China) in Dec. 2015
*    Third Prize @ Chinese Mathematics Competitions in Nov. 2015
*    Second Prize @ Shandong Province Zone of China Undergraduate Mathematical Contest in Modelling (MCM) in Oct. 2015
*    Meritorious Winner @ Certificate Authority Cup International MCM in Jan. 2015

# Skills
*    Python, including TensorFlow, Keras, Pandas, sk-learn, etc.
*    Linux
*    Hadoop
*    Beginner: C, C++, Java, SAS, SQL, Matlab, R
