# Re-DocRED Dataset

This repository contains the dataset of our EMNLP 2022 research paper [Revisiting DocRED – Addressing the False Negative Problem
in Relation Extraction](https://arxiv.org/pdf/2205.12696.pdf). 

DocRED is a widely used benchmark for document-level relation extraction. However, the DocRED dataset contains a significant percentage of false negative examples (incomplete annotation). We revised 4,053 documents in the DocRED dataset and resolved its problems. We released this dataset as: Re-DocRED dataset.

The Re-DocRED Dataset resolved the following problems of DocRED:
1. Resolved the incompleteness problem by supplementing large amounts relationtion triples.
2. Addressed the logical inconsistencies in DocRED.
3. Corrected the coreferential errors within DocRED.

# Statistics of Re-DocRED
The Re-DocRED dataset is located as ./data directory, the statistics of the dataset are shown below:


|  | #Train  | #Dev  |  #Test  |
| :---:   | :-: | :-: |:-: |
| # Documents | 3,053 | 500 |  500 |
| Avg. # Triples | 28.1 | 34.6 |  34.9 |
| Avg. # Entities | 19.4 | 19.4 | 19.6 |
| Avg. # Sents | 7.9 | 8.2 | 7.9 |

# Citation
If you find our work useful, please cite our work as:
```bibtex
@inproceedings{tan2022revisiting,
  title={Revisiting DocRED – Addressing the False Negative Problem in Relation Extraction},
  author={Tan, Qingyu and Xu, Lu and Bing, Lidong and Ng, Hwee Tou and Aljunied, Sharifah Mahani},
  booktitle={Proceedings of EMNLP},
  url={https://arxiv.org/abs/2205.12696},
  year={2022}
}

