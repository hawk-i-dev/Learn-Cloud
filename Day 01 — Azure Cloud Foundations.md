## Day 1 — Azure Cloud Foundations

Today’s goal: understand how Azure organizes cloud resources and create your first project structure.

Key ideas:

- **Cloud computing:** renting computing services online instead of owning servers.
- **Azure subscription:** your billing and access boundary.
- **Resource group:** a folder-like container for one project’s Azure resources.
- **Region:** the physical Azure location where a service runs, such as Central India.
- **Resource:** an individual service—Storage Account, Virtual Machine, Azure OpenAI, etc.

Think of it like this:

```text
Azure account
└── Subscription
    └── Resource group: rg-ai-learning-dev
        ├── Storage Account
        ├── Azure AI service
        └── Web App
```

Your first hands-on task:

1. Create or sign in to an Azure account.
2. Open the Azure Portal.
3. Search for **Resource groups**.
4. Choose **Create**.
5. Select your subscription.
6. Name it: `rg-ai-learning-dev`
7. Choose a nearby region, such as **Central India**.
8. Select **Review + create**, then **Create**.

Why this matters: every AI app you build later should keep its related Azure services in a dedicated resource group. It makes access, costs, deployment, and cleanup much easier.

Mini quiz:

1. What is the difference between a resource group and a resource?
2. Why does choosing an Azure region matter?
3. Where would an Azure OpenAI service sit in the structure above?

Tomorrow, we can cover Azure’s core services—compute, storage, networking, and databases—using an AI application as the running example.
