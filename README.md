
# AI Business Command Center

An end-to-end multi-agent AI business development automation system built with n8n, Supabase, Tavily, RAG, and Gmail.

## Overview

This system automates the business development process from researching potential businesses to creating qualified leads and sending personalized outreach.

## Workflow

User Request  
↓  
Supervisor Agent  
↓  
Research Agent  
↓  
Lead Agent  
↓  
Qualification Agent  
↓  
Supabase CRM  
↓  
Outreach Agent  
↓  
Gmail  

## AI Agents

### Supervisor Agent
Coordinates the different agents and tools and manages the overall workflow.

### Research Agent
Researches businesses using web search and identifies useful company information, potential pain points, and automation opportunities.

### Lead Agent
Converts research into structured lead records and stores them in Supabase.

### Qualification Agent
Analyzes leads and assigns qualification scores, priority, and recommendations.

### Outreach Agent
Creates personalized outreach using the lead's verified information and sends the message through Gmail.

## RAG

Supabase Vector Store is used for storing and retrieving contextual information for the AI agents.

## Tech Stack

- n8n
- AI Agents
- Supabase
- PostgreSQL
- Supabase Vector Store
- Tavily
- Gmail
- RAG
- PowerShell

## Key Features

- Multi-agent AI architecture
- Automated web research
- Lead generation
- Lead qualification
- CRM storage
- Vector search / RAG
- Personalized outreach
- Gmail automation
- End-to-end workflow orchestration

## Screenshots

### Workflow

![Workflow](screenshots/workflow.png)

### Supabase CRM

![Supabase CRM](screenshots/supabase-crm.png)

### Lead Qualification

![Qualification](screenshots/qualification.png)

### Personalized Outreach

![Outreach](screenshots/outreach.png)

### Gmail Result

![Gmail](screenshots/gmail-result.png)

## Security

API keys, OAuth tokens, passwords, and other private credentials are not included in this repository.

## Status

Completed end-to-end AI business development automation project.
