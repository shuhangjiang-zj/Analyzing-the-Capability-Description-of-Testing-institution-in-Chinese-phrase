# Analyzing the Capability Description of Testing institution in Chinese phrase using a Joint Approach of Semi-Supervised K-Means Clustering and BERT
    The capability parameters of third-party testing institutions not only serve as a critical reflection of their technical and quality
 management capabilities but also form the key basis for categorizing their testing abilities. However, current Chinese phrase
based descriptions of these capability parameters are influenced by diverse expression styles and varying internal standards,
 making it difficult to establish consistent criteria for classifying testing capabilities. This inconsistency presents notable difficulties
 for clients and regulatory bodies. Therefore, leveraging clustering techniques to uncover the intrinsic relationships and latent
 information between testing capabilities and their corresponding parameters is one of the crucial approaches to achieving
 scientific and reasonable classification of testing capabilities. Traditional text feature extraction methods suffer from several
 limitations, including sparse features, high-dimensional features, and lack of semantic information. These shortcomings
 complicate the classification and analysis of testing capability descriptions. To address this issue, this study focuses on the
 "products and testing objects" within the capability parameters of Chinese testing institutions as the research subject and
 proposes a joint model based on BERT and semi-supervised K-Means clustering. This model employs BERT to extract textual
 features from Chinese descriptive phrases and combines them with a small number of labeled samples for semi-supervised
 K-Means clustering analysis. The clustering results are then used to train a multi-output Softmax classifier, thereby enabling
 the classification of testing capabilities for third-party institutions. Experimental results demonstrate that the proposed method
 outperforms traditional methods such as TF-IDF and one-hot encoding when applied to the Chinese description datasets
 of testing institutions. Specifically, it exhibits advantages in reducing the dimensionality of textual features and enhancing
 clustering performance. When the proportion of labeled samples accounts for 10% of the total sample size, the method
 achieves optimal clustering results, with an average classifier accuracy of 89.8%.
