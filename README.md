# Salesforce AI Chef

Salesforce AI Chef is an AI-powered recipe generation application built on the Salesforce platform. It leverages Salesforce Prompt Builder and Einstein AI to generate personalized recipes based on user-provided ingredients, dietary preferences, and meal requirements through a modern Lightning Web Components (LWC) interface.

---

## Table of Contents

1. [Features](#features)
2. [Tech Stack](#tech-stack)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Architecture](#architecture)
6. [Contact](#contact)

---

## Features

- AI-powered recipe generation using Salesforce Prompt Builder and Einstein AI  
- Dynamic Lightning Web Components (LWC) UI with real-time responses  
- Personalized recipes based on ingredients, dietary restrictions, and servings  
- Structured recipe output including prep time, cook time, and difficulty  
- Production-ready error handling and input validation  
- Deployed on Salesforce Lightning App and Experience Cloud  

---

## Tech Stack

- **Frontend:** Lightning Web Components (LWC), SLDS  
- **Backend:** Apex, ConnectApi (Einstein Prompt APIs)  
- **AI:** Salesforce Prompt Builder, Einstein AI  
- **Dev Tools:** Salesforce DX (SFDX), VS Code  
- **Cloud Services:** AWS S3 (for document ingestion)  

---

## Installation

### Prerequisites

Ensure the following are installed and enabled:

- Salesforce CLI (SFDX)
- Salesforce Developer Org with Einstein AI & Prompt Builder enabled
- VS Code with Salesforce Extensions

### Setup

```bash
git clone https://github.com/your-username/salesforce-ai-chef.git
cd salesforce-ai-chef
sfdx auth:web:login -d -a AI_Chef_Org
sfdx force:source:push
sfdx force:org:open


## Read All About It

- [Salesforce Extensions Documentation](https://developer.salesforce.com/tools/vscode/)
- [Salesforce CLI Setup Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_setup.meta/sfdx_setup/sfdx_setup_intro.htm)
- [Salesforce DX Developer Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_intro.htm)
- [Salesforce CLI Command Reference](https://developer.salesforce.com/docs/atlas.en-us.sfdx_cli_reference.meta/sfdx_cli_reference/cli_reference.htm)
