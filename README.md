# Toxic Comment Classification Challenge
<img src="Toxic Comment Classification Challenge/toxic_comment.png" width="700" height='300'>

### Abstract
- Host : Google Jigsaw.
- Prize : $ 35,000
- Problem : Classification based on Multi-headed model  
- Evaluation : ROC-AUC
- Period : December 19, 2017 ~ March 20, 2018, 11:59 PM UTC


### Description
---
In this competition, you’re challenged to build a **multi-headed model** that’s capable of detecting different types of of toxicity like threats, obscenity, insults, and identity-based hate better than Perspective’s current models. You’ll be using a dataset of comments from Wikipedia’s talk page edits. Improvements to the current model will hopefully help online discussion become more productive and respectful.


### Result

| Submission | CV Mean-Score | Public LB | Rank | Private LB | Rank |
|:----------:|:----------:|:---------:|:----:|:----------:|:----:|
| LR_wordvectorized | 0.989 | 0.5344 | - | 0.5438 | - |
| LR_word&char_vectorized | 0.9792 | 0.9764 | **3100** | 0.9756 | **3196** |
