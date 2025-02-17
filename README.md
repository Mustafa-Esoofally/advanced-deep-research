# Open Advanced Deep Research

Open Deep Research is an AI-powered, iterative research assistant that leverages search engines, web scraping, and large language models to conduct deep research on any topic. It refines its research direction dynamically based on user feedback and previous learnings, ultimately generating a comprehensive Markdown report with detailed insights and sources.

Checkout the [detailed post](https://x.com/mustafa_2vec/status/1889817757903999440) here. Follow along for [more updates](https://x.com/mustafa_2vec).

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [New Features](#new-features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [How It Works](#how-it-works)
- [Contributing](#contributing)
- [License](#license)
- [References](#references)

## Overview
Open Deep Research is designed as a minimalistic yet powerful research agent that automatically refines its research process. By generating specific SERP queries and processing the results recursively, it collects in-depth learnings on any topic. The resulting Markdown report aggregates insights, key entities, and sources to support rapid decision-making and further exploration.

## Features
- **Iterative Research:** Reassesses and refines research direction based on follow-up queries.
- **Intelligent Query Generation:** Uses large language models to create unique, targeted SERP queries.
- **Customizable Depth & Breadth:** Configure research breadth (number of queries per iteration) and depth (levels of recursion).
- **Comprehensive Reporting:** Produces detailed Markdown reports that include learnings and visited URLs as sources.
- **Real-time Progress Tracking:** Monitors research progress with live updates during the process.

## Upcoming Features

- **Personal Knowledge Base:** Build a personal research library over time. Add/ update custom sources to the library.
- **Voice / Chat Mode**: Talk to the research agent in natural language. Ask question and ask it to make changes as needed.
- **Intelligent Research Direction:** Decide on the best research direction based on the most relevant queries and results (auto depth and breadth).
- **Web Dashboard & Interactive UI:** Leverage Shadcn components to build a modern, interactive web interface for real-time progress monitoring and data visualization.
- **Research Templates:** Curated web templates for common research scenarios (market analysis, technical due diligence).
- **Knowledge Graph Visualization:** Interactive force-directed graph showing connections between research concepts.
- **Advanced Reporting Formats:** Offer export options for final reports in additional formats such as PDF, Word and PowerPoint.
- **Hallucination:** Add hallucination detector for content generated. (for verification)

## Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Mustafa-Esoofally/advanced-deep-research.git
   ```
2. **Navigate into the project directory:**
   ```bash
   cd open-deep-research
   ```
3. **Install dependencies:**
   ```bash
   npm install
   ```
4. **Set up environment variables:**
   Copy the `.env.example` file as `.env` and populate it with your keys:

## Usage
To start the research assistant, run:
```bash
npm run dev
```

This command will initiate the research assistant, allowing you to input your research query and configure the parameters for breadth and depth.

### Credits

Inspired by [Deep Research](https://github.com/dzhng/deep-research)  built by [Dzhng](https://github.com/dzhng).
