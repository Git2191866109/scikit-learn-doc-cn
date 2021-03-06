=============
API 参考
=============

这是scikit-learn函数和累的引用，请参考
:ref:`完整的用户指南 <user_guide>` 了解细节,类和函数原始规格可能不足以充分使用指南。


.. _base_ref:

:mod:`sklearn.base`: 基类和通用函数
=======================================================

.. automodule:: sklearn.base
    :no-members:
    :no-inherited-members:

基类
------------
.. currentmodule:: sklearn

.. autosummary::
   :toctree: generated/
   :template: class.rst

   base.BaseEstimator
   base.ClassifierMixin
   base.ClusterMixin
   base.RegressorMixin
   base.TransformerMixin

函数
---------
.. currentmodule:: sklearn

.. autosummary::
   :toctree: generated/
   :template: function.rst

   base.clone


.. _cluster_ref:

:mod:`sklearn.cluster`: 聚类
==================================

.. automodule:: sklearn.cluster
   :no-members:
   :no-inherited-members:

**使用手册:** 参见:ref:`clustering` 了解进一步的细节部分.

类
-------
.. currentmodule:: sklearn

.. autosummary::
   :toctree: generated/
   :template: class.rst

   cluster.AffinityPropagation
   cluster.AgglomerativeClustering
   cluster.Birch
   cluster.DBSCAN
   cluster.FeatureAgglomeration
   cluster.KMeans
   cluster.MiniBatchKMeans
   cluster.MeanShift
   cluster.SpectralClustering

函数
---------
.. autosummary::
   :toctree: generated/
   :template: function.rst

   cluster.estimate_bandwidth
   cluster.k_means
   cluster.ward_tree
   cluster.affinity_propagation
   cluster.dbscan
   cluster.mean_shift
   cluster.spectral_clustering

.. _bicluster_ref:

:mod:`sklearn.cluster.bicluster`: 双向聚类
==============================================

.. automodule:: sklearn.cluster.bicluster
   :no-members:
   :no-inherited-members:

**用户指南:** 参见 :ref:`biclustering`了解进一步的细节部分.

类
-------
.. currentmodule:: sklearn.cluster.bicluster

.. autosummary::
   :toctree: generated/
   :template: class.rst

   SpectralBiclustering
   SpectralCoclustering

.. _covariance_ref:

:mod:`sklearn.covariance`:协方差估计
================================================

.. automodule:: sklearn.covariance
   :no-members:
   :no-inherited-members:

**用户指南:** 参见:ref:`covariance`了解进一步的细节部分.

.. currentmodule:: sklearn

.. autosummary::
   :toctree: generated/
   :template: class.rst

   covariance.EmpiricalCovariance
   covariance.EllipticEnvelope
   covariance.GraphLasso
   covariance.GraphLassoCV
   covariance.LedoitWolf
   covariance.MinCovDet
   covariance.OAS
   covariance.ShrunkCovariance

.. autosummary::
   :toctree: generated/
   :template: function.rst

   covariance.empirical_covariance
   covariance.ledoit_wolf
   covariance.shrunk_covariance
   covariance.oas
   covariance.graph_lasso


.. _cross_validation_ref:

:mod:`sklearn.cross_validation`: 交叉验证
=================================================

.. automodule:: sklearn.cross_validation
   :no-members:
   :no-inherited-members:

**用户指南:** 参见:ref:`cross_validation`了解进一步的细节部分.

.. currentmodule:: sklearn

.. autosummary::
   :toctree: generated/
   :template: class.rst

   cross_validation.KFold
   cross_validation.LabelKFold
   cross_validation.LabelShuffleSplit
   cross_validation.LeaveOneLabelOut
   cross_validation.LeaveOneOut
   cross_validation.LeavePLabelOut
   cross_validation.LeavePOut
   cross_validation.PredefinedSplit
   cross_validation.ShuffleSplit
   cross_validation.StratifiedKFold
   cross_validation.StratifiedShuffleSplit


.. autosummary::
   :toctree: generated/
   :template: function.rst

   cross_validation.train_test_split
   cross_validation.cross_val_score
   cross_validation.cross_val_predict
   cross_validation.permutation_test_score
   cross_validation.check_cv

.. _datasets_ref:

:mod:`sklearn.datasets`: 数据集
=================================

.. automodule:: sklearn.datasets
   :no-members:
   :no-inherited-members:

**用户指南:** 参见:ref:`datasets`了解进一步的细节部分.

加载器
-------

.. currentmodule:: sklearn

.. autosummary::
   :toctree: generated/
   :template: function.rst

   datasets.clear_data_home
   datasets.get_data_home
   datasets.fetch_20newsgroups
   datasets.fetch_20newsgroups_vectorized
   datasets.load_boston
   datasets.load_diabetes
   datasets.load_digits
   datasets.load_files
   datasets.load_iris
   datasets.fetch_lfw_pairs
   datasets.fetch_lfw_people
   datasets.load_linnerud
   datasets.mldata_filename
   datasets.fetch_mldata
   datasets.fetch_olivetti_faces
   datasets.fetch_california_housing
   datasets.fetch_covtype
   datasets.fetch_rcv1
   datasets.load_mlcomp
   datasets.load_sample_image
   datasets.load_sample_images
   datasets.load_svmlight_file
   datasets.load_svmlight_files
   datasets.dump_svmlight_file

样例生成
-----------------

.. currentmodule:: sklearn

.. autosummary::
   :toctree: generated/
   :template: function.rst

   datasets.make_blobs
   datasets.make_classification
   datasets.make_circles
   datasets.make_friedman1
   datasets.make_friedman2
   datasets.make_friedman3
   datasets.make_gaussian_quantiles
   datasets.make_hastie_10_2
   datasets.make_low_rank_matrix
   datasets.make_moons
   datasets.make_multilabel_classification
   datasets.make_regression
   datasets.make_s_curve
   datasets.make_sparse_coded_signal
   datasets.make_sparse_spd_matrix
   datasets.make_sparse_uncorrelated
   datasets.make_spd_matrix
   datasets.make_swiss_roll
   datasets.make_biclusters
   datasets.make_checkerboard


.. _decomposition_ref:

:mod:`sklearn.decomposition`: 矩阵分解
==================================================

.. automodule:: sklearn.decomposition
   :no-members:
   :no-inherited-members:

**用户指南:** 参见:ref:`decompositions`了解进一步的细节部分.

.. currentmodule:: sklearn

.. autosummary::
   :toctree: generated/
   :template: class.rst

   decomposition.PCA
   decomposition.IncrementalPCA
   decomposition.ProjectedGradientNMF
   decomposition.RandomizedPCA
   decomposition.KernelPCA
   decomposition.FactorAnalysis
   decomposition.FastICA
   decomposition.TruncatedSVD
   decomposition.NMF
   decomposition.SparsePCA
   decomposition.MiniBatchSparsePCA
   decomposition.SparseCoder
   decomposition.DictionaryLearning
   decomposition.MiniBatchDictionaryLearning
   decomposition.LatentDirichletAllocation

.. autosummary::
   :toctree: generated/
   :template: function.rst

   decomposition.fastica
   decomposition.dict_learning
   decomposition.dict_learning_online
   decomposition.sparse_encode

.. _dummy_ref:

:mod:`sklearn.dummy`: 假的估计
======================================

.. automodule:: sklearn.dummy
   :no-members:
   :no-inherited-members:

**用户指南:** 参见:ref:`model_evaluation`了解进一步的细节部分.

.. currentmodule:: sklearn

.. autosummary::
   :toctree: generated/
   :template: class.rst

   dummy.DummyClassifier
   dummy.DummyRegressor

.. autosummary::
   :toctree: generated/
   :template: function.rst

.. _ensemble_ref:

:mod:`sklearn.ensemble`: 集成方法
=========================================

.. automodule:: sklearn.ensemble
   :no-members:
   :no-inherited-members:

**用户指南:** 参见:ref:`ensemble`了解进一步的细节部分.

.. currentmodule:: sklearn

.. autosummary::
   :toctree: generated/
   :template: class.rst

   ensemble.AdaBoostClassifier
   ensemble.AdaBoostRegressor
   ensemble.BaggingClassifier
   ensemble.BaggingRegressor
   ensemble.ExtraTreesClassifier
   ensemble.ExtraTreesRegressor
   ensemble.GradientBoostingClassifier
   ensemble.GradientBoostingRegressor
   ensemble.RandomForestClassifier
   ensemble.RandomTreesEmbedding
   ensemble.RandomForestRegressor
   ensemble.VotingClassifier

.. autosummary::
   :toctree: generated/
   :template: function.rst


部分依赖
------------------

.. automodule:: sklearn.ensemble.partial_dependence
   :no-members:
   :no-inherited-members:

.. currentmodule:: sklearn

.. autosummary::
   :toctree: generated/
   :template: function.rst

   ensemble.partial_dependence.partial_dependence
   ensemble.partial_dependence.plot_partial_dependence


.. _feature_extraction_ref:

:mod:`sklearn.feature_extraction`: 特征提取
=====================================================

.. automodule:: sklearn.feature_extraction
   :no-members:
   :no-inherited-members:

**用户指南:** 参见:ref:`feature_extraction`了解进一步的细节部分.

.. currentmodule:: sklearn

.. autosummary::
   :toctree: generated/
   :template: class.rst

   feature_extraction.DictVectorizer
   feature_extraction.FeatureHasher

图片来源
-----------

.. automodule:: sklearn.feature_extraction.image
   :no-members:
   :no-inherited-members:

.. currentmodule:: sklearn

.. autosummary::
   :toctree: generated/
   :template: function.rst

   feature_extraction.image.img_to_graph
   feature_extraction.image.grid_to_graph
   feature_extraction.image.extract_patches_2d
   feature_extraction.image.reconstruct_from_patches_2d

   :template: class.rst

   feature_extraction.image.PatchExtractor

.. _text_feature_extraction_ref:

文本来源
---------

.. automodule:: sklearn.feature_extraction.text
   :no-members:
   :no-inherited-members:

.. currentmodule:: sklearn

.. autosummary::
   :toctree: generated/
   :template: class.rst

   feature_extraction.text.CountVectorizer
   feature_extraction.text.HashingVectorizer
   feature_extraction.text.TfidfTransformer
   feature_extraction.text.TfidfVectorizer


.. _feature_selection_ref:

:mod:`sklearn.feature_selection`: 特征选择
===================================================

.. automodule:: sklearn.feature_selection
   :no-members:
   :no-inherited-members:

**用户指南:** 参见:ref:`feature_selection`了解进一步的细节部分.

.. currentmodule:: sklearn

.. autosummary::
   :toctree: generated/
   :template: class.rst

   feature_selection.GenericUnivariateSelect
   feature_selection.SelectPercentile
   feature_selection.SelectKBest
   feature_selection.SelectFpr
   feature_selection.SelectFdr
   feature_selection.SelectFromModel
   feature_selection.SelectFwe
   feature_selection.RFE
   feature_selection.RFECV
   feature_selection.VarianceThreshold

.. autosummary::
   :toctree: generated/
   :template: function.rst

   feature_selection.chi2
   feature_selection.f_classif
   feature_selection.f_regression


.. _gaussian_process_ref:

:mod:`sklearn.gaussian_process`: 高斯过程
===================================================

.. automodule:: sklearn.gaussian_process
   :no-members:
   :no-inherited-members:

**用户指南:** 参见:ref:`gaussian_process`了解进一步的细节部分.

.. currentmodule:: sklearn

.. autosummary::
  :toctree: generated/
  :template: class.rst

  gaussian_process.GaussianProcess

.. autosummary::
   :toctree: generated
   :template: function.rst

   gaussian_process.correlation_models.absolute_exponential
   gaussian_process.correlation_models.squared_exponential
   gaussian_process.correlation_models.generalized_exponential
   gaussian_process.correlation_models.pure_nugget
   gaussian_process.correlation_models.cubic
   gaussian_process.correlation_models.linear
   gaussian_process.regression_models.constant
   gaussian_process.regression_models.linear
   gaussian_process.regression_models.quadratic


.. _grid_search_ref:

:mod:`sklearn.grid_search`: 网格搜索
=======================================

.. automodule:: sklearn.grid_search
   :no-members:
   :no-inherited-members:

**用户指南:** 参见:ref:`grid_search`了解进一步的细节部分.

.. currentmodule:: sklearn

.. autosummary::
   :toctree: generated/
   :template: class.rst

   grid_search.GridSearchCV
   grid_search.ParameterGrid
   grid_search.ParameterSampler
   grid_search.RandomizedSearchCV


.. _isotonic_ref:

:mod:`sklearn.isotonic`: 等张回归
============================================

.. automodule:: sklearn.isotonic
   :no-members:
   :no-inherited-members:

**用户指南:** 参见:ref:`isotonic`了解进一步的细节部分.

.. currentmodule:: sklearn

.. autosummary::
   :toctree: generated/
   :template: class.rst

   isotonic.IsotonicRegression

.. autosummary::
   :toctree: generated
   :template: function.rst

   isotonic.isotonic_regression
   isotonic.check_increasing

.. _kernel_approximation_ref:

:mod:`sklearn.kernel_approximation`核逼近
========================================================

.. automodule:: sklearn.kernel_approximation
   :no-members:
   :no-inherited-members:

**用户指南:** 参见:ref:`kernel_approximation`了解进一步的细节部分.

.. currentmodule:: sklearn

.. autosummary::
   :toctree: generated/
   :template: class.rst

   kernel_approximation.AdditiveChi2Sampler
   kernel_approximation.Nystroem
   kernel_approximation.RBFSampler
   kernel_approximation.SkewedChi2Sampler

.. _kernel_ridge_ref:

:mod:`sklearn.kernel_ridge` Kernel岭回归
========================================================

.. automodule:: sklearn.kernel_ridge
   :no-members:
   :no-inherited-members:

**用户指南:** 参见:ref:`kernel_ridge`了解进一步的细节部分.

.. currentmodule:: sklearn

.. autosummary::
   :toctree: generated/
   :template: class.rst

   kernel_ridge.KernelRidge

.. _lda_ref:

:mod:`sklearn.discriminant_analysis`: 判别分析
===========================================================

.. automodule:: sklearn.discriminant_analysis
   :no-members:
   :no-inherited-members:

**用户指南:** 参见:ref:`lda_qda`了解进一步的细节部分.

.. currentmodule:: sklearn

.. autosummary::
   :toctree: generated
   :template: class.rst

   discriminant_analysis.LinearDiscriminantAnalysis
   discriminant_analysis.QuadraticDiscriminantAnalysis


.. _learning_curve_ref:

:mod:`sklearn.learning_curve` 学习曲线评价
=======================================================

.. automodule:: sklearn.learning_curve
   :no-members:
   :no-inherited-members:

.. currentmodule:: sklearn

.. autosummary::
   :toctree: generated/
   :template: function.rst

   learning_curve.learning_curve
   learning_curve.validation_curve

.. _linear_model_ref:

:mod:`sklearn.linear_model`: 广义线性模型
======================================================

.. automodule:: sklearn.linear_model
   :no-members:
   :no-inherited-members:

**用户指南:** 参见:ref:`linear_model`了解进一步的细节部分.

.. currentmodule:: sklearn

.. autosummary::
   :toctree: generated/
   :template: class.rst

   linear_model.ARDRegression
   linear_model.BayesianRidge
   linear_model.ElasticNet
   linear_model.ElasticNetCV
   linear_model.Lars
   linear_model.LarsCV
   linear_model.Lasso
   linear_model.LassoCV
   linear_model.LassoLars
   linear_model.LassoLarsCV
   linear_model.LassoLarsIC
   linear_model.LinearRegression
   linear_model.LogisticRegression
   linear_model.LogisticRegressionCV
   linear_model.MultiTaskLasso
   linear_model.MultiTaskElasticNet
   linear_model.MultiTaskLassoCV
   linear_model.MultiTaskElasticNetCV
   linear_model.OrthogonalMatchingPursuit
   linear_model.OrthogonalMatchingPursuitCV
   linear_model.PassiveAggressiveClassifier
   linear_model.PassiveAggressiveRegressor
   linear_model.Perceptron
   linear_model.RandomizedLasso
   linear_model.RandomizedLogisticRegression
   linear_model.RANSACRegressor
   linear_model.Ridge
   linear_model.RidgeClassifier
   linear_model.RidgeClassifierCV
   linear_model.RidgeCV
   linear_model.SGDClassifier
   linear_model.SGDRegressor
   linear_model.TheilSenRegressor

.. autosummary::
   :toctree: generated/
   :template: function.rst

   linear_model.lars_path
   linear_model.lasso_path
   linear_model.lasso_stability_path
   linear_model.orthogonal_mp
   linear_model.orthogonal_mp_gram


.. _manifold_ref:

:mod:`sklearn.manifold`: 多方面的学习
==========================================

.. automodule:: sklearn.manifold
   :no-members:
   :no-inherited-members:

**用户指南:** 参见:ref:`manifold`了解进一步的细节部分.

.. currentmodule:: sklearn

.. autosummary::
    :toctree: generated
    :template: class.rst

    manifold.LocallyLinearEmbedding
    manifold.Isomap
    manifold.MDS
    manifold.SpectralEmbedding
    manifold.TSNE

.. autosummary::
    :toctree: generated
    :template: function.rst

    manifold.locally_linear_embedding
    manifold.spectral_embedding


.. _metrics_ref:

:mod:`sklearn.metrics`: 指标
===============================

参见:ref:`model_evaluation` 选择并 :ref:`metrics` 了解进一步的细节部分.

.. automodule:: sklearn.metrics
   :no-members:
   :no-inherited-members:

.. currentmodule:: sklearn

Model Selection Interface
-------------------------
参见:ref:`scoring_parameter` 部分用户指南进一步了解.

.. autosummary::
   :toctree: generated/
   :template: function.rst

   metrics.make_scorer
   metrics.get_scorer

Classification metrics
----------------------

参见:ref:`classification_metrics` 部分用户指南进一步了解


.. autosummary::
   :toctree: generated/
   :template: function.rst

   metrics.accuracy_score
   metrics.auc
   metrics.average_precision_score
   metrics.brier_score_loss
   metrics.classification_report
   metrics.confusion_matrix
   metrics.f1_score
   metrics.fbeta_score
   metrics.hamming_loss
   metrics.hinge_loss
   metrics.jaccard_similarity_score
   metrics.log_loss
   metrics.matthews_corrcoef
   metrics.precision_recall_curve
   metrics.precision_recall_fscore_support
   metrics.precision_score
   metrics.recall_score
   metrics.roc_auc_score
   metrics.roc_curve
   metrics.zero_one_loss
   metrics.brier_score_loss

Regression metrics
------------------

参见:ref:`regression_metrics` 部分用户指南进一步了解


.. autosummary::
   :toctree: generated/
   :template: function.rst

   metrics.explained_variance_score
   metrics.mean_absolute_error
   metrics.mean_squared_error
   metrics.median_absolute_error
   metrics.r2_score

Multilabel ranking metrics
--------------------------
参见:ref:`multilabel_ranking_metrics` 部分用户指南进一步了解


.. autosummary::
   :toctree: generated/
   :template: function.rst

   metrics.coverage_error
   metrics.label_ranking_average_precision_score
   metrics.label_ranking_loss


Clustering metrics
------------------

参见:ref:`clustering_evaluation` 部分用户指南进一步了解


.. automodule:: sklearn.metrics.cluster
   :no-members:
   :no-inherited-members:

.. currentmodule:: sklearn

.. autosummary::
   :toctree: generated/
   :template: function.rst

   metrics.adjusted_mutual_info_score
   metrics.adjusted_rand_score
   metrics.completeness_score
   metrics.homogeneity_completeness_v_measure
   metrics.homogeneity_score
   metrics.mutual_info_score
   metrics.normalized_mutual_info_score
   metrics.silhouette_score
   metrics.silhouette_samples
   metrics.v_measure_score

Biclustering metrics
--------------------

参见:ref:`biclustering_evaluation` 部分用户指南进一步了解.

.. currentmodule:: sklearn

.. autosummary::
   :toctree: generated/
   :template: function.rst

   metrics.consensus_score


Pairwise metrics
----------------

参见:ref:`metrics` 部分用户指南进一步了解 .

.. automodule:: sklearn.metrics.pairwise
   :no-members:
   :no-inherited-members:

.. currentmodule:: sklearn

.. autosummary::
   :toctree: generated/
   :template: function.rst

   metrics.pairwise.additive_chi2_kernel
   metrics.pairwise.chi2_kernel
   metrics.pairwise.distance_metrics
   metrics.pairwise.euclidean_distances
   metrics.pairwise.kernel_metrics
   metrics.pairwise.linear_kernel
   metrics.pairwise.manhattan_distances
   metrics.pairwise.pairwise_distances
   metrics.pairwise.pairwise_kernels
   metrics.pairwise.polynomial_kernel
   metrics.pairwise.rbf_kernel
   metrics.pairwise.laplacian_kernel
   metrics.pairwise_distances
   metrics.pairwise_distances_argmin
   metrics.pairwise_distances_argmin_min


.. _mixture_ref:

:mod:`sklearn.mixture`: 高斯混合模型
===============================================

.. automodule:: sklearn.mixture
   :no-members:
   :no-inherited-members:

**用户指南:** 参见:ref:`mixture`了解进一步的细节部分.

.. currentmodule:: sklearn

.. autosummary::
   :toctree: generated/
   :template: class.rst

   mixture.GMM
   mixture.DPGMM
   mixture.VBGMM


.. _multiclass_ref:

:mod:`sklearn.multiclass`: 多级和多级分类
===================================================================

.. automodule:: sklearn.multiclass
   :no-members:
   :no-inherited-members:

**用户指南:** 参见:ref:`multiclass`了解进一步的细节部分.

.. currentmodule:: sklearn

.. autosummary::
    :toctree: generated
    :template: class.rst

    multiclass.OneVsRestClassifier
    multiclass.OneVsOneClassifier
    multiclass.OutputCodeClassifier

.. _naive_bayes_ref:

:mod:`sklearn.naive_bayes`: 贝叶斯
=======================================

.. automodule:: sklearn.naive_bayes
   :no-members:
   :no-inherited-members:

**用户指南:** 参见:ref:`naive_bayes`了解进一步的细节部分.

.. currentmodule:: sklearn

.. autosummary::
   :toctree: generated/
   :template: class.rst

   naive_bayes.GaussianNB
   naive_bayes.MultinomialNB
   naive_bayes.BernoulliNB


.. _neighbors_ref:

:mod:`sklearn.neighbors`: 最近邻
===========================================

.. automodule:: sklearn.neighbors
   :no-members:
   :no-inherited-members:

**用户指南:** 参见:ref:`neighbors`了解进一步的细节部分.

.. currentmodule:: sklearn

.. autosummary::
   :toctree: generated/
   :template: class.rst

   neighbors.NearestNeighbors
   neighbors.KNeighborsClassifier
   neighbors.RadiusNeighborsClassifier
   neighbors.KNeighborsRegressor
   neighbors.RadiusNeighborsRegressor
   neighbors.NearestCentroid
   neighbors.BallTree
   neighbors.KDTree
   neighbors.LSHForest
   neighbors.DistanceMetric
   neighbors.KernelDensity

.. autosummary::
   :toctree: generated/
   :template: function.rst

   neighbors.kneighbors_graph
   neighbors.radius_neighbors_graph

.. _neural_network_ref:

:mod:`sklearn.neural_network`: 神经网络模型
=====================================================

.. automodule:: sklearn.neural_network
   :no-members:
   :no-inherited-members:

**用户指南:** 参见:ref:`neural_network`了解进一步的细节部分.

.. currentmodule:: sklearn

.. autosummary::
   :toctree: generated/
   :template: class.rst

   neural_network.BernoulliRBM


.. _calibration_ref:

:mod:`sklearn.calibration`: 概率校准
===================================================

.. automodule:: sklearn.calibration
   :no-members:
   :no-inherited-members:

**用户指南:** 参见:ref:`calibration`了解进一步的细节部分.

.. currentmodule:: sklearn

.. autosummary::
   :toctree: generated/
   :template: class.rst

   calibration.CalibratedClassifierCV


.. autosummary::
   :toctree: generated/
   :template: function.rst

   calibration.calibration_curve


.. _cross_decomposition_ref:

:mod:`sklearn.cross_decomposition`:正交分解
=======================================================

.. automodule:: sklearn.cross_decomposition
   :no-members:
   :no-inherited-members:

**用户指南:** 参见:ref:`cross_decomposition`了解进一步的细节部分.

.. currentmodule:: sklearn

.. autosummary::
   :toctree: generated/
   :template: class.rst

   cross_decomposition.PLSRegression
   cross_decomposition.PLSCanonical
   cross_decomposition.CCA
   cross_decomposition.PLSSVD


.. _pipeline_ref:

:mod:`sklearn.pipeline`: Pipeline管道
=================================

.. automodule:: sklearn.pipeline
   :no-members:
   :no-inherited-members:

.. currentmodule:: sklearn

.. autosummary::
   :toctree: generated/
   :template: class.rst

   pipeline.Pipeline
   pipeline.FeatureUnion

.. autosummary::
   :toctree: generated/
   :template: function.rst

   pipeline.make_pipeline
   pipeline.make_union


.. _preprocessing_ref:

:mod:`sklearn.preprocessing`: 预处理和标准化
=============================================================

.. automodule:: sklearn.preprocessing
   :no-members:
   :no-inherited-members:

**用户指南:** 参见:ref:`preprocessing`了解进一步的细节部分.

.. currentmodule:: sklearn

.. autosummary::
   :toctree: generated/
   :template: class.rst

   preprocessing.Binarizer
   preprocessing.FunctionTransformer
   preprocessing.Imputer
   preprocessing.KernelCenterer
   preprocessing.LabelBinarizer
   preprocessing.LabelEncoder
   preprocessing.MultiLabelBinarizer
   preprocessing.MaxAbsScaler
   preprocessing.MinMaxScaler
   preprocessing.Normalizer
   preprocessing.OneHotEncoder
   preprocessing.PolynomialFeatures
   preprocessing.RobustScaler
   preprocessing.StandardScaler

.. autosummary::
   :toctree: generated/
   :template: function.rst

   preprocessing.add_dummy_feature
   preprocessing.binarize
   preprocessing.label_binarize
   preprocessing.maxabs_scale
   preprocessing.minmax_scale
   preprocessing.normalize
   preprocessing.robust_scale
   preprocessing.scale


.. _random_projection_ref:

:mod:`sklearn.random_projection`: 随机投影
===================================================

.. automodule:: sklearn.random_projection
   :no-members:
   :no-inherited-members:

**用户指南:** 参见:ref:`random_projection`了解进一步的细节部分.

.. currentmodule:: sklearn

.. autosummary::
   :toctree: generated/
   :template: class.rst

   random_projection.GaussianRandomProjection
   random_projection.SparseRandomProjection

.. autosummary::
   :toctree: generated/
   :template: function.rst

   random_projection.johnson_lindenstrauss_min_dim


.. _semi_supervised_ref:

:mod:`sklearn.semi_supervised` Semi-Supervised 学习
========================================================

.. automodule:: sklearn.semi_supervised
   :no-members:
   :no-inherited-members:

**用户指南:** 参见:ref:`semi_supervised`了解进一步的细节部分.

.. currentmodule:: sklearn

.. autosummary::
   :toctree: generated/
   :template: class.rst

   semi_supervised.LabelPropagation
   semi_supervised.LabelSpreading


.. _svm_ref:

:mod:`sklearn.svm`: 支持向量机
===========================================

.. automodule:: sklearn.svm
   :no-members:
   :no-inherited-members:

**用户指南:** 参见:ref:`svm`了解进一步的细节部分.

Estimators估计
----------

.. currentmodule:: sklearn

.. autosummary::
   :toctree: generated/
   :template: class.rst

   svm.SVC
   svm.LinearSVC
   svm.NuSVC
   svm.SVR
   svm.LinearSVR
   svm.NuSVR
   svm.OneClassSVM

.. autosummary::
   :toctree: generated/
   :template: function.rst

   svm.l1_min_c

低级别的方法
-----------------

.. autosummary::
   :toctree: generated
   :template: function.rst

   svm.libsvm.fit
   svm.libsvm.decision_function
   svm.libsvm.predict
   svm.libsvm.predict_proba
   svm.libsvm.cross_validation


.. _tree_ref:

:mod:`sklearn.tree`: 决策树
===================================

.. automodule:: sklearn.tree
   :no-members:
   :no-inherited-members:

**用户指南:** 参见:ref:`tree`了解进一步的细节部分.

.. currentmodule:: sklearn

.. autosummary::
   :toctree: generated/
   :template: class.rst

   tree.DecisionTreeClassifier
   tree.DecisionTreeRegressor
   tree.ExtraTreeClassifier
   tree.ExtraTreeRegressor

.. autosummary::
   :toctree: generated/
   :template: function.rst

   tree.export_graphviz


.. _utils_ref:

:mod:`sklearn.utils`: 公共类
===============================

.. automodule:: sklearn.utils
   :no-members:
   :no-inherited-members:

**开发指南:** 参见:ref:`developers-utils` 页了解特征详细信息.

.. currentmodule:: sklearn

.. autosummary::
   :toctree: generated/
   :template: function.rst

   utils.check_random_state
   utils.estimator_checks.check_estimator
   utils.resample
   utils.shuffle
