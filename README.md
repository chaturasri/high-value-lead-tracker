 High Value Lead Tracker (n8n Workflow)

📌 Overview
This project is an automated workflow built using n8n to identify high-value GitHub users based on their activity.

 ⚙️ Workflow Description
- Fetch GitHub users (stargazers or sample data)
- Enrich user details (bio, company, followers, repositories)
- Apply filtering logic:
  - Followers > 100 OR
  - Public repositories > 50
- Generate a sales pitch
- Send results to Discord via webhook

 Logic
The workflow identifies influential developers and helps generate outreach opportunities.

 Note
Due to GitHub API rate limits during testing, sample data was used to demonstrate the workflow.

Security
API tokens were removed from the workflow JSON before uploading for security reasons.

Files
- `workflow.json` → n8n workflow file

Future Improvements
- Integrate OpenAI/LLM for dynamic pitch generation
- Add real-time polling trigger
- Improve error handling
