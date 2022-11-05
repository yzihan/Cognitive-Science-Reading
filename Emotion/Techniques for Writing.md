## Tecniques for Writing

### Automated hate speech detection and the problem of offensive language

abstract

>A key challenge for automatic hate-speech detection on social media is the separation of hate speech from other instances of offensive language. Lexical detection methods tend to have low precision because they classify all messages containing particular terms as hate speech and previous work using supervised learning has failed to distinguish between the two categories. We used a crowd-sourced hate speech lexicon to collect tweets containing hate speech keywords. We use crowd-sourcing to label a sample of these tweets into three categories: those containing hate speech, only offensive language, and those with neither. We train a multi-class classifier to distinguish between these different categories. Close analysis of the predictions and the errors shows when we can reliably separate hate speech from other offensive language and when this differentiation is more difficult. We find that racist and homophobic tweets are more likely to be classified as hate speech but that sexist tweets are generally classified as offensive. Tweets without explicit hate keywords are also more difficult to classify.

### A benchmark for understanding implicit hate speech.

abstract

>Hate speech has grown significantly on social media, causing serious consequences for victims of all demographics. Despite much attention being paid to characterize and detect discriminatory speech, most work has focused on explicit or overt hate speech, failing to address a more pervasive form based on coded or indirect language. To fill this gap, this work introduces a theoretically-justified taxonomy of implicit hate speech and a benchmark corpus with fine-grained labels for each message and its implication. We present systematic analyses of our dataset using contemporary baselines to detect and explain implicit hate speech, and we discuss key features that challenge existing models. This dataset will continue to serve as a useful benchmark for understanding this multifaceted issue.

### Style transfer in text: Exploration and evaluation.

Abstract

> The ability to transfer styles of texts or images, is an important measurement of the advancement of artificial intelligence (AI). However, the progress in language style transfer is lagged behind other domains, such as computer vision, mainly because of the lack of parallel data and reliable evaluation metrics. In response to the challenge of lacking parallel data, we explore learning style transfer from non-parallel data. We propose two models to achieve this goal. The key idea behind the proposed models is to learn separate content representations and style representations using adversarial networks. Considering the problem of lacking principle evaluation metrics, we propose two novel evaluation metrics that measure two aspects of style transfer: transfer strength and content preservation. We benchmark our models and the evaluation metrics on two style transfer tasks: paper-news title transfer, and positive-negative review transfer. Results show that the proposed content preservation metric is highly correlate to human judgments, and the proposed models are able to generate sentences with similar content preservation score but higher style transfer strength comparing to auto-encoder.

### Will I sound like me? improving persona consistency in dialogues through pragmatic selfconsciousness. 

Abstract

> We explore the task of improving persona consistency of dialogue agents. Recent models tackling consistency often train with additional Natural Language Inference (NLI) labels or attach trained extra modules to the generative agent for maintaining consistency. However, such additional labels and training can be demanding. Also, we find even the best-performing persona-based agents are insensitive to contradictory words. Inspired by social cognition and pragmatics, we endow existing dialogue agents with public self-consciousness on the fly through an imaginary listener. Our approach, based on the Rational Speech Acts framework (Frank and Goodman, 2012), can enforce dialogue agents to refrain from uttering contradiction. We further extend the framework by learning the distractor selection, which has been usually done manually or randomly. Results on Dialogue NLI (Welleck et al., 2019) and PersonaChat (Zhang et al., 2018) dataset show that our approach reduces contradiction and improves consistency of existing dialogue models. Moreover, we show that it can be generalized to improve context-consistency beyond persona in dialogues.



### The Impact of Multiple Parallel Phrase Suggestions on Email Input and Composition Behaviour of Native and Non-Native English Writers

https://doi.org/10.1145/3411764.3445372

```
@inproceedings{10.1145/3411764.3445372,
author = {Buschek, Daniel and Z\"{u}rn, Martin and Eiband, Malin},
title = {The Impact of Multiple Parallel Phrase Suggestions on Email Input and Composition Behaviour of Native and Non-Native English Writers},
year = {2021},
isbn = {9781450380966},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3411764.3445372},
doi = {10.1145/3411764.3445372},
booktitle = {Proceedings of the 2021 CHI Conference on Human Factors in Computing Systems},
articleno = {732},
numpages = {13},
keywords = {text suggestions, language model, Text entry, typing, dataset, neural network, deep learning},
location = {Yokohama, Japan},
series = {CHI '21}
}
```



### RECAST: Enabling User Recourse and Interpretability of Toxicity Detection Models with Interactive Visualization

https://doi.org/10.1145/3449280

abstract

> With the widespread use of toxic language online, platforms are increasingly using automated systems that leverage advances in natural language processing to automatically flag and remove toxic comments. However, most automated systems, when detecting and moderating toxic language, do not provide feedback to their users, let alone provide an avenue of recourse for these users to make actionable changes. We present our work, RECAST, an interactive, open-sourced web tool for visualizing these models' toxic predictions, while providing alternative suggestions for flagged toxic language. Our work also provides users with a new path of recourse when using these automated moderation tools. RECAST highlights text responsible for classifying toxicity, and allows users to interactively substitute potentially toxic phrases with neutral alternatives. We examined the effect of RECAST via two large-scale user evaluations, and found that RECAST was highly effective at helping users reduce toxicity as detected through the model. Users also gained a stronger understanding of the underlying toxicity criterion used by black-box models, enabling transparency and recourse. In addition, we found that when users focus on optimizing language for these models instead of their own judgement (which is the implied incentive and goal of deploying automated models), these models cease to be effective classifiers of toxicity compared to human annotations. This opens a discussion for how toxicity detection models work and should work, and their effect on the future of online discourse.



### Wordcraft: a Human-AI Collaborative Editor for Story Writing

https://arxiv.org/pdf/2107.07430.pdf

>As neural language models grow in effectiveness, they are increasingly being applied in real-world settings. However these applications tend to be limited in the modes of interaction they support. In this extended abstract, we propose Wordcraft, an AI-assisted editor for story writing in which a writer and a dialog system collaborate to write a story. Our novel interface uses few-shot learning and the natural affordances of conversation to support a variety of interactions. Our editor provides a sandbox for writers to probe the boundaries of transformer-based language models and paves the way for future human-in-the-loop training pipelines and novel evaluation methods.



### WearWrite: Crowd-Assisted Writing from Smartwatches

CHI 2016

> The physical constraints of smartwatches limit the range and complexity of tasks that can be completed. Despite interface improvements on smartwatches, the promise of enabling productive work remains largely unrealized. This paper presents *WearWrite*, a system that enables users to write documents from their smartwatches by leveraging a crowd to help translate their ideas into text. WearWrite users dictate tasks, respond to questions, and receive notifications of major edits on their watch. Using a dynamic task queue, the crowd receives tasks issued by the watch user and generic tasks from the system. In a week-long study with seven smartwatch users supported by approximately 29 crowd workers each, we validate that it is possible to manage the crowd writing process from a watch. Watch users captured new ideas as they came to mind and managed a crowd during spare moments while going about their daily routine. WearWrite represents a new approach to getting work done from wearables using the crowd.https://dl.acm.org/doi/10.1145/2858036.2858169



### Delete, Retrieve, Generate: a Simple Approach to Sentiment and Style Transfer

ACL 2018

> We consider the task of text attribute transfer: transforming a sentence to alter a specific attribute (e.g., sentiment) while preserving its attribute-independent content (e.g., “screen is just the right size” to “screen is too small”). Our training data includes only sentences labeled with their attribute (e.g., positive and negative), but **not pairs of sentences** that only differ in the attributes, so we must learn to disentangle attributes from attribute-independent content in an unsupervised way. Previous work using adversarial methods has struggled to produce high-quality outputs. In this paper, we propose simpler methods motivated by the observation that text attributes are often marked by **distinctive phrases** (e.g., “too small”). Our strongest method extracts content words by deleting phrases associated with the sentence’s original attribute value, retrieves new phrases associated with the target attribute, and uses a neural model to fluently combine these into a final output. Based on human evaluation, our best method generates grammatical and appropriate responses on 22% more inputs than the best previous system, averaged over three attribute transfer datasets: altering sentiment of reviews on Yelp, altering sentiment of reviews on Amazon, and altering image captions to be more romantic or humorous.

