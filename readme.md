# HolySync: Never miss a Deadline

**HolySync** is a real-time chat application with AI-driven task extraction and summarization. Users can create chat threads, send messages, and let the AI automatically extract tasks (e.g., "Todo: Finish report by Friday") and summarize discussions and seamlessly integrate with Notion or Google Tasks

![HolySync Demo](https://via.placeholder.com/800x400) *(Replace with a screenshot of your app later!)*

---

## **📌 Table of Contents**
1. [Features](#-features)
2. [Tech Stack](#-tech-stack)
3. [Project Structure](#-project-structure)
4. [Setup Instructions](#-setup-instructions)
   - [Backend](#backend)
   - [Frontend](#frontend)
5. [API Documentation](#-api-documentation)
6. [Collaboration Guidelines](#-collaboration-guidelines)
7. [Deployment](#-deployment)
8. [Contributing](#-contributing)
9. [License](#-license)

---

## **✨ Features**
- **Multithreaded Chat**: Create and join chat threads (e.g., "Project X").
- **AI-Powered Task Extraction**: Detect tasks in messages (e.g., "Todo: Call client").
- **Todo List Integration**: Manage tasks linked to chat threads by adding them to Google Tasks or Notion.
- **Real-Time Updates**: Messages and tasks update instantly.
- **Chat Summarization**: AI-generated recaps of discussions.
- **User Authentication**: Secure access with Spring Security.

---

## **🛠 Tech Stack**
| Area          | Technologies                                                                                     |
|---------------|-------------------------------------------------------------------------------------------------|
| **Backend**   | Java, Spring Boot, Spring Security, Spring Data JPA, H2 Database (dev), PostgreSQL (prod)   |
| **Frontend**  | Next.js, TypeScript, Shadcn UI (Tailwind CSS), React Hooks                                    |
| **Real-Time** | Spring WebSocket                                               |
| **AI**        | Rule-based task extraction (prototype), HuggingFace (BART)|
| **DevOps**    | Maven, GitHub, Render (backend), Vercel (frontend)                                          |

---
