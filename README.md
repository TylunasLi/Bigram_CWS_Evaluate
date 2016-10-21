# Bigram_CWS_Evaluate

采用统一训练数据。评测Java环境下，利用了N-gram的中文分词器。 

an N-Gram-based Chinese word segmentation tool evaluation platform in Java

### 缘起
Word分词的作者提供了一个中文分词评测平台，并得到了测试报告。在他的报告中，自己的分词器得分较高。
但是他的分词器仅仅使用了几种分词工具自带的数据和模型，无法作为算法的比较。

### 说明
本仓库提供了对常见开源中文分词器采用同一数据源进行训练后，分词效果的评测，

数据来源于Word分词项目.

注意：本评测不能代表在实际使用的效果。

We trained some open-source, commonlly used N-Gram-based Chinese word segmentation tool using unified dataset and made this benchmark to evaluate their algorithms and implementations;

ATTENTION : the result of this evaluation cannot represent real profermance in production environment.
