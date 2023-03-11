## Multi-modal models

### Language Is Not All You Need: Aligning Perception with Language Models

Paper: [ https://doi.org/10.48550/arXiv.2302.14045](https://doi.org/10.48550/arXiv.2302.14045)

Github: https://github.com/microsoft/unilm

Microsoft: [Shaohan Huang](https://arxiv.org/search/cs?searchtype=author&query=Huang%2C+S), [Li Dong](https://arxiv.org/search/cs?searchtype=author&query=Dong%2C+L), [Wenhui Wang](https://arxiv.org/search/cs?searchtype=author&query=Wang%2C+W), [Yaru Hao](https://arxiv.org/search/cs?searchtype=author&query=Hao%2C+Y), [Saksham Singhal](https://arxiv.org/search/cs?searchtype=author&query=Singhal%2C+S), [Shuming Ma](https://arxiv.org/search/cs?searchtype=author&query=Ma%2C+S), [Tengchao Lv](https://arxiv.org/search/cs?searchtype=author&query=Lv%2C+T), [Lei Cui](https://arxiv.org/search/cs?searchtype=author&query=Cui%2C+L), [Owais Khan Mohammed](https://arxiv.org/search/cs?searchtype=author&query=Mohammed%2C+O+K), [Barun Patra](https://arxiv.org/search/cs?searchtype=author&query=Patra%2C+B), [Qiang Liu](https://arxiv.org/search/cs?searchtype=author&query=Liu%2C+Q), [Kriti Aggarwal](https://arxiv.org/search/cs?searchtype=author&query=Aggarwal%2C+K), [Zewen Chi](https://arxiv.org/search/cs?searchtype=author&query=Chi%2C+Z), [Johan Bjorck](https://arxiv.org/search/cs?searchtype=author&query=Bjorck%2C+J), [Vishrav Chaudhary](https://arxiv.org/search/cs?searchtype=author&query=Chaudhary%2C+V), [Subhojit Som](https://arxiv.org/search/cs?searchtype=author&query=Som%2C+S), [Xia Song](https://arxiv.org/search/cs?searchtype=author&query=Song%2C+X), [Furu Wei](https://arxiv.org/search/cs?searchtype=author&query=Wei%2C+F)

>A big convergence of language, multimodal perception, action, and world modeling is a key step toward artificial general intelligence. 
>
>In this work, we introduce Kosmos-1, a Multimodal Large Language Model (MLLM) that can perceive general modalities, learn in context (i.e., few-shot), and follow instructions (i.e., zero-shot). Specifically, we train Kosmos-1 from scratch on web-scale multimodal corpora, including arbitrarily interleaved text and images, image-caption pairs, and text data. We evaluate various settings, including zero-shot, few-shot, and multimodal chain-of-thought prompting, on a wide range of tasks without any gradient updates or finetuning. 
>
>Experimental results show that Kosmos-1 achieves impressive performance on (i) language understanding, generation, and even OCR-free NLP (directly fed with document images), (ii) perception-language tasks, including multimodal dialogue, image captioning, visual question answering, and (iii) vision tasks, such as image recognition with descriptions (specifying classification via text instructions). 
>
>We also show that MLLMs can benefit from cross-modal transfer, i.e., transfer knowledge from language to multimodal, and from multimodal to language. In addition, we introduce a dataset of Raven IQ test, which diagnoses the nonverbal reasoning capability of MLLMs.



### Data2vec 2.0: Highly efficient self-supervised learning for vision, speech and text

paper: https://arxiv.org/abs/2212.07525

[Alexei Baevski](https://arxiv.org/search/cs?searchtype=author&query=Baevski%2C+A), [Arun Babu](https://arxiv.org/search/cs?searchtype=author&query=Babu%2C+A), [Wei-Ning Hsu](https://arxiv.org/search/cs?searchtype=author&query=Hsu%2C+W), [Michael Auli](https://arxiv.org/search/cs?searchtype=author&query=Auli%2C+M)

>Current self-supervised learning algorithms are often modality-specific and require large amounts of computational resources. 
>
>To address these issues, we increase the training efficiency of data2vec, a learning objective that generalizes across several modalities. We do not encode masked tokens, use a fast convolutional decoder and amortize the effort to build teacher representations. data2vec 2.0 benefits from the rich contextualized target representations introduced in data2vec which enable a fast self-supervised learner. 
>
>Experiments on ImageNet-1K image classification show that data2vec 2.0 matches the accuracy of Masked Autoencoders in 16.4x lower pre-training time, on Librispeech speech recognition it performs as well as wav2vec 2.0 in 10.6x less time, and on GLUE natural language understanding it matches a retrained RoBERTa model in half the time. Trading some speed for accuracy results in ImageNet-1K top-1 accuracy of 86.8\% with a ViT-L model trained for 150 epochs.



### Flamingo: a Visual Language Model for Few-Shot Learning

DeepMind

>Building models that can be rapidly adapted to novel tasks using only a handful of annotated examples is an open challenge for multimodal machine learning research. We introduce Flamingo, a family of Visual Language Models (VLM) with this ability. We propose key architectural innovations to: (i) bridge powerful pretrained vision-only and language-only models, (ii) handle sequences of arbitrarily interleaved visual and textual data, and (iii) seamlessly ingest images or videos as inputs. Thanks to their flexibility, Flamingo models can be trained on large-scale multimodal web corpora containing arbitrarily interleaved text and images, which is key to endow them with in-context few-shot learning capabilities. We perform a thorough evaluation of our models, exploring and measuring their ability to rapidly adapt to a variety of image and video tasks. These include open-ended tasks such as visual question-answering, where the model is prompted with a question which it has to answer; captioning tasks, which evaluate the ability to describe a scene or an event; and close-ended tasks such as multiple-choice visual question-answering. For tasks lying anywhere on this spectrum, a single Flamingo model can achieve a new state of the art with few-shot learning, simply by prompting the model with task-specific examples. On numerous benchmarks, Flamingo outperforms models f ine-tuned on thousands of times more task-specific data.



### Experience Grounds Language

>Language understanding research is held back by a failure to relate language to the physical world it describes and to the social interactions it facilitates. Despite the incredible effectiveness of language processing models to tackle tasks after being trained on text alone, successful linguistic communication relies on a shared experience of the world. It is this shared experience that makes utterances meaningful. Natural language processing is a diverse field, and progress throughout its development has comefromnewrepresentational theories, modeling techniques, data collection paradigms, and tasks. We posit that the present success of representation learning approaches trained on large, text-only corpora requires the parallel tradition of research on the broader physical and social context of language to address the deeper questions of communication.

**5-level world scopes of language**

> WS1: Corpus (past NLP)
>
> WS2: Internet (current NLP)
>
> **WS3: Perception (multimodal NLP)**
>
> WS4: Embodiment
>
> WS5: Social 



### Human Language  Understanding & Reasoning

Christopher D. Manning

>The last decade has yielded dramatic and quite surprising breakthroughs in natural language processing through the use of simple artificial neural network computations, replicated on a very large scale and trained over exceedingly large amounts of data. 
>
>The resulting pretrained language models, such as BERT and GPT-3, have provided a powerful universal language understanding and generation base, which can easily be adapted to many understanding, writing, and reasoning tasks. These models show the first inklings of a more general form of artificial intelligence, which may lead to powerful foundation models in domains of sensory experience beyond just language.



### The Increasing Role of Sensorimotor Experience in Artificial Intelligence 

Richard Sutton

All Rich Sutton's Talks :http://www.incompleteideas.net/Talks/Talks.html

> Sensorimotor experience is the sensations and actions of an agent's ordinary interaction with the world
>
> >- Reinforcement learning involves experience
> >- Predictive learning involves experience
> >- Supervised learning does not involve experience: it learns from special training data
> >- Experience is the agent's only access to the world
> >- Experience has meaning only by its relationship to other experience
> >  - except for reward, a special scalar part of the sensation, which is good

Will intelligence ultimately be explained in

>Experiential terms
>
>>- sensations
>>- actions
>>- rewards
>>- time steps
>>- things inside the agent

>Objective terms
>
>>- states of the external world
>>- objects, people, places, relationship, atoms
>>- space, motion, distances
>>- things outside the agent

Main points / outline
> Over Al's seven decades, experience has played an increasing role; I see four major steps in this progression:
>
> > Step 1: Agenthood (having experience)
> > Step 2: Reward (goals in terms of experience)
> > Step 3: Experiential state (state in terms of experience)
> > Step 4: Predictive knowledge (to know is to predict experience)
> 
> For each step, Al has reluctantly moved toward experience in order to be more grounded, learnable, and scalable



### Cross-Modal Fine-Tuning: Align then Refine

> Fine-tuning large-scale pretrained models has led to tremendous progress in well-studied modalities such as vision and NLP. However, similar gains have not been observed in many other modalities due to a lack of relevant pretrained models. In this work, we propose ORCA, a general cross-modal f ine-tuning framework that extends the applicability of a single large-scale pretrained model to diverse modalities. ORCA adapts to a target task via an align-then-refine workflow: given the target input, ORCA first learns an embedding network that aligns the embedded feature distribution with the pretraining modality. The pretrained model is then fine-tuned on the embedded data to exploit the knowledge shared across modalities. Through extensive experiments, we show that ORCA obtains state-of-the-art results on 3 benchmarks containing over 60 datasets from 12 modalities, outperforming a wide range of hand-designed, AutoML, general-purpose, and task-specific methods. We highlight the importance of data alignment via a series of ablation studies and demonstrate ORCA’s utility in data-limited regimes.