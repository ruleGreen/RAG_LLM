# RAG

- Retriever
- Knowledge Base
- Reader

## Process RAG

- [Retrieval-Augmented Generation for Large Language Models: A Survey](https://arxiv.org/abs/2312.10997.pdf) Survey Paper

- [PK-ICR: Persona-Knowledge Interactive Multi-Context Retrieval for Grounded Dialogue](https://aclanthology.org/2023.emnlp-main.1020.pdf) `EMNLP 2023`

- [Interleaving Retrieval with Chain-of-Thought Reasoning for Knowledge-Intensive Multi-Step Questions](https://aclanthology.org/2023.acl-long.557.pdf) `ACL 2023`

- [Self-Knowledge Guided Retrieval Augmentation for Large Language Models](https://aclanthology.org/2023.findings-emnlp.691/) `EMNLP 2023`

- [DB-GPT: Empowering Database Interactions with Private Large Language Models](https://arxiv.org/pdf/2312.17449.pdf)

- [Retrieval-Augmented Thought Process as Sequential Decision Making](https://arxiv.org/pdf/2402.07812.pdf)

## Query Rewriter

- [Compressing Context to Enhance Inference Efficiency of Large Language Models]

## Retriever

- [Active Retrieval Augmented Generation] `EMNLP 2023` :fire::fire::fire: interesting and useful -> may can be used in dialogues

- [I^3 Retriever: Incorporating Implicit Interaction in Pre-trained Language Models for Passage Retrieval](https://arxiv.org/abs/2306.02371)

- [Learning Retrieval Augmentation for Personalized Dialogue Generation](https://aclanthology.org/2023.emnlp-main.154.pdf) `EMNLP 2023`

- [Divide and Conquer: Towards Better Embedding-based Retrieval for Recommender Systems from a Multi-task Perspective]

- [TRAVEL: Tag-Aware Conversational FAQ Retrieval via Reinforcement Learning] interesting and useful work


#### Multimodal

- [CAR: Consolidation, Augmentation and Regulation for Recipe Retrieval]

#### Multilingual

- [Soft Prompt Decoding for Multilingual Dense Retrieval](https://arxiv.org/abs/2305.09025) [[blog]](https://mp.weixin.qq.com/s/oF86LV4injWZBoRzc37QMg)


## Reader

- [CHAIN-OF-NOTE: ENHANCING ROBUSTNESS IN RETRIEVAL-AUGMENTED LANGUAGE MODELS](https://arxiv.org/pdf/2311.09210.pdf) `Tecent` :fire:

- [Knowledgeable Preference Alignment for LLMs in Domain-specific Question Answering]

## Database

- [Trends in Integration of Knowledge and Large Language Models: A Survey and Taxonomy of Methods, Benchmarks, and Applications]

### Level of Granularity

- [Dense X Retrieval: What Retrieval Granularity Should We Use?](https://arxiv.org/pdf/2312.06648.pd) [[code]](https://github.com/chentong0/factoid-wiki/)

### Structure of Data

#### Knowledge Graph

- [Think-on-Graph: Deep and Responsible Reasoning of Large Language Model on Knowledge Graph](https://arxiv.org/pdf/2307.07697.pdf)  [[code]](https://github.com/IDEA-FinAI/ToG)


## Different Application

- [Tree of Clarifications: Answering Ambiguous Questions with Retrieval-Augmented Large Language Models](https://aclanthology.org/2023.emnlp-main.63.pdf) `EMNLP2023` using RAG to clarify ambiguous questions

- [Divide and Conquer: Towards Better Embedding-based Retrieval for Recommender Systems from a Multi-task Perspective](https://mp.weixin.qq.com/s/dc4xsFj1SWB1zNVNGp8qqA) :fire::fire::fire::fire::fire: this is very inspiring!

## Datasets

- [FRESHLLMS: REFRESHING LARGE LANGUAGE MODELS WITH SEARCH ENGINE AUGMENTATION](https://arxiv.org/pdf/2310.03214.pdf)

## Some Problems

### Lost in Middle

1. https://mp.weixin.qq.com/s/dahnrxGBaNIfEOzruxCbOw useful in practice, similiar with UniMS-RAG, the weights of different sources, the rerank processing for retrieved documents from different sources

### Retrieve or Generate？

- [Self-DC: When to retrieve and When to generate? Self Divide-and-Conquer for Compositional Unknown Questions](https://arxiv.org/abs/2402.13514.pdf) :fire::fire::fire::fire::fire: the benchmark and framework both are valuable and important.

- [Blinded by Generated Contexts: How Language Models Merge Generated and Retrieved Contexts for Open-Domain QA?](https://arxiv.org/pdf/2401.11911.pdf) :fire: a good paper for analysis, not a method paper

- [Retrieve Only When It Needs: Adaptive Retrieval Augmentation for Hallucination Mitigation in Large Language Models](https://arxiv.org/pdf/2402.10612.pdf)

- [Self-Knowledge Guided Retrieval Augmentation for Large Language Models](https://aclanthology.org/2023.findings-emnlp.691/)

- [ACTIVERAG: Revealing the Treasures of Knowledge via Active Learning](https://arxiv.org/pdf/2402.13547.pdf)


### Sub Functions

- [BRANCH-SOLVE-MERGE IMPROVES LARGE LANGUAGE MODEL EVALUATION AND GENERATION](https://arxiv.org/abs/2310.15123.pdf) combine_sub_qas in Self-DC


## References

1. https://mp.weixin.qq.com/s/BlU3I6Ww3L8a0_Dxt0lztA

2. https://github.com/HKUST-AI-Lab/Awesome-LLM-with-RAG

3. https://mp.weixin.qq.com/s/Hy78rtJuJTehAJIC-HK2Rg (baichuan)

4. RAG in EMNLP2023 -> https://mp.weixin.qq.com/s/GUroCns3yB_voufgKCXSUg

5. latest RAG papers: https://recsys.substack.com/

