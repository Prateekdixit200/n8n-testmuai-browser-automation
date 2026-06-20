# Autonomous Browser Scraper (n8n + TestMu AI)

An AI-driven automated web scraper built using **n8n** workflows and **TestMu AI (LambdaTest Browser Cloud)**.

## 📸 Project Visuals

### 1. The n8n Workflow Canvas
<img width="1660" height="714" alt="image" src="https://github.com/user-attachments/assets/6a89d48f-11b5-45ae-b85e-64e240d47687" />


### 2. Live Cloud Browser Execution
<img width="1673" height="741" alt="image" src="https://github.com/user-attachments/assets/a9a0d74e-4820-4846-93f1-dd0dda4ccc4e" />


### 3. Final Extracted Output Data
<img width="1665" height="757" alt="image" src="https://github.com/user-attachments/assets/7b94ac59-869c-4b70-af81-583fc5b1eaea" />


<img width="1919" height="811" alt="image" src="https://github.com/user-attachments/assets/369eaa0b-d4ba-499f-8a39-eb8ef7827ff5" />


---

## 🛠️ Project Stack
* **Workflow Engine:** n8n Cloud
* **AI Brain:** Google Gemini (`gemini-2.0-flash`)
* **Browser Automation:** TestMu AI Agent (Native Integration)

## 🚀 How It Works
1. **Trigger:** The flow runs manually using the canvas entry execution point.
2. **Browser Cloud Initialization:** The agent dynamically provisions a clean, remote **Chrome** browser instance hosted on **Windows 11** via the TestMu AI API.
3. **Autonomous Scraping:** It navigates to Hacker News, parses the web structures, extracts the top trending story title and target link without pre-coded selectors, and returns the output.

## 📥 How to Import and Run
1. Download the `My workflow.json` file from this repository.
2. Open your n8n canvas, click the **`...`** menu in the top right corner, and select **Import from file...**.
3. Plug in your own Google Gemini API key and TestMu AI credentials, and hit **Execute workflow**!
5. **Session Cleanup:** Once complete, it invokes a clean resource release command to terminate the browser immediately.

