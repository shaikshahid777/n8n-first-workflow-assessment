<!-- SHOWCASE_START --><div align="center">[![Typing](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&duration=2800&pause=900&color=58A6FF&center=true&vCenter=true&width=900&lines=n8n%20first%20workflow%20assessment;AI%20%7C%20Automation%20%7C%20Engineering;Explore%20the%20project%20%F0%9F%9A%80)](https://github.com/shaikshahid777/n8n-first-workflow-assessment)<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:161B22,100:58A6FF&height=110&section=header&text=n8n-first-workflow-assessment&fontSize=26&fontColor=FFFFFF&animation=twinkling&fontAlignY=65" width="100%" alt="Animated project banner"/>

[![Repository](https://img.shields.io/badge/Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/shaikshahid777/n8n-first-workflow-assessment) [![Issues](https://img.shields.io/badge/Report-Issue-red?style=for-the-badge&logo=github)](https://github.com/shaikshahid777/n8n-first-workflow-assessment/issues/new) [![Stars](https://img.shields.io/github/stars/shaikshahid777/n8n-first-workflow-assessment?style=for-the-badge&logo=github)](https://github.com/shaikshahid777/n8n-first-workflow-assessment/stargazers) [![Fork](https://img.shields.io/github/forks/shaikshahid777/n8n-first-workflow-assessment?style=for-the-badge&logo=github)](https://github.com/shaikshahid777/n8n-first-workflow-assessment/fork) [![Profile](https://img.shields.io/badge/Profile-Visit-0A66C2?style=for-the-badge&logo=github)](https://github.com/shaikshahid777)</div>

> ✨ **Project Showcase Mode:** animated banner • interactive navigation • live repository actions

[🚀 Repository](https://github.com/shaikshahid777/n8n-first-workflow-assessment) · [🐞 Report Issue](https://github.com/shaikshahid777/n8n-first-workflow-assessment/issues/new) · [⭐ Star](https://github.com/shaikshahid777/n8n-first-workflow-assessment/stargazers) · [🔱 Fork](https://github.com/shaikshahid777/n8n-first-workflow-assessment/fork) · [👤 Profile](https://github.com/shaikshahid777)

<!-- SHOWCASE_END -->

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
