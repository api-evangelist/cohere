# Cohere (cohere)
Cohere is an enterprise AI platform that provides large language model APIs for text generation, embeddings, search, and classification. Their developer platform offers a suite of APIs built around the Command, Embed, and Rerank model families, enabling developers to build conversational AI, semantic search, and natural language understanding applications.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/cohere/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Artificial Intelligence, Large Language Models, Embeddings, Search, Natural Language Processing

## Timestamps

- **Created:** 2025-03-05
- **Modified:** 2026-03-20

## APIs

### Cohere Chat API
The Cohere Chat API enables developers to integrate large language model text generation capabilities into their applications through a conversational interface. It supports multi-turn conversations, tool use with JSON schema definitions, retrieval-augmented generation, and streaming responses. The API is available via the v2 endpoint and works with Cohere's Command family of models.

**Human URL:** [https://docs.cohere.com/reference/chat](https://docs.cohere.com/reference/chat)


#### Tags:

 - Artificial Intelligence, Large Language Models, Chat, Text Generation, Conversational AI

#### Properties

- [Documentation](https://docs.cohere.com/reference/chat)
- [OpenAPI](openapi/cohere-chat-api-openapi.yml)

### Cohere Embed API
The Cohere Embed API generates vector embeddings from text and images, enabling semantic search, clustering, and classification use cases. It supports multilingual content and can process both text and image inputs using the Embed v3 model family. Developers can use these embeddings to build retrieval systems, recommendation engines, and other applications that require understanding semantic similarity between content.

**Human URL:** [https://docs.cohere.com/reference/embed](https://docs.cohere.com/reference/embed)


#### Tags:

 - Artificial Intelligence, Embeddings, Vector Search, Semantic Search, Natural Language Processing

#### Properties

- [Documentation](https://docs.cohere.com/reference/embed)
- [OpenAPI](openapi/cohere-embed-api-openapi.yml)

### Cohere Rerank API
The Cohere Rerank API takes a query and a list of text documents and returns them ordered by relevance with assigned relevance scores. It is commonly used as a second-stage ranker in retrieval-augmented generation pipelines to improve the quality of search results before passing them to a language model. The API supports multilingual reranking and can significantly improve the precision of search and retrieval systems.

**Human URL:** [https://docs.cohere.com/reference/rerank](https://docs.cohere.com/reference/rerank)


#### Tags:

 - Artificial Intelligence, Search, Reranking, Relevance, Information Retrieval

#### Properties

- [Documentation](https://docs.cohere.com/reference/rerank)
- [OpenAPI](openapi/cohere-rerank-api-openapi.yml)

### Cohere Classify API
The Cohere Classify API performs text classification by assigning labels to input text based on provided examples. It can be used for sentiment analysis, content moderation, topic categorization, and other classification tasks. Developers provide a set of labeled examples along with texts to classify, and the API returns predicted labels with confidence scores for each input.

**Human URL:** [https://docs.cohere.com/reference/classify](https://docs.cohere.com/reference/classify)


#### Tags:

 - Artificial Intelligence, Classification, Text Analysis, Natural Language Processing

#### Properties

- [Documentation](https://docs.cohere.com/reference/classify)
- [OpenAPI](openapi/cohere-classify-api-openapi.yml)

### Cohere Embed Jobs API
The Cohere Embed Jobs API allows developers to create and manage batch embedding jobs for processing large volumes of text data asynchronously. Rather than embedding texts one at a time, developers can submit datasets for bulk embedding and monitor job progress. This is useful for initializing vector databases, processing large document collections, and other scenarios where embedding large amounts of content is needed.

**Human URL:** [https://docs.cohere.com/reference/list-embed-jobs](https://docs.cohere.com/reference/list-embed-jobs)


#### Tags:

 - Artificial Intelligence, Embeddings, Batch Processing, Vector Search

#### Properties

- [Documentation](https://docs.cohere.com/reference/list-embed-jobs)
- [OpenAPI](openapi/cohere-embed-jobs-api-openapi.yml)

### Cohere Datasets API
The Cohere Datasets API provides endpoints for uploading, managing, and retrieving datasets used with other Cohere services such as fine-tuning and embed jobs. Developers can create datasets from files, list existing datasets, retrieve dataset metadata, and delete datasets they no longer need. The API supports various data formats and validates uploaded data against expected schemas.

**Human URL:** [https://docs.cohere.com/reference/list-datasets](https://docs.cohere.com/reference/list-datasets)


#### Tags:

 - Artificial Intelligence, Datasets, Data Management, Fine-Tuning

#### Properties

- [Documentation](https://docs.cohere.com/reference/list-datasets)
- [OpenAPI](openapi/cohere-datasets-api-openapi.yml)

### Cohere Models API
The Cohere Models API allows developers to list and retrieve information about available Cohere models, including the Command, Embed, and Rerank model families. It provides details such as model names, versions, supported endpoints, context lengths, and capabilities. This API is useful for programmatically discovering which models are available and selecting the appropriate model for a given task.

**Human URL:** [https://docs.cohere.com/reference/list-models](https://docs.cohere.com/reference/list-models)


#### Tags:

 - Artificial Intelligence, Models, Machine Learning

#### Properties

- [Documentation](https://docs.cohere.com/reference/list-models)
- [OpenAPI](openapi/cohere-models-api-openapi.yml)

### Cohere Tokenize API
The Cohere Tokenize API splits input text into tokens using the tokenizer associated with a specified model. It returns both the token strings and their corresponding token IDs. This is useful for understanding how text will be processed by Cohere models, estimating token counts for billing purposes, and debugging input formatting issues.

**Human URL:** [https://docs.cohere.com/reference/tokenize](https://docs.cohere.com/reference/tokenize)


#### Tags:

 - Artificial Intelligence, Tokenization, Natural Language Processing, Text Processing

#### Properties

- [Documentation](https://docs.cohere.com/reference/tokenize)
- [OpenAPI](openapi/cohere-tokenize-api-openapi.yml)

### Cohere Detokenize API
The Cohere Detokenize API converts a sequence of token IDs back into their corresponding text string using the tokenizer for a specified model. It is the inverse operation of the Tokenize API and is useful for inspecting model outputs at the token level, debugging tokenization behavior, and reconstructing text from token representations.

**Human URL:** [https://docs.cohere.com/reference/detokenize](https://docs.cohere.com/reference/detokenize)


#### Tags:

 - Artificial Intelligence, Tokenization, Natural Language Processing, Text Processing

#### Properties

- [Documentation](https://docs.cohere.com/reference/detokenize)
- [OpenAPI](openapi/cohere-detokenize-api-openapi.yml)

## Common Properties

- [Portal](https://docs.cohere.com/)
- [Documentation](https://docs.cohere.com/docs)
- [Website](https://cohere.com/)
- [PrivacyPolicy](https://cohere.com/privacy)
- [TermsOfService](https://cohere.com/terms-of-use)
- [Blog](https://cohere.com/blog)
- [Login](https://dashboard.cohere.com/)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
