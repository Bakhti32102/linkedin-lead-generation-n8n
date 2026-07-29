<p align="center">
  <img src="assets/banner.png" alt="LinkedIn Lead Generation Banner" width="100%">
</p>

# 💼 LinkedIn Lead Generation - n8n Workflow

An open-source LinkedIn job lead generation workflow built with **n8n**, **Apify**, and **Gmail**.

This workflow automatically scrapes LinkedIn job listings, filters the latest opportunities, and sends daily email notifications so you never miss new AI automation and remote job postings.

---

# ✨ Features

- 🔍 Automatically scrape LinkedIn job listings
- ⏰ Daily scheduled execution
- 🚀 Powered by Apify LinkedIn Job Scraper
- 📧 Send email notifications with Gmail
- 🎯 Filter and limit the latest job opportunities
- ⚡ Fully automated workflow
- 🔓 Open-source and easy to customize

---

# 📷 Workflow Preview

<p align="center">
  <img src="assets/workflow.png" alt="Workflow Preview" width="100%">
</p>

---

# ⚙️ Tech Stack

- n8n
- Apify
- LinkedIn Jobs
- Gmail
- HTTP Request Node
- Schedule Trigger

---

# 📦 Installation

1. Download **workflow.json** from this repository.
2. Open your n8n instance.
3. Click **Import Workflow**.
4. Select **workflow.json**.
5. Configure your credentials:
   - Apify API Token
   - Gmail OAuth
6. Update the LinkedIn search URL if needed.
7. Activate the workflow.

---

# 📁 Repository Structure

```
linkedin-lead-generation-n8n/
│
├── workflow.json
├── README.md
├── LICENSE
└── assets/
    ├── banner.png
    └── workflow.png
```

---

# 🔄 Workflow Process

1. Schedule Trigger starts automatically.
2. Apify scrapes LinkedIn jobs.
3. Workflow waits for scraping to finish.
4. Fetches job results.
5. Limits results to the latest 10 jobs.
6. Sends job details via Gmail.

---

# 📧 Email Example

Subject

```
New Job: AI Customer Support at Company Name
```

Body

```
Job Title
Company
Location
Apply Link
```

---

# 📌 Requirements

- n8n
- Apify Account
- Gmail Account
- LinkedIn Job Search URL

---

# 🤝 Contributing

Contributions, improvements, and feature requests are welcome.

If you like this project, consider giving it a ⭐ on GitHub.

---

# 📄 License

This project is licensed under the MIT License.
