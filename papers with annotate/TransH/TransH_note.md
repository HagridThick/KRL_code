### 核心

在基于Translation的Embedding模型(TransE)的高性能之上，TransE仅限于one-to-one，因此在实际应用中常常是将many转化为one。但是实际生活中的many是比较多的情况，所以该模型在TransE的基础上增加了一个Hyperplane。

最终模型能应用于flexible/one-to-many/many-to-one/many-to-many的多种情况。

### 几点

1. 适用与知识图谱的任何具体应用
2. 保证效率的情况下实现了TransE在“many”的情况下的优化
3. 结果是能在实际场景下，速度达到接近TransE，模型效果超过已知的其他Embedding模型(包括TransE)

### 改进

该模型应该能更好地嵌入到知识图谱中，改进还在思考中

