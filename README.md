# 📊 N8N Use Cases Library

Welcome to the **N8N Use Cases** repository! This collection contains ready-to-use workflows, patterns, and ideas for automating everyday tasks using N8N selfhosted.

---

## 🚀 What is N8N?

[N8N](https://n8n.io) is a **fair-code licensed workflow automation tool** that lets you connect APIs, services, databases, and internal tools using a visual, node-based editor.

You can think of it as your open-source Zapier or Make (Integromat), with **more control, privacy, and extensibility.**

---

## 📚 Use Cases Included

| Use Case | Description | Tags |
|----------|-------------|------|
| 📥 Gmail Labeler with AI | Classifies incoming Gmail using OpenAI and labels them automatically. | `gmail` `openai` `labeling` |
| 📰 Web Scraper to Summary | Scrape a webpage, extract paragraphs, and summarize with GPT. | `http` `html` `openai` |
| 🧾 Conversational Telegram Bot with GPT-4o for Text and Voice Messages. | `Telegram` `Open AI` `google sheets` |
| 🔁 PyAutoGui_Automation_Selfhosted. | `PyAutoGui` `FlaskAPI` |'Ngrog'
| 🔄 Google_Review_Analysis. | `gmail` `openai` `Google API` |
| 🔄 N8N_Challenge_Slack_Mention_Logs | `gmail` `openai` `Slack APP` |
| 🔄 Slack_Meeting_Summary | `gmail` `openai` `Slack APP` |


---

## 🛠 Setup Instructions

1. **Install N8N:**
   ```bash
   npm install n8n -g
   n8n start
2. SelfHosted npm - use your selfhosted url to launch the app

3. Import a Workflow:

    Go to n8n → Menu → Import Workflow.

    Upload .json from the /workflows/ folder.

4. Configure Credentials:

    Gmail: OAuth2 with access to Gmail API.

    OpenAI: API key for ChatGPT.

    Others: As required by the use case.

🔧 Tips
Use Set nodes to manipulate or format data.

Use Merge nodes to combine multiple sources.

Use Code nodes for JavaScript logic (looping, filtering, mapping).

Use Wait and IF nodes for control flow and scheduling.

📁 Folder Structure
.
├── README.md
├── workflows/
│   ├── Gmail_Labeler_with_OpenAI.json
│   ├── Web_Scraper_Summarizer.json
│   ├── Invoice_Extractor_to_Sheets.json
└── docs/
    ├── Gmail_Setup_Guide.md
    └── OpenAI_API_Key.md
💬 Contributions
If you have a cool use case, feel free to contribute via PR or share ideas in the n8n community.

🔐 Disclaimer
These workflows may involve sensitive data (e.g., email contents, API keys). Always store credentials securely and test workflows before deploying them in production.

📧 Contact
Created by [Victor Fernandez S]
📫 Email: victor.ferz82@gmail.com
🔗 GitHub: [github.com/your-profile  ](https://github.com/victorfernandez-sebastin/N8N) 
