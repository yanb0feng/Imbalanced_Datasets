# Imbalanced Datasets

Imbalanced datasets refer to datasets where the sample sizes of different classes are highly unequal. For instance, in [network security datasets](https://raw.githubusercontent.com/arjbah/nsl-kdd/master/nsl-kdd), data representing non-attacks and a few common types of attacks (majority) far exceed those representing other, less common types of attacks (minority). As a result, a trained model might achieve high accuracy but fail to effectively distinguish between majority and minority classes. However, in real-life scenarios, we often focus on the impact of these minority classes, such as how to prevent uncommon types of network attacks. 

To ensure minority classes are given equal importance and treated equally by the model, this article presents several oversampling and undersampling techniques. It also uses AdaBoost and Random Forest—models known for good generalization—to compare the performance of models before and after applying these sampling techniques.
