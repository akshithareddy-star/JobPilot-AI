# 🚀 JobPilot AI – Multi-Agent Career Intelligence System

![n8n](https://img.shields.io/badge/n8n-Workflow%20Automation-orange)
![Groq](https://img.shields.io/badge/Groq-Llama%203.3%2070B-blue)
![REST API](https://img.shields.io/badge/API-REST-green)
![AI](https://img.shields.io/badge/AI-Multi--Agent-purple)
![License](https://img.shields.io/badge/License-Portfolio-blue)

---

## 📌 Project Overview

**JobPilot AI** is a Multi-Agent Career Intelligence System designed to help candidates evaluate their resumes against a job description and receive personalized career guidance.

Instead of relying on a single AI prompt, the workflow is divided into multiple specialized AI agents, each responsible for a specific task such as candidate analysis, opportunity evaluation, career decision-making, and final report generation.

The system also integrates with an external Job Search API to fetch live job opportunities based on AI-generated recommendations, providing candidates with both career insights and relevant job opportunities.

---

## ✨ Key Features

- 📄 Resume Analysis
- 📋 Job Description Analysis
- 🤖 Multi-Agent AI Workflow
- 🎯 Skill Gap Identification
- 💼 Career Recommendations
- 🌐 Live Job Search Integration
- 📊 Career Intelligence Report Generation
- 🔗 REST API Integration
- ⚡ Workflow Automation using n8n

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| n8n | Workflow Automation |
| Groq Llama 3.3 70B | Large Language Model |
| Prompt Engineering | AI Agent Instructions |
| REST API | Live Job Search |
| JSON | Data Exchange |
| HTTP Request | API Communication |

---

# 🏗️ Workflow Architecture

The workflow follows a modular architecture where each AI agent is responsible for a single task.

1. Resume Upload
2. Job Description Upload
3. Resume Text Extraction
4. Job Description Text Extraction
5. Prepare AI Input
6. Candidate Intelligence Agent
7. Opportunity Intelligence Agent
8. Career Decision Agent
9. Extract Decision Data
10. HTTP Request (Job Search API)
11. Merge Report Data
12. Final AI Agent
13. Career Intelligence Report

---

## 📷 Workflow Overview

![Workflow Overview](docs/workflow-overview.png)

---

# 🤖 AI Agents

## 1️⃣ Candidate Intelligence Agent

### Purpose

Analyzes the candidate's resume against the uploaded job description.

### Responsibilities

- Resume Analysis
- Skill Matching
- Skill Gap Identification
- Candidate Strengths
- Learning Recommendations

### Screenshot

![Candidate Intelligence Agent](docs/candidate-agent.png)

---

## 2️⃣ Opportunity Intelligence Agent

### Purpose

Evaluates the candidate's career opportunities based on the previous AI analysis.

### Responsibilities

- Career Evaluation
- Suitable Role Recommendation
- Career Guidance
- Opportunity Analysis

### Screenshot

![Opportunity Intelligence Agent](docs/opportunity-agent.png)

---

## 3️⃣ Career Decision Agent

### Purpose

Generates a structured career decision for downstream processing.

### Responsibilities

- Recommended Role
- Overall Match Score
- Confidence Score
- Recommendation
- Decision Reasoning

### Screenshot

![Career Decision Agent](docs/career-decision-agent.png)

---

# 🌐 External API Integration

After the Career Decision Agent recommends the most suitable role, the workflow extracts the required decision data and sends it to an external Job Search API using an HTTP Request node.

The API retrieves live job opportunities matching the recommended role, enabling dynamic and real-time career recommendations.

---

# 📊 Final Career Intelligence Report

The Final AI Agent combines:

- Candidate Intelligence
- Opportunity Intelligence
- Career Decision
- Live Job Opportunities

into a single Career Intelligence Report.

### Screenshot

![Final Career Intelligence Report](docs/final-report.png)

---

# 📁 Project Structure

```text
JobPilot-AI/
│
├── README.md
│
├── workflow/
│   └── jobpilot-workflow.json
│
├── docs/
│   ├── workflow-overview.png
│   ├── candidate-agent.png
│   ├── opportunity-agent.png
│   ├── career-decision-agent.png
│   └── final-report.png
│
└── prompts/
```

---

# 🚀 Future Enhancements

- ATS Resume Score Prediction
- Resume Optimization Suggestions
- Cover Letter Generator
- Interview Question Generator
- Personalized Learning Roadmap
- Recruiter Dashboard
- Email Notifications
- Multi-language Support

---

# 🎯 Key Learnings

Through this project, I gained hands-on experience in:

- Multi-Agent AI Workflow Design
- Prompt Engineering
- Workflow Automation using n8n
- REST API Integration
- AI-Oriented System Design
- JSON Data Processing
- Modular Application Development

---

# 👩‍💻 Author

**Akshitha Reddy Gavinolla**

B.Tech – Computer Science Engineering (Data Science)

GitHub: https://github.com/your-github-username

LinkedIn: https://linkedin.com/in/your-linkedin-profile

---

# 📜 License

This project is created for educational, learning, and portfolio purposes.