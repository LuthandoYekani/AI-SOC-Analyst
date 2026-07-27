# Installation Guide

## Prerequisites

Before importing this workflow, ensure you have:

- n8n installed (Cloud or Self-Hosted)
- A Google AI Studio account
- A Google Gemini API Key

---

## Import Workflow

1. Open n8n.
2. Select **Import Workflow**.
3. Import `workflow/AI-SOC-Analyst.json`.

---

## Configure Credentials

Create a Google Gemini credential using your API key.

---

## Verify Connections

Ensure the Basic LLM Chain node is connected to the Google Gemini Chat Model.

---

## Execute

Run the workflow manually.

The workflow will generate a structured SOC incident analysis report based on the configured security alert.

---

## Customisation

You can modify the Edit Fields node to analyse different alerts without changing the prompt.
