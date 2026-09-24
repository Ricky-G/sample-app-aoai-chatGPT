# Repository Archival Notice

On 14 October 2026, we’ll retire Azure OpenAI On Your Data. After that date, requests that depend on this feature will no longer work. This retirement affects On Your Data, not the Azure OpenAI service as a whole. 

As part of the service retired, this repository is being archived permanently. The repository will be deleted in November, once the service retires.

## Action recommended 

- Migrate your applications by 14 October 2026. For production workloads, use [Microsoft Foundry Agent Service with the Azure AI Search tool](https://learn.microsoft.com/azure/ai-foundry/agents/how-to/tools/ai-search).
- You can also evaluate [Foundry IQ knowledge bases](https://learn.microsoft.com/azure/foundry/agents/how-to/foundry-iq-connect), noting that some capabilities remain in preview. 
- To identify affected applications, check code or request logs for chat-completion calls containing data_sources or legacy dataSources. Match each application’s configured Azure OpenAI endpoint to its resource in the Azure portal. 
- Review the [On Your Data retirement notice](https://learn.microsoft.com/azure/foundry-classic/openai/concepts/use-your-data) for more information. 
- If you have additional questions, visit [Microsoft Q&A](https://learn.microsoft.com/answers/tags/387/azure-openai).
- If you have a support plan and need technical help, create an [Azure support request](https://learn.microsoft.com/azure/azure-portal/supportability/how-to-create-azure-support-request).
