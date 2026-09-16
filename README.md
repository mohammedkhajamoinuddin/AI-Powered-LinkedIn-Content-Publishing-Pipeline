# AI Content Publishing Automation

An end-to-end AI-powered content publishing workflow that automatically transforms web articles into LinkedIn posts.

## Overview

This project automates the process of content creation and publishing using Google Cloud, Google Gemini, LinkedIn APIs, and n8n.

Instead of manually reading an article, drafting a post, and publishing it, the workflow performs the entire process automatically.

## Workflow

1. Add an article URL to Google Sheets
2. Google Sheets Trigger detects the new entry
3. n8n workflow starts automatically
4. Google Gemini analyzes the article
5. A LinkedIn-ready post is generated
6. The post is published to LinkedIn automatically

## Architecture

```text
Article URL
     ↓
Google Sheets
     ↓
Google Sheets Trigger
     ↓
n8n Workflow
     ↓
Google Gemini
     ↓
LinkedIn Content Generation
     ↓
LinkedIn API
     ↓
Published LinkedIn Post
```

## Technologies Used

### Cloud & APIs

- Google Cloud Platform
- Google Sheets API
- Google OAuth 2.0
- LinkedIn API
- LinkedIn OAuth 2.0

### AI & Automation

- Google Gemini
- n8n
- Workflow Automation

## What I Learned

- OAuth Authentication Flow
- Google Cloud Configuration
- LinkedIn Developer Platform Setup
- API Integrations
- Workflow Orchestration
- AI-Assisted Content Generation

## Project Screenshots

### Google Sheets Input

![Googleots/google-sheet-input.png.png

### Workflow Overview

![Workflows/workflow-overview.png.png

### Workflow Execution

![Workflows/workflow-execution.png.png

### LinkedIn Posts Generated

![LinkedIns/linkedin-post-output-01.png.png

![LinkedIn Post 2](screenshots/linkedin-post-![Linkedots/linkedin-post-output-03.png.png

## Future Improvements

- Multi-platform publishing
- Content scheduling
- Approval workflow
- Analytics dashboard
- Agentic AI capabilities
- RAG-powered content enrichment
`
