# Swedish Complex Word Identification Dataset

A dataset of 4,238 Swedish words (lemmas) with four annotated lexical complexity levels.
The dataset was developed for Complex Word Identification (CWI) and Automatic Text Simplification (ATS) tasks.

## Complexity Levels

### Simple words:
- Level 1: corresponds to language proficiency of a basic user
- Level 2: corresponds to language proficiency of an independent user

### Complex words:
- Level 3: corresponds to language proficiency of a proficient user
- Level 4: corresponds to language proficiency of a native speaker

## Format
Each line contains one lemma and its complexity level separated by a tab:
``` 
disk	1
omfattning	3
oklar	2
...
```

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
