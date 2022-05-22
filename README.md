# FIND: Human-in-the-Loop Debugging Deep Text Classifiers. EMNLP 2020

**Paper links**: [ArXiv (pre-print)](https://arxiv.org/abs/2010.04987)

## Requirements
- [Python 3.6](https://www.python.org/downloads/release/python-360/)
- Standard machine learning and deep learning modules
	- [tensorflow](https://www.tensorflow.org/) == 1.15.0
	- [keras](https://keras.io/) == 2.2.4
	- [numpy](https://numpy.org/) == 1.18.4
	- [scikit-learn](https://scikit-learn.org/stable/) == 0.21.3
- Interpretability, visualization, and interaction modules
	- [matplotlib](https://matplotlib.org/) == 3.2.1
	- [innvestigate](https://github.com/albermax/innvestigate) == 1.0.8
	- [wordcloud](https://github.com/amueller/word_cloud) == 1.7.0
	- [ipywidgets](https://github.com/jupyter-widgets/ipywidgets) == 7.5.1
- NLP module and word embeddings
	- [spacy](https://spacy.io/)==2.2.4 (en)
	- [GloVe.6B](http://nlp.stanford.edu/data/glove.6B.zip) (300 dimensions)

```commandline
conda install mamba
mamba create -n find-nlp python=3.6 tensorflow-gpu=1.15 keras=2.2.4 numpy=1.18.5 scikit-learn=0.21.3 matplotlib=3.2.1 wordcloud=1.7.0 ipywidgets=7.5.1 spacy=2.2.4
```

Note that the packages with slightly different versions might work as well.

## Datasets
The datasets used in this paper can be downloaded [here](https://drive.google.com/file/d/1yKgNqbli_loWakg0NpZkmfi3jBj_N7FK/view?usp=sharing) as a single zip file.


This is not originally my work, citing Piyawat Lertvittayakumjorn's work on my thesis 
```
@inproceedings{lertvittayakumjorn-etal-2020-find,
    title = "{FIND}: {H}uman-in-the-{L}oop {D}ebugging {D}eep {T}ext {C}lassifiers",
    author = "Lertvittayakumjorn, Piyawat  and
      Specia, Lucia  and
      Toni, Francesca",
    booktitle = "Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing (EMNLP)",
    month = nov,
    year = "2020",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/2020.emnlp-main.24",
    pages = "332--348",
}
```
	
