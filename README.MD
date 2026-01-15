# Upwork Automation Workflow

## Overview

This project is an **end-to-end automation workflow** that fetches job postings from Upwork, analyzes them using an AI model, scores their relevance, and stores the structured results in Airtable.

The goal is to demonstrate how AI, automation tools, and external data sources can be combined to build a **lead qualification system** for freelancers or agencies.

---

## Problem Statement

Manually scanning Upwork job listings is time-consuming and inefficient. Freelancers often miss high-quality opportunities or waste time on low-relevance jobs.

This workflow automates:

* Job discovery
* AI-based job evaluation
* Structured storage for later action

---
## Setup & Installation

### Prerequisites
* [Docker](https://www.docker.com/) (if running n8n locally)
* Airtable Account (Free tier is fine)
* Google Cloud Platform Account (for Gemini API)

### 1. Run n8n with Docker
```bash
docker run -it --rm --name n8n -p 5678:5678 -v ~/.n8n:/home/node/.n8n n8nio/n8n



## Author
Sachin Minglani
