# This repository is part of the master thesis in MSc in Data Science of Chrysogonidis Georgios with title 'Prediction of student performance using dynamic machine learning models'.


More specifically, this repository contains:

1. The files 'data' and 'embeddings' that include all the datasets and the embeddings needed to run the model.

2. The ipynb notebook named as 'Thesis_model.ipynb' that contains the final model architecture of the thesis.

3. The ipynb notebook named as 'skill_names_embeddings.ipynb' that contains the generation of Word2Vec embeddings. 

   Note that the txt files of 100d and 300d embeddings are missing because it's size is enormous.

4. The ipynb notebook named as 'lineplot_of_folds_vs_auc_in_corrected_and_updated.ipynb' that contains the thesis lineplots' generation.
 
5. The excel files 'folds_vs_auc_in_corrected.xlsx' and 'folds_vs_auc_in_updated.xlsx' that contain the mean validation auc of both 'Assistments2009_corrected' and 'Assistments2009_updated' per fold. These files are needed in 4.

6. The ipynb notebook named as 'skill_name_fasttext_emb.ipynb' contains the FastText embeddings generation for all the datasets.

7. A document file named as 'Skill ids and skill names corrections.docx' that summarizes the preprocessing that has been done in all datasets.
