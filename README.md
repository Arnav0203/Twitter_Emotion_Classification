# Twitter_Emotion_Classification
This project aims to develop a robust classification model to address challenges in multi-class classification tasks, such as sentiment analysis and customer segmentation. These problems have practical applications in improving customer experience, targeted marketing, and fraud detection. The objective is to explore efficient deep learning techniques to capture complex data patterns while managing computational limitations.

**Dataset:** [Kaggle](https://www.kaggle.com/datasets/aadyasingh55/twitter-emotion-classification-dataset). This dataset consists of labeled tweets, where each tweet is associated with an emotion label, such as "anger," "joy," "sadness," "fear," "love,’ or “sadness.”

**Modeling:**
Baseline Model: A simple fully connected model was implemented with a single layer. This model served as a benchmark to evaluate the performance improvements achieved by more complex architectures.
Multi-layer Perceptron Model(MLP): five fully connected layers, incorporating ReLU activations, dropout, weight decay, and residual connections. These enhancements improved the model's capacity to learn hierarchical patterns while mitigating overfitting and stabilizing training.

**Results:**
Achieved a 66% test accuracy in classifying the emotion of a tweet. The MLP model outperformed the baseline model by 6%. 
