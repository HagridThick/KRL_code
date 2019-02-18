An entity may have multiple aspects and various relations may focus on different aspects of entites. TransR first projects entities from entity space to corresponding relation space and then builds translations between projected entities. CTransR extends TransR by clustering diverse head-tail entity pairs into groups and learning distinct relation vectors for each group, which is the initial exploration for modeling internal correlations within each relation type.

## 做了什么

对比 transE transH（将实体放在相同语义空间），transR 有着实体空间和关系空间。实体空间维度和关系空间维度可以不同。在3种评估任务，链路预测，三重分类，文本关系实体提取中，针对不同的数据集，起到了更好的效果。

提出结合聚类相似关系的聚类 transR =   CTransR，有些方面效果更好。

## 核心内容

transR =  映射函数、socre function

CtransR = 增加了一个 rc-r 的项防止偏离



Margin-based score function 用于训练

SGD



Mean rank of correct entities 与 top10  proportion of correct 两种评估标准 

 

##  