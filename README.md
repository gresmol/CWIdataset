# Complex Word Identification Dataset for Swedish

A dataset of 4,238 Swedish words (lemmas) with four annotated lexical complexity levels.
The dataset was developed for Complex Word Identification (CWI) and Automatic Text Simplification (ATS) tasks.

## Complexity Levels

### Simple words:
- Level 1: corresponds to language proficiency of a basic user or CEFR levels A1, A2
- Level 2: corresponds to language proficiency of an independent user or CEFR levels B1, B2

### Complex words:
- Level 3: corresponds to standard Swedish (CEFR C1, C2)
- Level 4: corresponds to complex Swedish (words that are considered to be complex for native speakers as well)

## Format
Each line contains one lemma and its complexity level separated by a tab:
``` 
disk	1
omfattning	3
oklar	2
...
```

## Evaluation
The dataset was evaluated by one native speaker and one intermediate learner of Swedish.

The dataset was evaluated in terms of fuzzy match (allows a missmatch of one difficulty level) and exact match (the levels are the same).

The results show both high annotation accuracy and high inter-annotator agreement.

Match | Learner | Native Speaker
------------ | ------------ | -------------
Fuzzy | 0.745 | 0.99
Exact | 0.755 | 0.985

## Sources
Swedish CWI dataset was compiled from various sources of simple, standard and complex Swedish. 
The basis for simple words is Rivstart coursebook dicionaries for second language learners of Swedish.
The basis for complex words is standard Swedish words that do not appear in simple English datasets.

### List of sources
- [Rivstart](https://www.nok.se/Laromedel/-Laromedelswebb-/-B23-/-Lararwebb-/Rivstart/-Flikar-/A1A2/Textbok/Ordlista/)
- [8 sidor](http://8sidor.se)
- [LäsBart](http://linghub.org/metashare/b3cb2a5a5a6811e29a5400504503039cf4797cdb8997419a8ee6d0969356fc51)
- [Aligned Corpus](https://www.semanticscholar.org/paper/Towards-a-Corpus-of-Easy-to-Read-Authority-Web-Rennes-J%C3%B6nsson/12b78567d03f3ee42f56d03b9ce5e77947ebdf36)
- [SUC](https://spraakbanken.gu.se/en/resources/suc2)
- [Ordtestet](	https://ord.relaynode.info/)

## Further reading
The dataset was developed as a part of [Complex Word Identification for Swedish](https://www.semanticscholar.org/paper/Complex-Word-Identification-for-Swedish-Smolenska/8728f63b7a08b1c9668bef101ba36a7950aa2432) Master thesis.
More information about the dataset collection can be found in the thesis.
