# Awesome Credit Modeling [![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

> A curated collection of recent and frontier papers, benchmarks, and resources on credit scoring and credit risk modeling.

This fork focuses on modern credit modeling: transformer-style models, reinforcement learning, LLMs, agents, alternative data, sampling bias, and explainability for regulated lending decisions.

- **Open the** [Interactive Mind Map](https://htmlpreview.github.io/?https://github.com/yankaizhao322/awesome-credit-modeling/blob/main/mindmap.html) **- Browser-rendered preview with expandable nodes, search, focus, zoom, pan, and Chinese/English voice search controls.**

    <img width="340" height="200" alt="image" src="https://github.com/user-attachments/assets/80dba1f7-4665-4ba1-9d89-dd51464867eb" />

- [Local HTML file](mindmap.html) - Use this if you clone the repository and open the file locally.

## Contents

- [Recent Surveys and Market Context](#recent-surveys-and-market-context)
- [Credit Scoring](#credit-scoring)
- [Deep Learning and Transformers](#deep-learning-and-transformers)
- [Transformer Best Practices for Credit Modeling](#transformer-best-practices-for-credit-modeling)
- [Institutional Credit Risk](#institutional-credit-risk)
- [Peer-to-Peer Lending](#peer-to-peer-lending)
- [Reinforcement Learning and Dynamic Decisions](#reinforcement-learning-and-dynamic-decisions)
- [LLMs and Financial Agents](#llms-and-financial-agents)
- [Sample Selection and Bias](#sample-selection-and-bias)
- [Model Explainability and Governance](#model-explainability-and-governance)
- [Modeler Interview Notebook and Prep](#modeler-interview-notebook-and-prep)

## Recent Surveys and Market Context

- [Credit scoring methods: Latest trends and points to consider](https://www.sciencedirect.com/science/article/pii/S2405918822000095) - Reviews credit scoring research from 2016 to 2021 and highlights recent practice shifts in datasets, validation, evaluation metrics, and model choices.

- [Fintech and big tech credit: a new database](https://www.bis.org/publ/work887.pdf) - BIS working paper mapping fintech and big tech credit markets, useful context for alternative-data and platform-lending credit models.

- [FinBen: A Holistic Financial Benchmark for Large Language Models](https://arxiv.org/abs/2402.12659) - Open benchmark for financial LLMs covering information extraction, textual analysis, question answering, risk management, forecasting, decision-making, and agent/RAG evaluation.
- [PRAGMA: Revolut Foundation Model](https://arxiv.org/abs/2604.08649) - Modern financial systems generate vast quantities of transactional and event-level data that encode rich economic signals. This paper presents PRAGMA, a family of foundation models for multi-source banking event sequences.

## Credit Scoring

- [Super-App Behavioral Patterns in Credit Risk Models: Financial, Statistical and Regulatory Implications](https://arxiv.org/abs/2005.14658) - Studies alternative data from app-based marketplaces and its predictive, statistical, and regulatory implications for underserved lending segments.

- [Machine learning predictivity applied to consumer creditworthiness](https://fbj.springeropen.com/articles/10.1186/s43093-020-00041-w) - Applies modern machine learning models to a Brazilian bank loan dataset and compares predictive accuracy against logistic regression.

## Deep Learning and Transformers

- [A Deep Learning Approach for Credit Scoring Using Feature Embedded Transformer](https://www.mdpi.com/2076-3417/12/21/10995) - Introduces FE-Transformer, combining a transformer-based deep component over online behavioral data with a wide feature component for credit scoring.

- [Explaining Deep Learning Models for Credit Scoring with SHAP: A Case Study Using Open Banking Data](https://www.mdpi.com/1911-8074/16/4/221) - Builds deep learning credit scoring models from transaction descriptions in open banking data, including multilingual BERT transfer learning, and analyzes explanations with SHAP.

- [Credit Risk Meets Large Language Models: Building a Risk Indicator from Loan Descriptions in P2P Lending](https://arxiv.org/abs/2401.16458) - Fine-tunes BERT on Lending Club loan descriptions to create a text-derived risk score used alongside tabular features for XGBoost credit risk prediction.

## Transformer Best Practices for Credit Modeling

- [Revisiting Deep Learning Models for Tabular Data](https://arxiv.org/abs/2106.11959) - Strong reference for transformer experiments on structured data. It argues for serious MLP/ResNet/GBDT baselines and introduces FT-Transformer as a competitive, but not universally dominant, option.

- [TabTransformer: Tabular Data Modeling Using Contextual Embeddings](https://arxiv.org/abs/2012.06678) - Useful when categorical variables, missingness, and semi-supervised pretraining matter in application-style tabular datasets.

- [TabPFN: A Transformer That Solves Small Tabular Classification Problems in a Second](https://arxiv.org/abs/2207.01848) - Relevant as a rapid benchmark for smaller credit datasets and model-development sanity checks.

- [Challenging Gradient Boosted Decision Trees with Tabular Transformers for Fraud Detection at Booking.com](https://arxiv.org/abs/2405.13692) - Not a lending paper, but highly relevant to production credit-model research because it compares tabular transformers against GBDTs under label-selection bias.

- **Best-practice themes to track** - Benchmark against strong scorecard/GBDT baselines, report temporal validation and calibration, study missingness and categorical encoding explicitly, and separate gains from architecture from gains caused by data leakage or richer feature pipelines.

## Institutional Credit Risk

- [Modeling Institutional Credit Risk with Financial News](https://arxiv.org/abs/2004.08204) - Predicts institutional downgrade risk using financial news embeddings, showing how unstructured text can complement rating-agency and quantitative data.

- [Forecasting Credit Ratings: A Case Study where Traditional Methods Outperform Generative LLMs](https://arxiv.org/abs/2407.17624) - Evaluates generative LLMs for corporate credit rating forecasting and finds that traditional models with fundamentals, macro data, and dense text embeddings remain highly competitive.

## Peer-to-Peer Lending

- [Network based credit risk models](https://www.tandfonline.com/doi/abs/10.1080/08982112.2019.1655159) - Augments P2P credit risk models with borrower similarity networks and centrality measures derived from financial ratios.

- [Credit Risk Meets Large Language Models: Building a Risk Indicator from Loan Descriptions in P2P Lending](https://arxiv.org/abs/2401.16458) - Uses borrower-provided loan narratives as unstructured signal for P2P default modeling.

## Reinforcement Learning and Dynamic Decisions

- [Offline Deep Reinforcement Learning for Dynamic Pricing of Consumer Credit](https://arxiv.org/abs/2203.03003) - Applies conservative offline Q-learning to personalized consumer credit pricing without requiring online experimentation during policy learning.

- [Deep reinforcement learning based on balanced stratified prioritized experience replay for customer credit scoring in peer-to-peer lending](https://link.springer.com/article/10.1007/s10462-023-10697-9) - Proposes a deep reinforcement learning method for P2P credit scoring that targets class imbalance and minority default samples through replay design.

- [Cost-sensitive reinforcement learning for credit risk](https://www.sciencedirect.com/science/article/pii/S0957417425003306) - Frames credit risk as a dynamic, cost-sensitive decision problem and extends online learning and bandit algorithms for loan-amount-dependent misclassification costs.

- [Reinforcement Learning in Credit Scoring and Underwriting](https://arxiv.org/abs/2212.07632) - Studies underwriting as a sequential decision problem with renewed action spaces and multiple underwriting choices.

- [Optimizing Credit Limit Adjustments Under Adversarial Goals Using Reinforcement Learning](https://arxiv.org/abs/2306.15585) - Frames line-management policy as an RL optimization problem balancing revenue and provisioning.

- **Best-practice themes to track** - Prefer offline RL or contextual bandit framing when online experiments are unrealistic, define reward functions in profit/risk terms, evaluate policies off-policy before deployment, and document constraints around fairness, approval-rate drift, and delayed defaults.

## LLMs and Financial Agents

- [Empowering Many, Biasing a Few: Generalist Credit Scoring through Large Language Models](https://arxiv.org/abs/2310.00566) - Explores LLMs for credit scoring across multiple datasets and proposes CALM, an instruction-tuned credit and risk assessment language model with bias analysis.

- [Credit scoring model for fintech lending: An integration of large language models and FocalPoly loss](https://www.sciencedirect.com/science/article/pii/S0169207024000724) - Proposes LLM-FP-CatBoost, where LLMs extract narrative data as supplementary credit information and FocalPoly loss addresses class imbalance.

- [MASCA: LLM based-Multi Agents System for Credit Assessment](https://arxiv.org/abs/2507.22758) - Introduces a multi-agent LLM framework for credit assessment, with specialized agents collaborating on risk, reward, and fairness-oriented sub-tasks.

## Sample Selection and Bias

- [Fighting Sampling Bias: A Framework for Training and Evaluating Credit Scoring Models](https://arxiv.org/abs/2407.13009) - Revisits reject inference and sampling bias in credit scoring, proposing bias-aware self-learning and Bayesian evaluation when labels are observed only for accepted applicants.

- [Empowering Many, Biasing a Few: Generalist Credit Scoring through Large Language Models](https://arxiv.org/abs/2310.00566) - Includes fairness and bias analysis for LLM-based credit decisions, making it relevant beyond predictive performance.

## Model Explainability and Governance

- [Explaining Deep Learning Models for Credit Scoring with SHAP: A Case Study Using Open Banking Data](https://www.mdpi.com/1911-8074/16/4/221) - Uses SHAP to inspect deep credit scoring models built on open banking transaction descriptions.

- [Regulatory learning: How to supervise machine learning models? An application to credit scoring](https://www.sciencedirect.com/science/article/pii/S2405918817300648) - Discusses supervision of dynamic machine learning credit scoring models and the need for model libraries, switching strategies, and risk-mitigated innovation.

## Modeler Interview Notebook and Prep

- [Credit_Risk_Modelling](https://github.com/levist7/Credit_Risk_Modelling) - Practical notebook sequence covering PD, LGD, EAD, expected loss, cutoff analysis, and population stability monitoring.

- [HELOC Interpretable Machine Learning](https://github.com/annabelleluo/HELOC) - Good interview-prep notebook for explainability, monotonicity constraints, and model comparison on a well-known credit dataset.

- [Graph-based Credit Scoring](https://github.com/awslabs/sagemaker-graph-based-credit-scoring) - Adds a useful notebook for network features and firm-linkage thinking beyond standard application-scorecard workflows.

- [Real-time Credit Scoring with Feast on Local Setup](https://github.com/feast-dev/feast-credit-score-local-tutorial) - Helpful for discussing training/serving consistency, feature stores, and productionization questions in interviews.

- [Credit Risk Modeling (PD/LGD/EAD): Introduction (Part 1)](https://www.youtube.com/watch?v=q4TaJHmu788) - Concise video refresher for the vocabulary interviewers often expect candidates to use precisely.

- [Model Risk interview](https://www.reddit.com/r/quant/comments/vse9wr/model_risk_interview/) - Community discussion that surfaces likely preparation areas such as PD/LGD/EAD, regression families, and model-validation framing.

- **Notebook prompts worth preparing** - Build one compact notebook each for scorecard-style PD, tree/boosting baseline, explainability, stability monitoring, and a small offline policy experiment so you can speak from artifacts instead of only from theory.

- **Chinese-language discovery** - Xiaohongshu search terms such as `信用评分 面试`, `风控 建模`, `PD LGD EAD`, and `授信策略` can surface practitioner interview notes and study roadmaps. Treat them as discovery aids and verify technical claims against papers, code, or regulations.
