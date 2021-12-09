# Factual Consistency Papers

A paper list on Factual Consistency

## Contents

* [Survey Paper](#1-survey-paper)
* [Model](#2-model)
  * [Architectures](#21-architectures)
  * [Generation Strategies](#2.2 Generation Strategies)
  * [Training Strategies](#2.3 Training Strategies)
  * [Different Stages](#2.4 Different Stages)
  * [Different Granularities](#2.5 Different Granularities)
  * [Different Views](#2.6 Different Views)

* [Evaluation](#3 Evaluation)
* [Resource](#4 Resource)
* [Analysis](#5 Analysis)

## 1 Survey Paper

* [The Factual Inconsistency Problem in Abstractive Text Summarization: A Survey](https://arxiv.org/pdf/2104.14839.pdf)

  

## 2 Model

### 2.1 Architectures

#### Copy-based

* [Get to the Point: Summarization with Pointer-generator Networks](https://www.aclweb.org/anthology/P17-1099.pdf)

* [On the Faithfulness for E-commerce Product Summarization](https://www.aclweb.org/anthology/2020.coling-main.502.pdf)

#### Attention-based

* [Faithful to the original: Fact-aware neural abstractive summarization](https://ojs.aaai.org/index.php/AAAI/article/view/11912/11771)

* [Enhancing Factual Consistency of Abstractive Summarization](https://aclanthology.org/2021.naacl-main.58.pdf)

* [Mind The Facts: Knowledge-Boosted Coherent Abstractive Text Summarization](https://arxiv.org/pdf/2006.15435.pdf)

* [Encouraging Lexical Translation Consistency for Document-Level Neural Machine Translation](https://aclanthology.org/2021.emnlp-main.262.pdf)

#### Retrieval-augmented

* [Retrieval Augmentation Reduces Hallucination in Conversation](https://arxiv.org/pdf/2104.07567.pdf)

#### Graph-augmented

* [Knowledge Graph-Augmented Abstractive Summarization with Semantic-Driven Cloze Reward](https://arxiv.org/pdf/2005.01159.pdf)

* [Enhancing Factual Consistency of Abstractive Summarization](https://aclanthology.org/2021.naacl-main.58.pdf)

* [Neural Path Hunter: Reducing Hallucination in Dialogue Systems via Path Grounding](https://arxiv.org/pdf/2104.08455.pdf)

  

### 2.2 Generation Strategies

#### Constrained Generation  

* [Constrained Abstractive Summarization: Preserving Factual Consistency with Constrained Generation](https://arxiv.org/pdf/2010.12723.pdf)

#### Integer Linear Programming

* [Discourse Constraints for Document Compression](https://watermark.silverchair.com/coli_a_00004.pdf?token=AQECAHi208BE49Ooan9kkhW_Ercy7Dm3ZL_9Cf3qfKAc485ysgAAAsIwggK-BgkqhkiG9w0BBwagggKvMIICqwIBADCCAqQGCSqGSIb3DQEHATAeBglghkgBZQMEAS4wEQQMGmvXbzzk38iTsUKUAgEQgIICdR0jzH8Geh8MhPIF1zzRLuEWKkHdTezZ0zABo_ABv9rxCoL2KUbn-6iNwNczXTcSkgLIjgr6309OI7a7yTCfSQpmaXcpj4U2oNdLxm9jGFKEJp8eRcMuxeg47UJJf2wF4AdrR-GFfuJ1nzBDPZgkuppKw4OlPbsyDY5ErAyzHtDVFyXRT6aHTYvzeAnOijP3kUHJdWnN_o8HhyAkRsJKhWnxEKC5_KI0CWaLPnX6Wb5VGAQuoIVFHYdb0vv8nZpdV_yWPgW3AbGOWOZfkYVFBB1QlWaLk3G_kkfowSN8SIQ-neei_7XihrhlnFzzwSZL7UzfytPbk_2p35C1GwxCR5-HxAlNmDtgSVE7eJL5rCM0Kfqwos2NGMRFp7zhY5jyuTEA80s-FjXhnI7KQhtSpp45ADEdUOUWtPdIukT3azj9jNA5hIt3F2Ubc8qa8mVoM9tE4HMfYckYP2ioB1k1Mc0k3PRCkfv1horpu3qpy9V0AYzK6EASwiBxulNrkE73HZjyFnqxzSJwfZXb9rCOOotvMXMzRY51faFFV8_u2_WRTZd_O-zapIyOgpBdUdC93P3Bx93xF1LucARGvynL4AHr4H4DgsLzaDrWLcpuprknpxIVjpQPXxIK-GuVRadC-M6RhROreWi9P1a7dK8xAfHoLk_rZzmlp8tWGDCIJ0f_yAVWT76-laquNp0pmbS_20EJiFOkPXIgdiw236_EIGKjp2O3Q4u7J_DGmNkwuUcD8NWlIRLptRfLm6JYINNcbsnTlAZZUd6RgOLEn_eGlcC_YMeUXRsKLk7mMuH0Fa7bNolpSvCM2Qd-DV1i3xvla1lC4GHk)



### 2.3 Training Strategies

#### Reinforcement Learning

* [Guiding Extractive Summarization with Question-Answering Rewards](https://arxiv.org/pdf/1904.02321.pdf)
* [Knowledge Graph-Augmented Abstractive Summarization with Semantic-Driven Cloze Reward](https://arxiv.org/pdf/2005.01159.pdf)

* [Optimizing the Factual Correctness of a Summary: A Study of Summarizing Radiology Reports](https://arxiv.org/pdf/1911.02541.pdf)
* [Refine and Imitate: Reducing Repetition and Inconsistency in Persuasion Dialogues via Reinforcement Learning and Human Demonstration](https://arxiv.org/pdf/2012.15375.pdf)

#### Multi-task Learning

* [Soft layer-specific multi-task summarization with entailment and question generation](https://arxiv.org/pdf/1805.11004.pdf)
* [Entity-level Factual Consistency of Abstractive Text Summarization](https://aclanthology.org/2021.eacl-main.235.pdf)
* [Towards Improving Abstractive Summarization via Entailment Generation](https://www.aclweb.org/anthology/W17-4504.pdf)

* [Ensure the Correctness of the Summary: Incorporate Entailment Knowledge into Abstractive Sentence Summarization](https://www.aclweb.org/anthology/C18-1121.pdf)

#### Contrastive Learning

* [CLIFF: Contrastive Learning for Improving Faithfulness and Factuality in Abstractive Summarization](https://aclanthology.org/2021.emnlp-main.532.pdf)

* [Neural Path Hunter: Reducing Hallucination in Dialogue Systems via Path Grounding](https://arxiv.org/pdf/2104.08455.pdf)

#### Unlikelihood Training

* [Don’t Say That! Making Inconsistent Dialogue Unlikely with Unlikelihood Training](https://arxiv.org/pdf/1911.03860.pdf)

#### Other Loss / Reward-based

#### - Entailment Reward

* [Ensure the Correctness of the Summary: Incorporate Entailment Knowledge into Abstractive Sentence Summarization](https://www.aclweb.org/anthology/C18-1121.pdf)

#### - Consistency / Hallucination Loss

* [Encouraging Lexical Translation Consistency for Document-Level Neural Machine Translation](https://aclanthology.org/2021.emnlp-main.262.pdf)

* [Detecting Hallucinated Content in Conditional Neural Sequence Generation](https://arxiv.org/pdf/2011.02593.pdf)

#### - Reconstruction Loss

* [Math Word Problem Generation with Mathematical Consistency and Problem Context Constraints](https://arxiv.org/pdf/2109.04546.pdf)

#### - Uncertainty Term

* [On hallucination and predictive uncertainty in conditional language generation](https://aclanthology.org/2021.eacl-main.236.pdf)

  

### 2.4 Different Stages

#### Summarizer

* [Soft layer-specific multi-task summarization with entailment and question generation](https://arxiv.org/pdf/1805.11004.pdf)
* [Don’t Say That! Making Inconsistent Dialogue Unlikely with Unlikelihood Training](https://arxiv.org/pdf/1911.03860.pdf)
* [Enhancing Factual Consistency of Abstractive Summarization](https://aclanthology.org/2021.naacl-main.58.pdf)

#### Post-processor

#### - Factual Error Correction

* [Factual Error Correction for Abstractive Summarization Models](https://aclanthology.org/2020.emnlp-main.506.pdf)

* [Multi-Fact Correction in Abstractive Text Summarization](https://aclanthology.org/2020.emnlp-main.749.pdf)

* [Enhancing Factual Consistency of Abstractive Summarization](https://aclanthology.org/2021.naacl-main.58.pdf)

* [Neural Path Hunter: Reducing Hallucination in Dialogue Systems via Path Grounding](https://arxiv.org/pdf/2104.08455.pdf)

#### - Re-ranking by Correctness / Consistency

* [Ranking generated summaries by correctness: An interesting but challenging application for natural language inference](https://www.aclweb.org/anthology/P19-1213.pdf)

* [I like fish , especially dolphins : Addressing Contradictions in Dialogue Modeling](https://arxiv.org/pdf/2012.13391.pdf)

* [Reducing Quantity Hallucinations in Abstractive Summarization](https://arxiv.org/pdf/2009.13312.pdf)

#### Pre-processor

#### - Process Input Data

* [Entity-level Factual Consistency of Abstractive Text Summarization](https://aclanthology.org/2021.eacl-main.235.pdf)

* [A Simple Recipe towards Reducing Hallucination in Neural Surface Realisation](https://www.aclweb.org/anthology/P19-1256.pdf)



### 2.5 Different Granularities

#### Token / Entity-level

* [Mind The Facts: Knowledge-Boosted Coherent Abstractive Text Summarization](https://arxiv.org/pdf/2006.15435.pdf)

* [CLIFF: Contrastive Learning for Improving Faithfulness and Factuality in Abstractive Summarization](https://aclanthology.org/2021.emnlp-main.532.pdf)

* [Multi-Fact Correction in Abstractive Text Summarization](https://aclanthology.org/2020.emnlp-main.749.pdf)

* [Neural Path Hunter: Reducing Hallucination in Dialogue Systems via Path Grounding](https://arxiv.org/pdf/2104.08455.pdf)

* [Entity-level Factual Consistency of Abstractive Text Summarization](https://aclanthology.org/2021.eacl-main.235.pdf)

* [Reducing Quantity Hallucinations in Abstractive Summarization](https://arxiv.org/pdf/2009.13312.pdf)

* [Factual Error Correction for Abstractive Summarization Models](https://aclanthology.org/2020.emnlp-main.506.pdf)

* [Retrieval Augmentation Reduces Hallucination in Conversation](https://arxiv.org/pdf/2104.07567.pdf)
* [Encouraging Lexical Translation Consistency for Document-Level Neural Machine Translation](https://aclanthology.org/2021.emnlp-main.262.pdf)

#### Sequence / Relation or Event-level

* [CLIFF: Contrastive Learning for Improving Faithfulness and Factuality in Abstractive Summarization](https://aclanthology.org/2021.emnlp-main.532.pdf)

* [Knowledge Graph-Augmented Abstractive Summarization with Semantic-Driven Cloze Reward](https://arxiv.org/pdf/2005.01159.pdf)

* [Math Word Problem Generation with Mathematical Consistency and Problem Context Constraints](https://arxiv.org/pdf/2109.04546.pdf)

* [Refine and Imitate: Reducing Repetition and Inconsistency in Persuasion Dialogues via Reinforcement Learning and Human Demonstration](https://arxiv.org/pdf/2012.15375.pdf)

* [Faithful to the original: Fact-aware neural abstractive summarization](https://ojs.aaai.org/index.php/AAAI/article/view/11912/11771)

* [Enhancing Factual Consistency of Abstractive Summarization](https://aclanthology.org/2021.naacl-main.58.pdf)

* [Optimizing the Factual Correctness of a Summary: A Study of Summarizing Radiology Reports](https://arxiv.org/pdf/1911.02541.pdf)

  

### 2.6 Different Views

#### Fact-aware

* [Faithful to the original: Fact-aware neural abstractive summarization](https://ojs.aaai.org/index.php/AAAI/article/view/11912/11771)

* [Enhancing Factual Consistency of Abstractive Summarization](https://aclanthology.org/2021.naacl-main.58.pdf)

* [Mind The Facts: Knowledge-Boosted Coherent Abstractive Text Summarization](https://arxiv.org/pdf/2006.15435.pdf)

* [Refine and Imitate: Reducing Repetition and Inconsistency in Persuasion Dialogues via Reinforcement Learning and Human Demonstration](https://arxiv.org/pdf/2012.15375.pdf)

* [CLIFF: Contrastive Learning for Improving Faithfulness and Factuality in Abstractive Summarization](https://aclanthology.org/2021.emnlp-main.532.pdf)
* [Neural Path Hunter: Reducing Hallucination in Dialogue Systems via Path Grounding](https://arxiv.org/pdf/2104.08455.pdf)
* [Optimizing the Factual Correctness of a Summary: A Study of Summarizing Radiology Reports](https://arxiv.org/pdf/1911.02541.pdf)

#### NLI-based / Entailment-aware

* [Ensure the Correctness of the Summary: Incorporate Entailment Knowledge into Abstractive Sentence Summarization](https://www.aclweb.org/anthology/C18-1121.pdf)
* [Refine and Imitate: Reducing Repetition and Inconsistency in Persuasion Dialogues via Reinforcement Learning and Human Demonstration](https://arxiv.org/pdf/2012.15375.pdf)
* [Ranking generated summaries by correctness: An interesting but challenging application for natural language inference](https://www.aclweb.org/anthology/P19-1213.pdf)

#### QA-based

* [Guiding Extractive Summarization with Question-Answering Rewards](https://arxiv.org/pdf/1904.02321.pdf)
* [Multi-Fact Correction in Abstractive Text Summarization](https://aclanthology.org/2020.emnlp-main.749.pdf)
* [Knowledge Graph-Augmented Abstractive Summarization with Semantic-Driven Cloze Reward](https://arxiv.org/pdf/2005.01159.pdf)

#### Reconstruction-based

* [Math Word Problem Generation with Mathematical Consistency and Problem Context Constraints](https://arxiv.org/pdf/2109.04546.pdf)

  

## 3 Evaluation

* [Entity-level Factual Consistency of Abstractive Text Summarization](https://aclanthology.org/2021.eacl-main.235.pdf)

  

## 4 Resource

* [GENIE: A Leaderboard for Human-in-the-Loop Evaluation of Text Generation](https://arxiv.org/pdf/2101.06561.pdf)

* [I like fish , especially dolphins : Addressing Contradictions in Dialogue Modeling](https://arxiv.org/pdf/2012.13391.pdf)

  

## 5 Analysis

* [Understanding the Behaviour of Neural Abstractive Summarizers using Contrastive Examples](https://www.aclweb.org/anthology/N19-1396.pdf)
* [Retrieval Augmentation Reduces Hallucination in Conversation](https://arxiv.org/pdf/2104.07567.pdf)