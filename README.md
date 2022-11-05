# QuestGen

### 论文列表
* A Feasibility Study of Answer-Unaware Question Generation for Education ACL22
* Educational Question Generation of Children Storybooks via Question Type Distribution Learning and Event-centric 
   Summarization ACL22
* Question Generation for Reading Comprehension Assessment by Modeling How and What to Ask ACL22
* What Makes Reading Comprehension Questions Difficult ACL22
* Predicting Difficulty and Discrimination of Natural Language Questions ACL22
* On the Robustness of Question Rewriting Systems to Questions of Varying Hardness. ACL22
* CQG: A Simple and Effective Controlled Generation Framework for Multi-hop Question Generation ACL22
* It is AI’s Turn to Ask Humans a Question- Question-Answer Pair Generation for Children's Story Books ACL22
* Unsupervised multiple-choice question generation for out-of-domain Q&A fine-tuning ACL22
* 
**EMNLP22**
* Generative Language Models for Paragraph-Level Question Generation  用了几个PLM做了对比测试，有Demo
* Consecutive Question Generation via Dynamic Multitask Learning
* CONSISTENT: Open-Ended Question Generation From News Articles
* 
* Learning to Generate Question by Asking Question: A Primal-Dual Approach with Uncommon Word Generation
* Multi-VQG: Generating Engaging Questions for Multiple Images
* QRelScore: Better Evaluating Generated Questions with Deeper Understanding of Context-aware Relevance
* Successive Prompting for Decomposing Complex Questions
* Semantic Framework based Query Generation for Temporal Question Answering over Knowledge Graphs
* Learning to Decompose: Hypothetical Question Decomposition Based on Comparable Texts
* Varifocal Question Generation for Fact-checking
* Generating Literal and Implied Subquestions to Fact-check Complex Claims
* Improving Passage Retrieval with Zero-Shot Question Generation
* Automatic Generation of Socratic Subquestions for Teaching Math Word Problems
* DSM: Question Generation over Knowledge Base via Modeling Diverse Subgraphs with Meta-learner
* Is a Question Decomposition Unit All We Need?
* POQue: Asking Participant-specific Outcome Questions for a Deeper Understanding of Complex Events
* CycleKQR: Unsupervised Bidirectional Keyword-Question Rewriting

### 数据集

[HotpotQA](https://huggingface.co/datasets/hotpot_qa)（多跳），[FairytaleQA](https://huggingface.co/datasets/GEM/FairytaleQA)（教育问题），[RACE](https://huggingface.co/datasets/race)（教育）

### 代码项目介绍 （默认使用HuggingFace/PyTorch)
- 论文代码：[eval-summary-qg](https://github.com/weibifan/eval-summary-qg)
A Feasibility Study of Answer-Agnostic Question Generation for Education ACL22  
使用T5

- 论文代码：[eval-lm-question-generation](https://github.com/weibifan/eval-lm-question-generation)
Generative Language Models for Paragraph-Level Question Generation-EMNLP22  

- 论文代码：[eval-qg-ui](https://github.com/weibifan/eval-qg-ui)
ParaQG: A System for Generating Questions and Answers from Paragraphs, EMNLP19  

- 中文问题生成：eval_question_generation_ch  
基于mT5

- 代码工程：eval_question_generation  
基于mT5


