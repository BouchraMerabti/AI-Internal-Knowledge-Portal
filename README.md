# AI-Internal-Knowledge-Portal
A conceptual AI-powered internal knowledge portal built using OutSystems, featuring GPT integration and a robust security model
# AI-Powered Internal Knowledge Portal Concept

# Project Summary

AI-Powered Internal Knowledge Portal, a conceptual application built during a 3-day hackathon using the  OutSystems low-code platform**. The project demonstrates a solution to the common enterprise problem of fragmented knowledge by leveraging AI for intelligent search and robust security for sensitive data.

The core idea is to transform scattered internal documents (PDFs, emails, etc.) into a smart, conversational knowledge base.

# Key Features

* **AI-Powered Natural Language Search:** Users can ask questions in plain English (e.g., "How do we handle returns in Germany?") and receive summarized answers.
* **Intelligent Summarization (GPT Integration):** The system uses AI to interpret and synthesize information from documents, providing a concise answer with source links, rather than just returning a list of files.
* **Learning Knowledge Base:** The AI is trained on the company's internal knowledge, allowing it to provide answers that fit the organization's specific context and terminology. The system also records previously asked questions and answers, creating a growing, searchable knowledge base.
* **Security by Design (Principle of Least Privilege):** The application enforces strict access controls, ensuring that users can only view documents and information they are explicitly authorized to access, based on their user role (e.g., Employee, Admin, IT Security).
* **Centralized Document Ingestion:** The portal is designed to ingest and index various document types from different sources (e.g., PDFs, Word files, etc.).
* **User Interface & Dashboards:** A user-friendly front-end with dashboards to track document access levels, user interactions (views, edits, downloads), and top-asked questions.
* **Rapid Prototyping:** The entire MVP was conceptualized and built in just 3 days, showcasing the power of the OutSystems platform for agile development.

# Problem Statement**

In large organizations, valuable knowledge is fragmented across different platforms and formats, making it difficult for employees to find information. This leads to redundant work and a lack of visibility on who the subject matter experts are.

# Solution Overview**

The portal acts as a central brain for the company's knowledge. Instead of manually searching through countless documents, an employee can ask a question and get an instant, summarized, and permissions-aware answer. This is achieved by:

1.  Ingesting and indexing internal documents.
2.  Using semantic search to find relevant document chunks.
3.  Feeding those chunks to a large language model (e.g., GPT) to generate a concise answer.
4.  Ensuring the user has permission to access the source document before displaying any information.

# **Technical Implementation**

* **Platform:** OutSystems
* **AI Integration:** A connector or API integration to a large language model (e.g., OpenAI's GPT API) for summarization and natural language processing.
* **Key Concepts:** Data modeling for documents and user permissions, UI/UX design, dashboard creation, and REST API integration.

### **Screenshots**

Here are some screenshots from the application's user interface to showcase the functionality and design.

- **Login Screen with User Roles:**
  ![Login Screen](https://github.com/BouchraMerabti/AI-Internal-Knowledge-Portal/blob/3724e6d27edcb67f47945c47c9dc3537f1f28d51/Screenshot%202025-05-26%20at%2000.19.42%20copy.png)
  *Demonstrates the implementation of different user roles for security.*

- **Main Dashboard:**
  ![Main Dashboard](https://github.com/BouchraMerabti/AI-Internal-Knowledge-Portal/blob/3724e6d27edcb67f47945c47c9dc3537f1f28d51/Screenshot%202025-05-26%20at%2000.44.14.png)
  *Shows user interaction analytics and a list of top-asked questions and recent documents.*

- **AI Assistant in Action:**
  ![AI Assistant](https://raw.githubusercontent.com/BouchraMerabti/AI-Internal-Knowledge-Portal/main/Screenshot%202025-05-26%20at%2000.25.48.png)
  *Highlights the conversational, natural language interface.*

- **User Interaction Logs:**
  ![User Interaction Logs](https://raw.githubusercontent.com/BouchraMerabti/AI-Internal-Knowledge-Portal/main/Screenshot%202025-05-26%20at%2000.31.44.png)
  *Displays backend tracking of user activities for auditing and insights.*
