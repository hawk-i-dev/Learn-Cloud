Great place to start. We’ll learn Azure through small, practical steps—with AI as the focus.

Start with this roadmap:

1. Azure basics — subscriptions, resource groups, regions, identity, and cost control.
2. Core cloud services — compute, storage, networking, databases.
3. Azure AI — Azure AI Foundry, Azure OpenAI, AI Search, and document intelligence.
4. Build projects — a chatbot, RAG document assistant, and an AI-powered API.
5. Production skills — security, monitoring, deployments, and responsible AI.

Lesson 1: Azure’s basic structure

- A **subscription** is your billing and access boundary.
- A **resource group** is a logical container for related resources in one project.
- A **resource** is a service instance, such as an Azure OpenAI resource, Storage Account, or Web App.
- A **region** is the geographic Azure datacenter location where a resource runs.

For example, an “AI Study Assistant” could have:

```text
Subscription
└── Resource group: rg-ai-study-dev
    ├── Azure OpenAI / Azure AI Foundry
    ├── Azure AI Search
    ├── Storage Account (PDFs and uploads)
    └── Web App (the user interface)
```

My suggested first goal: build a small Azure AI chatbot, then evolve it into a document-question-answering assistant.
