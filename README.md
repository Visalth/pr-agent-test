# PR Triage Agent

A small LangGraph chatbot that helps you review GitHub pull requests.
You ask it about open PRs, it summarizes the diff, suggests reviewers,
and drafts a comment. It pauses for your approval before posting anything.

## Setup

1. `pip install -r requirements.txt`
2. Copy `.env.example` to `.env` and fill in your keys:
   - `GROQ_API_KEY` — from https://console.groq.com
   - `GITHUB_TOKEN` — a GitHub personal access token with repo access
   - `GITHUB_REPO` — the repo to triage, like `owner/name`
3. `jupyter notebook final_project.ipynb`
4. Run the cells in order.

## Author

Irakli Katsitadze
