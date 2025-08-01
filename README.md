Knowledge Transfer Platform (KTP)

A collaborative web app designed to simplify and streamline technical knowledge sharing within teams — built using Streamlit.

##  Features
-  Create and browse technical knowledge articles
-  GitHub API integration to track real-time contributions
-  Slack notifications for article updates
-  Search and tag-based filtering
- Data visualizations of team activity (optional)

## 🛠 Tech Stack

**Frontend & App UI**
- [Streamlit](https://streamlit.io/) — Python-based interactive UI framework

**Backend / Logic**
- Python (APIs & integrations)
- GitHub REST API
- Slack Webhooks

**Database**
- vector database


## ⚙️ Setup Instructions

Clone the repo:
```bash
git clone https://github.com/your-username/ktp.git
cd ktp
## Team
- Nandini (Frontend & Repo Manager)
- [Add other members]

## License
This project is licensed under the MIT License.
See the LICENSE file for details.

Contact
Have questions? Reach out via GitHub Issues.


### **Optional Enhancements**

1. **Add badges** to the top of your README (before "Features"):

```md
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![Issues](https://img.shields.io/github/issues/Nannndini/ktp)
![Stars](https://img.shields.io/github/stars/Nannndini/ktp?style=social)
Add a screenshot or demo GIF
Place it under a section like:
Demo
![Screenshot](./assets/screenshot.png)
Add .env.example file (if using .env)
Include something like:

MONGO_URI=your-mongodb-uri
GITHUB_TOKEN=your-github-token
SLACK_WEBHOOK_URL=your-slack-webhook
PORT=5000
