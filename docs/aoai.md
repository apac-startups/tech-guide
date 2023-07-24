# Azure Open AI

This section covers interesting technical guides for Azure OpenAI which includes models like GPT-4 and da-vinci and ....



## Hands on Course
https://learn.microsoft.com/en-us/users/nataliemickey-1929/collections/w4grfn275nnp0w?wt.mc_id=build23_breakout_collection_azuremktg_BRK214H


## Prompt Engineering

https://learn.microsoft.com/en-us/azure/cognitive-services/openai/concepts/prompt-engineering

Best Practices from OpenAI:
https://platform.openai.com/docs/guides/gpt-best-practices?

### Hands-on

https://learn.microsoft.com/en-us/training/modules/apply-prompt-engineering-azure-openai/

## Retrieval Augmented Generation (RAG)


### Leveraging native Cognitive Search
A sample app for the Retrieval-Augmented Generation pattern running in Azure, using Azure Cognitive Search for retrieval and Azure OpenAI large language models to power ChatGPT-style and Q&A experiences.
The integration between Azure OpenAI and Cognitive search relies on an orchestrator application

https://github.com/Azure-Samples/azure-search-openai-demo

### Using Vector Search in Azure Cognitive Search

Automatically helps do embeddings for you, leveraging Azure Cognitive Search. This demonstrates a direct integration between Azure OpenAI and Cognitive Search.

https://github.com/Azure/cognitive-search-vector-pr/tree/main




## Reference architecture - inlcd logging queries, throttling controls, etc
This a reference architecture demonstrating how you can get:
- Comprehensive logging of Azure OpenAI model execution tracked to Source IP address.
- Advanced Usage and Throttling controls
- High availability of the model APIs
- Security via role based access

https://github.com/Azure-Samples/openai-python-enterprise-logging#readme

## Function calling

This enables you to leverage GPT to call a catalog of functions we define. The value here is
1. Extend functionality of GPT to custom actions
2. a mechanism to more deterministically control the output returned in certain use cases.

### Official docs:
https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/function-calling#defining-functions

from openAI
https://platform.openai.com/docs/guides/gpt/function-calling


### A straightforward practical guided introduction
https://medium.com/@james.matson_64120/the-next-evolution-of-azure-openai-gpt-models-a-guide-to-executing-functions-baa93d67aeaa