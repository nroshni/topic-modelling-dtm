
# topic-modelling-dtm

Topic Modelling using DTM (Dynamic Topic Models) on NYT article dataset.

## Getting Started

1) Download NYT article dataset from https://www.kaggle.com/nzalake52/new-york-times-articles

2) Download Spacy medium english language model: https://spacy.io/usage/models  - OR -
```
pip install spacy
python -m spacy download en_core_web_md
```
3) Download DTM: https://github.com/magsilva/dtm

4) Download the ipython notebook (topic_modelling.ipynb) and do the following:
    - Set NYT data path
    - Set spacy model name (Ex: en, en_core_web_md)
    - Set DTM binary path
    - Download the necessary python packages from the imports

5) Run the ipython.

### Acknowledgments
* https://github.com/RaRe-Technologies/gensim