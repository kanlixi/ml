对目前主流的机器学习算法进行公式推导、问题分析以及代码实现（主要基于numpy），持续更新（下面链接如果加载不出来，对应内容可在notebooks文件夹下找到）：

01_线性模型_线性回归

01_线性模型_线性回归_正则化(Lasso,Ridge,ElasticNet)

02_线性模型_逻辑回归

03_二分类转多分类的一般实现

04_线性模型_感知机

05_线性模型_最大熵模型

06_优化_拟牛顿法实现(DFP,BFGS)

07_01_svm_硬间隔支持向量机与SMO

07_02_svm_软间隔支持向量机

07_03_svm_核函数与非线性支持向量机

08_代价敏感学习_添加sample_weight支持

09_01_决策树_ID3与C4.5

09_02_决策树_CART

10_01_集成学习_简介

10_02_集成学习_boosting_adaboost_classifier

10_03_集成学习_boosting_adaboost_regressor

10_04_集成学习_boosting_提升树

10_05_集成学习_boosting_gbm_regressor

10_06_集成学习_boosting_gbm_classifier

10_07_集成学习_bagging

10_08_集成学习_bagging_randomforest

10_09_集成学习_bagging_高阶组合_stacking

10_10_集成学习_xgboost_原理介绍及回归树的简单实现

10_11_集成学习_xgboost_回归的简单实现

10_12_集成学习_xgboost_回归的更多实现：泊松回归、gamma回归、tweedie回归

10_13_集成学习_xgboost_分类的简单实现

10_14_集成学习_xgboost_优化介绍

10_15_集成学习_lightgbm_进一步优化

10_16_集成学习_dart_提升树与dropout的碰撞

10_17_集成学习_树模型的可解释性_模型的特征重要性及样本的特征重要性(sabaas,shap,tree shap)

11_01_EM_GMM引入问题

11_02_EM_算法框架

11_03_EM_GMM聚类实现

11_04_EM_GMM分类实现及其与LogisticRegression的关系

12_01_PGM_贝叶斯网(有向无环图)初探

12_02_PGM_朴素贝叶斯分类器实现

12_03_PGM_半朴素贝叶斯分类器实现

12_04_PGM_朴素贝叶斯的聚类实现

12_05_PGM_马尔科夫链_初探及代码实现

12_06_PGM_马尔科夫链_语言模型及文本生成

12_07_PGM_马尔科夫链_PageRank算法

12_08_PGM_HMM_隐马模型：介绍及概率计算（前向、后向算法）

12_09_PGM_HMM_隐马模型：参数学习（有监督、无监督）

12_10_PGM_HMM_隐马模型：隐状态预测

12_11_PGM_HMM_隐马模型实战：中文分词

12_12_PGM_马尔科夫随机场（无向图）介绍

12_13_PGM_CRF_条件随机场：定义及形式（简化、矩阵形式）

12_14_PGM_CRF_条件随机场：如何定义特征函数

12_15_PGM_CRF_条件随机场：概率及期望值计算（前向后向算法）

12_16_PGM_CRF_条件随机场：参数学习

12_17_PGM_CRF_条件随机场：标签预测

12_18_PGM_CRF_代码优化及中文分词实践

12_19_PGM_CRF与HMM之间的区别与联系

13_01_sampling_为什么要采样（求期望、积分等）

13_02_sampling_MC采样：接受-拒绝采样、重要采样

13_03_sampling_MCMC：采样原理（再探马尔可夫链）

13_04_sampling_MCMC：MH采样的算法框架

13_05_sampling_MCMC：单分量MH采样算法

13_06_sampling_MCMC：Gibbs采样算法

14_01_概率分布：二项分布及beta分布

14_02_概率分布：多项分布及狄利克雷分布

14_03_概率分布：高斯分布（正态分布）及其共轭先验

14_04_概率分布：指数族分布

15_01_VI_变分推断的原理推导

15_02_VI_变分推断与EM的关系

15_03_VI_一元高斯分布的变分推断实现

15_04_VI_高斯混合模型（GMM）的变分推断实现

15_05_VI_线性回归模型的贝叶斯估计推导

15_06_VI_线性回归模型的贝叶斯估计实现：证据近似

15_07_VI_线性回归模型的变分推断实现

15_08_VI_线性回归模型的贝叶斯估计实现：进一步扩展VI

16_01_LDA_主题模型原理

16_02_LDA_Gibss采样实现

16_03_LDA_变分EM实现

17_01_FM_因子分解机的原理介绍及实现

17_02_FM_FFM的原理介绍及实现

17_03_FM_FFM的损失函数扩展(possion,gamma,tweedie回归实现以及分类实现)

18_01_聚类_距离度量以及性能评估

18_02_聚类_层次聚类_AGNES

18_03_聚类_密度聚类_DBSCAN

18_04_聚类_原型聚类_K均值

18_05_聚类_原型聚类_LVQ

18_06_聚类_谱聚类

19_01_降维_奇异值分解(SVD)

19_02_降维_主成分分析(PCA)

19_03_降维_线性判别分析(LDA)

19_04_降维_多维缩放(MDS)

19_05_降维_流形学习_等度量映射(Isomap)

19_06_降维_流形学习_局部线性嵌入(LLE)

19_07_降维_非负矩阵分解_NMF

20_01_异常检测_HBOS

20_01_异常检测_pHBOS

20_02_异常检测_iForest

20_03_异常检测_KNN

20_04_异常检测_LOF

参考
《统计学习方法》第二版 --李航

《机器学习》 --周志华

《深入理解XGBoost》 --何龙

《模式识别与机器学习》（PRML）

《徐亦达机器学习课程》 bilibili传送门>>>

《机器学习—白板推导系列》 bilibili传送门>>>
