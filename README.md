# Awesome Credit Modeling [![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

> A growing collection of awesome papers, articles, datasets, and resources on credit scoring and credit risk modeling.

Credit scoring is the term used to describe formal statistical methods used for classifying applicants for credit into risk classes. Lenders use such classifications to assess an applicant's creditworthiness and probability of default.

## Contents

- [Introduction](#introduction)
- [Fintech and Market Context](#fintech-and-market-context)
- [Credit Scoring](#credit-scoring)
- [Deep Learning and Transformers](#deep-learning-and-transformers)
- [Institutional Credit Risk](#institutional-credit-risk)
- [Peer-to-Peer Lending](#peer-to-peer-lending)
- [Reinforcement Learning and Dynamic Credit Decisions](#reinforcement-learning-and-dynamic-credit-decisions)
- [Large Language Models and Credit Risk](#large-language-models-and-credit-risk)
- [Sample Selection](#sample-selection)
- [Feature Selection](#feature-selection)
- [Model Explainability and Governance](#model-explainability-and-governance)

## Introduction

- [Statistical Classification Methods in Consumer Credit Scoring: A Review](https://www.jstor.org/stable/2983268) - Classic introduction and review of the subject of credit scoring.

- [Consumer Finance: Challenges for Operational Research](https://www.jstor.org/stable/40540227) - Reviews the development of credit scoring, the way of assessing risk in consumer finance, and what is meant by a credit score. Outlines challenges for Operational Research to support modelling in consumer finance.

- [Machine Learning in Credit Risk Modeling](https://www.slideshare.net/YvanDeMunck/machine-learning-in-credit-risk-modeling-a-james-white-paper) - Overview of machine learning applications in credit risk modeling from James, a formerly active online credit risk management startup.

- ['Lending by numbers': credit scoring and the constitution of risk within American consumer credit](https://www.tandfonline.com/doi/abs/10.1080/03085140601089846) - Examines how statistical credit-scoring technologies became applied by lenders to control default risk within American consumer credit.

- [Machine Learning in Financial Crisis Prediction: A Survey](https://ieeexplore.ieee.org/document/6069610) - Reviews machine-learning techniques for bankruptcy prediction and credit score modeling.

## Fintech and Market Context

- [Fintech and big tech credit: a new database](https://www.bis.org/publ/work887.pdf) - BIS working paper mapping fintech and big tech credit markets, useful context for platform lending, alternative credit, and non-bank credit growth.

- [Consumer Credit Trends](https://www.consumerfinance.gov/data-research/consumer-credit-trends/) - CFPB tool tracking consumer credit market trends, including mortgages, credit cards, auto loans, student loans, and credit inquiries.

- [Finextra](https://www.finextra.com/) - Industry news and research resource for banking technology, payments, open banking, capital markets, wealth, and fintech innovation.

- [The Fintech Times](https://thefintechtimes.com/) - Fintech-focused news outlet covering industry trends, startups, digital finance, payments, banking technology, and regulatory developments.

## Credit Scoring

- [Benchmarking state-of-the-art classification algorithms for credit scoring: An update of research](https://www.sciencedirect.com/science/article/abs/pii/S0377221715004208) - Compares novel classification algorithms with state-of-the-art credit scoring methods and examines how model assessment changes across predictive accuracy indicators.

- [Classification methods applied to credit scoring: Systematic review and overall comparison](https://www.sciencedirect.com/science/article/abs/pii/S1876735416300101) - Systematic review of binary classification techniques for credit scoring and financial risk analysis.

- [Classifier Technology and the Illusion of Progress](https://projecteuclid.org/euclid.ss/1149600839) - Argues that simple classifiers often perform nearly as well as more complex methods once uncertainty and practical constraints are considered.

- [Financial credit risk assessment: a recent review](https://dl.acm.org/doi/10.1007/s10462-015-9434-x) - Summarizes traditional statistical models and intelligent methods for financial distress forecasting.

- [Good practice in retail credit scorecard assessment](https://www.tandfonline.com/doi/abs/10.1057/palgrave.jors.2601932) - Discusses performance monitoring for retail credit scorecards and limitations of common measures such as Gini, KS, mean difference, and information value.

- [A literature review on the application of evolutionary computing to credit scoring](https://link.springer.com/article/10.1057/jors.2012.145) - Reviews developments in the application of evolutionary algorithms to credit scoring.

- [Machine learning predictivity applied to consumer creditworthiness](https://fbj.springeropen.com/articles/10.1186/s43093-020-00041-w) - Applies modern machine learning models to a Brazilian bank loan dataset and compares predictive accuracy against logistic regression.

- [Consumer credit-risk models via machine-learning algorithms](https://alo.mit.edu/wp-content/uploads/2015/06/Household-behaviorConsumer-credit-riskCredit-card-borrowingMachine-learningNonparametric-estimation.pdf) - Applies machine learning to construct nonlinear forecasting models of consumer credit risk.

- [Example-Dependent Cost-Sensitive Logistic Regression for Credit Scoring](https://ieeexplore.ieee.org/document/7033125) - Develops a cost-sensitive logistic regression approach where misclassification costs vary across examples.

- [Credit scoring using the clustered support vector machine](https://www.sciencedirect.com/science/article/abs/pii/S0957417414005119) - Introduces clustered SVM for credit scorecard development, targeting scalability issues in nonlinear SVM methods.

- [A comparative study on base classifiers in ensemble methods for credit scoring](https://www.sciencedirect.com/science/article/abs/pii/S0957417416306947) - Compares base classifiers in ensemble methods for credit risk assessment.

- [Multiple classifier application to credit risk assessment](https://www.sciencedirect.com/science/article/abs/pii/S0957417409008847) - Studies classifier behavior under different noise conditions and investigates ensemble methods for improving credit risk prediction.

- [Recent developments in consumer credit risk assessment](https://www.sciencedirect.com/science/article/abs/pii/S0377221706011866) - Reviews consumer credit risk assessment, data quality issues, and the challenge of training on accepted applicants only.

- [A survey of credit and behavioural scoring: forecasting financial risk of lending to consumers](https://www.sciencedirect.com/science/article/abs/pii/S0169207000000340) - Surveys statistical and operational research methods for credit and behavioural scoring.

- [The comparisons of data mining techniques for the predictive accuracy of probability of default of credit card clients](https://www.sciencedirect.com/science/article/abs/pii/S0957417407006719) - Compares data mining methods for estimating probability of default among credit card clients.

- [Super-App Behavioral Patterns in Credit Risk Models: Financial, Statistical and Regulatory Implications](https://arxiv.org/abs/2005.14658) - Studies alternative data from app-based marketplaces and its predictive, statistical, and regulatory implications for underserved lending segments.

- [Credit scoring methods: Latest trends and points to consider](https://www.sciencedirect.com/science/article/pii/S2405918822000095) - Reviews credit scoring research from 2016 to 2021 and highlights recent trends in datasets, validation, metrics, and model choices.

## Deep Learning and Transformers

- [Revisiting Deep Learning Models for Tabular Data](https://arxiv.org/abs/2106.11959) - Important benchmark paper for tabular deep learning; argues for strong MLP, ResNet, and GBDT baselines when evaluating transformer-style models.

- [TabTransformer: Tabular Data Modeling Using Contextual Embeddings](https://arxiv.org/abs/2012.06678) - Introduces contextual embeddings for categorical tabular features and is relevant to credit datasets with many categorical variables.

- [TabPFN: A Transformer That Solves Small Tabular Classification Problems in a Second](https://arxiv.org/abs/2207.01848) - Transformer-based method for small tabular classification problems, useful as a rapid benchmark or sanity check.

- [A Deep Learning Approach for Credit Scoring Using Feature Embedded Transformer](https://www.mdpi.com/2076-3417/12/21/10995) - Introduces FE-Transformer, combining transformer-based feature learning with credit scoring.

- [Explaining Deep Learning Models for Credit Scoring with SHAP: A Case Study Using Open Banking Data](https://www.mdpi.com/1911-8074/16/4/221) - Builds deep learning credit scoring models from open banking transaction data and uses SHAP for explanation.

- [Challenging Gradient Boosted Decision Trees with Tabular Transformers for Fraud Detection at Booking.com](https://arxiv.org/abs/2405.13692) - Not a lending paper, but useful for production-style comparison between tabular transformers and GBDTs under label-selection bias.

## Institutional Credit Risk

- [Availability of Credit to Small Businesses](https://www.federalreserve.gov/publications/2017-september-availability-of-credit-to-small-businesses.htm) - Federal Reserve report on the availability of credit to small businesses.

- [Credit Scoring and the Availability, Price, and Risk of Small Business Credit](https://muse.jhu.edu/article/181124) - Studies the association between small business credit scoring and credit availability, price, and risk.

- [Credit Risk Assessment Using Statistical and Machine Learning: Basic Methodology and Risk Modeling Applications](https://link.springer.com/article/10.1023/A:1008699112516) - Compares statistical and machine learning classification methods on mortgage loan data.

- [Random Survival Forests Models for SME Credit Risk Measurement](https://link.springer.com/article/10.1007/s11009-008-9078-2) - Applies Random Survival Forests to SME credit default risk and compares performance with a standard logit model.

- [Modeling Institutional Credit Risk with Financial News](https://arxiv.org/abs/2004.08204) - Predicts institutional downgrade risk using financial news embeddings.

- [Bankruptcy prediction for credit risk using neural networks: A survey and new results](https://ieeexplore.ieee.org/document/935101) - Reviews bankruptcy prediction with neural networks and develops a neural-network bankruptcy prediction model.

- [Forecasting Credit Ratings: A Case Study where Traditional Methods Outperform Generative LLMs](https://arxiv.org/abs/2407.17624) - Evaluates generative LLMs for corporate credit rating forecasting and finds traditional models with fundamentals, macro data, and text embeddings remain highly competitive.

## Peer-to-Peer Lending

- [Network based credit risk models](https://www.tandfonline.com/doi/abs/10.1080/08982112.2019.1655159) - Augments P2P credit risk models with borrower similarity networks and centrality measures derived from financial ratios.

- [Credit Risk Meets Large Language Models: Building a Risk Indicator from Loan Descriptions in P2P Lending](https://arxiv.org/abs/2401.16458) - Fine-tunes BERT on Lending Club loan descriptions and uses the text-derived risk score alongside tabular features for credit risk prediction.

## Reinforcement Learning and Dynamic Credit Decisions

- [Offline Deep Reinforcement Learning for Dynamic Pricing of Consumer Credit](https://arxiv.org/abs/2203.03003) - Applies conservative offline Q-learning to personalized consumer credit pricing without requiring online experimentation during policy learning.

- [Reinforcement Learning in Credit Scoring and Underwriting](https://arxiv.org/abs/2212.07632) - Studies underwriting as a sequential decision problem with renewed action spaces and multiple underwriting choices.

- [Optimizing Credit Limit Adjustments Under Adversarial Goals Using Reinforcement Learning](https://arxiv.org/abs/2306.15585) - Frames credit line management as a reinforcement learning problem balancing revenue and provisioning.

- [Deep reinforcement learning based on balanced stratified prioritized experience replay for customer credit scoring in peer-to-peer lending](https://link.springer.com/article/10.1007/s10462-023-10697-9) - Proposes a deep reinforcement learning method for P2P credit scoring with class-imbalance-aware replay.

## Large Language Models and Credit Risk

- [FinBen: A Holistic Financial Benchmark for Large Language Models](https://arxiv.org/abs/2402.12659) - Financial LLM benchmark covering information extraction, textual analysis, question answering, risk management, forecasting, decision-making, and agent/RAG evaluation.

- [Empowering Many, Biasing a Few: Generalist Credit Scoring through Large Language Models](https://arxiv.org/abs/2310.00566) - Explores LLMs for credit scoring across multiple datasets and proposes CALM, an instruction-tuned credit and risk assessment language model.

- [Credit scoring model for fintech lending: An integration of large language models and FocalPoly loss](https://www.sciencedirect.com/science/article/pii/S0169207024000724) - Proposes LLM-FP-CatBoost, where LLMs extract narrative data as supplementary credit information and FocalPoly loss addresses class imbalance.

- [PRAGMA: Revolut Foundation Model](https://arxiv.org/abs/2604.08649) - Presents a family of foundation models for multi-source banking event sequences, useful for understanding emerging research on transaction- and event-level financial modeling.

## Sample Selection

- [Reject inference in application scorecards: evidence from France](https://econpapers.repec.org/paper/drmwpaper/2016-10.htm) - Introduction and discussion of reject inference in application scorecards.

- [Reject inference, augmentation, and sample selection](https://www.sciencedirect.com/science/article/abs/pii/S0377221706011969) - In-depth discussion of reject inference, augmentation, and sample selection in credit scoring.

- [Instance sampling in credit scoring: An empirical study of sample size and balancing](http://www.research.lancs.ac.uk/portal/en/publications/instance-sampling-in-credit-scoring-an-empirical-study-of-sample-size-and-balancing(89b83914-c7f2-499a-8fa1-844d6cb6004d).html) - Discusses sample size and balancing conventions in credit modeling.

- [Fighting Sampling Bias: A Framework for Training and Evaluating Credit Scoring Models](https://arxiv.org/abs/2407.13009) - Revisits reject inference and sampling bias when labels are observed only for accepted applicants.

## Feature Selection

- [A multi-objective approach for profit-driven feature selection in credit scoring](https://www.sciencedirect.com/science/article/pii/S0167923619300570) - Proposes profit-driven feature selection for credit scoring.

- [Data mining feature selection for credit scoring models](https://link.springer.com/article/10.1057/palgrave.jors.2601976) - Empirical study of machine learning feature selection methods for credit scoring.

- [Combination of feature selection approaches with SVM in credit scoring](https://www.sciencedirect.com/science/article/abs/pii/S0957417409010719) - Studies SVM-based feature selection approaches for credit scoring.

## Model Explainability and Governance

- [Explainable Machine learning in Credit Risk Management](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3506274) - Proposes explainable AI methods for credit risk management.

- [Machine learning explainability in finance: an application to default risk analysis](https://www.bankofengland.co.uk/working-paper/2019/machine-learning-explainability-in-finance-an-application-to-default-risk-analysis) - Bank of England working paper on explaining machine learning models in default risk analysis.

- [Explaining Deep Learning Models for Credit Scoring with SHAP: A Case Study Using Open Banking Data](https://www.mdpi.com/1911-8074/16/4/221) - Uses SHAP to inspect deep credit scoring models built on open banking transaction descriptions.

- [Regulatory learning: How to supervise machine learning models? An application to credit scoring](https://www.sciencedirect.com/science/article/pii/S2405918817300648) - Discusses supervision of dynamic machine learning credit scoring models and risk-mitigated model innovation.

- [Good practice in retail credit scorecard assessment](https://www.tandfonline.com/doi/abs/10.1057/palgrave.jors.2601932) - Useful governance reference for monitoring credit scorecard performance over time.
