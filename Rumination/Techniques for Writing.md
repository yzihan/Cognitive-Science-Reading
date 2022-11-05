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