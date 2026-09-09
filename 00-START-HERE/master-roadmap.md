# AI/ML Master Roadmap

A practical path from programming basics to production AI systems. Use the tracks in order, but loop back whenever a project exposes a gap.

## How to study

1. Learn a concept from one primary course or book.
2. Reproduce the examples in a notebook.
3. Complete a small exercise without copying the solution.
4. Build a project and write a short README explaining decisions, metrics, and limitations.
5. Keep experiments, datasets, and environments reproducible.

## Stage 0: Setup and orientation

- Git and GitHub: branches, commits, pull requests, issues.
- Python environment management: `venv` or Conda, Jupyter, VS Code.
- Command line basics, Markdown, package installation, and data privacy.
- Start with [p-n/ai-ml-roadmap](https://github.com/p-n/ai-ml-roadmap) as the broad map.

## Stage 1: Python foundations

**Goal:** write clear Python without relying on notebooks to hide the control flow.

- Syntax, variables, conditionals, loops, functions, modules, exceptions.
- Lists, dictionaries, sets, tuples, comprehensions, iterators.
- Files, JSON, CSV, APIs, testing, debugging, and object-oriented basics.
- NumPy arrays and vectorized operations.
- Pandas Series, DataFrames, joins, grouping, reshaping, and time series.

Primary practice: `01-FOUNDATIONS/Python/`.

## Stage 2: Data foundations and preprocessing

**Goal:** turn imperfect raw data into an auditable analysis table.

- Data types, schemas, missingness, duplicates, leakage, and sampling.
- Exploratory analysis and visualization.
- SQL: relational modeling, filtering, aggregation, joins, subqueries, and windows.
- Reproducible preprocessing pipelines.

Primary practice: `02-DATA-SCIENCE/` and `04-SQL/`.

## Stage 3: Mathematics and statistics

**Goal:** understand the assumptions and mechanics behind models.

- Linear algebra: vectors, matrices, projections, eigenvectors, SVD.
- Calculus: derivatives, gradients, chain rule, partial derivatives.
- Probability: random variables, conditional probability, Bayes, expectations.
- Statistics: estimation, confidence intervals, hypothesis testing, regression.
- Optimization: objectives, convexity, gradient descent, regularization.

Primary practice: `01-FOUNDATIONS/Mathematics/`.

## Stage 4: Machine learning foundations

**Goal:** build a trustworthy baseline and evaluate it correctly.

- Train/validation/test splits and cross-validation.
- Regression, classification, trees, ensembles, nearest neighbors, and clustering.
- Feature preprocessing, pipelines, hyperparameter search, and calibration.
- Metrics, error analysis, interpretability, fairness, and data leakage.

Primary practice: `05-MACHINE-LEARNING/`.

## Stage 5: Feature engineering

**Goal:** represent real-world signals in a way models can learn.

- Missing values, outliers, encoding, scaling, transformations.
- Feature selection, dimensionality reduction, imbalanced data.
- Explainability with SHAP and model interpretation.

Primary practice: `03-FEATURE-ENGINEERING/` and the local book *Feature Engineering for Machine Learning*.

## Stage 6: Deep learning

**Goal:** understand and train neural networks with PyTorch.

- Tensors, datasets, dataloaders, modules, autograd, optimization.
- MLPs, CNNs, sequence models, transfer learning, and experiment tracking.
- Checkpoints, reproducibility, GPU memory, regularization, and deployment concerns.

Primary practice: `07-DEEP-LEARNING/`.

## Stage 7: Computer vision

**Goal:** solve image classification, detection, and segmentation problems.

- Image tensors, augmentation, CNNs, transfer learning.
- Object detection, instance and semantic segmentation.
- Dataset labeling, evaluation, error analysis, and inference pipelines.

Primary practice: `08-COMPUTER-VISION/`.

## Stage 8: NLP

**Goal:** progress from text features to transformer-based language models.

- Text cleaning, tokenization, bag-of-words, TF-IDF, and embeddings.
- RNNs/LSTMs, attention, transformers, BERT, fine-tuning.
- Dataset preparation, evaluation, bias, and responsible language modeling.

Primary practice: `09-NLP/`.

## Stage 9: Generative AI and LLM applications

**Goal:** build useful, measurable systems around language models.

- Transformer internals, embeddings, prompting, structured outputs.
- Vector databases, retrieval-augmented generation, agents, and tool use.
- Fine-tuning, LoRA, QLoRA, evaluation, cost, latency, safety, and observability.

Primary practice: `10-GENERATIVE-AI/`. Prefer current official documentation over old API examples.

## Stage 10: MLOps and production

**Goal:** make models repeatable, deployable, observable, and maintainable.

- Git workflows, Docker, data/model versioning, MLflow.
- APIs with FastAPI, CI/CD, orchestration, monitoring, and cloud basics.
- Data and concept drift, rollback plans, security, governance, and incident response.

Primary practice: `11-MLOPS/`.

## Capstone progression

1. Clean and analyze a public tabular dataset.
2. Train and explain a classical ML model.
3. Deploy it behind an API with tests.
4. Train a PyTorch image or text model.
5. Build a RAG application with a held-out evaluation set.
6. Package the best project with Docker, tracking, monitoring, and a clear model card.

## Resource policy

This repository links to original sources and keeps local notes, exercises, and lawful materials. Check each upstream license before copying notebooks, datasets, or code. The existing PDFs are for personal study; do not redistribute them without permission.
