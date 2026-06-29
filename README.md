# Enterprise AI Readiness Framework

## Executive Summary

Enterprise AI Readiness Framework is a practical portfolio accelerator for evaluating an organization's data maturity, AI infrastructure readiness, cybersecurity posture, operating model, and adoption readiness for GenAI and agentic AI initiatives.

The repository includes a Windows-friendly AIMM assessment app and supporting framework material for enterprise advisory conversations.

## Business Problem

Many organizations want to adopt GenAI but lack a structured view of whether their data, infrastructure, controls, processes, and people are ready. This framework helps translate AI ambition into a practical readiness discussion that can be reviewed by technology, security, data, and executive stakeholders.

## Key Features

- Five-pillar maturity assessment covering data, AI infrastructure, cyber posture, process/BizOps, and talent/culture
- 0-5 scoring model for readiness discussion
- Evidence notes by pillar
- Overall readiness score and maturity level
- GenAI and agentic AI use-case prioritization
- Local browser storage for draft assessments
- Exportable assessment output from the local Windows app

## Target Users

- Enterprise technology leaders
- AI governance teams
- Cloud and infrastructure teams
- Cybersecurity and risk leaders
- Consultants and transformation advisors
- Teams planning GenAI adoption roadmaps

## Architecture Overview

```text
User / Advisor
|
AIMM Windows App
|
Assessment Questions + Evidence Notes
|
Maturity Scoring + Use Case Prioritization
|
Local Browser Storage
|
Board-ready Export / Recommendations
```

## Technology Stack

- HTML-based local app
- Windows batch launcher
- Browser local storage
- Source framework materials in PDF/PPTX form

## Installation

```powershell
git clone https://github.com/rahulrainarr/Enterprise-AI-Readiness-Framework.git
cd Enterprise-AI-Readiness-Framework\AIMM-Windows-App
.\"Launch AIMM App.bat"
```

You can also open `AIMM-Windows-App/index.html` directly in a browser.

## Usage

1. Launch the AIMM Windows app.
2. Score each maturity pillar from 0 to 5.
3. Add evidence notes for the organization or scenario being reviewed.
4. Review the overall readiness score and suggested next phase.
5. Export or share the resulting assessment summary as appropriate.

## Example Outputs

- AI readiness score
- Maturity heatmap
- Recommended next phase
- Use-case prioritization board
- Exported HTML assessment report

## Security And Privacy

The app is designed for local use. Draft assessment data is stored in the browser's local storage. Do not commit real customer assessments, private documents, credentials, or confidential export files to this repository.

## Current Status

MVP / useful portfolio tool.

## Roadmap

- Add screenshots of the assessment workflow
- Add a sample sanitized readiness report
- Add a one-page consulting playbook
- Add mapping to NIST AI RMF, ISO/IEC 42001, OWASP LLM risks, and cloud landing-zone controls
- Add versioned releases for the Windows app package

## Disclaimer

This is a personal portfolio and experimental project unless otherwise stated. It is not legal, compliance, cybersecurity, or procurement advice. Validate all controls and recommendations against organizational policy and current regulatory requirements.
