# ICU Length of Stay

This project is based loosely on [this Clinical natural language processing tutorial](https://blog.insightdatascience.com/introduction-to-clinical-natural-language-processing-c563b773053f). I will be using the Medical Information Mart for Intensive Care III (MIMIC-III) database. Access to data for this database can be requested at [PhysioNet](mimic.physionet.org/gettingstarted/access/). The MIMIC database consists of data from over 50,000 patients admitted to the Beth Israel Deaconness Medical Center in Boston from 2001 - 2012. 

For this project, I will combine a natural language processing approach (Bag of Words) with additional features, such as physiological measurements and previous admissions, to predict ICU length of stay. For now, I will remove patients who have died from this analysis, although I may revisit and predict death in a separate project in the future. 
