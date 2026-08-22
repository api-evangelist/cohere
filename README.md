# cohere (cohere)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Generates a text response to a user message and streams it down, token by token.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cohere/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cohere/refs/heads/main/apis.yml)

## Timestamps

- **Modified:** 2026-05-29

## APIs

### Cohere Chat API

The Cohere Chat API enables developers to integrate large language model text generation capabilities into their applications through a conversational interface. It supports multi-turn conversations, tool use with JSON schema definitions, retrieval-augmented generation, and streaming responses. The API is available via the v2 endpoint and works with Cohere's Command family of models.

- **Human URL:** [https://docs.cohere.com/reference/chat](https://docs.cohere.com/reference/chat)
- **Base URL:** `https://api.cohere.com`

#### Tags

- Artificial Intelligence
- Chat
- Conversational AI
- Large Language Models
- Text Generation

#### Properties

- [Documentation](https://docs.cohere.com/reference/chat)
- [OpenAPI](openapi/cohere-chat-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cohere-chat-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cohere-chat-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/cohere-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)

### Cohere Embed API

The Cohere Embed API generates vector embeddings from text and images, enabling semantic search, clustering, and classification use cases. It supports multilingual content and can process both text and image inputs using the Embed v3 model family. Developers can use these embeddings to build retrieval systems, recommendation engines, and other applications that require understanding semantic similarity between content.

- **Human URL:** [https://docs.cohere.com/reference/embed](https://docs.cohere.com/reference/embed)
- **Base URL:** `https://api.cohere.com`

#### Tags

- Artificial Intelligence
- Embeddings
- Natural Language Processing
- Semantic Search
- Vector Search

#### Properties

- [Documentation](https://docs.cohere.com/reference/embed)
- [OpenAPI](openapi/cohere-embed-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cohere-embed-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cohere-embed-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cohere Rerank API

The Cohere Rerank API takes a query and a list of text documents and returns them ordered by relevance with assigned relevance scores. It is commonly used as a second-stage ranker in retrieval-augmented generation pipelines to improve the quality of search results before passing them to a language model. The API supports multilingual reranking and can significantly improve the precision of search and retrieval systems.

- **Human URL:** [https://docs.cohere.com/reference/rerank](https://docs.cohere.com/reference/rerank)
- **Base URL:** `https://api.cohere.com`

#### Tags

- Artificial Intelligence
- Information Retrieval
- Relevance
- Reranking
- Search

#### Properties

- [Documentation](https://docs.cohere.com/reference/rerank)
- [OpenAPI](openapi/cohere-rerank-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cohere-rerank-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cohere-rerank-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cohere Classify API

The Cohere Classify API performs text classification by assigning labels to input text based on provided examples. It can be used for sentiment analysis, content moderation, topic categorization, and other classification tasks. Developers provide a set of labeled examples along with texts to classify, and the API returns predicted labels with confidence scores for each input.

- **Human URL:** [https://docs.cohere.com/reference/classify](https://docs.cohere.com/reference/classify)
- **Base URL:** `https://api.cohere.com`

#### Tags

- Artificial Intelligence
- Classification
- Natural Language Processing
- Text Analysis

#### Properties

- [Documentation](https://docs.cohere.com/reference/classify)
- [OpenAPI](openapi/cohere-classify-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cohere-classify-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cohere-classify-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cohere Embed Jobs API

The Cohere Embed Jobs API allows developers to create and manage batch embedding jobs for processing large volumes of text data asynchronously. Rather than embedding texts one at a time, developers can submit datasets for bulk embedding and monitor job progress. This is useful for initializing vector databases, processing large document collections, and other scenarios where embedding large amounts of content is needed.

- **Human URL:** [https://docs.cohere.com/reference/list-embed-jobs](https://docs.cohere.com/reference/list-embed-jobs)
- **Base URL:** `https://api.cohere.com`

#### Tags

- Artificial Intelligence
- Batch Processing
- Embeddings
- Vector Search

#### Properties

- [Documentation](https://docs.cohere.com/reference/list-embed-jobs)
- [OpenAPI](openapi/cohere-embed-jobs-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cohere-embed-jobs-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cohere-embed-jobs-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cohere Datasets API

The Cohere Datasets API provides endpoints for uploading, managing, and retrieving datasets used with other Cohere services such as fine-tuning and embed jobs. Developers can create datasets from files, list existing datasets, retrieve dataset metadata, and delete datasets they no longer need. The API supports various data formats and validates uploaded data against expected schemas.

- **Human URL:** [https://docs.cohere.com/reference/list-datasets](https://docs.cohere.com/reference/list-datasets)
- **Base URL:** `https://api.cohere.com`

#### Tags

- Artificial Intelligence
- Data Management
- Datasets
- Fine-Tuning

#### Properties

- [Documentation](https://docs.cohere.com/reference/list-datasets)
- [OpenAPI](openapi/cohere-datasets-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cohere-datasets-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cohere-datasets-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cohere Models API

The Cohere Models API allows developers to list and retrieve information about available Cohere models, including the Command, Embed, and Rerank model families. It provides details such as model names, versions, supported endpoints, context lengths, and capabilities. This API is useful for programmatically discovering which models are available and selecting the appropriate model for a given task.

- **Human URL:** [https://docs.cohere.com/reference/list-models](https://docs.cohere.com/reference/list-models)
- **Base URL:** `https://api.cohere.com`

#### Tags

- Artificial Intelligence
- Machine Learning
- Models

#### Properties

- [Documentation](https://docs.cohere.com/reference/list-models)
- [OpenAPI](openapi/cohere-models-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cohere-models-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cohere-models-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cohere Tokenize API

The Cohere Tokenize API splits input text into tokens using the tokenizer associated with a specified model. It returns both the token strings and their corresponding token IDs. This is useful for understanding how text will be processed by Cohere models, estimating token counts for billing purposes, and debugging input formatting issues.

- **Human URL:** [https://docs.cohere.com/reference/tokenize](https://docs.cohere.com/reference/tokenize)
- **Base URL:** `https://api.cohere.com`

#### Tags

- Artificial Intelligence
- Natural Language Processing
- Text Processing
- Tokenization

#### Properties

- [Documentation](https://docs.cohere.com/reference/tokenize)
- [OpenAPI](openapi/cohere-tokenize-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cohere-tokenize-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cohere-tokenize-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cohere Detokenize API

The Cohere Detokenize API converts a sequence of token IDs back into their corresponding text string using the tokenizer for a specified model. It is the inverse operation of the Tokenize API and is useful for inspecting model outputs at the token level, debugging tokenization behavior, and reconstructing text from token representations.

- **Human URL:** [https://docs.cohere.com/reference/detokenize](https://docs.cohere.com/reference/detokenize)
- **Base URL:** `https://api.cohere.com`

#### Tags

- Artificial Intelligence
- Natural Language Processing
- Text Processing
- Tokenization

#### Properties

- [Documentation](https://docs.cohere.com/reference/detokenize)
- [OpenAPI](openapi/cohere-detokenize-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cohere-detokenize-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cohere-detokenize-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/cohere-ai)
- [LinkedIn](https://www.linkedin.com/company/cohere-ai)
- [JSON-LD](json-ld/cohere-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/cohere-chat-message-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cohere-embedding-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cohere-model-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cohere-dataset-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Features](undefined)
- [L L Ms Txt](https://docs.cohere.com/llms.txt)
