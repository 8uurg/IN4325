# Applied NLP Lectures <!-- omit in toc -->
**In progress**

The following sections contain the materials for the eight applied NLP lectures. The applied NLP papers to review each week are listed here as well.

## Table of contents <!-- omit in toc -->

- [NLP resources](#NLP-resources)
  - [Books](#books)
  - [Software](#software)
  - [Datasets](#datasets)
- [Lecture 9: NLP introduction (week 3.5)](#lecture-9-NLP-Introduction)
  - [Recommended readings](#recommended-readings)
- [Lecture 10: Text analysis (week 3.5)](#lecture-10-Syntax)
  - [Recommended readings](#recommended-readings)
  - [:warning: Paper P8 to review](#warning-paper-p8-to-review)
- [Lecture 11: Semantics (week 3.6)](#lecture-11-Semantics)
  - [Recommended readings](#recommended-readings)
  - [:warning: Paper P9 to review](#warning-paper-p9-to-review)
- [Lecture 12: Evaluation NLP (week 3.6)](#lecture-12-Evaluation-NLP)
  - [Recommended readings](#recommended-readings)
  - [:warning: Paper P10 to review](#warning-paper-p10-to-review)
- [Lecture 13: ML for NLP (week 3.7)](#lecture-13-ML-for-NLP)
  - [Recommended readings](#recommended-readings)
  - [:warning: Paper P11 to review](#warning-paper-p11-to-review)
- [Lecture 14: Natural Language Generation  (week 3.7)](#lecture-14-Natural-Language-Generation)
  - [Recommended readings](#recommended-readings)
  - [:warning: Paper P12 to review](#warning-paper-p12-to-review)
- [Lecture 15: NLP annotations (week 3.8)](#lecture-15-NLP-annotations)
  - [Recommended readings](#recommended-readings)
  - [:warning: Paper P13 to review](#warning-paper-p13-to-review)
- [Lecture 16: Word embeddings (week 3.8)](#lecture-16-Word-embeddings)
  - [Recommended readings](#recommended-readings)
  - [:warning: Paper P14 to review](#warning-paper-p14-to-review)

## NLP resources

### Books
Speech and Language Processing (3rd ed.) by Dan Jurafsky and James H. Martin. [Available online](https://web.stanford.edu/~jurafsky/slp3).

Natural language processing, forthcoming with MIT press. [Also online](https://github.com/jacobeisenstein/gt-nlp-class/blob/master/notes/eisenstein-nlp-notes.pdf)

### Software

A number of open-source retrieval toolkits exist. They have different strengths and weaknesses. Which ones are applicable to your project depend to some extent in your *taste* of programming languages and the kind of NLP task you are working on:

### Open Source Natural Language Processing Tools

   - [NLTK](http://www.nltk.org/)
   - [Apache OpenNLP](http://opennlp.apache.org/)
   
   Also in Dutch:
   - [SentiStrength](http://sentistrength.wlv.ac.uk/)
   - [Polyglot](https://polyglot.readthedocs.io/en/latest/)
   - [Clips](https://github.com/clips/pattern)

### Datasets
  - [Movie reviews](http://ai.stanford.edu/~amaas/data/sentiment/)
  - [Stanford sentiment treebank](nlp.stanford.edu/sentiment/code.html)
  - [Sentiment on Twitter](http://help.sentiment140.com/for-students/)
  - [Various text datasets, UCI](https://archive.ics.uci.edu/ml/datasets.html?format=&task=&att=&area=&numAtt=&numIns=&type=text&sort=nameUp&view=table)
- [Stance detection](https://github.com/FakeNewsChallenge/fnc-1)

## Lecture 9: NLP Introduction
Natural Language processing describes computational methods that allow computers to "understand" human communication. This lecture explains what NLP can do, and describes common NLP applications. It describes the kind of tasks that are solved by NLP, and the kind of components/sub-tasks that make it possible for us to solve these tasks.

The slides are [online](https://drive.google.com/open?id=1Lp3RA4Bc7XZqrvEki43U2Vpj9xoC6KLw-JsjPY2jaDc) - **currently from the 2017/18 course edition**. The slides will be updated (as needed) after the lecture.

### Recommended readings

## Lecture 10: Syntax
While human language is very flexible, it does follow certain rules, principles, and processes that govern the structure of sentences. We can use that structure to improve machine understanding of human language, and solve many NLP tasks. Therefore this lecture focuses on syntax, or the structure of sentences.

### Recommended readings
[Large Language Models in Machine Translation ("Stupid Backoff")](http://www.aclweb.org/anthology/D07-1090.pdf)
[NLP book - Part-of-speech tagging:](https://web.stanford.edu/~jurafsky/slp3/10.pdf)

[Stanford parser FAQ:](https://nlp.stanford.edu/software/parser-faq.html)
[Sentiment analysis:](http://www.aclweb.org/anthology/P02-1053.pdf)
### Recommended resources:

[The Dutch translation of the Linguistic Inquiry and Word Count (LIWC) 2007 dictionary:](https://benjamins.com/#catalog/journals/dujal.6.1.04boo/details)

[NLTK Dutch PoS:](http://www.nltk.org/book/ch07.html)

### :warning: Paper P8 to review
[The Social Impact of Natural Language Processing](https://aclanthology.info/papers/P16-2096/p16-2096)

Hovy, Dirk, and Shannon L. Spruit. "The social impact of natural language processing." Proceedings of the 54th Annual Meeting of the Association for Computational Linguistics (Volume 2: Short Papers). Vol. 2. 2016.


## Lecture 11: Semantics
What does it mean, what does it all mean? Unlike controlled languages, natural language is full of ambiguities. Words have multiple meanings, and words are related to each other in different ways. This lecture looks at semantics, or **meaning** in language.

### Recommended readings
[Similarity for news recommender systems](http://navatintarev.com/papers/TintarevMasthoffAH2006.pdf)

[Determining the sentiment of opinions](https://dl.acm.org/citation.cfm?id=1220555)

[Mining and summarizing customer reviews.](https://dl.acm.org/citation.cfm?id=1014073)

### Recommended resources:

[NLTK similarity](http://nltk.github.com/api/nltk.corpus.reader.html?highlight=similarity%23nltk.corpus.reader.WordNetCorpusReader.res_similarity)

[Wordnet::similarity](http://wn-similarity.sourceforge.net/)

[DutchSemCor](http://wordpress.let.vupr.nl/dutchsemcor/)


### :warning: Paper P9 to review
[Offspring from reproduction problems: What replication failure teaches us](https://aclanthology.info/papers/P13-1166/p13-1166)

Fokkens, Antske, et al. "Offspring from reproduction problems: What replication failure teaches us." Proceedings of the 51st Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers). Vol. 1. 2013.


## Lecture 12: Evaluation NLP
<img src="img/overfitting.jpg" width="300px" align="middle">
How do we know if our NLP methods are working well? What are the methods used in NLP, and what are the metrics? How do we interpret these are when are they suitable? This lecture looks at evaluation, and assessing the performance of NLP systems.

### Recommended readings

### :warning: Paper P10 to review
[An investigation into the validity of some metrics for automatically evaluating natural language generation systems](https://dl.acm.org/citation.cfm?id=1667994)
**Sections 2.1-2.3 only (6 pages)**

Reiter, Ehud, and Anja Belz. "An investigation into the validity of some metrics for automatically evaluating natural language generation systems." Computational Linguistics 35.4 (2009): 529-558.

## Lecture 13: ML for NLP
How do we apply what we know about classifiers and regression to NLP problems? What are commonpitfalls and mistakes? Which kind of biases in the data and analysis should we look out for as ethical data scientists? This lecture focuses on applying classical machine learning techniques to natural language processing.

### Recommended readings


### :warning: Paper P11 to review
[Thumbs up?: sentiment classification using machine learning techniques](https://dl.acm.org/citation.cfm?doid=1118693.1118704)

Pang, Bo, Lillian Lee, and Shivakumar Vaithyanathan. "Thumbs up?: sentiment classification using machine learning techniques." Proceedings of the ACL-02 conference on Empirical methods in natural language processing-Volume 10. Association for Computational Linguistics, 2002.

## Lecture 14: Natural Language Generation
So far we've only looked at how to improve computational **understanding** natural language. However in conversational systems (like, but not limited to chatbots), we also might want a computer to communicate with us. There is an area of research that focuses on going from abstract, often rich and complex, representations to natural language that people can understand. In this lecture we will introduce this area of research, which is called Natural Language Generation.

### Recommended readings


### :warning: Paper P12 to review
[MinkApp: generating spatio-temporal summaries for nature conservation volunteers](https://dl.acm.org/citation.cfm?id=2392720)

Tintarev, Nava, et al. "MinkApp: Generating spatio-temporal summaries for nature conservation volunteers." Proceedings of the Seventh International Natural Language Generation Conference. Association for Computational Linguistics, 2012.

## Lecture 15: NLP annotations
The results that we get in many NLP tasks are dependent on the quality and properties of the underlying data. In many (most) cases this is as important as applying the right machine learning techniques. In addition, a lot of the annotation is noisy or simply subjective. In this lecture we discuss the challenges and some of the state-of-the-art solutions.

### Recommended readings

[Exploiting 'subjective' annotations](https://dl.acm.org/citation.cfm?id=1611631)

Reidsma, Dennis. "Exploiting 'subjective' annotations." Proceedings of the Workshop on Human Judgements in Computational Linguistics. Association for Computational Linguistics, 2008.

### :warning: Paper P13 to review

## Lecture 16: Word embeddings
The theory of distributional semantics effectively builds on the principle "A word is known by the company it keeps". In this lecture we will have an introduction to how to learn abstract word vectors that can help us compute the semantic (meaning) distance between different words. We will look at different ways these kinds of vectors can be used, and also talk about some of their limitations.

### Recommended readings


### :warning: Paper P14 to review
[Two/Too Simple Adaptations of Word2Vec for Syntax Problems](https://aclanthology.info/papers/N15-1142/n15-1142)

Ling, Wang, et al. "Two/too simple adaptations of word2vec for syntax problems." Proceedings of the 2015 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies. 2015.
