# OpenLegalBenchmark

Multilingual datasets and tasks for evaluating Large Language Models (LLMs) in the EU legal domain.

The aims of the project are:
* to collect and develop open source datasets and an evaluation benchmark for LLMs and LLM’s based legal systems in the EU legal domain, particularly about question-answering on EU laws and regulations, in Italian, French, Spanish, German, English languages;
* to evaluate existing LLMs and legal NLP systems on this benchmark and other benchmarks.
  
The datasets produced will be published as open source. All the sw code produced will be published as open source. The repository will also contain automated scripts and instructions to test, maintain, add features and deploy the application. The license for the software and the datasets will be Apache-2.0 license.

# List of benchmarks

**LEXam**: Benchmarking Legal Reasoning on 340 Law Exams (https://lexam-benchmark.github.io/)  
(Fan et al. 2025)

**Lextreme** (https://arxiv.org/abs/2301.13126, https://huggingface.co/datasets/joelniklaus/lextreme)
A Multi-Lingual and Multi-Task Benchmark for the Legal Domain. It was the first multilingual legal benchmark (2023). The dataset supports the tasks of text classification and token classification (Judgment Prediction, Topic Classification, NER, etc ). As stated by the authors, LEXTREME leaves ample room for improvement. 

**LawBench** (https://lawbench.opencompass.org.cn/home, https://github.com/open-compass/LawBench/) has been developed by chinese ML researchers (Fei et al. 2023). They propose a benchmark to evaluate the extent of legal knowledge LLMs possess and whether they can reliably perform legal-related tasks. This benchmark is focused on Chinese laws and chinese oriented LLMs; e.g., they used the JEC-QA dataset collected from the National Judicial Examination of China, and the contents of laws and regulations from the national database ( https://flk.npc.gov.cn/ ).

**LegalBench** (https://hazyresearch.stanford.edu/legalbench/) is an ongoing open science effort lead by Stanford University to collaboratively curate tasks for evaluating legal reasoning in LLMs (Guha et al. 2024). All LegalBench tasks are in English and focused on common law.

**ArabLegalEval** is a multitask benchmark dataset for assessing the Arabic legal knowledge of LLMs. Inspired by the MMLU and LegalBench datasets, ArabLegalEval consists of multiple tasks sourced from Saudi legal documents and synthesized questions.

**IL-TUR**: Benchmark for Indian Legal Text Understanding and Reasoning (2024) contains monolingual (English, Hindi) and multi-lingual (9 Indian languages) domain-specific tasks that address different aspects of the legal system from the point of view of understanding and reasoning over Indian legal documents.
(Hijazi et al. 2024)



# References

(Canaverde et al. 2025) Canaverde, Beatriz, Telmo Pessoa Pires, Leonor Melo Ribeiro, and André FT Martins. "LegalBench. PT: A Benchmark for Portuguese Law." arXiv preprint arXiv:2502.16357 (2025).

(Cheong et al. 2024) Cheong, Inyoung, King Xia, KJ Kevin Feng, Quan Ze Chen, and Amy X. Zhang. "(A) I am not A lawyer, but...: engaging legal experts towards responsible LLM policies for legal advice." In Proceedings of the 2024 ACM Conference on Fairness, Accountability, and Transparency, pp. 2454-2469. 2024.

(Colombo et al. 2024) Colombo, Pierre, Telmo Pessoa Pires, Malik Boudiaf, Dominic Culver, Rui Melo, Caio Corro, Andre FT Martins et al. "Saullm-7b: A pioneering large language model for law." arXiv preprint arXiv:2403.03883 (2024). https://arxiv.org/abs/2403.03883

(Dahl et al. 2024) Matthew Dahl, Varun Magesh, Mirac Suzgun & Daniel E. Ho, Large Legal Fictions: Profiling Legal Hallucinations in Large Language Models, arXiv (2024)

(Fan et al. 2025) Fan, Y., Ni, J., Merane, J., Salimbeni, E., Tian, Y., Hermstrüwer, Y., ... & Niklaus, J. (2025). LEXam: Benchmarking Legal Reasoning on 340 Law Exams. arXiv preprint arXiv:2505.12864. https://arxiv.org/abs/2505.12864

(Fei et al. 2023) Fei, Zhiwei, Xiaoyu Shen, Dawei Zhu, Fengzhe Zhou, Zhuo Han, Songyang Zhang, Kai Chen, Zongwen Shen, and Jidong Ge. "Lawbench: Benchmarking legal knowledge of large language models." arXiv preprint arXiv:2309.16289 (2023). https://arxiv.org/abs/2309.16289

(Fei et al. 2024) Fei, Zhiwei, Songyang Zhang, Xiaoyu Shen, Dawei Zhu, Xiao Wang, Maosong Cao, Fengzhe Zhou et al. "InternLM-Law: An Open Source Chinese Legal Large Language Model." arXiv preprint arXiv:2406.14887 (2024). https://arxiv.org/abs/2406.14887

(Guha et al. 2024) Guha, Neel, Julian Nyarko, Daniel Ho, Christopher Ré, Adam Chilton, Alex Chohlas-Wood, Austin Peters et al. "Legalbench: A collaboratively built benchmark for measuring legal reasoning in large language models." Advances in Neural Information Processing Systems 36 (2024).

(Hijazi et al. 2024) Hijazi, Faris, Somayah AlHarbi, Abdulaziz AlHussein, Harethah Abu Shairah, Reem AlZahrani, Hebah AlShamlan, Omar Knio, and George Turkiyyah. "ArabLegalEval: A Multitask Benchmark for Assessing Arabic Legal Knowledge in Large Language Models." arXiv preprint arXiv:2408.07983 (2024).

Joshi, Abhinav, Shounak Paul, Akshat Sharma, Pawan Goyal, Saptarshi Ghosh, and Ashutosh Modi. "IL-TUR: Benchmark for Indian Legal Text Understanding and Reasoning." arXiv preprint arXiv:2407.05399 (2024).

(Lai et al. 2023) Lai, Jinqi, Wensheng Gan, Jiayang Wu, Zhenlian Qi, and Philip S. Yu. "Large language models in law: A survey." arXiv preprint arXiv:2312.03718 (2023).

(Magesh et al. 2024) Magesh, Varun, Faiz Surani, Matthew Dahl, Mirac Suzgun, Christopher D. Manning, and Daniel E. Ho. "Hallucination-Free? Assessing the Reliability of Leading AI Legal Research Tools." arXiv preprint arXiv:2405.20362 (2024). https://arxiv.org/abs/2405.20362

(Niklaus 2024) Niklaus, Joël. "Decoding Legalese Without Borders: Multilingual Evaluation of Language Models on Long Legal Texts." PhD diss., University of Bern, 2024.

(Niklaus et al. 2023) Niklaus, Joel, Veton Matoshi, Pooja Rani, Andrea Galassi, Matthias Stürmer, and Ilias Chalkidis. "Lextreme: A multi-lingual and multi-task benchmark for the legal domain." arXiv preprint arXiv:2301.13126 (2023)

(Palmirani et. al. 2022) Drafting legislation in the era of artificial intelligence and digitization, EU Commission, DG Informatics.

