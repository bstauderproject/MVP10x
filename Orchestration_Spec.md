# Agent Orchestrator Spec

## Purpose
Enable execution of multi-step workflows using modular agents based on scoped operator goals.

## Core Functions
- Accept scope and context
- Select agents based on function category
- Execute agent chains (sequential or parallel)
- Log outputs and return to whiteboard or terminal

## Example Flow
> Operator parses JD → 3 agents selected  
> → CampaignAgent, ResumeAgent, ReportingAgent  
> → Outputs: 1 roadmap, 1 resume, 1 executive update

## Interfaces
- Trigger: UI, co-pilot, JD parser
- Output: Whiteboard, Notion, email, database
