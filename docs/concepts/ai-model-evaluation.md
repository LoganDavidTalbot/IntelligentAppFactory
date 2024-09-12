# AI Model Evaluation

AI Test, Evaluation, Validation and Verification (TEVV) is a critical part of the AI development lifecycle. It is important to ensure that the AI model is performing as expected and is not biased. AI model evaluation is the process of evaluating the performance of an AI model on a given dataset. The evaluation process involves measuring the performance of the model on various metrics such as accuracy, precision, recall, F1 score, etc. The evaluation process also involves identifying and mitigating any biases present including harmful content in the model.

My short AI definition for "AI Model Evaluation": tests and metrics used to evaluate the performance of an AI model on a given dataset to ensure production readiness.


## Frameworks & Tooling

There are several frameworks and tools available for AI model evaluation. Some of the popular frameworks and tools include:

- [Azure AI Studio](https://azure.microsoft.com/en-us/services/machine-learning/): Azure AI Studio is a cloud-based platform that provides a suite of tools for building, training, and deploying AI models. Azure AI Studio also provides tools for evaluating the performance of AI models. Work particularly well within the Azure ecosystem.
- [Prompt Flow](https://github.com/microsoft/promptflow): Microsoft created tool for evaluating the performance of AI models. It provides a suite of tools for measuring the performance of AI models on various metrics. This is also integrated with Azure AI Studio.
- [Amazon Bedrock](https://docs.aws.amazon.com/bedrock/latest/userguide/what-is-bedrock.html): Amazon's tool for evaluating the performance of AI models. It provides a suite of tools for measuring the performance of AI models on various metrics. Good if you are in the AWS ecosystem and your models are deployed on AWS.
- [Google's Vertex AI Studio](https://cloud.google.com/vertex-ai): Google's tool for evaluating the performance of AI models. It provides a suite of tools for measuring the performance of AI models on various metrics. Good choice if you are in the GCP ecosystem.
- [LangSmith](https://www.langchain.com/langsmith): LangSmith is a tool for evaluating the performance of AI models. It provides a suite of tools for measuring the performance of AI models on various metrics. It is a good choice if you are looking for a tool that is not tied to a specific cloud provider and can be free for a single developer but has a cost for teams.
- [TruLens](https://www.trulens.com/): Open-source tool with high transparency and expandability. It provides a suite of tools for measuring the performance of AI models on various metrics. It is a good choice if you are looking for a tool that is not tied to a specific cloud provider and is free for all users.
- [DeepEval](https://deepeval.com/): DeepEval is an open-source tool for evaluating the performance of AI models. It provides a suite of tools for measuring the performance of AI models on various metrics. It is a good choice if you are looking for a tool that is not tied to a specific cloud provider and is free for all users.

## Metrics

### Performance & Quality Metrics

There are several metrics that are commonly used to evaluate the performance of AI models. Some of the popular metrics include:
- Groundless: How well the model is grounded in the data.
- Similarity: How similar the model's predictions are to a given dataset.
- Accuracy: The percentage of correct predictions made by the model.
- Relevance:
- Coherence

### Risk &  Safety Metrics

- Content risk defect rate
- Jailbreak defect rate