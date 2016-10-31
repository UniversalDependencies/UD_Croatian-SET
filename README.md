# Universal Dependencies for Croatian

### Training set.

Contains 5,792 sentences (127,894 tokens) from two domains:

1. Sentences 1-3557: Newspaper text from the [Southeast European Times](http://en.wikipedia.org/wiki/Southeast_European_Times) news website, obtained from the [SETimes parallel corpus](http://nlp.ffzg.hr/resources/corpora/setimes/). This part of the treebank is built on top of the [SETimes.HR dependency treebank of Croatian](https://github.com/ffnlp/sethr).
2. Sentences 3558-5792: Text from various [Croatian web sources](http://nl.ijs.si/isjt14/proceedings/isjt2014_10.pdf).

### Development set.

Contains 200 sentences (4,823 words) of newspaper text from the Croatian SETimes.

### Test set.

Contains 297 sentences (6,306 tokens) from three domains:

1. Sentences 1-100: newspaper text, 
2. Sentences 101-200: Wikipedia, 
3. Sentences 201-297: web sources.

### Details

Sentence and word segmentation was manually checked. The treebank does not include multiword tokens. No language-specific features and relations were used. The POS tags and features were converted from [Multext East v4](http://nlp.ffzg.hr/data/tagging/msd-hr.html) and manually checked. The syntactic annotation was done manually.

When using the Croatian UD treebank, please cite the following paper:

* Željko Agić and Nikola Ljubešić. 2015. [Universal Dependencies for Croatian (that work for Serbian, too).](http://aclweb.org/anthology/W/W15/W15-5301.pdf). In Proc. BSNLP, pp. 1--8 ([bib](http://aclweb.org/anthology/W/W15/W15-5301.bib)).

See file LICENSE.txt for further licensing information.

### Changelog

2016-10-31

* added 2235 new sentences to the training set, and 97 new sentences to the test set, from various Croatian web sources



=== Machine-readable metadata =================================================
Documentation status: stub
Data source: semi-automatic
Data available since: UD v1.1
License: CC BY-SA 4.0
Genre: news web wiki
Contributors: Agić, Željko; Ljubešić, Nikola
===============================================================================
