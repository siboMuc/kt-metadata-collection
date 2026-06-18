# KT Metadata Collection

This repository collects knowledge-transfer / contributor metadata through a
structured **GitHub issue form**.

## How to submit

1. Go to the [**Issues**](https://github.com/siboMuc/kt-metadata-collection/issues/new/choose) tab.
2. Choose **📋 Metadata Collection**.
3. Fill in the form and submit.

The GitHub account that opens the issue is automatically recorded as the
**author**, so the submitter is always identified. The *GitHub handle* field is
optional and only used when submitting on behalf of someone else.

## What the form captures

| Field | Required | Purpose |
|-------|----------|---------|
| GitHub handle | No | Person the entry is for (defaults to issue author) |
| Team | Yes | Which team the person belongs to |
| Seniority level | Yes | Role seniority |
| Tenure on product | Yes | How long they've worked on the product |
| Notes | No | Areas of expertise / extra context |
| Confirmation | Yes | Confirms accuracy |

## Files

- `.github/ISSUE_TEMPLATE/metadata-collection.yml` — the issue form definition.
- `.github/ISSUE_TEMPLATE/config.yml` — disables blank issues, adds a discussion link.
