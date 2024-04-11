# NER-g

Datasets used in the articles [Context-sensitive Gender Inference of Named Entities in Text](https://doi.org/10.1016/j.ipm.2020.102423) and [Gender tagging of named entities using retrieval-assisted multi-context aggregation: An unsupervised approach](https://doi.org/10.1002/asi.24735).

## Datasets

This repo contains four datasets:
1. CoNLL-g
2. Wiki-g
3. IEER-g
4. Textbook-g

NER tags for these datasets can be obtained from the sources listed below:

1. [CoNLL](https://github.com/glample/tagger/tree/master/dataset)
2. [Wiki](https://github.com/juand-r/entity-recognition-datasets/tree/master/data/wikigold)
3. [IEER](https://raw.githubusercontent.com/nltk/nltk_data/gh-pages/packages/corpora/ieer.zip)
4. [Textbook NER](https://github.com/das-sudeshna/textbook-ner) (gold standard subset)

## Format

The files are in CoNLL format: each line contains one token and its corresponding gender label separated by a tab. Document boundaries are denoted by blank lines. 

### Tag set:
1. `O` - `Out` (not part of `PERSON` named entity)
2. `F` - `Female`
3. `M` - `Male`
4. `A` - `Ambiguous`

## Pre-processing & Annotation

Annotated using the IO tagging scheme.

For details, please refer to Section 3 of the article.

## Citing

If you find this dataset useful, please cite:

```
@article{das2023gender,
  title={Gender tagging of named entities using retrieval-assisted multi-context aggregation: An unsupervised approach},
  author={Das, Sudeshna and Paik, Jiaul H},
  journal={Journal of the Association for Information Science and Technology},
  volume={74},
  number={4},
  pages={461--475},
  year={2023},
  doi="https://doi.org/10.1002/asi.24735",
  url="https://asistdl.onlinelibrary.wiley.com/doi/abs/10.1002/asi.24735"
  publisher={Wiley Online Library}
}
```

```
@article{DAS2021102423,
title = "Context-sensitive gender inference of named entities in text",
journal = "Information Processing & Management",
volume = "58",
number = "1",
pages = "102423",
year = "2021",
issn = "0306-4573",
doi = "https://doi.org/10.1016/j.ipm.2020.102423",
url = "http://www.sciencedirect.com/science/article/pii/S0306457320309171",
author = "Sudeshna Das and Jiaul H Paik"
}
```
