# Cohere GraphQL Schema

This document describes a conceptual GraphQL schema for the Cohere AI API, covering the full surface of Cohere's language model, embedding, reranking, classification, tokenization, dataset, connector, and model management capabilities.

## Provider

**Name:** Cohere  
**Base URL:** https://api.cohere.com  
**Docs:** https://docs.cohere.com/reference/  
**GitHub:** https://github.com/cohere-ai

## Schema Overview

The schema covers the following capability areas:

### Chat and Text Generation
Types for multi-turn conversations, streaming responses, tool use, retrieval-augmented generation, and citations: `ChatRequest`, `ChatResponse`, `NonStreamedChatResponse`, `StreamedChatResponse`, `StreamingChatTextGeneration`, `Message`, `UserMessage`, `AssistantMessage`, `SystemMessage`, `ToolMessage`, `ChatResponseText`, `ChatResponseSearchQueries`, `ChatResponseCitations`.

### Tool Use and Function Calling
Types for defining tools and processing tool results: `Tool`, `ToolParameter`, `CohereTool`, `ToolCall`, `ToolCallDelta`, `ToolResult`.

### Retrieval-Augmented Generation
Types for citations, search results, documents, and search queries used in RAG pipelines: `Citation`, `SearchResult`, `Document`, `SearchQuery`.

### Text Generation (Legacy)
Types for non-conversational text completion: `GenerateRequest`, `GenerateResponse`, `Generation`, `Token`, `LogprobItem`.

### Embeddings
Types for generating and working with vector embeddings: `EmbedRequest`, `EmbedResponse`, `Embedding`, `EmbedType`, `EmbedJob`, `EmbedJobStatus`.

### Reranking
Types for relevance-based reranking of documents: `RerankRequest`, `RerankResponse`, `RerankResult`.

### Classification
Types for few-shot text classification: `ClassifyRequest`, `ClassifyResponse`, `Classification`, `ClassifyExample`, `ClassifyLabel`.

### Tokenization
Types for tokenizing and detokenizing text: `TokenizeRequest`, `TokenizeResponse`, `DetokenizeRequest`, `DetokenizeResponse`.

### Models
Types for listing and inspecting available models: `Model`, `ModelCapability`, `ModelEndpoint`.

### Datasets and Files
Types for managing datasets used in fine-tuning and embed jobs: `Dataset`, `DatasetValidation`, `File`.

### Connectors
Types for managing connectors used in RAG over external data sources: `Connector`, `ConnectorAuthStatus`, `ConnectorOAuthConfig`.

### Users and Organization
Types for managing API keys, users, and organization membership: `APIKey`, `User`, `OrganizationUser`.

## Queries

- `chat(input: ChatRequest!)` — Perform a chat completion
- `generate(input: GenerateRequest!)` — Generate text (legacy)
- `embed(input: EmbedRequest!)` — Generate embeddings
- `rerank(input: RerankRequest!)` — Rerank documents by relevance
- `classify(input: ClassifyRequest!)` — Classify text inputs
- `tokenize(input: TokenizeRequest!)` — Tokenize text
- `detokenize(input: DetokenizeRequest!)` — Detokenize token IDs
- `listModels` — List available models
- `getModel(modelId: String!)` — Get a specific model
- `listDatasets` — List datasets
- `getDataset(datasetId: String!)` — Get a specific dataset
- `listEmbedJobs` — List embed jobs
- `getEmbedJob(jobId: String!)` — Get a specific embed job
- `listConnectors` — List connectors
- `getConnector(connectorId: String!)` — Get a specific connector

## Mutations

- `createEmbedJob(input: EmbedJobInput!)` — Start a batch embed job
- `cancelEmbedJob(jobId: String!)` — Cancel an in-progress embed job
- `createDataset(input: DatasetInput!)` — Upload a new dataset
- `deleteDataset(datasetId: String!)` — Delete a dataset
- `createConnector(input: ConnectorInput!)` — Register a new connector
- `updateConnector(connectorId: String!, input: ConnectorInput!)` — Update connector settings
- `deleteConnector(connectorId: String!)` — Delete a connector
- `authorizeConnector(connectorId: String!)` — Initiate OAuth for a connector
- `createAPIKey(name: String!)` — Create a new API key
- `deleteAPIKey(keyId: String!)` — Delete an API key

## Subscriptions

- `streamChat(input: ChatRequest!)` — Stream a chat response token by token

## Schema File

See `cohere-schema.graphql` for the full type definitions.
