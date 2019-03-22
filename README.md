# Advanced Machine Learning

### GTSRB Traffic Sign Image Multi-class Classification
using Python

by Sean Sungil Kim

The purpose of Computer Vision would include but not only be limited to image detection and recognition. For example, successfully classifying traffic signs given image data of traffic signs could benefit vehicle companies tremendously. To be able to classify traffic signs with significant performance, finding the optimal model with corresponding hyperparameters is important. Therefore, implementing machine learning algorithms in addition to analytical algorithms is necessary. The goal of this traffic sign image multi-class classification analysis is to explore the effectiveness of different classifiers on lower quality (both in dimension size and color), non-centered traffic sign image (researched and provided by INI Benchmark, which can be downloaded here: http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset). Being able to build models with powerful predictive performance using lower quality and non-centered image data can excel in environments that are extremely time sensitive and limited in computing power, which are very frequent in the real world. Random Forest and Multi-Layer Perceptron classifiers fit on wrapper-based feature selected images demonstrated significant testing f-score performance of 0.879842 and 0.911308 respectively. The model fitting and the hyper-tuning steps also required extremely less time compared to Gradient Boosting, Ada Boost, SVM and XGBoost. Random Forest had the fastest runtime with lower f-score performance, whereas Multi-layer Perceptron took significantly longer than Random Forest but had the highest f-score performance among all models explored.
