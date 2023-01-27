## Empathic Conversation

#### Human-AI Collaboration Enables More Empathic Conversations in Text-based Peer-to-Peer Mental Health Support

Ashish Sharma, Inna Lin, Adam Miner, David Atkins, *Tim Althoff*

Nature Machine Intelligence 2023

**Abstract **

Advances in artificial intelligence (AI) are enabling systems that augment and collaborate with humans to perform simple, mechanistic tasks like scheduling meetings and grammar-checking text. However, such Human-AI collaboration poses challenges for more complex, creative tasks, such as carrying out empathic conversations, due to difficulties of AI systems in understanding complex human emotions and the open-ended nature of these tasks. Here, we focus on peer-to-peer mental health support, a setting in which empathy is critical for success, and examine how AI can collaborate with humans to facilitate peer empathy during textual, online supportive conversations. We develop HAILEY, an AI-in-the-loop agent that provides just-in-time feedback to help participants who provide support (peer supporters) respond more empathically to those seeking help (support seekers). We evaluate HAILEY in a non-clinical randomized controlled trial with real-world peer supporters on TalkLife (N=300), a large online peer-topeer support platform. We show that our Human-AI collaboration approach leads to a 19.60% increase in conversational empathy between peers overall. Furthermore, we find a larger 38.88% increase in empathy within the subsample of peer supporters who self-identify as experiencing difficulty providing support. We systematically analyze the Human-AI collaboration patterns and find that peer supporters are able to use the AI feedback both directly and indirectly without becoming overly reliant on AI while reporting improved self-efficacy post-feedback. Our findings demonstrate the potential of feedback-driven, AI-in-the-loop writing systems to empower humans in open-ended, social, creative tasks such as empathic conversations.



#### A Computational Approach to Understanding Empathy Expressed in Text-Based Mental Health Support

[Ashish Sharma](https://aclanthology.org/people/a/ashish-sharma/), [Adam Miner](https://aclanthology.org/people/a/adam-miner/), [David Atkins](https://aclanthology.org/people/d/david-atkins/), [Tim Althoff](https://aclanthology.org/people/t/tim-althoff/)

https://aclanthology.org/2020.emnlp-main.425/

**Abstract**

> Empathy is critical to successful mental health support. Empathy measurement has predominantly occurred in synchronous, face-toface settings, and may not translate to asynchronous, text-based contexts. Because millions of people use text-based platforms for mental health support, understanding empathy in these contexts is crucial. In this work, we present a computational approach to understanding how empathy is expressed in online mental health platforms. We develop a novel unifying theoretically-grounded framework for characterizing the communication of empathy in text-based conversations. We collect and share a corpus of 10k (post, response) pairs annotated using this empathy framework with supporting evidence for annotations (rationales). We develop a multi-task RoBERTa-based bi-encoder model for identifying empathy in conversations and extracting rationales underlying its predictions. Experiments demonstrate that our approach can effectively identify empathic conversations. We further apply this model to analyze 235k mental health interactions and show that users do not self-learn empathy over time, revealing opportunities for empathy training and feedback.

##### How to measure empathy

> Empathy is a complex multi-dimensional construct with two broad aspects related to emotion and cognition (Davis et al., 1980). The “emotion” aspect relates to the emotional stimulation in reaction to the experiences and feelings expressed by a user. The “cognition” aspect is a more deliberate process of understanding and interpreting the experiences and feelings of the user and communicating that understanding to them (Elliott et al., 2018).

> Here, we study expressed empathy in text-based mental health support– empathy expressed or communicated by peer supporters in their textual interactions with seekers (cf. Barrett-Lennard (1981)).3 Table 1 lists existing empathy scales in psychology and psychotherapy research. Truax and Carkhuff (1967) focus only on communicating cognitive understanding of others while Davis et al. (1980); Watson et al. (2002) also make use of expressing stimulated emotions.

> These scales, however, have been designed for in-person interactions and face-to-face therapy, often leveraging audio-visual signals like expressive voice. In contrast, in text-based support, empathy must be expressed using textual response alone. Also, they are designed to operate on long, synchronous conversations and are unsuited for the shorter, asynchronous conversations of our context.

> In this work, we adapt these scales to text-based, asynchronous support. We develop a new comprehensive framework for text-based, asynchronous conversations (Table 1; §3), use it to create a new dataset of empathic conversations (§4), a computational approach for identifying empathy (§5; §6), & gaining insights into mental health platforms (§7).

```
Davis, M. H. A. et al. A multidimensional approach to individual differences in empathy. J. Pers. Soc. Psychol. (1980).

Elliott, R., Bohart, A. C., Watson, J. C. & Murphy, D. Therapist empathy and client outcome: An updated meta-analysis. Psychotherapy 55, 399–410 (2018)
```

