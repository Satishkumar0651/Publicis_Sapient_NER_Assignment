# Named Entity Recognition

## About the Dataset

The `ner_dataset.csv` file maps sentence number (Sentence #) to the first word (Word) of the respective sentence. Each word is then mapped to its respective POS tag (POS) and NER tag (Tag). For this case study, ignore the POS tag column. For every sentence, only consider the word and its NER tag.

### Sample mapping of a sentence:
Today O
Micheal B-PER
Jackson I-PER
and O
Mark B-PER
ate O
lasagna O
at O
New B-geo
Delhi I-geo
. O

### Sequence tagging scheme: IOB2
- **I** : Inside – word is inside a chunk
- **O** : Outside – word belongs to no chunk
- **B** : Beginning – word is the beginning of a chunk

### Columns:
- **Sentences #** : Sentence number
- **Word** : Word to be classified
- **POS** : POS tags for respective word
- **Tag** : NER tags for respective word

## Probable Tasks
The following tasks are provided as direction:
1. **Divide the dataset into 3 parts**:
    - Train
    - Validation
    - Test (at least 20%)
   
2. **Identify the metrics for evaluating model's performance.**

3. **Pre-process the data** such that words of each sentence are mapped to their respective NER tags.

4. **Develop a baseline model** which takes a sentence (list of words) as input and predicts the NER tag for each word in that sentence.

5. **Identify the shortcomings of the baseline model.**

6. **Develop a new model** that overcomes the shortcomings of the baseline model.

7. **Identify future scope** to further optimize the model.

## System Design Tasks
1. **Design system architecture** to deploy the ML model in production.
   
2. **How do you perform a canary build?**
   
3. **What should be the strategy for ML Model Monitoring?**

4. **How do you perform load and stress testing?**
   
5. **How do you track, monitor, and audit ML training?**
   
6. **Design a framework for continuous delivery and automation of machine learning tasks.**

## Deliverables:
- **Jupyter notebook** (or equivalent) showcasing your work
- **PowerPoint presentation** clearly explaining the approach and findings.
- **System design architecture** (if applicable) and explanations.
