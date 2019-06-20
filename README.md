C1  这个文档实现的是4个线性模型：(sklearn.linear_model)

1. 线性回归模型(.LinearRegression)

2. 线性回归模型的**正则化**:岭回归(.Ridge)(考察$\alpha$)lasso(.Lasso)(考察$\alpha$)弹性网(.ElasticNet)(考察$\alpha,\rho$)

3. 逻辑回归(.LogisticRegressor)(考察C)

4. 线性判别分析/LDA（.LinearDiscriminantAnalysis）(考察solver)                                                                       

   


C2.1  这个文档实现的是决策树回归器(sklearn.tree.DecisionTreeRegressor)(考察splitter,max_depth)

C2.2  这个文档实现的是决策树分类器(sklearn.tree.DecisionTreeClassifier)(考察criterion,splitter,max_depth)


C3  这个文档实现的是贝叶斯分类器(sklearn.naive_bayes):

1. 高斯贝叶斯分类器(.GaussianNB)
2. 多项式贝叶斯分类器(.MultinomialNB)(考察 α  )
3. 伯努利贝叶斯分类器(.BernoulliNB)(考察 α ,binarize)


C4  这个文档实现的是KNN分类器和回归器(sklearn.neighbors):

1. 分类器(.KNeighborsClassifier)(考察k_w,k_p)
2. 回归器(.KNeighborsRegressor)(考察k_w,k_p)


C5.1  这个文档实现的是数据降维(Ⅰ)：(sklearn.decomposition)

1. .PCA
2. .IncrementalPCA--超大规模数据降维
3. .KernelPCA(考察poly,rbf,sigmoid)


C5.2  这个文档实现的是数据降维(Ⅱ)的流行学习降维：(sklearn.manifold)

1. 多维缩放降维(.MDS)
2. 等度量映射降维(.Isomap)(考察k)
3. 局部线性嵌入/LLE(.LocallyLinearEmbedding)(考察k)  


C6  这个文档实现了几个聚类方法：(sklearn.cluster)

1. K均值聚类(.KMeans)(考察ncluster,n_init)
2. 密度聚类(.DBSCAN)(考察$\epsilon$,min_samples)
3. 层次聚类(.AgglomerativeClustering)(考察ncluster,linkage)
4. 混合高斯模型(sklearn.mixture.GaussianMixture)(考察n_conponents,cov_type)


C7  (Omit)


C8.1  这个文档实现了感知机的底层代码和它的对偶形式，并考察了参数$\eta$

C8.2  这个文档实现了多层神经网络(sklearn.neural_network.MLPClassifier)

C8.3  这个文档用多层神经网络来对鸢尾花进行分类(考察参数隐含层，激活函数和优化算法的影响)


C9  这个文档实现了半监督学习(sklearn.semi_supervised):

1. .LabelPropagation(考察rbf,knn)
2. .LabelSpreading(考察rbf,knn)(这部分没有码出来)


C10.1  这个文档实现了集成学习(Ⅰ)：(sklearn.ensemble)

1. .AdaBoostClassifier(考察个体学习器，学习率和优化算法)
2. .AdaBoostRegressor(考察个体学习其，学习率和损失函数)

C10.2  这个文档实现了集成学习(Ⅱ)：(sklearn.ensemble)
1. .GradientBoostingClassifier/GBDT(考察一堆参数···)
2. .GradientBoostingRegressor/GBRT(考察一堆参数···)


C11  