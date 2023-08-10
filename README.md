# Deep Learning Techniques for Named Entity Recognition applied to Brazilian Legal Documents

This article explores the application of deep learning techniques for named entity recognition (NER) in Brazilian legal documents, which is an essential task in Natural Language Processing (NLP).

The report can be seen here: [Report](Deep Learning Techniques for Named Entity Recognition applied to Brazilian Legal Documents.pdf).

[LeNER-Br] (https://github.com/peluz/lener-br) (Luz de Araujo et al., 2018) is a manually annotated Portuguese language data set for the recognition of named entities, specifically focused on legal documents. It includes named entities related to legislations and legal
cases, aiming to enhance the extraction of lawful knowledge.

This project leveraged 3 different approaches to perform the taks:

- [X] BERT

    - [X] [Bert - Finetune](BERT/1.%20Finetune%20BERT%20-%20NER%20Brazilian%20legal%20documents.ipynb).
    - [X] [Bert - Load finetuned model](BERT/2.%20Load%20Finetuned%20BERT%20-%20NER%20Brazilian%20legal%20documents.ipynb).

- [X] [LSTM](LSTM/LSTM%20-%20NER%20Brazilian%20legal%20documents.ipynb).

- [X] [spaCy](spaCy/SPACY%20-%20NER%20Brazilian%20legal%20documents.ipynb).
