# bakalarka_isv

data_annotsv: 
- AnnotSV.r2yo0QbkMl_full.tsv súbor s CNV anotáciami (z nástroja AnnotSV)
- train_val_test obsahuje trénovacie, validačné a testovacie dáta


Codes in Jupyter Notebook:
- data_prepare.ipynb, ingest_data.ipynb – vytvorenie datasetov a nových atribútov
- attribute_correlations.ipynb – porovnávanie atribútov
- unclassified_regions.ipynb – hľadanie oblastí neklasifikovaných CNV
- train_evaluate_models.ipynb, model_evaluation.ipynb – vyhodnotenie presností
modelov
- porovnanie_ClassifyCNV_AnnotSV.ipynb – vyhodnotenie presností ClassifyCNV
a AnnotSV na testovacej sade


Priečinky s výsledkami:
- attributes_selection – tabuľky a grafy vybraných atribútov ako korelujú s klinickým významom (podľa Point-Biserial korelačného koeficientu), ako sa správa
prenosť modelu postupným pridávaním vybratých atribútov
- comparison_attributes_annotsv_full – porovnania atribútov ohodnotením CNV ako celku
    – correlations_attributes – tabuľky a grafy znázorǔjúce korelácie atribútov podľa
Pearsonovho a Point-Biserial korelačného koeficientu
    – correlations_info_train_loss_gain.tsv – komplexné hodnotenie atribútov pre delécie aj duplikácie (p-hodnota podľa Mann-Whitney Testu, Point-Biserial ko-
eficient, min, max, medián, priemer)
- comparison_attributes_annotsv_split – porovnania atribútov génových hodnôt
- models – natrénované modely, tabuľky a vizualizácie presností viacerých modelov na jednotlivých dátových sadách
- test_prediction – tabuľky a vizualizácie predikcií samotného modelu aj klasikifikácií neklasifikovaných CNV
- unclassified_tresholds - grafy vygenerované pri identifikácii neklasifikovaných CNV
- classifyCNV_test – klasifikácie CNV z testovacích sád nástrojom ClassifyCNV
