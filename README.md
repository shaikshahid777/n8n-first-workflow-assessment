# n8n First Workflow Assessment

## N8N Hands-On Beginner Course — Topic 1: Create Your First Workflow

This repository contains the source configuration and documentation for the Topic 1 practical assessment.

## Objective

Create, configure, execute, inspect, and save a basic n8n workflow using a Manual Trigger and an Edit Fields node.

## Workflow

```text
When clicking "Execute workflow"
            ↓
       Edit Fields
            ↓
          Output
```

## Workflow Name

**My First N8N Workflow**

## Node Configuration

### 1. Manual Trigger

- Node: `When clicking "Execute workflow"`
- Purpose: Starts the workflow manually for testing.

### 2. Edit Fields

- Field name: `greeting`
- Type: `String`
- Value: `Hello, n8n!`

## Expected JSON Output

```json
{
  "greeting": "Hello, n8n!"
}
```

## Execution

1. Open the workflow in n8n.
2. Click **Execute workflow**.
3. Select the **Edit Fields** node.
4. Inspect the output in JSON view.
5. Confirm that the `greeting` field contains `Hello, n8n!`.
6. Save the workflow as **My First N8N Workflow**.

## Assessment Evidence

### Demo Video

[Loom Demo Video](https://www.loom.com/share/2e2cbf49ba8848d088af5599756dfe7b)

The demo demonstrates the workflow configuration and successful execution.

## Repository Contents

- `README.md` — assessment documentation and setup instructions.
- `workflow-source.md` — equivalent source configuration for the n8n workflow.

## Requirements Covered

- Blank workflow creation
- Workflow naming and saving
- Manual Trigger
- Edit Fields (Set) node
- Node connection
- String field configuration
- Manual execution
- JSON output inspection
- Demo video evidence

## Notes

The assessment requires a public repository and a Loom/YouTube demonstration. No credentials, passwords, API keys, or private workspace information are included in this repository.
