# cohere (cohere)

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
