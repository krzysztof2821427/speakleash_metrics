# speakleash_metrics
The aim of the research was to define metrics allowing to identify low-quality documents in [SpeakLeash](https://github.com/speakleash) datasets. Analyzed are documents from *religia* domain - the results should be revised and adjusted to fit general purpose (and support all domains).
The report consists of 5 parts:
* *DataFrame_prep.ipynb* - preliminary data preparation, i.e. text data and meatadata downloading and shaping them in DataFrame format.
* *Metrics_analysis.ipynb* - adding new metrics: additional parts of speech, readability indices, and calculated ratios (to check for absolute values rather than word-count dependant).
* *Metrics_summary.ipynb* - adding charts: for data correlation and distribution, checking for outliers, extracting documents affected, and final conclusion.
DataFrames for this job (saved to .pkl files) can be found on Google Drive [here](https://drive.google.com/drive/folders/1qb8Cs27i_9zgw5f1vDGME1vBPXYwhJzG?usp=sharing), of which *df_feat_added_full.pkl* is the final and the most complete DataFrame.
* *Text_similarity_Levensthein.ipynb* - edit distance calculation for documents of similar length, to remove duplicates and almost duplicates (of low training value).
* *CamelCase_detection.ipynb* - looking for camelCase words.

DataFrames for this job (saved to .pkl files) can be found on Google Drive [here](https://drive.google.com/drive/folders/1qb8Cs27i_9zgw5f1vDGME1vBPXYwhJzG?usp=sharing), of which *df_feat_added_full.pkl* is the final and the most complete DataFrame.

Feel free to share what you think!
