# Overview

1. GenAI models
1. AI Services
1. Prompt Engineering
1. AI Orchestration 
2. Embedding/ Vector databases
1. Memory management
1. Agents & Assistants
1. REST API Plugins

=== "Azure Components"

    ![Azure Components](../images/diagrams/azure-components.png)

    Explanation:

    ### Data
    | Category | Services | Description | Documentation |
    | --- | --- | --- | --- |
    | Managed Databases | Azure Cosmos DB | Globally distributed, multi-model database service | [Link](./azure/azure-cosmos-db.md) |
    | Managed Databases | Azure SQL Family | Fully managed relational database with auto-scale, integral intelligence, and robust security | [Link](https://docs.microsoft.com/en-us/azure/sql-database/) |
    | Managed Databases | Postgres | Fully managed, intelligent, and flexible PostgreSQL relational database service | [Link](https://docs.microsoft.com/en-us/azure/postgresql/) |
    | Managed Databases | Azure Cache for Redis | Fully managed, open source-compatible in-memory data store to power fast, scalable applications | [Link](https://docs.microsoft.com/en-us/azure/azure-cache-for-redis/) |
    | Managed Databases | Azure AI Search | AI-powered cloud search service for mobile and web app development | [Link](https://docs.microsoft.com/en-us/azure/search/) |
    | Storage | Azure Storage Account | Durable, highly available, and massively scalable cloud storage | [Link](https://learn.microsoft.com/en-us/azure/storage/) |
    | Analytics | Azure Synapse Analytics | Analytics service that brings together enterprise data warehousing and Big Data analytics | [Link](https://docs.microsoft.com/en-us/azure/synapse-analytics/) |
    | Analytics | Azure Event Hubs | Big data streaming platform and event ingestion service | [Link](https://docs.microsoft.com/en-us/azure/event-hubs/) |

    ### AI
    | Category | Service | Description | Documentation |
    | --- | --- | --- | --- |
    | GenAI Models | Mistral AI | LLMs created by Mistral AI for advanced AI modeling | [Link](https://docs.mistral.ai/cloud-deployment/azure/) |
    | GenAI Models | Meta | AI models developed by Meta e.g. Llama 2 | [Link](https://llama.meta.com/get-started/) |
    | GenAI Models | Azure Open AI | Open source AI models provided by Azure e.g. GPT4 | [Link](https://learn.microsoft.com/en-us/azure/ai-services/openai/) |
    | GenAI Models | Hugging Face | Open source AI Models | [Link](https://huggingface.co/) |
    | GenAI Models | Deci AI | Simplify and accelerate the development of computer vision, Generative AI, and NLP applications with advanced tools to build, optimize, and deploy accurate and highly efficient models. | [Link](https://deci.ai/blog/deci-generative-ai-models-join-azure-ai-studio/) |
    | GenAI Models | NVIDIA | NVIDIA AI Foundation Models | [Link](https://nvidianews.nvidia.com/news/nvidia-introduces-generative-ai-foundry-service-on-microsoft-azure-for-enterprises-and-startups-worldwide) |
    | GenAI Models | Microsoft Research | Cutting-edge AI models from Microsoft Research | [Link](https://techcommunity.microsoft.com/t5/ai-machine-learning-blog/welcoming-mistral-phi-jais-code-llama-nvidia-nemotron-and-more/ba-p/3982699) |
    | AI Services | Azure Cognitive Services | Suite of AI services and cognitive APIs to help developers build intelligent applications | [Link](https://learn.microsoft.com/en-us/azure/ai-services/) |
    | AI Services | Azure Machine Learning | Service that provides a cloud-based environment you can use to develop, train, test, deploy, manage, and track machine learning models | [Link](https://learn.microsoft.com/en-us/azure/machine-learning) |
    | AI Services | Azure AI Studio | Build cutting-edge, market-ready, responsible applications for your organization with AI | [Link](https://learn.microsoft.com/en-us/azure/ai-studio/) |

    ### Compute
    | Category | Service | Description | Documentation |
    | --- | --- | --- | --- |
    | AI Orchestration | Semantic Kernel | AI orchestration SDK for .NET, Java, & Python | [Link](https://learn.microsoft.com/en-us/semantic-kernel/overview/) |
    | AI Orchestration | LangChain | AI orchestration SDK for Python, & JavaScript | [Link](https://python.langchain.com/docs/get_started/introduction) |
    | Cloud Native Platform | Azure Container Apps | Fully managed service for running containerized apps | [Link](https://docs.microsoft.com/en-us/azure/container-apps/) |
    | Cloud Native Platform | Azure App Service | Fully managed platform for building, deploying, and scaling web apps | [Link](https://docs.microsoft.com/en-us/azure/app-service/) |
    | Cloud Native Platform | Azure Functions | Event-driven, serverless compute platform | [Link](https://docs.microsoft.com/en-us/azure/azure-functions/) |
    | Cloud Native Platform | Azure Kubernetes | Managed Kubernetes service for deploying, managing, and scaling containerized applications | [Link](https://docs.microsoft.com/en-us/azure/aks/) |
    | Remote Plugin/ Function (REST API) | .NET | Programming language that supports development of REST APIs | [Link](https://docs.microsoft.com/en-us/dotnet/) |
    | Remote Plugin/ Function (REST API) | Java | Programming language that supports development of REST APIs | [Link](https://docs.oracle.com/en/java/) |
    | Remote Plugin/ Function (REST API) | Python | Programming language that supports development of REST APIs | [Link](https://docs.python.org/3/) |
    | Remote Plugin/ Function (REST API) | JS/NodeJS | Programming language that supports development of REST APIs | [Link](https://nodejs.org/docs/latest/api/) |
    | Cloud Native Community | Kubernetes | Open-source system for automating deployment, scaling, and management of containerized applications | [Link](https://kubernetes.io/docs/home/) |
    | Cloud Native Community | Dapr | Event-driven, portable runtime for building microservices | [Link](https://dapr.io/) |
    | Cloud Native Community | Helm | The package manager for Kubernetes | [Link](https://helm.sh/) |
    | Cloud Native Community | KEDA | Kubernetes-based event-driven autoscaling component | [Link](https://keda.sh/) |
    | Secrets & Config | Azure App Configuration | Service that centralizes app configuration and feature settings | [Link](https://docs.microsoft.com/en-us/azure/azure-app-configuration/) |
    | Secrets & Config | Azure Key Vault | Service for securely storing and accessing secrets | [Link](https://docs.microsoft.com/en-us/azure/key-vault/) |
    
    ### Observability
    | Category | Service | Description | Documentation |
    | --- | --- | --- | --- |
    | Monitoring | Azure Monitor | Full stack monitoring service for applications and infrastructure | [Link](https://docs.microsoft.com/en-us/azure/azure-monitor/) |
    | Monitoring | Azure Application Insights | Application performance management service for developers and DevOps professionals | [Link](https://learn.microsoft.com/en-us/azure/azure-monitor/) |
    | Monitoring | Azure Managed Grafana | Fully managed Grafana service for visualizing real-time analytics | [Link](https://learn.microsoft.com/en-us/azure/managed-grafana/) |
    | Monitoring | Azure Managed Prometheus | Fully managed Prometheus service for monitoring system metrics | [Link](https://learn.microsoft.com/en-us/azure/azure-monitor/essentials/prometheus-metrics-overview) |

    ### Integration
    | Category | Service | Description | Documentation |
    | --- | --- | --- | --- |
    | Messaging | Azure Service Bus | Fully managed enterprise message broker with message queues and publish-subscribe topics | [Link](https://docs.microsoft.com/en-us/azure/service-bus-messaging/) |
    | Messaging | Azure Event Grid | Fully managed event routing service | [Link](https://docs.microsoft.com/en-us/azure/event-grid/) |
    | APIM | Azure API Management | Turnkey solution for publishing APIs to external and internal customers | [Link](https://docs.microsoft.com/en-us/azure/api-management/) |

    ### Development Tools
    | Category | Service | Description | Documentation |
    | --- | --- | --- | --- |
    | DevOps Tools | GitHub | Platform for version control and collaboration | [Link](https://docs.github.com/) |
    | DevOps Tools | Azure DevOps | Services for teams to share code, track work, and ship software | [Link](https://docs.microsoft.com/en-us/azure/devops/user-guide/) |
    | DevOps Tools | Terraform | Infrastructure as Code tool for building, changing, and versioning infrastructure | [Link](https://www.terraform.io/docs/index.html) |
    | DevOps Tools | Powershell | Task automation and configuration management framework | [Link](https://docs.microsoft.com/en-us/powershell/) |
    | DevOps Tools | Bicep | Infrastructure as Code tool for deploying infrastructure Azure resources | [Link](https://docs.microsoft.com/en-us/azure/azure-resource-manager/bicep/overview) |
    | DevOps Tools | Azure Container Registry | Managed Docker registry service for storing and managing container images | [Link](https://docs.microsoft.com/en-us/azure/container-registry/) |
    | IDEs | Visual Studio Code | Free source-code editor made by Microsoft | [Link](https://code.visualstudio.com/docs) |
    | IDEs | Visual Studio 2022 | Integrated development environment from Microsoft | [Link](https://docs.microsoft.com/en-us/visualstudio/) |
    | Copilots | GitHub Copilot | AI-powered code completion tool | [Link](https://copilot.github.com/) |
    | Copilots | Microsoft Copilot for Azure | AI-powered tool for Azure services | [Link](https://azure.microsoft.com/en-us/products/copilot#Overview) |

    

=== "AWS Components"

    !!! info "We need you!"
        
        We are looking for contributors to aid us in completing this project.