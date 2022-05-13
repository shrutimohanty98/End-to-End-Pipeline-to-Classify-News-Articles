# End to End Pipeline to Classify News Articles

The task of learning to select a subset of categories that correspond to a data point (sample of text, an image, a video clip, a time-signal, etc.) from a preset (usually human-guided) broader collection of categories is referred to as statistical categorization. Given a training data set (that is kept separate from an evaluation set) in which each data point is pre-labeled with their "proper" category membership/s, the model attempts to master the task. The classification of text data is the focus of this study.

The project consists of building an end-to-end pipeline to classify samples of news articles and involves the following ML components:
1. Feature Extraction: Construction of TF-IDF representations of textual data;
2. Dimensionality Reduction: Principal Component Analysis (PCA) and non-Negative
Matrix Factorization (NMF) - Generally necessary for classical ML methods
3. Application of Simple Classification Models: Applying common classification methods
to the extracted features such as Logistic/Linear Classification and Support Vector
Machines;
4. Evaluation the Pipeline: Evaluating and diagnosing classification results using Grid-
Search and Cross Validation;
5. Replace corpus-level features with pretrained features: To apply pre-training to
a downstream classification task and evaluate comparative performance.
