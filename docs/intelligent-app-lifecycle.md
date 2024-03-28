# Intelligent Application Lifecycle

The lifecycle of an intelligent application borrows elements from both the cloud-native application and LLM application lifecycles. It is an iterative process that involves exploring, building, augmenting, improving, optimizing, and managing intelligent applications. This lifecycle is specifically designed to assist intelligent app delivery teams and organizations in creating, deploying, and managing cloud-native applications. These applications leverage large language models (LLMs) and AI services to deliver value to end users.

[![Intelligent Application Lifecycle]][Intelligent Application Lifecycle]

  [Intelligent Application Lifecycle]: images/intelligent-app-lifecyle.png
The lifecycle of an intelligent application includes the following iterative steps:

- **Explore**: Create proof of concepts and prototypes to validate their ideas and hypotheses but also to understand the capabilities and limitations of the chosen technologies.
- **Build & Augment**: Develop the core features of the intelligent application. This including implementing security and observability features, and looking to increase the AI augmentation the model to better meet the business specific needs with such techniques as retrieval augmented generation (RAG), fine tuning and prompt engineering.
- **Improve & Optimize**: Transition from development to production. This phase primarily involves deploying to a production-like environment, enhancing monitoring, incorporating content safety systems, and ensuring full integration of DevOps capabilities, including CI/CD. This phase is crucial for ensuring continuous feedback from the application itself and the end users to ensure the continuation of business value is still provided over lifetime of the application.
- **Management & Oversight**: Working in parallel to all other phase involves an structured framework to development and evaluation of Intelligent Applications. Ensuring the correct governance, management, and security of the application.

## Explore

In this initial iterative phase, either a single developer or a team of developers aim to explore and experiment with a range of cloud and AI capabilities to identify the best technology choices for their specific business needs. They work on creating proof of concepts and prototypes to validate their ideas and hypotheses, and to understand the capabilities and limitations of the technology.

A good example of this is working with a subset of data and prompts, trying to understand the capabilities and limitations of a range of LLM models through prototyping and evaluation. This exploration involves altering prompts to the models, experimenting with different chunking sizes and vector indexing methods, and conducting basic interactions while trying to validate or refute business hypotheses.

This phase is repeated until the team has a clear understanding of the capabilities and limitations of the technology and has validated their business hypotheses, thereby ensuring that the business needs can be met.


## Build & Augment

Once a delivery team has a clear understanding of the capabilities and limitations of the technology, they move Build & Augment iterative phrase which focuses on guiding and enhancing the technology to better meet the business specific needs making the application more feature rich and useable for the targeted end users. This is where core development work of an intelligent application including taking an everything as code approach to development, testing, and the creation of the application's infrastructure. As well as looking to hardening the security and observability of the application. 

From an LLM feature perspective, this may include look to fine tune the model to better align the system’s responses with the specific requirements of the task at hand, but in the most case looking to provide better prompting or the implementation of a retrieval augmented generation (RAG) approach to inject information from internal or external data sources into the prompt based on the specific user request.

## Improve & Optimize

This is the final iterative phase of the intelligent application lifecycle, which aims to transition from development to production. This phase primarily involves deploying to a production-like environment, enhancing monitoring, incorporating content safety systems, and ensuring full integration of DevOps capabilities, including CI/CD (continuous integration and continuous deployment) processes, if not already in place.

Assuming the correct governance, management, and security of the application are in place, the application is ready to be deployed to production. The intelligent application should be ready to be improved and optimized, a continuous feedback loop needs to be established with several sources crucial to providing a comprehensive view of the application's performance and user experience. This includes monitoring the application's performance and outputs, gathering user feedback, and assessing the application's ability to meet business needs. This phase is crucial for ensuring that the intelligent application continues to provide value over time and adapts to changing needs and conditions. This allows your intelligent application to react quickly to changing business needs or potential issues.

The only way to escape of this phase to go back to the previous phase of 'Build & Augment' or for the application to be decommissioned.

## Management & Oversight

This phase is a continuous process of management and oversight of the deployed application which works in parallel to all other phase. This involved ensuring an structured framework to development and evaluation of Intelligent Applications. Ensuring the correct governance, management, and security of the application. This phase is crucial for ensuring that the intelligent application continues to provide value over time and adapts to changing needs and conditions.

It is important that as part of this phase your intelligent application adhere to the best practices for responsible AI and data governance. This includes ensuring that the application is secure, compliant with regulations, and respects user privacy. By following these best practices, organizations can build trust with their users and stakeholders and ensure the long-term success of their intelligent applications.

## Sources
- [The New Stack: The Cloud-Native Application Lifecycle Difference: Continuous Change](https://thenewstack.io/cloud-native-application-lifecycle-difference-continuous-change/)
- [Microsoft Azure Blog: Building for the future: The enterprise generative AI application lifecycle with Azure AI](https://azure.microsoft.com/en-us/blog/building-for-the-future-the-enterprise-generative-ai-application-lifecycle-with-azure-ai/)