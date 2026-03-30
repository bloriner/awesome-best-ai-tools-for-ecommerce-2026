---
title: "best-ai-tools-for-ecommerce-2026"
description: "Best AI tools for ecommerce in 2026: a curated open source GitHub list for search, recommendations, chat, catalog enrichment, and demand forecasting."
icon: 📋
category: artificial-intelligence
---

# Best AI Tools for Ecommerce in 2026

[![Awesome](https://cdn.jsdelivr.net/gh/sindresorhus/awesome@main/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Topics](https://img.shields.io/github/stars/GagnDeep/awesome-best-ai-tools-for-ecommerce-2026?style=social)

> This curated list of the best AI tools for ecommerce in 2026 focuses only on open source projects that exist as public GitHub repositories. It is built for teams that want recommendation engines, product search, support automation, visual catalog tooling, and forecasting stacks they can inspect, self-host, extend, and benchmark without depending on closed SaaS lock-in.

## Table of Contents
- [TL;DR](#tldr)
- [Why This List](#why-this-list)
- [Open Source Tools](#open-source-tools)
- [FAQ](#faq)
- [Contributing](#contributing)
- [License](#license)

## TL;DR
- `gorse`, `metarank`, and `recommenders-team/recommenders` are the strongest open source starting points for ecommerce ranking and recommendation work.
- `Meilisearch`, `Typesense`, `OpenSearch`, `Vespa`, and `Qdrant` cover most search, hybrid retrieval, and vector discovery use cases for product catalogs.
- `Rasa`, `Flowise`, `Langflow`, `ChatFAQ`, and `Libre Chat` are practical building blocks for conversational commerce and support automation.
- `docTR`, `clip-retrieval`, `Marqo`, and `Label Studio` help with product imagery, OCR, multimodal search, and annotation workflows.
- `NeuralForecast`, `Darts`, `Prophet`, `NeuralProphet`, and `GluonTS` are strong open source options for demand planning and inventory-aware forecasting.

## Why This List
Open source AI tools matter in ecommerce because search quality, ranking logic, customer support flows, and forecasting models directly affect revenue. A strong open source stack gives teams control over data, deployment, observability, and cost structure while making it easier to tune the best AI tools for ecommerce in 2026 around real catalog, traffic, and fulfillment constraints.

## Open Source Tools

### Recommendation and Ranking

#### [Gorse](https://github.com/gorse-io/gorse)
> **Description:** Gorse is an AI-powered recommender system written in Go and built for fast integration into online services. Its README highlights support for collaborative filtering, item-to-item and user-to-user recommendations, multimodal embeddings, dashboard-based pipeline management, and REST APIs for CRUD and recommendation requests. That makes it a strong fit for ecommerce teams building "related products", "you may also like", or homepage personalization with a deployable service instead of a notebook-only library. GitHub shows roughly 9.6k stars, Go as the main language, Apache-2.0 licensing, and recent commit activity on Mar 7, 2026.

- **GitHub:** [github.com/gorse-io/gorse](https://github.com/gorse-io/gorse)
- **Stars:** 9.6k ⭐
- **Language:** Go
- **License:** Apache-2.0
- **Last Commit:** 2026-03-07
- **Category:** recommendation, personalization
- **Best for:** real-time product recommendations

---

#### [Metarank](https://github.com/metarank/metarank)
> **Description:** Metarank is a low-code open source ranking service designed for personalized search and recommendations. Its README explicitly positions it for listings, search results, recommendations, and CTR optimization with customer signals such as clicks and purchases. It supports learning-to-rank, semantic or neural search, collaborative filtering recommendations, feature generation, A/B testing, and stateless deployment with Redis-backed state. For ecommerce teams, that is useful when a plain search engine is not enough and business wants reranking based on behavior. GitHub shows about 2.2k stars, Scala as the main language, Apache-2.0 licensing, and repository activity updated Sep 24, 2025.

- **GitHub:** [github.com/metarank/metarank](https://github.com/metarank/metarank)
- **Stars:** 2.2k ⭐
- **Language:** Scala
- **License:** Apache-2.0
- **Last Commit:** 2025-09-24
- **Category:** ranking, search-personalization
- **Best for:** personalized product listing reranking

---

#### [RecBole](https://github.com/RUCAIBox/RecBole)
> **Description:** RecBole is a comprehensive recommendation research and development framework built on Python and PyTorch. The README notes support for 94 recommendation algorithms across general, sequential, context-aware, and knowledge-based recommendation, plus 44 benchmark datasets and a unified data format. That breadth makes it valuable when ecommerce teams want to benchmark models before productionizing them in a separate serving layer. It is more of a toolkit than a drop-in service, but it is unusually broad. GitHub shows roughly 4.3k stars, Python as the primary language, MIT licensing, and recent commit history on Feb 24, 2025.

- **GitHub:** [github.com/RUCAIBox/RecBole](https://github.com/RUCAIBox/RecBole)
- **Stars:** 4.3k ⭐
- **Language:** Python
- **License:** MIT
- **Last Commit:** 2025-02-24
- **Category:** recommendation, experimentation
- **Best for:** benchmarking ecommerce recommendation algorithms

---

#### [Recommenders](https://github.com/recommenders-team/recommenders)
> **Description:** The Recommenders project focuses on best practices for recommendation systems rather than a single serving runtime. Its README emphasizes notebooks, examples, data preparation, model training, evaluation, and production-minded guidance across classic and modern recommenders. That makes it useful for ecommerce engineering and data teams that need reproducible reference implementations for ranking, collaborative filtering, retrieval, and evaluation workflows before choosing a serving architecture. It is backed by LF AI and Data, which helps with trust and longevity. GitHub shows around 21.3k stars, Python as the main language, MIT licensing, and the latest visible GitHub release on Dec 24, 2024.

- **GitHub:** [github.com/recommenders-team/recommenders](https://github.com/recommenders-team/recommenders)
- **Stars:** 21.3k ⭐
- **Language:** Python
- **License:** MIT
- **Last Commit:** 2024-12-24
- **Category:** recommendation, best-practices
- **Best for:** reference implementations and evaluation workflows

---

#### [LensKit for Python](https://github.com/lenskit/lkpy)
> **Description:** LensKit is a Python toolkit for studying, training, and evaluating recommender algorithms in a flexible way. The README presents it as a research and education oriented successor to the original Java LensKit project, with modern packaging, experiment support, and a focus on reproducible recommender workflows. It is a good fit for ecommerce teams that want to prototype recommendation logic, offline evaluation, and candidate-generation experiments before turning ideas into services. GitHub shows about 300 stars, Python as the main language, MIT licensing, and repository activity updated Nov 25, 2025.

- **GitHub:** [github.com/lenskit/lkpy](https://github.com/lenskit/lkpy)
- **Stars:** 300 ⭐
- **Language:** Python
- **License:** MIT
- **Last Commit:** 2025-11-25
- **Category:** recommendation, offline-evaluation
- **Best for:** recommender experimentation and offline tests

---

### Search, Discovery, and Vector Retrieval

#### [Meilisearch](https://github.com/meilisearch/meilisearch)
> **Description:** Meilisearch is a fast, typo-tolerant search engine that is easy to integrate into applications and storefronts. Its GitHub organization describes it as lightweight and developer friendly, while the ecosystem includes an ecommerce demo covering faceted search, filtering, sorting, and AI-powered image search. For ecommerce, Meilisearch is especially attractive when the priority is fast implementation, relevant product search, and clean API ergonomics without operating a large search cluster. GitHub shows roughly 55.4k stars, Rust as the primary language, MIT licensing, and repository activity updated Jan 14, 2026.

- **GitHub:** [github.com/meilisearch/meilisearch](https://github.com/meilisearch/meilisearch)
- **Stars:** 55.4k ⭐
- **Language:** Rust
- **License:** MIT
- **Last Commit:** 2026-01-14
- **Category:** search, product-discovery
- **Best for:** fast storefront search and faceting

---

#### [Typesense](https://github.com/typesense/typesense)
> **Description:** Typesense is an open source search engine built around fast, typo-tolerant, in-memory search. The GitHub organization positions it as an easier-to-use alternative to heavier search stacks and as an open alternative to Algolia-style developer search experiences. For ecommerce teams, it fits product search, category landing pages, autosuggest, merchandising filters, and hybrid retrieval when low operational friction matters. Its ecosystem also includes adapters for rich frontend experiences. GitHub shows about 25k stars, C++ as the primary language, GPL-3.0 licensing, and repository activity updated Jan 12, 2026.

- **GitHub:** [github.com/typesense/typesense](https://github.com/typesense/typesense)
- **Stars:** 25k ⭐
- **Language:** C++
- **License:** GPL-3.0
- **Last Commit:** 2026-01-12
- **Category:** search, faceted-search
- **Best for:** typo-tolerant product search

---

#### [OpenSearch](https://github.com/opensearch-project/OpenSearch)
> **Description:** OpenSearch is a distributed search and analytics engine suited to enterprise-scale workloads. Its README describes it as an enterprise-grade suite that brings order to unstructured data at scale, while the GitHub organization highlights application search as a core use case. In ecommerce, OpenSearch is a strong candidate for large catalogs, multi-index architectures, log analytics tied to search relevance, and teams that need a mature distributed platform with a broad ecosystem. GitHub shows roughly 12.1k stars, Java as the primary language, Apache-2.0 licensing, and repository activity updated Jan 9, 2026.

- **GitHub:** [github.com/opensearch-project/OpenSearch](https://github.com/opensearch-project/OpenSearch)
- **Stars:** 12.1k ⭐
- **Language:** Java
- **License:** Apache-2.0
- **Last Commit:** 2026-01-09
- **Category:** search, distributed-search
- **Best for:** large-scale catalog search infrastructure

---

#### [Vespa](https://github.com/vespa-engine/vespa)
> **Description:** Vespa is built for low-latency computation over large structured, text, and vector data. Its GitHub organization explicitly calls out real-time recommendation, personalization, targeting, and vector search, which maps very directly to ecommerce ranking and discovery workloads. Vespa is more infrastructure-heavy than lightweight search engines, but it is powerful for organizations that want serving, ranking, retrieval, and online feature computation in one platform. GitHub shows about 6.6k to 6.7k stars, Java as the main language, Apache-2.0 licensing, and repository activity updated Dec 1, 2025.

- **GitHub:** [github.com/vespa-engine/vespa](https://github.com/vespa-engine/vespa)
- **Stars:** 6.7k ⭐
- **Language:** Java
- **License:** Apache-2.0
- **Last Commit:** 2025-12-01
- **Category:** vector-search, ranking
- **Best for:** hybrid retrieval and real-time ranking

---

#### [Qdrant](https://github.com/qdrant/qdrant)
> **Description:** Qdrant is a high-performance vector database and vector search engine focused on similarity search with payload-aware filtering. The README explicitly mentions matching, recommending, faceted search, similar image search, semantic text search, and even ecommerce product categorization as practical applications. That makes it one of the clearest fits on this list for modern ecommerce retrieval, where dense vectors, sparse vectors, and metadata filters all matter. GitHub shows roughly 28.7k stars, Rust as the main language, Apache-2.0 licensing, and repository activity updated Feb 8, 2026.

- **GitHub:** [github.com/qdrant/qdrant](https://github.com/qdrant/qdrant)
- **Stars:** 28.7k ⭐
- **Language:** Rust
- **License:** Apache-2.0
- **Last Commit:** 2026-02-08
- **Category:** vector-database, semantic-search
- **Best for:** embedding-powered product retrieval

---

### Catalog Enrichment, Vision, and Annotation

#### [Marqo](https://github.com/marqo-ai/marqo)
> **Description:** Marqo is a unified embedding generation and search engine built for multimodal retrieval. The GitHub organization describes it as tensor search for humans and a single system for generating embeddings and searching over them. In ecommerce, that matters for similar product search, image-led browsing, multimodal discovery, and semantic retrieval over product titles, descriptions, and visual assets. It is especially useful where search quality depends on combining text and image understanding. GitHub shows roughly 5k stars, Python as the primary language, Apache-2.0 licensing, and repository activity updated Nov 27, 2025.

- **GitHub:** [github.com/marqo-ai/marqo](https://github.com/marqo-ai/marqo)
- **Stars:** 5.0k ⭐
- **Language:** Python
- **License:** Apache-2.0
- **Last Commit:** 2025-11-27
- **Category:** multimodal-search, catalog-enrichment
- **Best for:** visual and semantic product discovery

---

#### [docTR](https://github.com/mindee/doctr)
> **Description:** docTR is an OCR-focused deep learning library for document text recognition. Its README emphasizes text localization, word recognition, and end-to-end OCR models, along with a demo app and deployment-friendly packaging. For ecommerce teams, that is valuable for ingesting supplier PDFs, extracting attributes from invoices or catalogs, and turning semi-structured merchandising documents into machine-usable data. It is not a storefront tool on its own, but it solves an important catalog ingestion problem upstream of search and product information management. GitHub shows roughly 5.7k stars, Python as the main language, Apache-2.0 licensing, and visible GitHub release activity on Jul 9, 2025.

- **GitHub:** [github.com/mindee/doctr](https://github.com/mindee/doctr)
- **Stars:** 5.7k ⭐
- **Language:** Python
- **License:** Apache-2.0
- **Last Commit:** 2025-07-09
- **Category:** ocr, catalog-ingestion
- **Best for:** extracting product data from documents

---

#### [clip-retrieval](https://github.com/rom1504/clip-retrieval)
> **Description:** clip-retrieval is built to compute CLIP embeddings and serve large-scale text-image retrieval. The README walks through inference, indexing, filtering, backend hosting, and a simple UI, making it possible to build semantic search over images and captions with relatively little glue code. For ecommerce, this is useful for "find visually similar products", image-led navigation, and multimodal browsing where product photos matter as much as keywords. It is more of a toolkit than a full application, but it is unusually practical. GitHub shows about 1.8k stars, Python as the main language, MIT licensing, and active GitHub repository history visible in 2025.

- **GitHub:** [github.com/rom1504/clip-retrieval](https://github.com/rom1504/clip-retrieval)
- **Stars:** 1.8k ⭐
- **Language:** Python
- **License:** MIT
- **Last Commit:** 2025-01-01
- **Category:** visual-search, embeddings
- **Best for:** similar-image and multimodal product search

---

#### [Label Studio](https://github.com/HumanSignal/label-studio)
> **Description:** Label Studio is an open source data labeling and annotation platform that supports text, images, audio, video, and time series. The README highlights customizable interfaces, model-assisted pre-labeling, active learning, and API integration into existing pipelines. In ecommerce, that is useful for training product classifiers, moderation systems, attribute extractors, image tagging models, and support intent datasets. It is not an AI model itself, but it is a key piece of the open source AI workflow for teams creating proprietary retail datasets. GitHub shows roughly 25.5k to 25.9k stars, JavaScript as the dominant language, Apache-2.0 licensing, and repository activity updated Nov 17, 2025.

- **GitHub:** [github.com/HumanSignal/label-studio](https://github.com/HumanSignal/label-studio)
- **Stars:** 25.9k ⭐
- **Language:** JavaScript
- **License:** Apache-2.0
- **Last Commit:** 2025-11-17
- **Category:** data-labeling, training-data
- **Best for:** creating labeled ecommerce datasets

---

#### [Open Semantic Search](https://github.com/opensemanticsearch/open-semantic-search)
> **Description:** Open Semantic Search is an open source semantic search and text analytics platform for searching, browsing, and analyzing large document collections. The organization README highlights ETL, document extraction, OCR, metadata management, and exploration tooling. For ecommerce operations, that can help with internal knowledge bases, vendor documents, manuals, return policies, marketplace feeds, or support content that needs semantic retrieval and document understanding. This category is a smaller fit for pure ecommerce than search or recommendation infrastructure, so it is also an honest edge case in the list. GitHub shows about 1.1k stars, Shell as the main language, AGPL-3.0 licensing, and active organization-level maintenance through 2025.

- **GitHub:** [github.com/opensemanticsearch/open-semantic-search](https://github.com/opensemanticsearch/open-semantic-search)
- **Stars:** 1.1k ⭐
- **Language:** Shell
- **License:** AGPL-3.0
- **Last Commit:** 2025-01-01
- **Category:** semantic-search, document-processing
- **Best for:** internal knowledge and supplier document search

---

### Conversational Commerce and Support Automation

#### [Rasa](https://github.com/RasaHQ/rasa)
> **Description:** Rasa is an open source conversational AI framework for building reliable, scalable agents. GitHub describes it as suitable for text- and voice-based conversations with dialogue management, NLU, and production-minded orchestration. For ecommerce, Rasa fits customer support bots, order-status flows, return handling, product guidance, and layered automation where LLM flexibility needs to be constrained by business rules. It remains one of the strongest open source choices when conversational systems must be auditable and operationally controlled. GitHub shows about 21k stars, Python as the primary language, Apache-2.0 licensing, and repository activity updated Dec 18, 2025.

- **GitHub:** [github.com/RasaHQ/rasa](https://github.com/RasaHQ/rasa)
- **Stars:** 21.0k ⭐
- **Language:** Python
- **License:** Apache-2.0
- **Last Commit:** 2025-12-18
- **Category:** conversational-ai, support-automation
- **Best for:** rule-aware customer support agents

---

#### [Flowise](https://github.com/FlowiseAI/Flowise)
> **Description:** Flowise is a visual builder for AI agents and workflows. Its README focuses on self-hosting, multi-module architecture, deployment options, and visual composition of LLM and agent pipelines. In ecommerce, this is useful for quickly standing up internal copilots, support assistants, RAG workflows over policies or catalogs, and process automations that connect LLM steps to existing tools. It is best suited to teams that want a low-code orchestration layer but still need access to source code and self-hosting options. GitHub shows about 47.8k stars, TypeScript as the primary language, Apache-2.0 licensing, and repository activity updated Dec 29, 2025.

- **GitHub:** [github.com/FlowiseAI/Flowise](https://github.com/FlowiseAI/Flowise)
- **Stars:** 47.8k ⭐
- **Language:** TypeScript
- **License:** Apache-2.0
- **Last Commit:** 2025-12-29
- **Category:** ai-agents, workflow-builder
- **Best for:** low-code ecommerce AI workflows

---

#### [Langflow](https://github.com/langflow-ai/langflow)
> **Description:** Langflow is a visual platform for building and deploying AI agents and workflows with built-in API and MCP server capabilities. The README emphasizes visual authoring, source-level customization in Python, an interactive playground, observability integrations, and deployment as APIs or tools. For ecommerce teams, it can be used to prototype shopping assistants, support bots, internal ops copilots, and retrieval workflows tied to product or policy data. It is broader than a chatbot framework and especially useful when workflows need to graduate into reusable internal tools. GitHub shows roughly 142k to 143k stars, Python as the primary language, MIT licensing, and repository activity updated Jan 3, 2026.

- **GitHub:** [github.com/langflow-ai/langflow](https://github.com/langflow-ai/langflow)
- **Stars:** 143k ⭐
- **Language:** Python
- **License:** MIT
- **Last Commit:** 2026-01-03
- **Category:** ai-agents, visual-builder
- **Best for:** prototyping and deploying ecommerce assistants

---

#### [ChatFAQ](https://github.com/ChatFAQ/ChatFAQ)
> **Description:** ChatFAQ is an open source ecosystem for building conversational solutions with LLMs, RAG, agents, and finite-state logic. The README lists a backend, SDK, widget, admin dashboard, and infrastructure for retrieval and orchestration. That makes it directly relevant for storefront assistants, FAQ agents, order support, and embedded chat experiences where the frontend widget matters as much as the backend pipeline. It is smaller than Rasa or Langflow, but the project is opinionated around business-facing chat experiences. GitHub shows around 149 stars, Python as the primary language, MIT licensing, and recent commit activity visible in early 2025.

- **GitHub:** [github.com/ChatFAQ/ChatFAQ](https://github.com/ChatFAQ/ChatFAQ)
- **Stars:** 149 ⭐
- **Language:** Python
- **License:** MIT
- **Last Commit:** 2025-01-01
- **Category:** chat-widget, rag
- **Best for:** embedded conversational commerce widgets

---

#### [Libre Chat](https://github.com/vemonet/libre-chat)
> **Description:** Libre Chat is a self-hosted chatbot web UI and API for open source LLMs. Its README highlights offline-capable deployment, YAML-based configuration, OpenAPI support, CPU-friendly operation, and optional document-based question answering. For ecommerce teams, that makes it suitable for internal support assistants, knowledge-base search, policy QA, or lightweight self-hosted chat experiences that do not depend on proprietary hosted models. It is earlier-stage than the larger orchestration projects, but the self-hosted simplicity is a real advantage in some environments. GitHub shows about 164 stars, Python as the primary language, MIT licensing, and recent visible repository activity in 2025.

- **GitHub:** [github.com/vemonet/libre-chat](https://github.com/vemonet/libre-chat)
- **Stars:** 164 ⭐
- **Language:** Python
- **License:** MIT
- **Last Commit:** 2025-01-01
- **Category:** self-hosted-chatbot, llm-ui
- **Best for:** private self-hosted support chat

---

### Forecasting and Demand Planning

#### [NeuralForecast](https://github.com/Nixtla/neuralforecast)
> **Description:** NeuralForecast is a library of neural forecasting models built with usability and strong benchmarks in mind. The README emphasizes a broad set of architectures from RNNs to transformer-style models, support for exogenous variables, probabilistic forecasting, automatic model selection, and a familiar `.fit()` / `.predict()` interface. For ecommerce, it is a strong option for SKU-level demand forecasting, promotion-aware planning, and inventory-sensitive replenishment work where classical models are not enough. GitHub shows roughly 3.9k stars, Python as the primary language, Apache-2.0 licensing, and repository activity updated Jan 14, 2026.

- **GitHub:** [github.com/Nixtla/neuralforecast](https://github.com/Nixtla/neuralforecast)
- **Stars:** 3.9k ⭐
- **Language:** Python
- **License:** Apache-2.0
- **Last Commit:** 2026-01-14
- **Category:** forecasting, demand-planning
- **Best for:** neural demand forecasting for products

---

#### [Darts](https://github.com/unit8co/darts)
> **Description:** Darts is a user-friendly library for time series forecasting and anomaly detection. The README highlights a unified API across statistical and deep learning models, support for backtesting, multivariate series, covariates, probabilistic forecasting, and anomaly workflows. For ecommerce, it is a practical choice when teams need a broad forecasting toolbox for demand, traffic, conversion, returns, or stockout risk without committing to one modeling family too early. It is especially attractive for experimentation because the interfaces are consistent. GitHub shows about 9.3k stars, Python as the primary language, Apache-2.0 licensing, and repository activity updated Mar 27, 2026.

- **GitHub:** [github.com/unit8co/darts](https://github.com/unit8co/darts)
- **Stars:** 9.3k ⭐
- **Language:** Python
- **License:** Apache-2.0
- **Last Commit:** 2026-03-27
- **Category:** forecasting, anomaly-detection
- **Best for:** flexible retail time-series modeling

---

#### [Prophet](https://github.com/facebook/prophet)
> **Description:** Prophet is a well-known forecasting library built for time series with strong seasonal effects, non-linear growth, and holidays. Its README emphasizes robustness to missing data, outliers, and trend shifts, all of which are common in ecommerce calendars affected by promotions, seasonality, and operational disruptions. Prophet is not the newest approach in this category, but it remains one of the fastest ways to establish a durable forecasting baseline for marketing, demand, and planning problems. GitHub shows about 18.7k stars, Python as the primary language, MIT licensing, and visible GitHub release activity through 2025.

- **GitHub:** [github.com/facebook/prophet](https://github.com/facebook/prophet)
- **Stars:** 18.7k ⭐
- **Language:** Python
- **License:** MIT
- **Last Commit:** 2025-01-01
- **Category:** forecasting, seasonality
- **Best for:** fast baseline demand forecasting

---

#### [NeuralProphet](https://github.com/ourownstory/neural_prophet)
> **Description:** NeuralProphet extends the Prophet style of workflow with PyTorch-based neural components while keeping interpretability and iterative modeling in view. The README describes support for trend, seasonality, lagged regressors, future regressors, events, quantile regression, and human-in-the-loop refinement. For ecommerce, that is useful when teams need stronger forecasting flexibility than Prophet while still wanting understandable components for promotions, holidays, and exogenous business drivers. It is a practical bridge between classical and neural retail forecasting stacks. GitHub shows roughly 3k stars, Python as the primary language, MIT licensing, and the latest visible release on Jun 21, 2024.

- **GitHub:** [github.com/ourownstory/neural_prophet](https://github.com/ourownstory/neural_prophet)
- **Stars:** 3.0k ⭐
- **Language:** Python
- **License:** MIT
- **Last Commit:** 2024-06-21
- **Category:** forecasting, interpretable-ml
- **Best for:** explainable demand models with neural components

---

#### [GluonTS](https://github.com/awslabs/gluonts)
> **Description:** GluonTS is a probabilistic time series modeling library with deep learning models built around forecasting. The README focuses on probabilistic forecasts, PyTorch and MXNet support, pretrained Chronos work, and a mature research-backed ecosystem. For ecommerce, that makes it relevant when demand planning requires uncertainty estimates rather than point forecasts alone, which is often the case for inventory buffers, replenishment, or marketplace volatility. GluonTS is more library-oriented than turnkey, but it is one of the stronger probabilistic forecasting foundations available on GitHub. GitHub shows about 5.1k stars, Python as the primary language, Apache-2.0 licensing, and latest visible GitHub release activity on Jun 27, 2025.

- **GitHub:** [github.com/awslabs/gluonts](https://github.com/awslabs/gluonts)
- **Stars:** 5.1k ⭐
- **Language:** Python
- **License:** Apache-2.0
- **Last Commit:** 2025-06-27
- **Category:** probabilistic-forecasting, demand-planning
- **Best for:** inventory planning with uncertainty estimates

---

## FAQ

### What are the best open source AI tools for ecommerce in 2026?
For most teams, the strongest starting set is `gorse` or `metarank` for ranking, `Meilisearch` or `Typesense` for search, `Qdrant` or `Vespa` for vector retrieval, `Rasa` or `Langflow` for conversational workflows, and `NeuralForecast` or `Darts` for demand planning.

### Are these really open source and hosted on GitHub?
Yes. Every entry in this list links to a public `github.com` repository. Closed SaaS-only products were excluded. Some projects also sell managed hosting, but the repositories listed here are public and self-hostable.

### Which tools are best for product recommendation engines?
`gorse`, `metarank`, `RecBole`, `recommenders-team/recommenders`, and `LensKit` are the clearest recommendation-focused repos in this list. `Vespa` and `Qdrant` also matter when recommendation is built on retrieval or vector similarity.

### Which open source AI tools help ecommerce search the most?
`Meilisearch`, `Typesense`, `OpenSearch`, `Vespa`, and `Qdrant` are the main search stack choices here. The right pick depends on whether you need typo tolerance, distributed scale, hybrid search, or vector-heavy retrieval.

### What is the best open source stack for conversational commerce?
If you need high control and business rules, start with `Rasa`. If you want rapid workflow assembly, look at `Flowise` or `Langflow`. If you need embedded chat experiences with RAG, `ChatFAQ` and `Libre Chat` are worth testing.

### Which repos are best for forecasting ecommerce demand?
`NeuralForecast`, `Darts`, `Prophet`, `NeuralProphet`, and `GluonTS` cover most forecasting needs from fast baselines to probabilistic and neural approaches.

### Are there any category gaps in open source ecommerce AI on GitHub?
Yes. Dynamic pricing optimization, returns fraud models, and end-to-end merchandising copilots have fewer mature GitHub-native repos than search, recommendation, and forecasting. Those gaps are real, and this list reflects that instead of padding with irrelevant tools.

## GitHub Search Queries Used

```bash
gh search repos "recommender ecommerce ai in:name,description,readme stars:>50"
gh search repos "learning to rank ecommerce search recommendation stars:>50"
gh search repos "open source product search vector database ecommerce stars:>100"
gh search repos "multimodal search image retrieval product catalog stars:>50"
gh search repos "open source chatbot rag ecommerce support stars:>50"
gh search repos "time series forecasting retail demand stars:>100"
gh search repos "ocr product catalog extraction stars:>50"
gh search repos "data labeling annotation machine learning stars:>100"
```

## Contributing
Contributions are welcome. Please read [CONTRIBUTING.md](./CONTRIBUTING.md) before opening a pull request.

Submission requirements:
- The tool must have a public `github.com` repository URL.
- No proprietary SaaS-only products.
- Include current GitHub stars, primary language, license, and recent activity date.
- Explain the ecommerce use case clearly.

## License
MIT License. See [LICENSE](./LICENSE).
