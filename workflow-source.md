# Workflow Source Configuration

## Workflow

**My First N8N Workflow**

## Structure

`When clicking "Execute workflow" → Edit Fields`

## Manual Trigger

- Node type: Manual Trigger
- Trigger: When clicking "Execute workflow"

## Edit Fields

- Node type: Edit Fields (Set)
- Field type: String
- Field name: `greeting`
- Field value: `Hello, n8n!`

## Expected output

```json
{
  "greeting": "Hello, n8n!"
}
```

## Validation

The workflow was manually executed in n8n and the output was inspected in JSON view. The expected greeting payload was returned successfully.
