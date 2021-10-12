# Meetup Oct 2021, XGBoost  

 * Presented in a paper for the first time in 2016.  
   - https://arxiv.org/pdf/1603.02754.pdf 
   - Tianqi Chen and Carlos Guestrin, XGBoost: A Scalable Tree Boosting System.  

### Overview   

XGBoost is used primarily on tabular data or on structured data kept in databases.  XGBoost provides a paper and open-source library with optimization routines. After the paper and software was unveiled, many top Kaggle competitions for tabular data used XGBoost alone or with natural language processing for text data to win.  X stands for extreme gradient descent.  Library allows easy way to process large dataset and run the job in parallel on multiple CPUs. Processing time decreases almost linearly with additional CPUs.  Boosting is a supervised learning task.  Common uses are regression (predict sales price) and category identification.  Category text names are numericalized in "embeddings".  Example, (low, medium, high) values can be encoded as (0, 1, 2).

Fastbook chp9: Tabular Data Deep Dive

### Boosting vs Random Forest  
\(from XGBOOST docs:  https://xgboost.readthedocs.io/en/latest/tutorials/rf.html\)
"XGBoost is normally used to train gradient-boosted decision trees and other gradient boosted models. Random Forests use the same model representation and inference, as gradient-boosted decision trees, but a different training algorithm. One can use XGBoost to train a standalone random forest or use random forest as a base model for gradient boosting."   

Boosting trees learn sequentially. Earlier trees fit simpler models.  Later trees input resulting errors and fit complex models for finer predictions.  The "Boosting" is used to describe interdependent trees model.  


### SGBoost software library - supports multiple languages  
Python Dask (parallel) application available.  

### Diagrams of note:  

refers to paper:  

### My contact  
Jennifer E. Yoon  github: https://github.com/JennEYoon/  
email:  jenneyoon@gmail.com  
