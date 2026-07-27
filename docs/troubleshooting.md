# Troubleshooting

## Google Gemini Quota Error (429)

### Problem

The workflow returns:

```
429 Too Many Requests
Quota exceeded
```

### Cause

The selected Gemini model may not have available quota.

### Solution

Switch to a supported model with available quota (for example, Gemini 3 Flash Preview).

---

## Missing Output

Check that:

- All required fields are populated.
- The Basic LLM Chain is correctly configured.
- The Google Gemini credential is valid.

---

## Incorrect Analysis

Review the prompt in:

```
prompts/soc-analyst-prompt.md
```

Prompt quality directly affects AI output quality.
