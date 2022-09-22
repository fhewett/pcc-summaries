# PCC Summaries
Summary data for the Potsdam Commentary Corpus.

## About the data
- The original corpus is the [Potsdam Commentary Corpus](http://angcl.ling.uni-potsdam.de/resources/pcc.html). For more information, please view the [original corpus page](http://angcl.ling.uni-potsdam.de/resources/pcc.html).

- We used the (manual) syntax annotations available with the corpus to split the texts into sentences. 

- We then asked annotators to choose the three most important sentences. The exact wording of the task was as follows: "Read the texts and choose 3 sentences per text, that represent the core of the text. Then, order the sentences according to their importance: label the most important sentence with a `1', the second most important with a `2' and the third with a `3'. In this context, `importance' refers to the informative value of the sentence: is it a core statement, that could possibly be used to summarise the text? Then the sentence is `important'. Sentences which include anaphoric elements (particularly all types of pronouns) can also be chosen. When judging a sentence, you should "mentally" replace all anaphora by their antecedents."

- For a small subset of 30 texts, we got two annotations per text. We harmonised these using a scoring system. The highest ranked sentence was equivalent to 3 points, the second to 2 and the third to 1. The sentence with the most points was then deemed the highest ranked sentence in the harmonised annotation, and so on. Any tied scores were resolved by randomly selecting one of the sentences in the tie. 

## How to cite

If you use these summaries please cite the following paper:

@inproceedings{hewett-stede-2022-extractive,
    author = "Hewett, Freya and Stede, Manfred",
    title = "Extractive summarisation for {G}erman-language data: a text-level approach with discourse features",
    booktitle = "Proceedings of the 29th International Conference on Computational Linguistics (COLING)",
    year = "2022",
    keywords = "",
    note = "To appear"
}

Hewett, F., & Stede, M. (2021). [Automatically evaluating the conceptual complexity of German texts](https://aclanthology.org/2021.konvens-1.23.pdf). *Proceedings of the 17th Conference on Natural Language Processing (KONVENS 2021)*, 228–234.

If you use anything from the original corpus please cite the following paper:

@inproceedings{bourgonje-stede-lrec2020,
    author = "Bourgonje, Peter and Stede, Manfred",
    title = "{The Potsdam Commentary Corpus 2.2: Extending Annotations for Shallow Discourse Parsing}",
    booktitle = "Proceedings of the 12th International Conference on Language Resources and Evaluation (LREC 2020)",
    year = "2020",
    month = "May",
    location = "Marseille, France",
    publisher = "European Language Resources Association (ELRA)",
    address = "Marseille, France",
    keywords = "",
    pdf = "https://www.aclweb.org/anthology/2020.lrec-1.133.pdf"
}



