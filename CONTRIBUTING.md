
# How to Contribute to DifyHub Workflows

First off, thank you for considering contributing! Your contributions are what make DifyHub a valuable resource for the entire Dify community.

We welcome all high-quality workflow submissions. To ensure a smooth review process and maintain the quality of our library, please follow these guidelines.

## Submitting a New Workflow

All new workflow submissions must be made via a **Pull Request (PR)**.

### 1. Repository Structure

This repository is organized by category. Please place your workflow in the most relevant sub-directory under `/workflows`.

- **Good:** `workflows/social-media/ai-tweet-generator`
- **Good:** `workflows/rag/qdrant-pdf-qa`
- **Bad:** `workflows/my-awesome-workflow`

If you are unsure about the category, feel free to create a new one that makes sense.

### 2. Required Files

Each workflow submission (your new folder) **must** contain at least two files:

1.  `workflow.dsl`: The raw exported DSL file (JSON or YAML) from your Dify application.
2.  `README.md`: A markdown file that explains your workflow.

### 3. The `README.md` Template

Your `README.md` is the "manual" for your workflow. It must be clear and helpful. Please **copy and paste the template below** into your `README.md` file and fill it out:

```markdown
# [Workflow Name]

**Author:** `[Your GitHub Username]`

A brief, one-sentence description of what this workflow does.

## 🚀 How to Use

1.  **Set Up API Keys:**
    * This workflow requires the following API keys (e.g., `OPENAI_API_KEY`).
    * Explain where to get them and how to add them in Dify's "Credentials" section.
2.  **Configure Tools:**
    * Does the user need to configure any tools, like a database connection or a Google Search API?
3.  **Run the Workflow:**
    * Explain how to test it (e.g., "Provide a URL in the 'input' node...").

## 🛠️ Workflow Nodes (Optional but Recommended)

A brief overview of the main nodes and their roles:

* **Start Node:** Takes a user query (string).
* **LLM Node:** Summarizes the input.
* **End Node:** Returns the summary.

## 📸 Screenshot (Recommended)

A screenshot of the workflow graph from the Dify UI is highly recommended. You can drag and drop the image into this README.
````

### 4. Submission Checklist

Before you submit your PR:

  - [ ] Does your workflow run correctly?
  - [ ] Is your `workflow.dsl` file the raw export (not just a copy-paste of the text)?
  - [ ] Does your `README.md` (created from the template) clearly explain how to use the workflow?
  - [ ] Have you placed your workflow in a logical category folder?

### 5. The Review Process

1.  **Submit PR:** Submit your PR against our `main` branch.
2.  **Review:** Our team (`@dugufeng` and others) will review your submission. We may ask for changes.
3.  **Merge:** Once approved, your PR will be merged.
4.  **Sync:** After merging, your workflow will be automatically synced and published to [DifyHub.com](https://www.google.com/search?q=https://difyhub.com)\!

Thank you for building the Dify community with us!


