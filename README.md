# Salesforce AI Chef

An AI-powered recipe generator built on Salesforce using Prompt Builder, Lightning Web Components (LWC), Apex, and Salesforce DX.  
This project demonstrates how to integrate Salesforce AI (Einstein / Prompt Builder) with custom UI and backend logic to generate dynamic, structured recipe recommendations.

---

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Setup & Installation](#setup--installation)
- [Salesforce DX Configuration](#salesforce-dx-configuration)
- [Deployment](#deployment)
- [Usage](#usage)
- [Development Model](#development-model)
- [Contributing](#contributing)
- [Author](#author)

---

## Features

- AI-powered recipe generation using Salesforce Prompt Builder
- Dynamic ingredient-based recipe suggestions
- Lightning Web Components UI with responsive layout
- Apex controller integration with Einstein Prompt Templates
- Real-time recipe cards with prep time, cook time, difficulty, and servings
- Chef tips, ingredients, and step-by-step instructions
- Salesforce DX–based development workflow

---

## Tech Stack

- Salesforce DX (SFDX)
- Lightning Web Components (LWC)
- Apex
- Salesforce Prompt Builder (Einstein)
- Salesforce Health / Data Cloud compatible
- Git & GitHub

---

## Setup & Installation

### Prerequisites
- Salesforce CLI (SFDX)
- Salesforce Developer Org with AI features enabled (Prompt Builder)
- Git
- Node.js (recommended)

### Clone the Repository
git clone https://github.com/<your-username>/<your-repo-name>.git  
cd <your-repo-name>

### Authenticate Salesforce Org
sfdx auth:web:login -a DevOrg

---

## Salesforce DX Configuration

The `sfdx-project.json` file defines project configuration such as:
- Package directories
- Namespace (if any)
- Source format
- API version

This project follows **source-driven development** using Salesforce DX best practices.

---

## Deployment

### Deploy All Source
sfdx force:source:deploy -p force-app/main/default

### Deploy Using manifest/package.xml
sfdx force:mdapi:deploy -d manifest

### Validate Deployment (Check Only)
sfdx force:source:deploy -p force-app/main/default --checkonly

---

## Usage

1. Open Salesforce App Launcher
2. Launch **Salesforce AI Chef** app
3. Navigate to the custom Lightning App Page
4. Enter:
   - Ingredients (comma-separated)
   - Dietary restrictions
   - Meal type
   - Number of servings
5. Click **Generate Recipe**
6. View AI-generated recipe cards with:
   - Prep & cook time
   - Difficulty
   - Ingredients list
   - Instructions
   - Chef tips

---

## Development Model

This project uses a **Salesforce DX modular development model**:
- Source-controlled metadata
- Scratch/Developer org compatible
- Reusable LWC components
- Apex controllers for AI execution
- Prompt Builder templates for AI logic

---

## Contributing

1. Fork the repository
2. Create a new feature branch
3. Commit changes with clear messages
4. Push to your fork
5. Open a Pull Request

---

## Author

Built by Aryak Naik — Salesforce Administrator / Developer  
Focused on AI-driven Salesforce solutions using Prompt Builder, Apex, and Lightning Web Components.
