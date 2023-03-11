## Human language cognition & LLM

### Cloze Distillation: Improving Neural Language Models with Human Next-Word Prediction

[Tiwalayo Eisape](https://aclanthology.org/people/t/tiwalayo-eisape/), [Noga Zaslavsky](https://aclanthology.org/people/n/noga-zaslavsky/), [Roger Levy](https://aclanthology.org/people/r/roger-levy/)

paper: https://aclanthology.org/2020.conll-1.49

abstract

> Contemporary autoregressive language models (LMs) trained purely on corpus data have been shown to capture numerous features of human incremental processing. 
>
> However, past work has also suggested dissociations between corpus probabilities and human next-word predictions. Here we evaluate several state-of-the-art language models for their match to human next-word predictions and to reading time behavior from eye movements. 
>
> We then propose a novel method for distilling the linguistic information implicit in human linguistic predictions into pre-trained LMs: Cloze Distillation. 
>
> We apply this method to a baseline neural LM and show potential improvement in reading time prediction and generalization to held-out human cloze data.

### Understanding and Improving Word Embeddings through a Neuroscientific Lens

Sam Fereidooni, Viola Mocz, Dragomir Radev, Marvin Chun

doi: https://doi.org/10.1101/2020.09.18.304436

Abstract

> Despite the success of models making use of word embeddings on many natural language tasks, these models often perform significantly worse than humans on several natural language understanding tasks. 
>
> This difference in performance motivates us to ask: 
>
> > (1) if existing word vector representations have any basis in the brain’s representational structure for individual words, 
> >
> > and (2) whether features from the brain can be used to improve word embedding model performance, defined as their correlation with human semantic judgements. 
>
> To answer the first question, we compare the representational spaces of existing word embedding models with that of brain imaging data through representational similarity analysis. 
>
> We answer the second question by using regression-based learning to constrain word vectors to the features of the brain imaging data, thereby determining if these modified word vectors exhibit increased performance over their unmodified counterparts. To collect semantic judgements as a measure of performance, we employed a novel multi-arrangement method. 
>
> Our results show that there is variance in the representational space of the brain imaging data that remains uncaptured by word embedding models, and that brain imaging data can be used to increase their coherence with human performance.



### A Multimodal LDA Model integrating Textual, Cognitive and Visual Modalities

[Stephen Roller](https://aclanthology.org/people/s/stephen-roller/), [Sabine Schulte im Walde](https://aclanthology.org/people/s/sabine-schulte-im-walde/)

> Recent investigations into grounded models of language have shown that holistic views of language and perception can provide higher performance than independent views. In this work, we improve a two-dimensional multimodal version of Latent Dirichlet Allocation (Andrews et al., 2009) in various ways.
>
> (1) We outperform text-only models in two different evaluations, and demonstrate that low-level visual features are directly compatible with the existing model. 
>
> (2) We present a novel way to integrate visual features into the LDA model using unsupervised clusters of images. The clusters are directly interpretable and improve on our evaluation tasks. 
>
> (3) We provide two novel ways to extend the bimodal models to support three or more modalities. We f indthat the three-, four-, and five-dimensional models significantly outperform models using only one or two modalities, and that nontextual modalities each provide separate, disjoint knowledge that cannot be forced into a shared, latent structure.



### Learning Multimodal Word Representation via Dynamic Fusion Methods

[Shaonan Wang](https://arxiv.org/search/cs?searchtype=author&query=Wang%2C+S), [Jiajun Zhang](https://arxiv.org/search/cs?searchtype=author&query=Zhang%2C+J), [Chengqing Zong](https://arxiv.org/search/cs?searchtype=author&query=Zong%2C+C)

> Multimodal models have been proven to outperform text-based models on learning semantic word representations. Almost all previous multimodal models typically treat the representations from different modalities equally. However, it is obvious that information from different modalities contributes differently to the meaning of words. This motivates us to build a multimodal model that can dynamically fuse the semantic representations from different modalities according to different types of words. To that end, we propose three novel dynamic fusion methods to assign importance weights to each modality, in which weights are learned under the weak supervision of word association pairs. The extensive experiments have demonstrated that the proposed methods outperform strong unimodal baselines and state-of-the-art multimodal models.