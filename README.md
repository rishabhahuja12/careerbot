# CareerBot: Agentic AI Career Counseling for IBM Edunet Internship

CareerBot is an intelligent agent built using IBM Watsonx.ai and Granite LLM, designed to offer personalized, document-grounded career guidance for students across India. Created as part of the IBM SkillsBuild for Academia Internship 2025, the project demonstrates agentic orchestration, vector-based retrieval (RAG), and real-world deployment using IBM Cloud.

---

## 🏆 Features & Wow Factors

- **Agentic AI:** Multi-step reasoning, tool use, and personalized guidance for career selection.
- **Granite Model:** Uses IBM’s flagship LLM via watsonx.ai.
- **IBM Cloud Deployment:** Fully deployed on IBM Cloud Lite.
- **Real Student Use Case:** Designed for Indian students facing career confusion.
- **Interactive Chatbot:** Live preview and results.

---

## 🌟 Key Features & WOW Factors
- **Vector Index + RAG:** Fetches accurate answers from uploaded learning material (.txt) using Retrieval-Augmented Generation.
- **Custom Prompting:** Designed a prompt to restrict hallucination and tailor answers to Indian academic and career contexts.
- **Start Questions Configured:** Four smart starter queries to onboard users quickly.
- **Tool Use:** Optimized for semantic answers, polite redirection on out-of-scope questions.

---

## 📁 Repository Structure

```
careerbot/
├── README.md
├── docs/
│   ├── user_guide.md
│   ├── architecture.md
│   └── faq.md
├── prompts/
│   └── agent_prompt.txt
├── config/
│   ├── agent_config.json
│   └── .env.example
├── screenshots/
│   ├── resources_list.png
│   ├── deployed_status.png
│   ├── chatbot_preview.png
│   ├── chatbot_result.png
├── presentation/
│   ├── IBM_EduNet_Presentation.pptx
│   └── IBM_EduNet_Presentation.pdf
├── .gitignore
├── LICENSE
```

---

## 🚀 Quickstart

1. **Clone the repository:**
   ```
   git clone https://github.com/rishabhahuja12/careerbot.git
   cd careerbot
   ```

2. **Set up environment variables:**
   Copy `.env.example` to `.env` and fill in your IBM Cloud and watsonx.ai keys.

3. **Configure the agent:**
   Edit `config/agent_config.json` for prompt, tools, and deployment options.

4. **Run locally or deploy to IBM Cloud Lite.**

---

## 📸 Screenshots

| Resources List | Deployed Status | Chatbot Preview | Chatbot Result |
|:--------------:|:--------------:|:---------------:|:--------------:|
| ![Resources](screenshots/resources_list.png) | ![Deployed](screenshots/deployed_status.png) | ![Preview](screenshots/chatbot_preview.png) | ![Result](screenshots/chatbot_result.png) |

**To add screenshots:**  
Upload your PNG files to the `screenshots/` folder via GitHub web or git, using the exact names above.

---

## 📚 Documentation

- **[User Guide](docs/user_guide.md):** How students use CareerBot.
- **[Architecture](docs/architecture.md):** Agent, prompt, and deployment details.
- **[FAQ](docs/faq.md):** Common questions about the bot and IBM integration.

---

## 🎤 Presentation

Final IBM Edunet submission:
- [IBM_EduNet_Presentation.pptx](presentation/IBM_EduNet_Presentation.pptx)
- [IBM_EduNet_Presentation.pdf](presentation/IBM_EduNet_Presentation.pdf)

---
## 🧠 Technologies Used

- IBM Watsonx.ai Studio
- IBM Granite LLM
- IBM Cloud Object Storage
- Vector Index (for RAG)
- Prompt Engineering (system & user prompts)
- 
---

## 📄 License

This project is licensed under the MIT License. See [LICENSE](LICENSE).

---

## 🙋 Contact

Questions? Reach out at [GitHub Issues](https://github.com/rishabhahuja12/careerbot/issues) or email rishabhahuja961@gmail.com.
