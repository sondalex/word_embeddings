
# Word embeddings - GloVE and Word2vec

The purpose of this project is to draw insights on GloVe 840B Common
Crawl pretrained word embeddings (@ Pennington, Socher, and Manning
2015) and Word2Vec Google News pretrained word embeddings (Mikolov et
al. 2013).

The struture is the following:

-   `utils/`: contains utilities used in the analysis
-   `analysis.ipynb` A quarto file containing the analysis.
-   `data/` : The data folder contains only the tokens from GloVe 300
    dense word embeddings pretrained on 840 billion tokens.

## Requirements:

Downloading Peter Norvig merged sample of Google books unigram
http://norvig.com/google-books-common-words.txt

``` console
wget http://norvig.com/google-books-common-words.txt -P data/
```

Tokens from Word2vec embeddings are required. I made a repo which
contains those tokens only.

They should be downloaded and move to the data folder:

``` console
wget  https://raw.githubusercontent.com/sondalex/word2vec-tokens/master/word2vec_text_GloVe_format.wordsonly.txt -P data/
```

## References

<div id="refs" class="references csl-bib-body hanging-indent">

<div id="ref-mikolovWord2vecToolComputing2013" class="csl-entry">

Mikolov, Thomas, Kai Chen, Greg Corrado, and Jeffrey Dean. 2013.
“Word2vec - Tool for Computing Continous Distributed Representations of
Words - <span class="nocase">Pre-trained</span> Word and Phrase
Vectors.” Data Set GoogleNews-vectors-negative300.bin.gz.
<https://code.google.com/archive/p/word2vec/>.

</div>

<div id="ref-penningtonGloVeGlobalVectorsdata" class="csl-entry">

Pennington, Jeffrey, Richard Socher, and Christopher D. Manning. 2015.
“GloVe: Global Vectors for Word Representation.” Data set Common Crawl
(300D) pre-trained word vectors on 840B tokens.
<https://nlp.stanford.edu/projects/glove/>.

</div>

</div>
