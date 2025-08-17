# My-First-Logic-App
# Azure Logic App: Simple Email Sender

This repository contains a simple Azure Logic App workflow that demonstrates fundamental serverless concepts. The workflow is triggered by an HTTP request and sends a custom email via the Gmail connector.

It is designed as a learning resource for anyone getting started with Azure Logic Apps and cloud integration.

## Key Concepts Demonstrated

- **Azure Logic Apps:** An introduction to building automated, serverless workflows.
- **HTTP Trigger:** How to use a web request as an entry point for a workflow.
- **Connectors:** A practical example of using a pre-built connector (Gmail) to integrate with an external service.
- **Serverless Computing:** The workflow runs automatically without the need to manage any servers or infrastructure.

## Workflow

The workflow is defined by the JSON code in `workflow.json`.

Here is a simplified view of the steps:

1.  **Trigger:** A web browser or an application sends an HTTP GET request to a unique URL.
2.  **Action:** The Logic App sends an email using the Gmail connector.
3.  **Action:** The Logic App sends a response back to the requestor.

## How to Deploy and Run

Follow these steps to deploy this Logic App in your own Azure account.

1.  **Create a new Logic App:** In the Azure Portal, create a new Logic App resource with a **Consumption** plan.
2.  **Go to Code View:** In the Logic App Designer, switch to the **Code view** tab.
3.  **Paste the JSON:** Copy the JSON content from `workflow.json` and paste it into the code editor, replacing the existing code.
4.  **Create the Connection:** In the Designer, a warning may appear about the missing connection. Follow the prompts to sign in to your personal Gmail account and create the connection.
5.  **Save:** Click the **Save** button. Your Logic App will be ready to use.

## Security Note

**Important:** This JSON code has been sanitized for public sharing. It does **not** contain any sensitive information like Subscription IDs, Resource Group names, or authentication keys.

When you create your Logic App, Azure securely stores your connection details. **Never** share the original JSON code with personal data or secrets in a public repository.
