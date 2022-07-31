---
layout: page
title: Selected Projects
permalink: /projects/
---
## Zero-Shot Dialogue State Tracking with Choice Fusion

The predictions of dialogue states are enhanced in unseen domains based on pre-trained T5 leveraging domain-agnostic training, which fuses candidate choices as knowledge efficiently and achieves outperformed joint goal accuracy on MultiWOZ.

##  Cross-Lingual Commonsense Knowledge Transfer

We develop a three-step model based on XLM-R to minimize the performance gap between English and non-English languages for commonsense question-answering tasks by differentiating language-specific knowledge from commonsense knowledge; improve foreign languages on commonsense reasoning benchmarks.

## Act-Aware Dialogue State Tracking for Multi-Domain Task-Oriented Dialogues

We incorporate dialogue acts to predict categorical and non-categorical slots for ``multi-domain dialogue state tracking (DST)`` leveraging machine reading comprehension approaches. Experimental results demonstrate the overall accuracy improvement on ``MultiWOZ 2.1`` dialogue dataset with reasoning on dialogue states and scalability to new domain ontology. [[Paper](https://www.isca-speech.org/archive/interspeech_2021/su21_interspeech.html)] [[Code](https://github.com/youlandasu/ACT-AWARE-DST)]

## Factual Correction for Knowledge-Driven Dialogues

Factual errors undermine the quality of ``natural dialogue generation (NLG)`` significantly. We propose a transformer-based model for correcting factual errors of knowledge-driven dialogue generation by masking and rewriting. We leverage ``semantic role labeling (SRL)`` and ``named entity recognition (NER)`` to identify factual phrases in utterance and improve the generation results significantly by rewriting with information with grounded knowledge. This work is done during the summer internship at Tencent AI Lab supervised by Dr. Kun Xu and Dr. Linfeng Song.

## Joint Intent Detection and Slot Filling for Spoken Language Understanding

We model spoken language understanding as a joint task based on ``LSTM`` decoders and ``conditional random fields (CRF)``, leveraging semantic representations of utterance intents as knowledge for sequential slot labeling, and show improvement of accuracy on both tasks. 

## Neural Text Generation for Food Service Natural Language Understanding

Promising results are shown on text generation with neural ``hidden semi-Markov models (HSMM)`` against models trained on the generation from weighted ``context free grammars (CFG)`` for improving food service ``natural language understanding (NLU)``. This work is done during the summer internship at Interactions, LLC, and is supervised by Dr. John Chen. Our poster was awarded second place on the Natural Language, Dialog and Speech (NDS) Symposium at [The New York Academy of Sciences](https://www.nyas.org/). [[News](https://twitter.com/interactionsco/status/1198963196117299202)]

## Natural Language Processing Pipeline for Customer Service Automation

We implement segmentation and part-of-speech tagging to extract information from customer service conversations in mandarin, and fill structured information into designed semantic frames to automate customer service for express delivery.

## Deep Learning for Spontaneous Speech Recognition

Improve keyword spotting in spontaneous conversational speech with ``Bi-LSTM - HMM`` based acoustic models with non-uniform ``boosted minimum classification error (BMCE)`` criterion with Kaldi.

