# Autonomous Browser Scraper (n8n + TestMu AI)

An AI-driven automated web scraper built using **n8n** workflows and **TestMu AI (LambdaTest Browser Cloud)**.

## 📸 Project Visuals

### 1. The n8n Workflow Canvas
![n8n Workflow Canvas Layout](https://raw.githubusercontent.com/Prateekdixit200/n8n-testmuai-browser-automation/main/your-canvas-screenshot.png)

### 2. Live Cloud Browser Execution
![TestMu AI Remote Browser Session](https://raw.githubusercontent.com/Prateekdixit200/n8n-testmuai-browser-automation/main/your-browser-screenshot.png)

### 3. Final Extracted Output Data
![Scraped Output Results Data](https://raw.githubusercontent.com/Prateekdixit200/n8n-testmuai-browser-automation/main/your-output-screenshot.png)
---

## 🛠️ Project Stack
* **Workflow Engine:** n8n Cloud
* **AI Brain:** Google Gemini (`gemini-2.0-flash`)
* **Browser Automation:** TestMu AI Agent (Native Integration)

## 🚀 How It Works
1. **Trigger:** The flow runs manually using the canvas entry execution point.
2. **Browser Cloud Initialization:** The agent dynamically provisions a clean, remote **Chrome** browser instance hosted on **Windows 11** via the TestMu AI API.
3. **Autonomous Scraping:** It navigates to Hacker News, parses the web structures, extracts the top trending story title and target link without pre-coded selectors, and returns the output.
4. **Session Cleanup:** Once complete, it invokes a clean resource release command to terminate the browser immediately.
