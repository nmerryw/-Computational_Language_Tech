# Accelerating Cleantech Advancements through NLP-Powered Text Mining and Knowledge Extraction
## From Exploratory Text Analysis to Large Language Models (LLMs) Applications

![appolinary-kalashnikova-WYGhTLym344-unsplash](https://github.com/nbarnett19/Computational_Language_Tech/assets/127861184/cef65d1c-b550-4b3f-a0ed-08f19b286991)
<sup>Photo by <a href="https://unsplash.com/@appolinary_kalashnikova?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Appolinary Kalashnikova</a> on <a href="https://unsplash.com/photos/wind-turbine-surrounded-by-grass-WYGhTLym344?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a></sup>

### Background
In an era where addressing environmental challenges is paramount, the cleantech industry is pivotal in
fostering sustainable solutions. To empower the next generation of NLP (Natural Language
Processing) enthusiasts and cleantech innovators, we present the project titled “Accelerating
Cleantech Advancements through NLP-Powered Text Mining and Knowledge Extraction.” This project
aims to leverage NLP techniques to expedite the process of text analysis, knowledge acquisition, and
innovation within the cleantech sector. NLP technology can be a game-changer in this field, helping us
extract valuable insights from vast volumes of textual data.

In the context of our project, analyzing specialized media publications on cleantech topics is important
since this data can serve as a rich source of knowledge to expedite innovation. By delving into these
documents, we can uncover emerging trends, identify key players, and gain a deep
understanding of the cutting-edge technologies in cleantech, which, as we mentioned earlier, is an
essential part of our multifaceted NLP-powered text mining and knowledge extraction process. This
data can reveal not only the state of the art in the field but also potential white spaces where
innovation is needed. Moreover, the analysis of specialized online texts enables the identification of
critical technological gaps and opportunities for collaboration, making it a valuable resource for
cleantech researchers, entrepreneurs, and policymakers, further contributing to our vision of a more
sustainable future.

### Goals
In this project, we start with an exploratory text analysis including topic modeling to understand the
cleantech media data. We then train word and sentence embedding models to better represent the
content of cleantech innovations and develop a question answering / information retrieval system that
can help stakeholders facilitate cleantech innovations. The goal of this project is fourfold:

* **Text Analysis**: Use NLP techniques to effectively mine and extract
insights from specialized media data.

* **Cleantech Domain Expertise**: Use NLP as a tool to deepen our knowledge of the cleantech field,
enabling us to apply NLP to domain-specific challenges.

* **Innovation Acceleration**: Apply NLP to identify innovation opportunities and gaps within cleantech,
allowing us to leverage NLP for innovative solutions.

* **Communication and Collaboration**: Communicate and visualize NLP-driven
insights effectively, facilitating collaboration with peers, researchers, and industry professionals to drive
cleantech advancements.

### Dataset
The Cleantech Media Dataset contains ca. 10k specialized articles and other documents on
cleantech, published in authoritative online sources in the timespan 2021-2023.

The dataset is available for download from Kaggle:
https://www.kaggle.com/datasets/jannalipenkova/cleantech-media-dataset

## Pipeline

### [Stage 1](https://github.com/nbarnett19/Computational_Language_Tech/blob/Main/Stage_1_Barnett_Merryweather_Yaroshchuk.ipynb): Data cleaning, preprocessing, and exploratory data analysis including topic modelling
In this step, we get a first overview of the dataset ando prepare it for the subsequent
NLP analyses. This involves the following tasks:

* Data Collection and Cleaning
* Text Preprocessing
* Exploratory Data Analysis (EDA)

* Topic Modeling
  - Test topic modeling techniques such as LDA and NMF (https://github.com/AnushaMeka/NLP-Topic-Modeling-LDA-NMF), Top2Vec
(https://github.com/ddangelov/Top2Vec) and BERTopic (https://github.com/MaartenGr/BERTopic).

### [Stage 2](https://github.com/nbarnett19/Computational_Language_Tech/blob/Main/Stage_2_Barnett_Merryweather_Yaroshchuk.ipynb): Training word and sentence embedding models
In this step, we train our own embedding models based on the given dataset and compare the
model performance with the open-source embedding models. This involves the following tasks:

* Data Preparation for Embeddings
* Word Embedding Training
  - Train word embeddings using techniques like Word2Vec, FastText, or GloVe on the text data
* Sentence Embedding Training
  - Develop sentence embeddings using methods like averaging word vectors, Doc2Vec, or BERT embeddings.
* Embedding Model Evaluation

### [Stage 3](https://github.com/nbarnett19/Computational_Language_Tech/blob/Main/stage_3_Natalie_Alina_Nina.ipynb):  Question answering / Information retrieval
In this step, we create a question-answering system based on the cleantech media dataset
and fine-tune an LLM for question answering. This involves the following tasks:

* Extract Key Sentences
  - Extract sentences from the given cleantech dataset using, for example, TextRank
(https://github.com/davidadamojr/TextRank) or BERT Extractive Summarizer
(https://pypi.org/project/bert-extractive-summarizer/).
* Generate Questions and Answers
  - Generate a question and an answer for each sentence using a pre-trained language modelsuch as GPT-2 or T5
* Fine-tune the Model
  - Use the prepared QA dataset to fine-tune GPT-2 or T5 and evaluate model performance on new input data in the cleantech field.
* Compare to LLMs
  - Comparing the above results with the zero-shot capability of some open source large
language models (LLMs) such as ChatGPT and Llama-2.

### Contributors
1. @nbarnett19
2. @nmerryw
3. @Alina070687

<details>
<summary>References</summary>

* [1] Zhao, W. X., Zhou, K., Li, J., Tang, T., Wang, X., Hou, Y., ... & Wen, J. R. (2023). A survey of large
language models. arXiv preprint arXiv:2303.18223.
* [2] Toetzke, M., Probst, B., & Feuerriegel, S. (2023). Leveraging large language models to monitor
climate technology innovation. Environmental Research Letters, 18(9), 091004.
* [3] Lewis, P., Perez, E., Piktus, A., Petroni, F., Karpukhin, V., Goyal, N., ... & Kiela, D. (2020).
Retrieval-augmented generation for knowledge-intensive nlp tasks. Advances in Neural Information
Processing Systems, 33, 9459-9474.
</details>

<details>
<summary>Organizers</summary>
  
The project is organized by:

* Dr. Janna Lipenkova, CEO, Equintel GmbH, Germany
* Dr. Susie Xi Rao, Researcher at ETH Zurich
* Dr. Guang Lu, Lecturer for Data Science, Lucerne University of Applied Sciences and Arts

in collaboration with:
* Dr. Diego Antognini, Research Scientist, IBM Research AI

as a joint task of industry and academia for the HSLU Applied Information and Data Science Master’s
program in the course Computational Language Technologies.
</details>
