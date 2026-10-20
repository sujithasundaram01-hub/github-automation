# 🚀 GitHub Automation using n8n

## 📌 About the Project

This project automates GitHub learning-log creation using **n8n workflow automation**. It helps generate daily learning content and save it as Markdown files in a GitHub repository, reducing the need for manual updates.

## 🎯 Objectives

- Automate daily learning-log creation.
- Generate learning content using AI.
- Save content directly to GitHub.
- Maintain a record of daily learning activities.
- Reduce repetitive manual work.

## 🛠️ Technologies Used

- **n8n** – Workflow automation
- **GitHub** – Version control and file storage
- **AI Agent** – Learning-content generation, if configured
- **Schedule Trigger** – Runs the workflow at a scheduled time
- **Markdown** – Formats learning logs

## ⚙️ Workflow

1. **Schedule Trigger** – Starts the workflow at the configured time.
2. **AI Agent** – Generates learning content.
3. **Remove Duplicates** – Helps filter previously processed topics when configured correctly.
4. **GitHub Create a File** – Saves the generated content as a Markdown file.
5. **Automated Execution** – Runs according to the schedule when the workflow is active.

## ✨ Features

- Automated GitHub file creation
- Scheduled learning-log generation
- AI-powered content generation support
- Timestamp-based filenames
- Organized Markdown learning logs
- Reduced manual effort

## 📂 Repository Structure

```text
github-automation/
├── learning-logs/
│   ├── 2026-10-20-09-00-00.md
│   ├── 2026-10-21-09-00-00.md
│   └── 2026-10-22-09-00-00.md
└── README.md
```

*The filenames above are examples. Actual filenames depend on the workflow execution time.*

## 🚀 How It Works

1. Create a GitHub repository.
2. Configure GitHub credentials in n8n.
3. Add a Schedule Trigger to the workflow.
4. Configure the AI Agent to generate learning content, if required.
5. Configure the GitHub node to create files in the repository.
6. Test the workflow.
7. Activate the workflow for scheduled execution.

## 🔐 Requirements

- A GitHub account and repository
- An n8n instance
- GitHub credentials with the required repository permissions
- AI model credentials, if using an AI Agent

## 📚 Learning Outcomes

- Understanding workflow automation
- Integrating n8n with GitHub
- Working with scheduled triggers
- Automating file creation
- Exploring AI-powered automation

## 🔮 Future Enhancements

- Improve duplicate-topic detection using previous learning logs
- Add error notifications
- Generate topic-based learning summaries
- Automate daily progress reports

## 👩‍💻 Author

**Sujitha Sundaram**

Interested in AI, Generative AI, programming, and workflow automation.

---

⭐ Built as a hands-on project to explore automation with n8n and GitHub.
