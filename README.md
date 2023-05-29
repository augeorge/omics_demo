# omics_demo


August George, 2023

Demo notebook to explore an OMICS dataset related to diabetes: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE9006 
- transcriptomics: complete set of RNA transcripts produced by the genome under a certain condition or cell type. 



This notebook goes through different data science processes: 
* problem description - builing a predctive model to classify diabetes state (healthy, type1, type2) from blood samples
* data collection and preprocessing from the GEO database
* exploratory data analysis with descriptive statistics
* feature engineering with correlation ranking using random forest, and UMAP featurization
* modeling comparison using Grid Search and Support Vector Machine, Random Forest, Logistic Regression, XGBoost, and Deep Neural Network. This also including over sampling (SMOTE) for under represented training dataset.
* analysis using test performance metrics like F1 score, accuracy, precision, and recall. 

Given a sparse and noisey dataset (~100 samples, ~20k features), several predictive models were generated with an accuracy of ~75%. 

Given the preliminary nature of this work, more effort will be needed to improve accuracy and robustness. 

Some possible areas for future work include: collecting more data, better featurization, and extended model tuning. 
