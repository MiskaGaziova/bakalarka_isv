# bakalarka_isv

data_annotsv: 
- AnnotSV.r2yo0QbkMl_full.tsv súbor s génovými a CNV anotáciami (z nástroja AnnotSV)
- train_val_test obsahuje trénovacie, validačné a testovacie dáta

Codes in Jupyter Notebook:
- data_prepare.ipynb, ingest_data.ipynb – vytvorenie datasetov a nových atribútov
- attribute_correlations.ipynb – porovnávanie atribútov
- unclassified_regions.ipynb – hľadanie oblastí neklasifikovaných CNV
- train_evaluate_models.ipynb, model_evaluation.ipynb – vyhodnotenie presností
modelov
- porovnanie_ClassifyCNV_AnnotSV.ipynb – vyhodnotenie presností ClassifyCNV
a AnnotSV na testovacej sade
