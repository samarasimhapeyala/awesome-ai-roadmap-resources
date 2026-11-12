# Portfolio projects

> 32 projects, each with free videos, repos, blogs and datasets to build it, plus what interviewers tend to probe.

[← Back to the README](README.md)

## Machine learning

### Titanic survival prediction

_Beginner_ · Pandas, scikit-learn, Feature engineering, Cross-validation

**Build:** A full tabular ML workflow: cleaning, feature engineering, cross-validation and a leaderboard submission.

**Interviewers ask:** How you handled missing values, which features mattered, and why your validation score differs from the leaderboard.

- dataset: [Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic) · Kaggle
- blog: [Titanic Tutorial](https://www.kaggle.com/code/alexisbcook/titanic-tutorial) · Alexis Cook · Kaggle

### House price regression

_Beginner_ · Regression, Ridge / Lasso, XGBoost, Target transforms

**Build:** A regression model on 79 features, comparing linear models with regularisation against gradient boosting.

**Interviewers ask:** Why you log-transformed the target, how regularisation changed the coefficients, and how you avoided leakage.

- dataset: [House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques) · Kaggle
- repo: [Hands-On Machine Learning notebooks (3rd ed.)](https://github.com/ageron/handson-ml3) · Aurélien Géron

### Customer churn prediction with explanations

_Intermediate_ · Classification, SHAP, Business metrics, Threshold tuning

**Build:** A churn classifier that explains each prediction with SHAP, plus a short write-up of who to target and why.

**Interviewers ask:** How you chose the decision threshold, what precision vs recall costs the business, and what SHAP told you.

- dataset: [Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) · Kaggle
- docs: [SHAP documentation](https://shap.readthedocs.io/en/latest/) · SHAP

### Credit card fraud detection

_Intermediate_ · Imbalanced data, PR-AUC, Resampling, Cost-sensitive learning

**Build:** A model for a dataset with 0.17% positives, comparing resampling, class weights and PR-AUC-based evaluation.

**Interviewers ask:** Why accuracy is useless here, how you evaluated the model, and how you would pick an operating point.

- dataset: [Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) · Kaggle
- docs: [imbalanced-learn user guide](https://imbalanced-learn.org/stable/) · imbalanced-learn

### Movie recommendation system

_Intermediate_ · Recommender systems, Matrix factorisation, Ranking metrics, Cold start

**Build:** Collaborative filtering and a matrix-factorisation model, evaluated with recall@k against a popularity baseline.

**Interviewers ask:** How you evaluated offline, how you'd handle new users, and how retrieval and ranking stages differ.

- dataset: [MovieLens 20M Dataset](https://www.kaggle.com/datasets/grouplens/movielens-20m-dataset) · GroupLens · Kaggle
- course: [Recommendation Systems course](https://developers.google.com/machine-learning/recommendation) · Google for Developers

### Store sales forecasting

_Intermediate_ · Time series, Backtesting, LightGBM, Seasonality

**Build:** Daily sales forecasts for thousands of store-product series, beating a seasonal-naive baseline.

**Interviewers ask:** How you split time-series data without leakage, and why you chose your baseline and error metric.

- dataset: [Store Sales - Time Series Forecasting](https://www.kaggle.com/competitions/store-sales-time-series-forecasting) · Kaggle
- blog: [Forecasting: Principles and Practice (3rd ed.)](https://otexts.com/fpp3/) · Rob J Hyndman, George Athanasopoulos

### End-to-end ML project, deployed

_Intermediate_ · Model serving, Docker, FastAPI / Flask, Cloud deployment

**Build:** Train a model, wrap it in a web service, containerise it and deploy it, following a free structured course.

**Interviewers ask:** What happens between a notebook and production, and how you'd know if the deployed model got worse.

- course: [Machine Learning Zoomcamp](https://github.com/DataTalksClub/machine-learning-zoomcamp) · DataTalks.Club

## Deep learning

### Build an autograd engine (micrograd)

_Beginner_ · Backpropagation, Chain rule, Computation graphs, Python

**Build:** A tiny automatic differentiation engine and neural net library, written from scratch in about 150 lines.

**Interviewers ask:** Walk through backprop by hand on a small graph, and explain what loss.backward() actually does.

- video: [The spelled-out intro to neural networks and backpropagation: building micrograd](https://www.youtube.com/watch?v=VMj-3S1tku0) · Andrej Karpathy
- repo: [micrograd](https://github.com/karpathy/micrograd) · Andrej Karpathy

### Image classifier in PyTorch

_Beginner_ · PyTorch, CNNs, Training loops, Data augmentation

**Build:** A CNN trained on CIFAR-10 or MNIST, with training curves, augmentation and a confusion matrix.

**Interviewers ask:** How convolutions share weights, what overfitting looked like in your curves, and what fixed it.

- docs: [Training a Classifier](https://pytorch.org/tutorials/beginner/blitz/cifar10_tutorial.html) · PyTorch tutorials
- dataset: [Digit Recognizer (MNIST)](https://www.kaggle.com/competitions/digit-recognizer) · Kaggle
- video: [But what is a neural network?](https://www.youtube.com/watch?v=aircAruvnKk) · 3Blue1Brown

### Transfer learning on your own images

_Intermediate_ · Transfer learning, Fine-tuning, Small data, Evaluation

**Build:** Fine-tune a pretrained ResNet on a small custom dataset and compare feature extraction with full fine-tuning.

**Interviewers ask:** When to freeze layers, why pretrained features transfer, and how you avoided overfitting a small dataset.

- docs: [Transfer Learning for Computer Vision](https://pytorch.org/tutorials/beginner/transfer_learning_tutorial.html) · PyTorch tutorials

### Object detection fine-tuning

_Advanced_ · Object detection, torchvision, mAP, Annotations

**Build:** Fine-tune a Mask R-CNN detector on a custom dataset and report mAP.

**Interviewers ask:** How two-stage detectors work, what anchors and IoU are, and how mAP is computed.

- docs: [TorchVision Object Detection Finetuning Tutorial](https://pytorch.org/tutorials/intermediate/torchvision_tutorial.html) · PyTorch tutorials
- repo: [PyTorch examples](https://github.com/pytorch/examples) · PyTorch

### Character-level language model (makemore)

_Intermediate_ · Language modelling, Embeddings, Sampling, PyTorch

**Build:** A model that generates new names, built up from bigrams to an MLP to a small transformer.

**Interviewers ask:** What a language model's loss means, how sampling temperature works, and how you diagnosed training.

- video: [The spelled-out intro to language modeling: building makemore](https://www.youtube.com/watch?v=PaCmpygFfXo) · Andrej Karpathy
- repo: [makemore](https://github.com/karpathy/makemore) · Andrej Karpathy
- course: [Neural Networks: Zero to Hero](https://karpathy.ai/zero-to-hero.html) · Andrej Karpathy

## NLP & transformers

### Fine-tune a transformer for text classification

_Beginner_ · Hugging Face, Tokenisation, Fine-tuning, Evaluation

**Build:** Fine-tune a pretrained BERT-style model for sentiment or topic classification with the Hugging Face Trainer.

**Interviewers ask:** What the [CLS] token is for, how fine-tuning differs from training from scratch, and how you evaluated.

- course: [LLM Course, chapter 3: Fine-tuning a pretrained model](https://huggingface.co/learn/llm-course/chapter3/1) · Hugging Face

### Build a BPE tokenizer

_Intermediate_ · Tokenisation, BPE, Unicode, Python

**Build:** The byte-pair encoding algorithm used by GPT models, trained on your own text.

**Interviewers ask:** Why LLMs struggle with spelling and arithmetic, and how vocabulary size trades off against sequence length.

- video: [Let's build the GPT Tokenizer](https://www.youtube.com/watch?v=zduSFxRajkE) · Andrej Karpathy
- repo: [minbpe](https://github.com/karpathy/minbpe) · Andrej Karpathy

### Build GPT from scratch

_Intermediate_ · Self-attention, Transformers, PyTorch, Training

**Build:** A decoder-only transformer trained on Shakespeare: self-attention, multi-head attention and residual blocks.

**Interviewers ask:** Explain attention step by step, why we scale by √dₖ, and why causal masking is needed.

- video: [Let's build GPT: from scratch, in code, spelled out.](https://www.youtube.com/watch?v=kCc8FmEb1nY) · Andrej Karpathy
- repo: [nanoGPT](https://github.com/karpathy/nanoGPT) · Andrej Karpathy
- blog: [The Illustrated Transformer](https://jalammar.github.io/illustrated-transformer/) · Jay Alammar
- video: [Attention in transformers, step-by-step](https://www.youtube.com/watch?v=eMlx5fFNoYc) · 3Blue1Brown

### Build an LLM from scratch, then fine-tune it

_Advanced_ · Pre-training, Instruction tuning, PyTorch, Evaluation

**Build:** Pre-train a small GPT-style model, load open weights, then fine-tune it for classification and instruction following.

**Interviewers ask:** The difference between pre-training, supervised fine-tuning and preference tuning, with examples from your build.

- repo: [LLMs-from-scratch](https://github.com/rasbt/LLMs-from-scratch) · Sebastian Raschka
- video: [Transformers, the tech behind LLMs](https://www.youtube.com/watch?v=wjZofJX0v4M) · 3Blue1Brown

## LLMs & GenAI

### Fine-tune an open LLM with LoRA / QLoRA

_Intermediate_ · LoRA / QLoRA, PEFT, Quantisation, Evaluation

**Build:** Fine-tune a 7–8B open model on a narrow task with QLoRA on one GPU, and compare it against prompting the base model.

**Interviewers ask:** How LoRA reduces trainable parameters, when fine-tuning beats prompting or RAG, and how you measured the gain.

- blog: [How to fine-tune open LLMs in 2025 with Hugging Face](https://www.philschmid.de/fine-tune-llms-in-2025) · Philipp Schmid
- repo: [PEFT](https://github.com/huggingface/peft) · Hugging Face
- repo: [Unsloth (free fine-tuning notebooks)](https://github.com/unslothai/unsloth) · Unsloth

### Reproduce GPT-2 (124M)

_Advanced_ · Pre-training, Mixed precision, Distributed training, Optimisation

**Build:** Train GPT-2 small from an empty file: mixed precision, flash attention, gradient accumulation and distributed training.

**Interviewers ask:** How you'd speed up training, what the learning-rate schedule does, and how you validated against the original.

- video: [Let's reproduce GPT-2 (124M)](https://www.youtube.com/watch?v=l8pRSuU81PU) · Andrej Karpathy
- repo: [build-nanogpt](https://github.com/karpathy/build-nanogpt) · Andrej Karpathy

### LLM evaluation harness

_Intermediate_ · Evals, LLM-as-judge, Prompt testing, CI

**Build:** A test suite for an LLM feature: a graded question set, LLM-as-judge checks and regression runs in CI.

**Interviewers ask:** How you know a prompt change made things better, and how you checked the judge agrees with humans.

- repo: [promptfoo](https://github.com/promptfoo/promptfoo) · promptfoo
- blog: [Patterns for Building LLM-based Systems & Products](https://eugeneyan.com/writing/llm-patterns/) · Eugene Yan

### Your first GenAI apps

_Beginner_ · Prompting, LLM APIs, Function calling, Responsible AI

**Build:** Small apps for chat, text generation, image generation and function calling, following a free 21-lesson course.

**Interviewers ask:** How you'd pick a model for a task, and how you handled cost, latency and bad outputs.

- course: [Generative AI for Beginners](https://github.com/microsoft/generative-ai-for-beginners) · Microsoft
- video: [Large Language Models explained briefly](https://www.youtube.com/watch?v=LPZh9BOjkQs) · 3Blue1Brown
- repo: [LLM Course roadmaps and notebooks](https://github.com/mlabonne/llm-course) · Maxime Labonne

## RAG

### Chat with your documents (RAG from scratch)

_Beginner_ · Embeddings, Chunking, Vector search, Prompting

**Build:** A question-answering app over your own PDFs: chunking, embeddings, a vector store and grounded answers with sources.

**Interviewers ask:** How you chose chunk size, how retrieval works, and what you do when the answer isn't in the documents.

- repo: [RAG From Scratch](https://github.com/langchain-ai/rag-from-scratch) · LangChain

### Advanced RAG with hybrid search and reranking

_Intermediate_ · Hybrid search, Reranking, Query rewriting, Ablations

**Build:** Add BM25 + vector hybrid search, a cross-encoder reranker and query rewriting, and measure each step's effect.

**Interviewers ask:** Why retrieval is usually the bottleneck, and how you proved each technique helped instead of adding latency.

- repo: [RAG Techniques](https://github.com/NirDiamant/RAG_Techniques) · Nir Diamant

### Evaluate a RAG system

_Intermediate_ · RAG evaluation, Faithfulness, Context recall, Test sets

**Build:** Build a test set and measure faithfulness, answer relevance and context recall, then fix the weakest stage.

**Interviewers ask:** How you'd tell a retrieval failure from a generation failure, using numbers rather than examples.

- docs: [Ragas documentation](https://docs.ragas.io/) · Ragas
- repo: [ragas](https://github.com/vibrantlabsai/ragas) · Ragas

### End-to-end RAG application

_Intermediate_ · RAG, Search, Monitoring, Deployment

**Build:** A complete RAG app with ingestion, search, evaluation and monitoring, built as the capstone of a free course.

**Interviewers ask:** Walk through your architecture end to end and explain what you'd change at 100× the traffic.

- course: [LLM Zoomcamp](https://github.com/DataTalksClub/llm-zoomcamp) · DataTalks.Club

## AI agents

### Tool-using agent from scratch

_Intermediate_ · Tool calling, Agent loops, Prompt design, Guardrails

**Build:** An agent loop without a framework: the model picks a tool, you run it, feed back the result, and stop safely.

**Interviewers ask:** When to use a workflow instead of an agent, how you designed tools, and how you stop runaway loops.

- blog: [Building effective agents](https://www.anthropic.com/engineering/building-effective-agents) · Anthropic
- blog: [Writing effective tools for agents](https://www.anthropic.com/engineering/writing-tools-for-agents) · Anthropic
- blog: [LLM Powered Autonomous Agents](https://lilianweng.github.io/posts/2023-06-23-agent/) · Lilian Weng

### Multi-step agent with LangGraph

_Intermediate_ · LangGraph, State machines, Memory, Human-in-the-loop

**Build:** A stateful agent graph with memory, human-in-the-loop approval and retries for a real task like research or triage.

**Interviewers ask:** How state flows through your graph, how you recover from a failed tool call, and how you tested it.

- repo: [LangGraph](https://github.com/langchain-ai/langgraph) · LangChain
- repo: [GenAI Agents tutorials](https://github.com/NirDiamant/GenAI_Agents) · Nir Diamant

### Agents course final project

_Beginner_ · Agent frameworks, Tool use, Benchmarks, Hugging Face

**Build:** Build and benchmark your own agent across smolagents, LlamaIndex and LangGraph, following a free certified course.

**Interviewers ask:** How the frameworks differ, and how you measured your agent on the benchmark.

- course: [AI Agents Course](https://huggingface.co/learn/agents-course/unit0/introduction) · Hugging Face
- repo: [agents-course](https://github.com/huggingface/agents-course) · Hugging Face

### Agent design patterns, lesson by lesson

_Beginner_ · Planning, Multi-agent systems, Agentic RAG, Safety

**Build:** Small agents for each core pattern: tool use, planning, multi-agent collaboration, agentic RAG and trust and safety.

**Interviewers ask:** Name the agent patterns you know and when each one is worth the extra complexity.

- course: [AI Agents for Beginners](https://github.com/microsoft/ai-agents-for-beginners) · Microsoft
- repo: [Claude Cookbooks](https://github.com/anthropics/claude-cookbooks) · Anthropic

## MLOps

### Production ML pipeline

_Intermediate_ · Experiment tracking, Testing ML, CI/CD, Serving

**Build:** Design, train, test, serve and iterate on a model with experiment tracking, tests and CI/CD.

**Interviewers ask:** How you test an ML system, and how a model goes from an experiment to production safely.

- repo: [Made With ML](https://github.com/GokuMohandas/Made-With-ML) · Goku Mohandas
- course: [Made With ML lessons](https://madewithml.com/) · Goku Mohandas

### MLOps capstone: tracking, orchestration, monitoring

_Intermediate_ · MLflow, Orchestration, Deployment, Monitoring

**Build:** A full MLOps project with MLflow tracking, orchestrated retraining, deployment and monitoring.

**Interviewers ask:** How you'd schedule retraining, roll back a bad model, and what you monitor after launch.

- course: [MLOps Zoomcamp](https://github.com/DataTalksClub/mlops-zoomcamp) · DataTalks.Club

### Model monitoring and drift detection

_Intermediate_ · Data drift, Monitoring, Alerting, Data quality

**Build:** Monitor a deployed model's inputs and predictions, simulate drift, and alert before quality drops.

**Interviewers ask:** The difference between data drift and concept drift, and what you'd do when an alert fires.

- repo: [Evidently](https://github.com/evidentlyai/evidently) · Evidently AI
- docs: [Evidently documentation](https://docs.evidentlyai.com/) · Evidently AI

### Design a GenAI platform

_Advanced_ · System design, LLM gateways, Caching, Observability

**Build:** An architecture write-up and prototype of an LLM gateway: routing, caching, guardrails, observability and evals.

**Interviewers ask:** Walk through an LLM platform design and the trade-offs between latency, cost and quality.

- blog: [Building A Generative AI Platform](https://huyenchip.com/2024/07/25/genai-platform.html) · Chip Huyen

