# Papers and Resources for Low Resource Machine Translation 

There are a wide variety of techniques to employ when trying to create a new machine translation model for a low resource language or improve an existing baseline. The applicability of these techniques generally depend on the availability of parallel and monolingual corpora for the target language and the availability of parallel corpora for related languages/ domains.

## Common scenarios

### Scenario #1 - You don't have any parallel data for the source-target language pair, you only have monolingual target data

Papers:

- [Phrase-Based & Neural Unsupervised Machine Translation](https://aclweb.org/anthology/D18-1549)
- [Word Translation Without Parallel Data](https://arxiv.org/abs/1710.04087)
- [Unsupervised Statistical Machine Translation](https://paperswithcode.com/paper/unsupervised-statistical-machine-translation)

Resources/ examples:

- [Implementation - unsupervised MT (Facebook)](https://github.com/facebookresearch/UnsupervisedMT)

### Scenario #2 - You only have a small amount of parallel data for the source-target language pair, but you have lots of parallel data for a related source-target language pair

Papers:

- [Rapid Adaptation of Neural Machine Translation to New Languages](https://arxiv.org/abs/1808.04189)
- [Neural Machine Translation with Pivot Languages](https://arxiv.org/abs/1611.04928)
- [Transfer Learning across Low-Resource, Related Languages for Neural Machine Translation](https://arxiv.org/abs/1708.09803)
- [Transfer Learning for Low-Resource Neural Machine Translation](https://arxiv.org/pdf/1604.02201v1.pdf)
- [Trivial Transfer Learning for Low-Resource Neural Machine Translation](https://arxiv.org/abs/1809.00357)

Resources/ examples:

- [Implementation - rapid adaptation methods (Neubig)](https://github.com/neubig/rapid-adaptation)
- [Video - rapid adaptation methods (Neubig)](https://vimeo.com/305207187)
- [Implementation - transfer learning for low resource languages (Zorph)](https://github.com/isi-nlp/Zoph_RNN)

### Scenario #3 - You only have a small amount of parallel data for the source-target language pair, but you have lots of monolingual data for the target and/or source language

Papers:

- [Improving Neural Machine Translation Models with Monolingual Data](https://arxiv.org/abs/1511.06709)
- [Iterative Back-Translation for Neural Machine Translation](https://www.semanticscholar.org/paper/Iterative-Back-Translation-for-Neural-Machine-Hoang-Koehn/0669f0a031cfaada55841e5962eb6796d4e94971)
- [Generalizing Back-Translation in Neural Machine Translation](https://www.semanticscholar.org/paper/Generalizing-Back-Translation-in-Neural-Machine-Gra%C3%A7a-Kim/9a127a2903fb3dff2a480e82dd18fcf331333caa)
- [Improving Back-Translation with Uncertainty-based Confidence Estimation](https://www.semanticscholar.org/paper/Improving-Back-Translation-with-Uncertainty-based-Wang-Liu/dae35736329852c83d32cefd66448dc73cd73368)
- [Neural Machine Translation of Low-Resource and Similar Languages with Backtranslation](https://www.semanticscholar.org/paper/Neural-Machine-Translation-of-Low-Resource-and-with-Przystupa-Abdul-Mageed/19d9226a98066ef32b4c727a9992dbfbec7dbffc)

Resources/ examples:

- [Video - About iterative backtranslation and dealing with "place" issues](https://youtu.be/5A6MlGfZni0)

### Scenario #4 - You have a small amount of parallel data for the source-target language pair, but you also have a lot of parallel data for other language pairs

Papers:

- [Massively Multilingual Neural Machine Translationin the Wild: Findings and Challenges](https://arxiv.org/pdf/1907.05019.pdf)
- [Multilingual Neural Machine Translation With Soft Decoupled Encoding](https://arxiv.org/abs/1902.03499)
- [Meta-Learning for Low-Resource Neural Machine Translation](https://arxiv.org/pdf/1808.08437.pdf)

Resources/ examples:

- [Video - Meta-learning for low resource MT](https://vimeo.com/306147573)
- [Blog - Exploring Massively Multilingual, Massive Neural Machine Translation](https://ai.googleblog.com/2019/10/exploring-massively-multilingual.html)
- [Blog - Zero-Shot Translation with Google’s Multilingual Neural Machine Translation System](https://ai.googleblog.com/2016/11/zero-shot-translation-with-googles.html)

## Miscellaneous other resources

General papers and resources about African languages or African language MT:

- [Towards Neural Machine Translation for African Languages](https://arxiv.org/abs/1811.05467)
- [A Focus on Neural Machine Translation for African Languages](https://arxiv.org/abs/1906.05685)
- [Parallel Corpora for bi-lingual English-Ethiopian Languages Statistical Machine Translation](https://ethionlp.github.io/publication/2018-08-23-solomon_mt)

## Data gathering, corpus creation:

- [cocohub.cc, tools for crowdsourcing parallel corpora](https://cocohub.cc/)

## Research languages, language families, populations, known language resources online, etc. via:

- [OLAC](http://www.language-archives.org/)
- [Glottolog](https://glottolog.org/)
- [Ethnologue](https://www.ethnologue.com/) (Free up to a certain amount of clicks, but many Universities have subscriptions, if you happen to be affiliated with one)
