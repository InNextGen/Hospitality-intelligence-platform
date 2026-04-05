# ⚙️ Backend & AI Generator: AppSheet

The backend operational hub of the AI Hospitality Intelligence Platform is built using **Google AppSheet**. It acts as the central control room where raw data from Pinecone and n8n is transformed into actionable business proposals.

## 📸 System Interface & Logic
<img width="1440" height="778" alt="appsheet_proposal" src="https://github.com/user-attachments/assets/d522b6e9-3222-4a17-83de-7ee60d961c2e" />

## ✨ Key Capabilities
- **AI Proposal Generation:** Users can select specific competitors and market trends, and the AppSheet bot will trigger the AI pipeline to instantly generate a tailored marketing proposal.
- **Data Management:** Seamlessly connects with Google Sheets to manage the scraped data logs from the n8n pipelines.

<img width="677" height="712" alt="Screenshot 2569-04-06 at 01 32 55" src="https://github.com/user-attachments/assets/040d196e-f6cf-4110-958d-f663eebc58de" />


<img width="677" height="668" alt="Screenshot 2569-04-06 at 01 33 23" src="https://github.com/user-attachments/assets/96c5ba0a-a4e0-4fba-9fbe-81a710515fd5" />

- **Workflow Automation:** Built-in AppSheet Bots trigger approval processes and email notifications to the marketing team once a proposal is generated.
- **API Integration:** Acts as the bridge connecting the Frontend (Base44) via Webhooks/APIs to the AI models.

## 🛠️ Implementation Details
- **Platform:** Google AppSheet
- **Database:** Google Sheets
- **Role:** Backend Logic, User Action Trigger, Data Visualization
