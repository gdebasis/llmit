---
layout: default
---

[Call for Papers](#call-for-papers) |
[Keynote Talks](#keynote-talks) |
[Invited Talks](#invited-talks) |
[Submission Guidelines](#submission-guidelines) |
[Important Dates](#important-dates) |
[Schedule](#schedule) |
[Organizers](#organizers)

## About the Workshop

LLMIT (pronounced as "limit") will be a full day workshop at [CIKM 2023](https://uobevents.eventsair.com/cikm2023/).
 
### Background

Large language models (LLMs), when scaled from millions to billions of parameters, have been demonstrated to exhibit the so-called 'emergence' effect, in that they are not only able to produce semantically correct and coherent text, but are also able to adapt themselves surprisingly well with small changes in contexts supplied as inputs (commonly called prompts).
Despite producing semantically coherent and potentially relevant text for a given context, LLMs are vulnerable to yield incorrect information. This misinformation generation, or the so-called hallucination problem of an LLM, gets worse when an adversary manipulates the prompts to their own advantage, e.g., generating false propaganda to disrupt communal harmony, generating false information to trap consumers with target consumables etc. Not only does the consumption of an LLM-generated hallucinated content by humans pose societal threats, such misinformation, when used as prompts, may lead to detrimental effects for in-context learning (also known as few-shot prompt learning).

### Scope

With reference to the above-mentioned problems of LLM usage, in this workshop, **Large Language Models’ Interpretability and Trustworthiness (LLMIT)**, we intend to foster research on topics related to not only identifying misinformation from LLM-generated content, but also to mitigate the propagation effects of this generated misinformation on downstream predictive tasks thus leading to more robust and effective leveraging in-context learning. It is critical that researchers work towards a responsible and trustworthy innovation. For instance, identifying the source documents which the decoding phase of an LLM largely utilised to generate an output text can potentially help a user better understand the content, thus possibly contributing towards developing a trust towards the model. Relevant active areas in LLMs include misinformation detection, in-context learning, detection and mitigation of biases using prompts, alleviating adversarial attacks etc. for several downstream tasks to aid the goal of responsible AI. On the other hand, these responsible AI objectives are often viewed independently to each other, which is a significant constraint because it is necessary to comprehend the interplay and/or conflict between them. The purpose of this workshop is to bring together researchers working on those distinct yet connected areas, as well as their overlap, in order to move towards a more thorough understanding of trustworthy use of LLMs.

## Keynote Talks

We are excited to announce the following keynote talks.

#### - [Donald Metzler](https://research.google/people/DonaldMetzler/), Senior Staff Research Scientist, Google

Title: **Trustworthy Generative Information Retrieval**

Abstract: Generative AI has transformed the information retrieval landscape over the past year. This has given rise to a class of so-called generative information retrieval systems that rely on generative models to power a wide range of applications, such as conversational search, question answering, document retrieval, and recommendation, to name just a few. As these systems become more reliant on generative models, there arises the need to ensure the outputs produced are accurate, reliable, and trustworthy. This talk will cover a range of research topics related to improving the trustworthiness of such systems, viewed primarily through the lens of information provenance, including models that directly encode provenance information, response grounding via attribution, and minimally abstractive multi-document summarization.

#### - [Prof. Adam Jatowt](https://adammo12.github.io/adamjatowt/), Head of the Data Science Group, University of Innsbruck, Austria

Title: **Temporal Reasoning Capabilities of Large Language Models**

Abstract: Large language models (LLMs) have recently become quite popular thanks to their excellent performance in many NLP tasks. In this talk, we focus in particular on the temporal reasoning abilities of LLMs. Temporal reasoning is a key aspect of human communication and understanding, however it remains an underexplored area within the context of LLMs. We perform a comprehensive, large-scale analysis of temporal reasoning capabilities of LLMs both in terms of temporal commonsense reasoning and temporal knowledge understanding. We conduct a fine-grained investigation of performance of LLMs across different categories of temporal tasks offering insights into their proficiency in understanding and predicting the continuity, sequence, and progression of events over time. Our findings reveal a nuanced depiction of the capabilities and limitations of the models offering a comprehensive reference for future research in this pivotal domain. Finally, we present several novel datasets that we have constructed for investigating temporal reasoning of ML models.

## Invited Talks

We are excited to announce the following invited talks.

#### - [Kailai Yang](https://stevekgyang.github.io/), Ph.D. Scholar, Dept. of CSE, University of Manchester 

Title: **Towards Interpretable Mental Health Analysis with Large Language Models**

Abstract: Mental health-related issues are posing increasing threats to public health worldwide.  Many works have explored NLP techniques to perform mental health analysis in a discriminative manner, but bear the key limitation of lacking interpretability, especially in such a sensitive domain. The latest large language models (LLMs), such as ChatGPT and GPT-4, exhibit strong promise in improving the performance of mental health analysis. In this talk, we report our comprehensive evaluation of different prompting strategies on LLMs' mental health analysis ability, including few-shot learning, chain-of-thought prompting, and emotion supervision signals. We also explore LLMs for interpretable mental health analysis by instructing them to generate explanations for each of their decisions. We convey strict human evaluations to assess the quality of the generated explanations. With full investigations of existing LLMs, we formally model interpretable mental health analysis as text generation tasks,  and build the first multi-task and multi-source interpretable mental health instruction (IMHI) dataset. Based on the IMHI dataset and LLaMA2 foundation models, we train [MentaLLaMA](https://github.com/SteveKGYang/MentalLLaMA), the first open-source instruction-following LLM series for interpretable mental health analysis.

#### - [Xi Wang](https://www.xiwangeric.com/), Post-doctoral researcher, University College London 

Title: **Enhancing Conversational Techniques: the role of Synthetic Dialogue Generation**

Abstract: This talk delves into the research topic of conversational AI and the pivotal role played by synthetic dialogue generation. Drawing from two distinct approaches, we showcase how synthetic dialogues can advance task-oriented conversations and conversational recommendations. Firstly, we construct a large-scale knowledge base with rich task instruction knowledge, and then we harness the power of advanced language models by pre-training a language model on synthetic dialogues. These dialogues are generated from the structured task instructions, which encode rich task information, serving as a robust foundation for knowledge augmentation. The resulting task-oriented dialogue systems demonstrate significantly improved performance, especially in out-of-domain and semi-supervised scenarios. On the other hand, we also leverage large language models to enrich conversational recommendation datasets with synthetic dialogues that capture nuanced biases and popularity trends. This augmentation showcases its advances by injecting diversity and accuracy into recommendations. Hence, this talk exemplifies the potential of leveraging large language models to address various challenges in the conversational domain and foster many relevant studies.



## Schedule

Workshop Day: **22nd October, 2023** (all times in BST)

* 9:00 - 10:30 :- *Temporal Reasoning Capabilities of Large Language Models* -- Keynote talk by Prof. Adam Jatowt
* 10:30 - 11:00 :- Coffee break
* 11:00 - 12:00 :- *Enhancing Conversational Techniques: the role of Synthetic Dialogue Generation* -- Invited talk by Xi Wang
* 12.00 - 12.30: *Occupational Gender Bias in Large Language Models evaluated on multiple languages* -- Seung-Yeon Back, Eunju Park and Simon S. Woo. 
* 12:30 - 14:00 :- Lunch break
* 14:00 - 14:30 :- *Towards Interpretable Mental Health Analysis with Large Language Models* -- Invited talk by Kailai Yang
* 14:30 - 15:00 :- *Generative and Pseudo-Relevant Feedback for Sparse, Dense and Learned Sparse Retrieval* -- Iain Mackie, Shubham Chatterjee and Jeffrey Dalton.
* 15.00 - 15.30 :- *Is LLM Generated Synthetic Data Augmentation Beneficial for Fact Verification?* -- Payel Santra, Madhusudan Ghosh, Debasis Ganguly, Partha Basuchowdhuri and Sudip Kumar Naskar.
* 15:30 - 16:00 :- Coffee break
* 16:00 - 17:30 :- *Trustworthy Generative Information Retrieval* -- Keynote talk by Donald Metzler 

## Call for Papers

We solicit submissions on (but not limited to) the following research topics.

1. **Misinformation detection**: It is a widely known fact that the text generated by LLMs are often of hallucinatory in nature. Consequently, mapping back to the original documents (attribution at document level) which were likely responsible in affecting the decoding path to generate the text for a downstream task can throw insights on an LLM’s 0-shot or few-shot (in-context) task-specific abstraction of the input data.
2. **Prompt or In-Context Explanations** of the LLM-generated content in terms of attention-based or counter-factual explanations of the prompts, i.e., which parts of the prompts are more important in determining the class probabilities (via generation of class-specific sets of words by the decoder).
3. **Linking LLM-generated answers to knowledge bases** or use knowledge bases to formulate template-driven prompts.
4. **LLMs for generating weak labels** for various applications, or to generate simulated data (silver-standard ground-truth) to reduce annotation effort.
5. **Adaptive In-context learning for LLMs**, i.e., work towards developing a transparent LLM-based in-context learning model that explains the different choices employed in prompt learning, which may include -
   - What similarity metric to employ for generating the few-shot examples, e.g., sparse vectors, dense embedding, task-specific dense embedding etc.
   - How many few shot examples to use.
   - Explore combination (apriori and post-hoc) of LLM-based in-context learning with supervised parametric models.
6. **Fair Predictions with LLMs**, i.e., mitigate the detrimental effects of biased responses with suitable prompts.
7. **Adversarial Robustness of LLMs**, i.e., optimise the robustness of LLM-based in context learning to adversarial attacks based on prompt injections.
8. **LLM-driven in-context learning for search and recommendation**, i.e., explore the potential of LLMs for personalised search and recommendation. Since LLMs have been shown to work well with small quantities of task-specific training data, they can potentially be used to improve the effectiveness of personalized search and recommendation.
9. **Multi-modal LLMs**, involving exploration on the topics related to the interpretability and trustworthiness of LLMs in the particular context of multi-modal predictive tasks, e.g., visual question answering etc.
10. **Ethical concerns of LLMs**, i.e., research on topics related to a responsible use of LLMs and their socio-economic implications.


## Submission Guidelines

Papers submitted should be **4 to 10 pages of content** (plus any number of additional pages for references). Papers must be submitted in PDF as per the [CEUR](https://www.overleaf.com/latex/templates/template-for-submissions-to-ceur-workshop-proceedings-ceur-ws-dot-org/wqyfdgftmcfw) single-column conference format. The review process is **double-blind**. Papers should be uploaded via Easychair via the following submission link.

- Submit your papers via this [link](https://easychair.org/conferences/?conf=llmit23).

Accepted papers will be included in the CIKM'23 companion volume (**published by CEUR** and **indexed by DBLP**). At least one author of each accepted contribution must attend the workshop. No additional authors can be added after acceptance.

## Important Dates

The following dates are in AoE (Anywhere on Earth) timezone.

* Paper Submission Deadline - ~~30th August~~ 4th September, 2023
* Review Notifications - ~~18th September~~ 25th September, 2023
* Camera-ready Due - ~~25th September~~ 30th September, 2023
* Workshop Day - 22nd October, 2023

## Organizers

* [Tulika Saha](https://sahatulika15.github.io/), University of Liverpool, United Kingdom
* [Debasis Ganguly](https://gdebasis.github.io/), University of Glasgow, United Kingdom
* [Sriparna Saha](https://www.iitp.ac.in/~sriparna/), Indian Institute of Technology Patna, India
* [Prasenjit Mitra](https://ist.psu.edu/directory/pum10), Pennsylvania State University, USA

For any questions, send an email to this [alias](mailto:llmit23@easychair.org).

Please reach out to the organizers for any questions.
