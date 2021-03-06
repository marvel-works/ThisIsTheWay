-   Advanced ML engineering 
    -   Pre-requisites
        -   Please make sure you setup [Anaconda Python](https://www.anaconda.com/download/#linux) 3.6 and [VSCode](https://code.visualstudio.com/docs/python/python-tutorial) (for python with [debugging](https://code.visualstudio.com/docs/python/debugging) extension).
            -   [https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook](https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook)
        - Setup [https://github.com/prompt-toolkit/ptpython](https://github.com/prompt-toolkit/ptpython) to use Python. Dont use "python" from your commandline... use "ptpython".
        -   VSCode debugger setup - [https://code.visualstudio.com/docs/python/python-tutorial\#\_configure-and-run-the-debugger](https://code.visualstudio.com/docs/python/python-tutorial#_configure-and-run-the-debugger)
        -   Code Formatter setup - setup "Black" formatter for python [https://code.visualstudio.com/docs/python/editing#_formatting](https://code.visualstudio.com/docs/python/editing#_formatting) (Show this to your mentor)
    -  [Pandas bootcamp](https://www.udemy.com/course/the-pandas-bootcamp/)
    -  [Sagemaker](https://www.udemy.com/course/aws-machine-learning-a-complete-guide-with-python/)
    - How to structure your code. Scikit Pipelines
        - [Quick intro](https://ramhiser.com/post/2018-04-16-building-scikit-learn-pipeline-with-pandas-dataframe/)
        - [Create different pipelines for different features](https://www.kaggle.com/baghern/a-deep-dive-into-sklearn-pipelines)
        - [ColumnTransformers](https://towardsdatascience.com/columntransformer-meets-natural-language-processing-da1f116dd69f)
        - [Gridsearchcv and pipelines](https://scikit-learn.org/stable/auto_examples/compose/plot_compare_reduction.html#sphx-glr-auto-examples-compose-plot-compare-reduction-py)
    - Feature Engineering **memorise every bit of the following links**
        - Pre Processing  
          - [Pre-processing and normalization](https://scikit-learn.org/stable/modules/classes.html#module-sklearn.preprocessing)
          - [Pre-processing explanation](https://scikit-learn.org/stable/modules/preprocessing.html#preprocessing)
              - [Quantile transforms](https://scikit-learn.org/stable/modules/preprocessing.html#non-linear-transformation)
              - [Scalers](https://scikit-learn.org/stable/auto_examples/preprocessing/plot_all_scaling.html)
              - [Binning](https://scikit-learn.org/stable/modules/preprocessing.html#discretization)
              - [Categorical Features](https://scikit-learn.org/stable/modules/preprocessing.html#preprocessing-categorical-features)
              -  Imputation
                    - [Iterative Imputer](https://scikit-learn.org/stable/modules/generated/sklearn.experimental.enable_iterative_imputer.html#module-sklearn.experimental.enable_iterative_imputer)
                    - [algorithms](https://scikit-learn.org/stable/modules/classes.html#module-sklearn.impute)
                    - [explanation](https://scikit-learn.org/stable/modules/impute.html#impute)
        - Dimensionality reduction  
            - [algorithms](https://scikit-learn.org/stable/modules/classes.html#module-sklearn.decomposition) : especially kernelpca, pca, LDA, sparsepca, truncatedsvd
            - [explanation](https://scikit-learn.org/stable/modules/classes.html#module-sklearn.decomposition)
        - Cross Validation and splitting data
          - [explanation](https://scikit-learn.org/stable/modules/cross_validation.html)
          - [Explanation of Built-in Cross Validation iterators](https://scikit-learn.org/stable/modules/cross_validation.html#cross-validation-iterators)
          - [Plots to check model quality](https://scikit-learn.org/stable/modules/learning_curve.html#learning-curve)
          - [Built-in cross validation algorithms](https://scikit-learn.org/stable/modules/classes.html#module-sklearn.model_selection)  
          - [Holdout vs cross-validation](https://medium.com/@eijaz/holdout-vs-cross-validation-in-machine-learning-7637112d3f8f)
          - [Gridsearchcv and K-fold cross-val](https://www.kaggle.com/questions-and-answers/30560)
          - Memo Question (to follow the rules of a memo) :
                  -   ***"Let's say you have to build a model on Flipkart's order transaction data. Which cross-validation split will you use for Flipkart's order data ? why ? what are the tradeoffs. Write in your own words".***
    -  The only algorithm you will work on here is xgboost. 
       - [What Techniques to Use When](https://machinelearningmastery.com/evaluate-gradient-boosting-models-xgboost-python/)
       -  [Xgboost tuning](https://www.analyticsvidhya.com/blog/2016/03/complete-guide-parameter-tuning-xgboost-with-codes-python/)
       -  [Measuring models](https://medium.com/@wilamelima/metrics-to-measure-machine-learning-model-performance-e8c963665476)
       -  [Early stopping](https://machinelearningmastery.com/avoid-overfitting-by-early-stopping-with-xgboost-in-python/)
        
    - Data and histograms : **important: the visualization graphs in these notebooks are the most important part. not the algorithms** 
        - [Classification Metrics](https://scikit-learn.org/stable/modules/classes.html#classification-metrics) . plot these and compare  validation and out-of-time.
        - [Regression Metrics](https://scikit-learn.org/stable/modules/classes.html#regression-metrics)
        - [Mutual Info Score](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.adjusted_mutual_info_score.html#sklearn.metrics.adjusted_mutual_info_score)
        - [plots](https://scikit-learn.org/stable/modules/classes.html#id3)
        - [Discriminant Analysis](https://scikit-learn.org/stable/modules/classes.html#module-sklearn.discriminant_analysis)
        - [Plotting gridsearchcv](https://scikit-learn.org/stable/auto_examples/model_selection/plot_multi_metric_evaluation.html#sphx-glr-auto-examples-model-selection-plot-multi-metric-evaluation-py)
        -   Memo question (to follow the rules of a memo) :
            -   "**What kind of metrics and graphs will you use to continuously monitor a credit model that is being used for various cities in India. You have to research what are the kind of metrics is popular in research papers, understand and then justify which ones you should use. For example GINI coefficient is one of the no-brainers (or is it?)"**
