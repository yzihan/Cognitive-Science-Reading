## Neural model

### High-resolution image reconstruction with latent diffusion models from human brain activity

https://sites.google.com/view/stablediffusion-with-brain/

> Reconstructing visual experiences from human brain activity offers a unique way to understand how the brain represents the world, and to interpret the connection between computer vision models and our visual system. 
>
> While deep generative models have recently been employed for this task, reconstructing realistic images with high semantic fidelity is still a challenging problem. 
>
> Here, we propose a new method based on a diffusion model (DM) to reconstruct images from human brain activity obtained via functional magnetic resonance imaging (fMRI). More specifically, we rely on a latent diffusion model (LDM) termed Stable Diffusion. This model reduces the computational cost of DMs, while preserving their high generative performance. We also characterize the inner mechanisms of the LDM by studying how its different components (such as the latent vector Z, conditioning inputs C, and different elements of the denoising U-Net) relate to distinct brain functions. 
>
> We show that our proposed method can reconstruct high-resolution images with high fidelity in straightforward fashion, without the need for any additional training and fine-tuning of complex deep-learning models. We also provide a quantitative interpretation of different LDM components from a neuroscientific perspective. 
>
> Overall, our study proposes a promising method for reconstructing images from human brain activity, and provides a new framework for understanding DMs.

Key point

> Reconstructing visual experiences from human brain activity with Stable Diffusion

How does it work?

>reconstructed visual images from functional Magnetic Resonance Imaging (fMRI) signals using a latent diffusion model named Stable Diffusion.
>
>Understanding internal process of Stable Diffusion with encoding models of brain activity

### Shared computational principles for language processing in humans and deep language models

Nature Neuroscience: https://www.nature.com/articles/s41593-022-01026-4

> Departing from traditional linguistic models, advances in deep learning have resulted in a new type of predictive (autoregressive) deep language models (DLMs). Using a self-supervised next-word prediction task, these models generate appropriate linguistic responses in a given context. In the current study, nine participants listened to a 30-min podcast while their brain responses were recorded using electrocorticography (ECoG). We provide empirical evidence that the human brain and autoregressive DLMs share three fundamental computational principles as they process the same natural narrative: (1) both are engaged in continuous next-word prediction before word onset; (2) both match their pre-onset predictions to the incoming word to calculate post-onset surprise; (3) both rely on contextual embeddings to represent words in natural contexts. Together, our findings suggest that autoregressive DLMs provide a new and biologically feasible computational framework for studying the neural basis of language.



### Different computational relations in language are captured by distinct brain systems

>A critical way for humans to acquire information is through language, yet whether and how language experience drives specific neural semantic representations is still poorly understood.
>
>We considered statistical properties captured by 3 different computational principles of language(simpleco-occurrence,network-(graph)-topologicalrelations,andneural-network-vector-embeddingrelations) and tested the extent to which they can explain the neural patterns of semantic representations,measured by 2 functional magnetic resonance imaging experiments that shared common semantic processes.Distinct graph-topological word relations, and not simple co-occurrence or neural-network-vector-embedding relations, had unique explanatory power for the neural patterns in the anterior temporal lobe (capturing graph-common-neighbors), inferior frontal gyrus, and posterior middle/inferior temporal gyrus (capturing graph-shortest-path). These results were relatively specific to language: they were not explained by sensory-motor similarities and the samecomputational relations of visual objects (based on visual image database) showed effects in the visual cortex in the picture naming experiment. That is, different topological properties within language and the same topological computations (commonneighbors) for language and visual inputs are captured by different brain regions. These findings reveal the specific neural semantic representations along graph-topological properties of language, highlighting the information type-specific and statistical propertyspecific manner of semantic representations in the human brain.



### Many but not all deep neural network audio models capture brain responses and exhibit hierarchical region correspondence 

>Models that predict brain responses to stimuli provide one measure of understanding of a sensory system, and have many potential applications in science and engineering. Stimulus-computable sensory models are thus a longstanding goal of neuroscience. Deep neural networks have emerged as the leading such predictive models of the visual system, but are less explored in audition. Prior work provided examples of audio-trained neural networks that produced good predictions of auditory cortical fMRI responses and exhibited correspondence between model stages and brain regions, but left it unclear whether these results generalize to other neural network models, and thus how to further improve models in this domain. We evaluated brainmodel correspondence for publicly available audio neural network models along with in-house models trained on four different tasks. Most tested models out-predicted previous filter-bank models of auditory cortex, and exhibited systematic model-brain correspondence: middle stages best predicted primary auditory cortex while deep stages best predicted non-primary cortex. However, some state-of-the-art models produced substantially worse brain predictions. The training task influenced the prediction quality for specific cortical tuning properties, with best overall predictions resulting from models trained on multiple tasks. The results suggest the importance of task optimization for explaining brain representations and generally support the promise of deep neural networks as models of audition. 



### A hierarchy of linguistic predictions during natural language comprehension

Significance

> Theorists propose that the brain constantly generates implicit predictions that guide information processing. During language comprehension, such predictions have indeed been observed, but it remains disputed under which conditions and at which processing level these predictions occur. Here, we address both questions by analyzing brain recordings of participants listening to audiobooks, and using a deep neural network to quantify the predictions evoked by the story. We find that brain responses are continuously modulated by linguistic predictions. We observe predictions at the level of meaning, grammar, words, and speech sounds, and find that high-level predictions can inform low-level ones. These results establish the predictive nature of language processing, demonstrating that the brain spontaneously predicts upcoming language at multiple levels of abstraction.

Abstract

> Understanding spoken language requires transforming ambiguous acoustic streams into a hierarchy of representations, from phonemes to meaning. It has been suggested that the brain uses prediction to guide the interpretation of incoming input. However, the role of prediction in language processing remains disputed, with disagreement about both the ubiquity and representational nature of predictions. Here, we address both issues by analyzing brain recordings of participants listening to audiobooks, and using a deep neural network (GPT-2) to precisely quantify contextual predictions. First, we establish that brain responses to words are modulated by ubiquitous predictions. Next, we disentangle model-based predictions into distinct dimensions, revealing dissociable neural signatures of predictions about syntactic category (parts of speech), phonemes, and semantics. Finally, we show that high-level (word) predictions inform low-level (phoneme) predictions, supporting hierarchical predictive processing. Together, these results underscore the ubiquity of prediction in language processing, showing that the brain spontaneously predicts upcoming language at multiple levels of abstraction.



### Toward a realistic model of speech processing in the brain with self-supervised learning

>Several deep neural networks have recently been shown to generate activations similar to those of the brain in response to the same input. 
>
>These algorithms, however, remain largely implausible: they require (1) extraordinarily large amounts of data, (2) unobtainable supervised labels, (3) textual rather than raw sensory input, and / or (4) implausibly large memory (e.g. thousands of contextual words). 
>
>These elements highlight the need to identify algorithms that, under these limitations, would suffice to account for both behavioral and brain responses. Focusing on the issue of speech processing, we here hypothesize that self-supervised algorithms trained on the raw waveform constitute a promising candidate. 
>
>Specifically, we compare a recent self-supervised architecture, Wav2Vec 2.0, to the brain activity of 412 English, French, and Mandarin individuals recorded with functional Magnetic Resonance Imaging (fMRI), while they listened to ~1h of audio books. 
>
>Our results are four-fold. 
>
>> First, we show that this algorithm learns brain-like representations with as little as 600 hours of unlabelled speech -- a quantity comparable to what infants can be exposed to during language acquisition. 
>>
>> Second, its functional hierarchy aligns with the cortical hierarchy of speech processing. 
>>
>> Third, different training regimes reveal a functional specialization akin to the cortex: Wav2Vec 2.0 learns sound-generic, speech-specific and language-specific representations similar to those of the prefrontal and temporal cortices. 
>>
>> Fourth, we confirm the similarity of this specialization with the behavior of 386 additional participants. These elements, resulting from the largest neuroimaging benchmark to date, show how self-supervised learning can account for a rich organization of speech processing in the brain, and thus delineate a path to identify the laws of language acquisition which shape the human brain.