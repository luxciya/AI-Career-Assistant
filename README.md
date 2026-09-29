# 💼 AI Career Assistant

An AI-powered career assistant that helps job seekers analyze their resumes, evaluate ATS compatibility, understand job descriptions, improve their resumes, and practice interviews.

The project combines **n8n, Gemini, and Hatchable** to create an automated career-support application.

## 📌 Problem

Job seekers often struggle to understand whether their resume matches a job description, how to improve their resume for ATS systems, and how to prepare for interviews.

This project provides these features through one AI-powered application.

## 💡 What I Built

I developed an **AI Career Assistant** that provides:

* 📄 Resume analysis
* 📊 ATS score evaluation
* 📝 Resume improvement suggestions
* 💼 Job description analysis
* 🎯 Job-role-specific resume suggestions
* 🤖 AI mock interviews
* 💬 Career assistance through an AI agent

## 🏗️ Workflow

```text
User
 ↓
Career Assistant Interface
 ↓
n8n Workflow
 ↓
Gemini AI
 ↓
Resume / Job Description Analysis
 ↓
ATS Evaluation
 ↓
Suggestions & Career Guidance
```

For interview preparation:

```text
User
 ↓
Mock Interview
 ↓
AI Questions
 ↓
User Answers
 ↓
AI Evaluation
 ↓
Feedback
```

## 🛠️ Technologies Used

* **n8n**
* **Google Gemini**
* **Hatchable**
* **AI Agents**
* **LLM**
* **Web Application**
* **Automation Workflow**

## 🔗 Integrations

The project connects the application interface with an n8n-based AI workflow.

The AI processing is handled through **Gemini**, while n8n manages the workflow and automation.

The application interface was created using **Hatchable**.

## 🎯 My Role

I worked on:

* Designing the career assistant concept
* Creating the n8n workflow
* Building the AI processing flow
* Connecting Gemini
* Designing resume analysis
* Creating ATS evaluation logic
* Creating job description analysis
* Developing mock interview functionality
* Connecting the application interface with the AI workflow
* Testing and debugging the workflow

## 📁 Repository Contents

```text
ai-career-assistant/
│
├── README.md
├── workflow.json

```

### `workflow.json`

This file contains the exported n8n workflow.

It can be imported into an n8n environment and configured with the required credentials.

> API keys, authentication details, and private credentials should not be uploaded to GitHub.

## 🚀 How to Use

### 1. Import the n8n workflow

Import:

```text
workflow.json
```

into your n8n environment.

### 2. Configure Gemini

Add your own Gemini API credentials to the appropriate n8n node.

### 3. Configure the application

Connect the application interface to the n8n workflow using the required webhook/workflow configuration.

### 4. Use the Career Assistant

Users can provide their resume or career information and use the available features such as:

* Resume analysis
* ATS evaluation
* Job description analysis
* Resume improvement
* Mock interviews
  
## 🎯 Key Features

### Resume Analysis

Analyzes the provided resume and identifies areas that can be improved.

### ATS Evaluation

Provides an ATS-oriented evaluation of the resume based on relevant job requirements.

### Job Description Analysis

Analyzes a job description and identifies important skills, requirements, and keywords.

### Resume Improvement

Provides suggestions for improving resume content according to the target role.

### Mock Interview

Provides AI-generated interview questions and feedback to help users practice.

## 🔮 Future Improvements

* Add more resume templates
* Improve ATS analysis
* Add more interview modes
* Add voice-based interviews
* Add job-search integration
* Add personalized career-roadmap generation
* Add persistent user profiles and history

## ⚠️ Security

Do not upload:

* API keys
* n8n credentials
* Webhook secrets
* Database passwords
* Private authentication tokens

Use environment variables or secure credential storage instead.

## 👩‍💻 Project

**AI Career Assistant**

An AI-powered career assistant built using **n8n, Gemini, and Hatchable** for resume analysis, ATS evaluation, job description analysis, and mock interview practice.
