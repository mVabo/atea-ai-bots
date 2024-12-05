---
sidebar_position: 2
---

# Amazon Bedrock

Amazon Bedrock is a fully managed service that offers a choice of high-performing foundation models (FMs) from leading AI companies like AI21 Labs, Anthropic, Cohere, Luma (coming soon), Meta, Mistral AI, poolside (coming soon), Stability AI, and Amazon through a single API, along with a broad set of capabilities you need to build generative AI applications with security, privacy, and responsible AI. Using Amazon Bedrock, you can easily experiment with and evaluate top FMs for your use case, privately customize them with your data using techniques such as fine-tuning and Retrieval Augmented Generation (RAG), and build agents that execute tasks using your enterprise systems and data sources. Since Amazon Bedrock is serverless, you don't have to manage any infrastructure, and you can securely integrate and deploy generative AI capabilities into your applications using the AWS services you are already familiar with.

## Bedrock features

### Choose from a range of leading FMs

Amazon Bedrock helps you rapidly adapt and take advantage of the latest generative AI innovations with easy access to a choice of high-performing FMs from leading AI companies like AI21 Labs, Anthropic, Cohere, Luma (coming soon), Meta, Mistral AI, poolside (coming soon), Stability AI, and Amazon. In addition. Amazon Bedrock Marketplace, lets you discover, test, and use over 100 popular, emerging and specialized FMs on fully managed endpoints. The single-API access of Amazon Bedrock, regardless of the models you choose, gives you the flexibility to use different FMs and upgrade to the latest model versions with minimal code changes.

### Privately adapt models with your data

Model customization helps you deliver differentiated and personalized user experiences. To customize models for specific tasks, you can privately fine-tune FMs using your own labeled datasets in just a few quick steps. With fine-tuning and continued pretraining, Amazon Bedrock makes a separate copy of the base FM that is accessible only by you, and your data is not used to train the original base models.

### Deliver more relevant FM responses

To equip the FM with up-to-date proprietary information, organizations use RAG, a technique that involves fetching data from company data sources and enriching the prompt with that data to deliver more relevant and accurate responses. Knowledge Bases for Amazon Bedrock is a fully managed RAG capability that allows you to customize FM responses with contextual and relevant company data. Knowledge Bases for Amazon Bedrock automates the complete RAG workflow, including ingestion, retrieval, prompt augmentation, and citations, removing the need for you to write custom code to integrate data sources and manage queries. For unstructured data sources containing multimodal data, you can configure Amazon Bedrock Knowledge Bases to parse, analyze, and extract meaningful insights. For seamless processing of complex multimodal data, you can choose between Bedrock Data Automation or foundation models as the parser. For structured data sources, Amazon Bedrock Knowledge Bases provides a built-in managed Natural Language to Structured Query Language for generating a query command, allowing users to retrieve data directly from the source without the need to move or preprocess the data.

### Execute complex tasks across company systems

Agents for Amazon Bedrock plan and execute multistep tasks using company systems and data sources—from answering customer questions about your product availability to taking their orders. With Amazon Bedrock, you can create an agent in just a few quick steps by first selecting an FM and providing it access to your enterprise systems, knowledge bases, and AWS Lambda functions to securely execute your APIs. An agent analyzes the user request and automatically calls the necessary APIs and data sources to fulfill the request. Agents for Amazon Bedrock offer enhanced security and privacy—no need for you to engineer prompts, manage session context, or manually orchestrate tasks.

### Automate generation of useful insights from unstructured multimodal content for your AI-powered applications

Amazon Bedrock Data Automation streamlines the generation of valuable insights from unstructured multimodal content such as documents, images, audio, and videos, enabling you to build powerful generative AI applications and automate IDP, Media Analysis and RAG workflows quickly and cost-effectively. These insights include video summaries of key moments, detection of inappropriate image content, automated analysis of complex documents, and much more. You can customize outputs to tailor insights to your specific business needs. Bedrock Data Automation also incorporates confidence scores and visual grounding of the output data to mitigate hallucinations and improve result reliability.

## Bedrock pricing

Amazon Bedrock is a fully managed service that offers a choice of high-performing foundation models (FMs) through a single API, along with a broad set of capabilities you need to build generative AI applications with security, privacy, and responsible AI.

With Amazon Bedrock, you will be charged for model inference and customization. You have a choice of two pricing plans for inference: 1. On-Demand and Batch: This mode allows you to use FMs on a pay-as-you-go basis without having to make any time-based term commitments. 2. Provisioned Throughput: This mode allows you to provision sufficient throughput to meet your application's performance requirements in exchange for a time-based term commitment.

For more detailed pricing information, please refer to the [pricing page](https://aws.amazon.com/bedrock/pricing/).
