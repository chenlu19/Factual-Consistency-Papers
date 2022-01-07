# Factual Consistency Papers

A paper list on Factual Consistency

## Contents

* [Survey Paper](#1-survey-paper)
* [Model](#2-model)
  * [Architectures](#21-architectures)
  * [Generation Strategies](#22-generation-strategies)
  * [Training Strategies](#23-training-strategies)
  * [Different Stages](#24-different-stages)
  * [Different Granularities](#25-different-granularities)
  * [Different Views](#26-different-views)
* [Evaluation](#3-evaluation)
  * [Word Overlap-based Metrics](#31-word-overlap-based-metrics)
  * [Edit-distance-based Metrics](#32-edit-distance-based-metrics)
  * [Model-based Metrics](#33-model-based-metrics)
  * [Embedding-based Metrics](#34-embedding-based-metrics)
* [Resource](#4-resource)
* [Analysis](#5-analysis)

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
* [Wizard of wikipedia: Knowledge-powered conversational agents](https://arxiv.org/pdf/1811.01241.pdf)

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

#### Knowledge-enhanced Generation
* [Wizard of wikipedia: Knowledge-powered conversational agents](https://arxiv.org/pdf/1811.01241.pdf)
* [Reason first, then respond: Modular Generation for Knowledge-infused Dialogue](https://arxiv.org/pdf/2111.05204.pdf)

#### Lexicon-enhanced Generation
* [Improving lexical choice in neural machine translation](https://aclanthology.org/N18-1031.pdf)



### 2.3 Training Strategies

#### Reinforcement Learning
* [Guiding Extractive Summarization with Question-Answering Rewards](https://arxiv.org/pdf/1904.02321.pdf)
* [Knowledge Graph-Augmented Abstractive Summarization with Semantic-Driven Cloze Reward](https://arxiv.org/pdf/2005.01159.pdf)
* [Optimizing the Factual Correctness of a Summary: A Study of Summarizing Radiology Reports](https://arxiv.org/pdf/1911.02541.pdf)
* [Refine and Imitate: Reducing Repetition and Inconsistency in Persuasion Dialogues via Reinforcement Learning and Human Demonstration](https://arxiv.org/pdf/2012.15375.pdf)
* [Hallucinated but Factual! Inspecting the Factuality of Hallucinations in Abstractive Summarization](https://arxiv.org/pdf/2109.09784.pdf)
* [Multi-reward reinforced summarization with saliency and entailment](https://arxiv.org/pdf/1804.06451.pdf)

#### Multi-task Learning
* [Soft layer-specific multi-task summarization with entailment and question generation](https://arxiv.org/pdf/1805.11004.pdf)
* [Entity-level Factual Consistency of Abstractive Text Summarization](https://aclanthology.org/2021.eacl-main.235.pdf)
* [Towards Improving Abstractive Summarization via Entailment Generation](https://www.aclweb.org/anthology/W17-4504.pdf)
* [Ensure the Correctness of the Summary: Incorporate Entailment Knowledge into Abstractive Sentence Summarization](https://www.aclweb.org/anthology/C18-1121.pdf)
* [Dialogue Inspectional Summarization with Factual Inconsistency Awareness](https://arxiv.org/pdf/2111.03284.pdf)

#### Contrastive Learning
* [CLIFF: Contrastive Learning for Improving Faithfulness and Factuality in Abstractive Summarization](https://aclanthology.org/2021.emnlp-main.532.pdf)
* [Neural Path Hunter: Reducing Hallucination in Dialogue Systems via Path Grounding](https://arxiv.org/pdf/2104.08455.pdf)
* [CO2Sum:Contrastive Learning for Factual-Consistent Abstractive Summarization](https://arxiv.org/abs/2112.01147)
* [Improving factual consistency of abstractive summarization via question answering](https://arxiv.org/pdf/2105.04623.pdf)
* [Improving Factual Consistency of Abstractive Summarization on Customer Feedback](https://arxiv.org/pdf/2106.16188.pdf)

#### Unlikelihood Training
* [Don’t Say That! Making Inconsistent Dialogue Unlikely with Unlikelihood Training](https://arxiv.org/pdf/1911.03860.pdf)

#### Other Loss / Reward-based
#### - Entailment Reward
* [Ensure the Correctness of the Summary: Incorporate Entailment Knowledge into Abstractive Sentence Summarization](https://www.aclweb.org/anthology/C18-1121.pdf)
#### - Consistency / Hallucination Loss
* [Encouraging Lexical Translation Consistency for Document-Level Neural Machine Translation](https://aclanthology.org/2021.emnlp-main.262.pdf)
* [Detecting Hallucinated Content in Conditional Neural Sequence Generation](https://arxiv.org/pdf/2011.02593.pdf)
* [Learn to resolve conversational dependency: A consistency training framework for conversational question answering](https://aclanthology.org/2021.acl-long.478.pdf)
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
* [Improving Factual Consistency of Abstractive Summarization on Customer Feedback](https://arxiv.org/pdf/2106.16188.pdf)
* [Hallucinated but Factual! Inspecting the Factuality of Hallucinations in Abstractive Summarization](https://arxiv.org/pdf/2109.09784.pdf)
* [Dialogue Inspectional Summarization with Factual Inconsistency Awareness](https://arxiv.org/pdf/2111.03284.pdf)

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
* [Multi-reward reinforced summarization with saliency and entailment](https://arxiv.org/pdf/1804.06451.pdf)

#### QA-based
* [Guiding Extractive Summarization with Question-Answering Rewards](https://arxiv.org/pdf/1904.02321.pdf)
* [Multi-Fact Correction in Abstractive Text Summarization](https://aclanthology.org/2020.emnlp-main.749.pdf)
* [Knowledge Graph-Augmented Abstractive Summarization with Semantic-Driven Cloze Reward](https://arxiv.org/pdf/2005.01159.pdf)

#### Reconstruction-based
* [Math Word Problem Generation with Mathematical Consistency and Problem Context Constraints](https://arxiv.org/pdf/2109.04546.pdf)

  

## 3 Evaluation

### 3.1 Word Overlap-based Metrics

- [BLEU: a Method for Automatic Evaluation of Machine Translation](https://aclanthology.org/P02-1040.pdf) (2004, BLEU)
- [METEOR: An Automatic Metric for MT Evaluation with Improved Correlation with Human Judgments](https://aclanthology.org/W05-0909.pdf) (2005, METEOR)
- [Meteor Universal: Language Specific Translation Evaluation for Any Target Language](https://www.cs.cmu.edu/~alavie/METEOR/pdf/meteor-1.5.pdf) (2014, METEOR 1.5)
- [Meteor++ 2.0: Adopt Syntactic Level Paraphrase Knowledge into Machine Translation Evaluation](https://aclanthology.org/W19-5357.pdf) (2019, METEOR++ 2.0)
- [ROUGE: A Package for Automatic Evaluation of Summaries](https://aclanthology.org/W04-1013.pdf) (2004, ROUGE)
- [Entity-level Factual Consistency of Abstractive Text Summarization](https://arxiv.org/abs/2102.09130) (2021)

### 3.2 Edit-distance-based Metrics

- [A Study of Translation Edit Rate with Targeted Human Annotation](https://aclanthology.org/2006.amta-papers.25.pdf) (2006, TER)
- [ITER: Improving Translation Edit Rate through Optimizable Edit Costs](https://aclanthology.org/W18-6455.pdf) (2018, ITER)
- [CDER: Efficient MT Evaluation Using Block Movements](https://aclanthology.org/E06-1031.pdf) (2006, CDER)
- [CharacTer: Translation Edit Rate on Character Level](https://aclanthology.org/W16-2342.pdf) (2016, CharacTer)
- [EED: Extended Edit Distance Measure for Machine Translation](https://aclanthology.org/W19-5359.pdf) (2019, EED)

### 3.3 Model-based Metrics

- [BEER: BEtter Evaluation as Ranking](https://aclanthology.org/W14-3354.pdf) (2014, BEER)
- [Blend: a Novel Combined MT Metric Based on Direct Assessment — CASICT-DCU submission to WMT17 Metrics Task](https://aclanthology.org/W17-4768.pdf) (2017, Blend)
- [RUSE: Regressor Using Sentence Embeddings for Automatic Machine Translation Evaluation](https://aclanthology.org/W18-6456.pdf) (2018, RUSE)
- [Question Answering as an Automatic Evaluation Metric for News Article Summarization](https://aclanthology.org/N19-1395/) (2019, APES)
- [Assessing The Factual Accuracy of Generated Text](https://arxiv.org/abs/1905.13322) (2019)
- [FEQA: A Question Answering Evaluation Framework for Faithfulness Assessment in Abstractive Summarization](https://aclanthology.org/2020.acl-main.454.pdf) (2020, FEQA)
- [ESTIME: Estimation of Summary-to-Text Inconsistency by Mismatched Embeddings](https://aclanthology.org/2021.eval4nlp-1.10.pdf) (2020, ESTIME)
- [Asking and Answering Questions to Evaluate the Factual Consistency of Summaries](https://aclanthology.org/2020.acl-main.450.pdf) (2020, QAGS)
- [FFCI: A Framework for Interpretable Automatic Evaluation of Summarization](https://arxiv.org/pdf/2011.13662.pdf) (2021, FFCI)
- [Q2: Evaluating Factual Consistency in Knowledge-Grounded Dialogues via Question Generation and Question Answering](https://aclanthology.org/2021.emnlp-main.619.pdf) (2021, Q2)
- [QuestEval: Summarization Asks for Fact-based Evaluation](https://aclanthology.org/2021.emnlp-main.529/) (2021, QuestEval)
- [Improving factual consistency of abstractive summarization via question answering](https://arxiv.org/pdf/2105.04623.pdf) (2021, QUALS)
- [SummaC: Re-Visiting NLI-based Models for Inconsistency Detection in Summarization](https://arxiv.org/pdf/2111.09525.pdf) (2021, SUMMAC)

### 3.4 Embedding-based Metrics

- [MEANT 2.0: Accurate semantic MT evaluation for any output language](https://aclanthology.org/W17-4767.pdf) (2017, MEANT 2.0)
- [Accurate semantic textual similarity for cleaning noisy parallel corpora using semantic machine translation evaluation metric: The NRC supervised submissions to the Parallel Corpus Filtering task](https://aclanthology.org/W18-6481.pdf) (2018, YISI-1)
- [From word embeddings to document distances](https://proceedings.mlr.press/v37/kusnerb15.pdf) (2015, WMD)
- [WMDO: Fluency-based Word Mover’s Distance for Machine Translation Evaluation](https://aclanthology.org/W19-5356.pdf) (2019, WMDO)
- [Sentence Mover’s Similarity: Automatic Evaluation for Multi-Sentence Texts](https://aclanthology.org/P19-1264.pdf) (2019, SMS)
- [BERTScore: Evaluating Text Generation with BERT](https://arxiv.org/pdf/1904.09675) (2019, BERTScore)
- [MoverScore: Text generation evaluating with contextualized embeddings and earth mover distance](https://aclanthology.org/D19-1053.pdf) (2019, MoverScore)
- [Fill in the BLANC: Human-free quality estimation of document summaries](https://aclanthology.org/2020.eval4nlp-1.2.pdf) (2020, BLANC)
- [Play the Shannon Game With Language Models: A Human-Free Approach to Summary Evaluation](https://arxiv.org/abs/2103.10918) (2021, Shannoon Score)



## 4 Resource

* [GENIE: A Leaderboard for Human-in-the-Loop Evaluation of Text Generation](https://arxiv.org/pdf/2101.06561.pdf)
* [I like fish , especially dolphins : Addressing Contradictions in Dialogue Modeling](https://arxiv.org/pdf/2012.13391.pdf)
* [Wizard of wikipedia: Knowledge-powered conversational agents](https://arxiv.org/pdf/1811.01241.pdf)

  

## 5 Analysis

* [Understanding the Behaviour of Neural Abstractive Summarizers using Contrastive Examples](https://www.aclweb.org/anthology/N19-1396.pdf)
* [Retrieval Augmentation Reduces Hallucination in Conversation](https://arxiv.org/pdf/2104.07567.pdf)
