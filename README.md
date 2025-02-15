# TITLE: AI-Powered Research and Travel Planning System Using CrewAI and LangChain

## Description:
This project leverages AI agents to perform two distinct tasks:
#### 1.	AI Research & Content Creation: 
* A CrewAI system with collaborative agents (Researcher and Writer) generates detailed reports on AI advancements.
#### 2.	Travel Planning: 
* A LangChain-based system uses specialized agents (Local Expert, Historian, Food Expert) to provide city-specific travel recommendations, historical insights, and dining suggestions.

## Responsibilities:
#### 1.	AI Research Component:
o	Researcher Agent: Identifies AI trends, breakthrough technologies, and industry impacts using SerperDevTool for web searches.
o	Writer Agent: Transforms technical insights into engaging blog posts for a tech-savvy audience.
#### 2.	Travel Planning Component:
o	Local Expert Agent: Searches for top tourist attractions using DuckDuckGo.
o	Historian Agent: Provides historical context about the city.
o	Food Expert Agent: Recommends popular restaurants and local cuisine.

## Libraries Used:
#### • CrewAI: 
For multi-agent collaboration (Researcher/Writer).
#### •	LangChain: 
Framework for building AI workflows with search tools.
#### •	OpenAI API: 
Powers GPT-3.5-turbo for natural language processing.
#### •	SerperDevTool: 
Google Search API for real-time data retrieval.
#### •	DuckDuckGo Search: 
Web scraping for travel-related information.

## Summary: 
This project demonstrates two AI-driven workflows:
### 1.	AI Trend Analysis: 
* A Researcher-Writer "crew" collaborates to produce a structured report and blog post on cutting-edge AI developments. The Researcher uses SerperDevTool to gather data, while the Writer crafts accessible content.
### 2.	City Travel Guide: 
* Three specialized agents (Local Expert, Historian, Food Expert) use DuckDuckGo to generate a travel plan with attractions, historical insights, and dining recommendations. The system includes error handling with exponential backoff for robust API interactions.

### Technologies Highlighted:
•	Collaborative AI agents for task delegation.
•	Integration of search APIs (Serper, DuckDuckGo) for real-time data.
•	Natural language generation using OpenAI’s GPT-3.5-turbo.
•	Scalable workflows with LangChain and CrewAI frameworks.

