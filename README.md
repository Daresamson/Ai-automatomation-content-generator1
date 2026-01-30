

# Ai-automatomation-content-generator1
AI Automation Content Generator (Scheduled Agent)


<img width="1366" height="768" alt="Screenshot (405)" src="https://github.com/user-attachments/assets/a854d07d-c4cf-4a93-aa7e-5804f0dd195d" />
<img width="1366" height="768" alt="Screenshot (406)" src="https://github.com/user-attachments/assets/54c38aa2-846c-4e74-80c4-4b2a66c74a58" />


This project is an end-to-end AI automation system built to generate intelligent, web-informed content on a schedule with minimal human intervention.

The system uses a combination of workflow automation, web search intelligence, and an AI agent to transform raw topics into structured, publish-ready content.

🚀 Overview

The automation runs on a scheduled trigger and follows a structured pipeline:

Reads content topics from Google Sheets

Enriches topics using real-time web research (Tavily API)

Synthesizes insights using an AI Agent

Writes generated content back to Google Sheets

This enables scalable, repeatable content creation without manual execution.

🧠 System Architecture

Tools & Technologies

n8n – Workflow orchestration and scheduling

Google Sheets – Lightweight CMS (input + output)

Tavily API – Web search and content extraction

LangChain AI Agent – Content reasoning and synthesis

🔄 Workflow Steps

Schedule Trigger
Runs automatically at a defined time.

Google Sheets – Topic Intake
Fetches rows marked as To do.

Web Research (Tavily)
Searches the web and extracts high-signal content related to each topic.

AI Agent Processing
Uses a structured system prompt to ensure:

Strategic writing

Audience awareness

SEO-friendly structure

Clear and intelligent outputs

Content Update
Writes generated content back to the original Google Sheet.

✅ Key Features

Fully automated, scheduled execution

Real-time web intelligence

Agent-based content generation (not simple text output)

Modular and scalable design

Successful end-to-end execution

📌 Use Cases

Automated blog or article generation

Content research pipelines

SEO content drafting

AI agent experimentation

No-code / low-code AI automation demos

📈 Status

✔ Successfully executed
✔ Tested with live web search data
✔ Ready for extension (posting, publishing, analytics)

