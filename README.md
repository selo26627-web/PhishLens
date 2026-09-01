# PhishLens

### An Explainable Phishing Risk Analysis Platform

PhishLens is a web-based cybersecurity platform designed to analyze URLs and identify potential phishing risks using a **rule-based risk analysis approach**.

Instead of only providing a risk score, PhishLens explains **why a URL may be suspicious** by analyzing different indicators and presenting the results in an understandable way.

## Features

* URL Analysis
* Phishing Risk Detection
* Risk Score Generation
* Suspicious Pattern Detection
* Explainable Analysis Results
* Rule-Based Risk Engine
* Interactive Web Interface

## How It Works

```text
User Input
    ↓
React Interface
    ↓
Node.js Server
    ↓
URL Analysis
    ↓
Rules & Indicators
    ↓
Risk Engine
    ↓
Risk Score + Explanation
```

## Technologies

* **React** – Building the interactive web interface
* **TypeScript** – Application development
* **Node.js** – Running the backend server
* **URL Analysis** – Inspecting URL components
* **Pattern Matching** – Detecting suspicious patterns
* **Rule-Based Engine** – Combining indicators to calculate risk

## Risk Analysis

PhishLens analyzes different characteristics and indicators of a URL to estimate its potential phishing risk.

The result provides:

* **Risk Score**
* **Risk Level**
* **Detected Indicators**
* **Explanation of the Analysis**

## Project Goal

The goal of PhishLens is to make phishing URL analysis more **understandable and explainable**.

Instead of simply telling the user whether a URL is safe or suspicious, PhishLens provides insight into the indicators that contributed to the risk assessment.

## Running the Project Locally

### 1. Clone the repository

```bash
git clone https://github.com/selo26627-web/PhishLens.git
cd PhishLens
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start the development server

```bash
npm run dev
```

The server will run locally on:

```text
http://localhost:3000
```

## Cybersecurity Context

PhishLens is an educational cybersecurity project focused on **phishing detection and URL risk analysis**.

It demonstrates how multiple suspicious indicators can be combined into a rule-based risk assessment and presented through an explainable interface.

## Project

**PhishLens – An Explainable Phishing Risk Analysis Platform**

A cybersecurity project exploring phishing detection, URL analysis, and explainable risk assessment.
