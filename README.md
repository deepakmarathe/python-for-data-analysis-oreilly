# Python for data analysis - oreilly

Python is suitable for research and prototyping as well as building the production systems.
why maintain 2 development environments when one will suffice ?

## Why not python : 
   
    - interpreted, so substantially slower than code written in a compiled language like Java/C++.
    - tradeoff : programmer time is more valuable than CPU time. 
    - highly concurrent, multithreaded apps particularly applications with many CPU bound threads.
    - GIL : Global Interpreter Lock - mechanism preventing interpreter from executing more than one python instruction at a time. 
    - Python C uses native multitasking(C/C++) to run code in parallel without impacted by GIL, as long as they do not need to regularly interact with python objects.
    
## Essential Python Libraries  
* NumPy : Numerical Python
    - data structures, algorithms and library glue needed for most scientific apps.    
      
        - fast and efficient multidimentional array object *ndarray*
        - functions for performing element-wise computations with arrays or mathematical operations between arrays
        - tools for reading and writing array based data sets to disk.
        - linear algebra operations, Fourier transform and random number generation
        - mature C api to enable python extensions and native C/C++ code to access NumPy's data structures and computational facilities. 

    - fast array processing capabilities 
    - used as a container to pass around data between algorithms and libraries. 

* Pandas : fast, easy, expressive data structures and functions. 
    - panel data (Pandas) or Python data analysis (Pandas)
    - works with structured/tabulated data
    - DataFrame : tabular, column-oriented data structure with both row and column labels. 
    - combines high performance array-computing ideas of NumPy with the flexible data manipulation capabilities of spreadsheets and relational databases. 
    - sophisticated indexing functionality : reshape, slice and dice, aggregations and subset selection. 
    
        - data structures with labelled axes
        - integrated time series functionality
        - handle both time series and non-time series data
        - arithmetic operations and reductions(like summing across axes) would pass on the metadata
        - Flexible handling of missing data
        - merge and other relations operations 

* matplotlib : most popular library for producing plots and other 2D visualizations
    - safe choice as default visualization tool
    
* IPython and Jupyter : interactive python interpreter
    - execute explore workflow, rather than edit-compile-run workflow 
    - easy access to OS shell and file system.
    - language agnostic interactive computing tool
    - support for over 40 programing languages
    - interactive and exploratory computing 
    - data exploration and visualization 
    
* SciPy : collection of packages addressing standard problem domains in scientific computing. 
    
        scipy.integrate : numerical integration routines and differential equation solvers
        scipy.linalg : linear algebra routined and matrix decompositions extending beyond those provided by numpy.linalg
        scipy.optimize : function optimizers (minimizers) and root finding algorithms
        scipy.signal : signal processing tools
        scipy.sparse : sparse metrics and sparse linear systems solvers. 
        scipy.special : wrapper around SPECFUN, a fortran library implementing many common mathematical functions, such as the gamma function 
        scipy.stats : continuous and discrete probability distributions(density functions, samplers, continuous distribution functions), statistical tests and more descriptive statistics
        scipy.weave : tool for using inline C++ code to accelerate array computations. 

* scikit-learn : general purpose Machine Learning toolkit for python programmers. 
        
        Classification : SVM, nearest neighbours, random forest etc
        Regression : Lasso, Ridge regression, Logistic etc.
        Clustering : k-mean, spectral clustering
        Dimensionality reduction : PCA, feature selection, matrix factorization 
        Model selection : grid search, cross-validation, metrics
        preprocessing : feature extraction, normalization
        
* statsmodels : statistical analysis package
    - regression models : linear regression, generalized linear models, robust linear models, linear mixed effects models etc. 
    - ANOVA (analysis of variance)
    - Time series analysis : AR, ARMA, ARIMA, VAR and other models. 
    - nonparametric methods : kernel density estimation, kernel regression.
    - visualization of statistical model results
   
        
    
    
    