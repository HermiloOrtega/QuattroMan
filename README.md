# 🤖 QuattroMan

## 🧭 Overview  
**QuattroMan** is an AI Agent developed for Quattro Constructors, initially built using Microsoft Power Virtual Agents and later upgraded and migrated to **Microsoft Copilot Studio**. It functions as a company-wide virtual assistant that provides answers to common questions, integrates with internal systems via API, and automates actions using Power Automate.

The agent is embedded in **Microsoft Teams** and within the **Quattrofy Web App**, enabling users (field and office-based) to interact with the AI in a centralized, secure, and dynamic way.

---

## 💡 Idea & Concept  
Born out of the need to reduce repetitive inquiries in the **Project Controls** and **IT** departments, the project began with a simple set of static responses. With high demand and complexity, it evolved into a powerful **AI-powered agent**, capable of dynamic querying, API integration, and multi-channel availability.

Key Goals:
- Help employees access information from internal systems without manual requests.
- Allow interaction from Teams and directly within internal web platforms.
- Automatically trigger backend actions (like data syncing or status checks) using secure APIs and Power Automate.

---

## ✨ Features & Functionality  
- **Teams & Web Integration**  
- **Dynamic AI-Powered Responses** via Copilot Studio  
- **API Integration** with Quattrofy (project, people, equipment, sync commands)  
- **Power Automate Triggers** from chat inputs  
- **Fallback to ChatGPT** when questions are out-of-scope  
- **Knowledge base ingestion** (SOPs, documentation)  
- **Company-wide deployment through Microsoft Teams Admin Center**  
- **Embedded Agent in Quattrofy Web UI**  
- **Secured with Role-Based Access and Azure Auth**  

---

## ⚙️ Tech Stack  
| Technology | Description |
|------------|-------------|
| ![C#](https://img.shields.io/badge/C%23-239120?logo=csharp&logoColor=white&style=for-the-badge) | Used in backend APIs of Quattrofy |
| ![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?logo=microsoftsqlserver&logoColor=white&style=for-the-badge) | Quattrofy system DB |
| ![JSON](https://img.shields.io/badge/JSON-000000?logo=json&logoColor=white&style=for-the-badge) | API payloads and Power Automate connectors |
| ![Power Automate](https://img.shields.io/badge/Power%20Automate-0066FF?logo=microsoftpowerautomate&logoColor=white&style=for-the-badge) | Flow engine for triggers & backend processes |
| ![Microsoft Copilot Studio](https://img.shields.io/badge/Copilot%20Studio-000000?logo=microsoft&logoColor=white&style=for-the-badge) | Conversational design and agent deployment |
| ![Microsoft Teams](https://img.shields.io/badge/Microsoft%20Teams-6264A7?logo=microsoftteams&logoColor=white&style=for-the-badge) | Primary interaction channel |
| ![ChatGPT](https://img.shields.io/badge/OpenAI%20ChatGPT-412991?logo=openai&logoColor=white&style=for-the-badge) | Smart fallback responses |

---

## 🏗 Architecture & Design  
- **Copilot Studio Agent**: Hosts all logic, topics, and Power Automate connectors  
- **Power Automate Flows**: Executes HTTP requests to Quattrofy API  
- **Quattrofy APIs**: Developed in C#; provides secure access to employee, project, and equipment data  
- **ChatGPT Plugin**: Acts as fallback for general questions  
- **Deployment**: Integrated into Microsoft Teams via admin push and embedded in Quattrofy Web  

---

## 🧑‍💻 My Role & Contributions  
- Designed and implemented v2 of the QuattroMan agent  
- Migrated static agents to Copilot Studio  
- Integrated Power Automate for advanced system actions  
- Developed backend APIs in C# for secure data queries  
- Connected agent with ChatGPT fallback  
- Set up automatic deployment to Microsoft Teams users  
- Embedded agent in Quattrofy Web UI  

---

## 🧗 Challenges & Learnings  
- Migrating legacy Power Virtual Agent logic to Copilot Studio  
- Ensuring secure API access with role and token validation  
- Managing dual-channel availability: Teams and Web  
- Optimizing flow performance and reducing timeouts on large queries  
- Mapping language model boundaries vs business rules  

---

## 📈 Future Enhancements  
- Add analytics and logging dashboard (Power BI or Application Insights)  
- Expand knowledge ingestion with SharePoint integration  
- Introduce proactive alerts to users (e.g., status reports)  
- Integrate with mobile-friendly views  

---

## 📌 Related Projects  
- [Quattrofy](#) – Internal business operation platform  
- [Quattrofy Web](#) – Web portal where the agent is embedded  
- [Copilot Studio Integration Docs](https://learn.microsoft.com/en-us/copilot-studio/)  

---

## 📎 License  
Internal proprietary project for **Quattro Constructors**. Not available for external use or redistribution.