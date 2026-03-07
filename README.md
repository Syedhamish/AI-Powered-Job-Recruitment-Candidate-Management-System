# AI-Powered Job Recruitment & Candidate Management System

## Project Overview

Modern organizations receive a large number of job applications every day. Many hiring teams still rely on spreadsheets, emails, and disconnected tools, which often leads to duplicate candidate records, lost applications, delayed interviews, and poor tracking of recruitment activities.

To solve these challenges, this project implements a centralized recruitment management system built on the Salesforce platform. The system allows recruiters to manage candidates, track job applications, standardize hiring workflows, and use AI-powered insights to support better hiring decisions.

Salesforce was selected for this solution because it provides secure cloud infrastructure, powerful automation tools, AI capabilities through Agentforce, scalable architecture, and real-time reporting.

---

## Key Features

- Candidate Management using Salesforce Contact object  
- Job Opening Management for tracking available positions  
- Candidate Application tracking system  
- AI Candidate Score for evaluating candidate suitability  
- Duplicate detection using Email and Phone  
- Validation rules for recruitment data accuracy  
- Recruitment dashboard and reports for analytics  
- Agentforce Recruitment Assistant for AI-driven insights  

---

## Objects Used

### Candidate (Contact)

The Candidate object stores information about job applicants such as name, email, phone number, experience level, and application status. It helps recruiters maintain a centralized database of candidates.

### Job Opening

The Job Opening object manages available job positions within the organization. It stores details such as job title, department, salary range, number of vacancies, and job status.

### Candidate Application

The Candidate Application object tracks job applications submitted by candidates. It links candidates with job openings and stores details such as application date, experience level, AI candidate score, offer amount, and application status.

---

## Important Fields

- Application ID  
- Candidate  
- Job Opening  
- Application Date  
- Experience Level  
- AI Candidate Score  
- Offer Amount  
- Application Status  
- Approval Status  

---

## Automation Implemented

- Validation Rules  
- Duplicate Rules  
- Matching Rules  
- Profile and Permission configuration  
- Session timeout and password policies  

---

## AI Features

This system integrates AI capabilities using Agentforce to support recruitment decisions. The AI Recruitment Assistant can analyze candidate information and provide insights to recruiters during the hiring process.

---

## Technologies Used

- Salesforce CRM  
- Lightning App Builder  
- Agentforce AI  
- Salesforce Automation Tools  

---
## System Architecture

The following diagram represents the architecture of the **AI-Powered Job Recruitment & Candidate Management System** built on the Salesforce platform.

It illustrates how recruiters interact with the Salesforce Lightning application, how candidate data is stored in custom objects, and how automation, security, AI insights, and reporting layers work together to manage the recruitment lifecycle.
<img width="1024" height="1536" alt="system_architecture_diagram" src="https://github.com/user-attachments/assets/d29ab43e-2b9f-4e6e-bca4-46356c1685fd" />

    
## Future Enhancements

- AI-based candidate ranking system  
- Resume parsing automation  
- Automated interview scheduling  
- Advanced recruitment analytics dashboards

## Project Demo Video

You can watch the full project demonstration here:

https://youtu.be/3im8eM_fBU8
