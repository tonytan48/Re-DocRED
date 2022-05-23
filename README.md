# Re-DocRED Dataset

DocRED is a widely used benchmark for document-level relation extraction. However, the DocRED dataset contains a significant percentage of false negative examples (incomplete annotation). We revised 4,053 documents in the DocRED dataset and resolved its problems. We released this dataset as: Re-DocRED dataset.

The Re-DocRED Dataset resolved the following problems of DocRED:
1. Resolved the incompleteness problem by supplementing large amounts relationtion triples.
2. Addressed the logical inconsistencies in DocRED.
3. Corrected the coreferential errors within DocRED.

# Statistics of Re-DocRED
|  | Re-DocRED|
|  | #Train  | #Dev  |  #Test  |
| :---:   | :-: | :-: |:-: |
| # Documents | 3,053 | 500 |  500 |
| # Avg. Triples | 28.1 | 34.6 |  34.9 |
| # Avg. Entities | 19.4 | 19.4 | 19.6 |
| # Avg. Sents | 7.9 | 8.2 | 7.9 |
