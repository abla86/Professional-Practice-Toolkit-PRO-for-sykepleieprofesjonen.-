# Professional Practice Toolkit PRO

## Current status

This repository is an **early application scaffold**, not a working nursing toolkit. The current `src/App.tsx` renders an empty container. It does not currently implement clinical workflows, evidence lookup, clinical calculations, medication checks, documentation templates, or server-side Gemini integration.

Do not use this repository for patient care, clinical decisions, training sign-off, or production data. A functional scope, validated content sources, user requirements, test coverage and privacy/security review must be completed before any clinical use is considered.

## Development

Requirements: Node.js and npm.

```bash
npm install
npm run lint
npm run build
npm run dev
```

The development server binds to localhost by default. Do not expose it to a network unless the environment has been deliberately configured and reviewed.

## Data and security

- Do not commit credentials, API keys, patient data, national identity numbers, or confidential employer information.
- No clinical data-processing workflow is implemented or approved.
- Do not add AI features that process personal or health data until data flows, provider retention, access controls and lawful basis have been reviewed.
- A passing build verifies compilation only; it does not establish clinical correctness, safety, regulatory compliance or production readiness.

## Next release gate

Before presenting this as a usable product, implement and test the intended workflows, add validated references and versioning, define data retention and deletion behavior, complete a threat model and privacy assessment, and obtain qualified clinical review.
