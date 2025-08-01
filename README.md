**Knowledge Transfer Platform (KTP)**
A collaborative web application built to simplify and streamline technical knowledge sharing within engineering teams. Designed with a minimal, intuitive interface using Streamlit, and enhanced by GitHub and Slack integrations for seamless workflows.

**Features**
Create, edit, and browse technical knowledge articles

GitHub API integration to track real-time code contributions

Slack notifications to stay updated on new posts and edits

Search and filter content by tags or keywords

Optional data visualizations for team activity

**Tech Stack**
Frontend & App UI

Streamlit (Python-based UI framework)

Backend / Logic

Python (REST API logic & integrations)

GitHub REST API

Slack Webhooks

Database & Storage

Vector DB: Pinecone or ChromaDB

Redis for caching and fast lookups

MongoDB (optional, for structured content storage)

**Setup Instructions**
Clone the repository:

git clone https://github.com/Nannndini/ktp.git
cd ktp
Create and activate a virtual environment:

python -m venv venv
source venv/bin/activate  # For Windows: venv\Scripts\activate
Install dependencies:

pip install -r requirements.txt
Configure environment variables:

Create a .env file based on .env.example

Fill in your credentials:

MONGO_URI=your-mongodb-uri
GITHUB_TOKEN=your-github-token
SLACK_WEBHOOK_URL=your-slack-webhook
PORT=5000
Run the app locally:

streamlit run app.py
Project Structure

ktp/
├── app.py
├── components/
│   └── sidebar.py
├── services/
│   ├── github_api.py
│   └── slack_notifier.py
├── utils/
│   └── filters.py
├── assets/
│   └── screenshot.png
├── .env.example
├── requirements.txt
└── README.md
**Team**
Kailash 

Nandini  

Vardhan  

Sarayu 

**Demo**
Add a demo GIF or screenshot here for better visualization:

assets/screenshot.png

(Replace with the actual screenshot path once ready)

**License**
This project is licensed under the MIT License. See the LICENSE file for details.

**Contribution & Support**
Found a bug or have a suggestion?
Feel free to open an issue or submit a pull request.
We welcome contributions from the community!
