<h1>Summary of Jupyter Notebooks</h1><br>

For implementing hierarchical classification of articles, a classifier was implemented at each parent node.
Dataset used: train_data3.csv

Jupyter Notebooks:
	
<span style="color:blue">transforming_data_classification.ipynb</span>: 
    -- code for transforming data from table to the desired format in the dataframe
    
<span style="color:blue">Hierarchical_classification_classifier_per_parent_1.ipynb</span>: 
	-- FEATURES: title, preprocessed content, publisherId, length_preprocessed_content
MODEL: Logistic Regression and OneClassSVM

<span style="color:blue"> Hierarchical_classification_classifier_per_parent_2.ipynb</span>: 
	-- FEATURES: title, preprocessed content, publisherId, length_preprocessed_content
 MODEL: Logistic Regression only (ignored rows having only one class to be predicted)
 
 <span style="color:blue">Hierarchical_classification_classifier_per_parent_3_wo_pubid.ipynb</span>:
 	-- FEATURES: title, preprocessed content, length_preprocessed_content
 MODEL: Logistic Regression only (ignored rows having only one class to be predicted)


