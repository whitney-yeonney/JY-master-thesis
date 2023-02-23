# biomedical-openie
A Study on BERT based medical Open Information Extraction and Relation Prediction

## Abstract
This study presents a BERT based biomedical open information extraction system and event type prediction methods. Our model can extract information automatically from unstructured large corpus without human supervision. We aim to extract all possible relational tuples from the corpus, which is do not need a pre-specified relationship type. In this research, with the help of the BioBERT, we added generated decoded sequence as the input of the next encoding step. With this approach we managed to extract variable number of diverse S-P-O(Subject-Predicate-Object) relational tuple from unstructured sentence. Additionally, we obtained P-O (predicate sense, object head) pairs from extracted tuple and clustering generated extractions for identify the key information of the sentence more effectively.
