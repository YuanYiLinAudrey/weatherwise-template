---
title: "Summary of WeatherWise: Intelligent Weather Analysis & Advisory System"
subtitle: "Harnessing Python and AI to Create Intuitive Weather Applications"
author: "Michael Borck"
format: 
  pdf:
    toc: false
    colorlinks: true
  docx:
    toc: false
    highlight-style: github
  html:
    toc: true
    toc-expand: 2
    embed-resources: true
---

> **Note**: This is a condensed overview. The [complete specification document](link-to-full-spec) is the authoritative source for all requirements.

## Project Goal
Build a Python application that combines weather data with natural language capabilities to provide weather information through visualisations and conversational interactions.

## Core Requirements

### 1. Weather Data Component
- Retrieve and process weather data for user-specified locations
- Handle errors and edge cases appropriately
- Choose from: provided WeatherWrapper, direct wttr.in API, or custom solution (up to 5% bonus)

### 2. Natural Language Interface
- Parse user questions about weather (e.g., "Will it rain tomorrow in Sydney?")
- Extract location, time period, and weather attributes from questions
- Generate natural language responses based on weather data

### 3. Data Visualisation
- Create at least 2 different visualisations of weather data
- Ensure visualisations are properly labelled and informative
- Integrate visualisations with the rest of the application

### 4. User Interface
- Implement using pyinputplus menus OR ipywidgets OR a hybrid approach
- Provide clear feedback and error handling
- Create a clean, organised display of information

### 5. Core Functions
- Implement the required functions provided as stubs in the starter notebook:
  - Weather data retrieval
  - Question parsing
  - Response generation
  - Visualisation creation

## Implementation Options
Choose **one** of these approaches:
- **Dashboard Focus**: Emphasise visualisations with chat support
- **Chatbot Focus**: Prioritise conversation with supporting visualisations
- **Hybrid Approach**: Balance both interfaces with integrated functionality

## Required Documentation
- **AI Conversations**: Document at least 5, including options exploration
- **PROMPTING.md**: Show your intentional prompting process
- **Before/After Examples**: 3 examples showing how you improved AI-generated code

## Submission Items
- GitHub repository with your instructor added (all files must be uploaded here)
- sIP download of your GitHub repository submitted to the LMS
- Google Colab notebook with complete, working application
- AI conversation documentation files
- PROMPTING.md and reflection document (300-500 words)

## Suggested Timeline
- **Week 1**: Setup, basic weather data retrieval
- **Week 2**: Visualisation and UI framework
- **Week 3**: Natural language processing
- **Week 4**: Integration and feature completion
- **Week 5**: Testing and documentation

## Evaluation Focus
- Functionality and Technical Implementation (40%)
- Code Quality and Organisation (25%)
- Intentional AI Prompting and Documentation (35%)
- Both product AND process are important!

## Getting Started
1. Use the [GitHub template repository](link-to-template)
2. Review the full specification document
3. Start with the implementation options exploration conversation