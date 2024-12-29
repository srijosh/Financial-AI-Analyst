# Financial AI Analyst

This repository contains a project for a Financial AI Analyst that leverages advanced AI models and tools to analyze financial data and provide insights. The project integrates multiple agents for financial data analysis and web searches, offering a seamless user experience through a playground interface.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)

## Introduction

The Financial AI Analyst is designed to answer financial questions, retrieve market data, and perform web searches for additional context. It combines multiple agents into a cohesive system capable of delivering tabular insights with references.

## Features

- Integration with YFinance for financial data retrieval.
- Web search functionality via DuckDuckGo.
- AI-driven insights using the Groq model.
- Multi-agent collaboration for enhanced analysis.
- User-friendly interface via the PhiData playground.

## Installation

1. Clone the repository to your local machine:

```
   git clone https://github.com/srijosh/Financial-AI-Analyst.git
```

2. Navigate to the project directory:

```
   cd Financial-AI-Analyst
```

3. Install the required dependencies:

```
   pip install -r requirements.txt
```

4. Set up environment variables by creating a .env file (Use .env.sample as a reference for setting up your .env file.)

## Usage

1. Run the financial_agent.py to get dedicated answer on NVIDIA

```
   python financial_agent.py
```

2. OR, Run the playground.py to to interact with the agent in a user-friendly interface through phidata playground:

```
   python playground.py
```

3. Ask financial in the playground interface, and the agents will provide tabular data with proper sources.
