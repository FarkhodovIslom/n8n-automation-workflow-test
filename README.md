# 🤖 n8n AI Automation Workflow  
**Hansoft Team — Test Task**

## 🎯 Goal  
Build an **AI-powered automation** using **n8n**, where AI analyzes a text task and triggers automatic actions.

## ⚙️ Task Description  
Create an **n8n workflow** that:
1. Accepts input text (via Webhook, form, or Telegram).
2. Uses AI to define:
   - **Category** (Frontend, Backend, AI, etc.)
   - **Priority** (Low / Medium / High)
3. Depending on the AI result:
   - Adds the task to Google Sheets / Notion / DB  
   - Sends notification to Telegram or Discord

## 🧩 Requirements  
- Must use **n8n** (local or cloud).  
- AI node: **OpenAI**, **Anthropic**, or your custom **AI endpoint**.  
- Use **IF / Switch logic** to route based on priority or category.  
- The workflow must run automatically from input → result.

## 🧠 Example Scenario  
**Input:**  
```json
{ "task": "Fix 500 error on user API" }
```
**AI Output:**  
```json
{ "category": "Backend", "priority": "High" }
```
**Actions:**
- Add to Google Sheets: `Category: Backend`, `Priority: High`, `Task: Fix 500 error on user API`
- Send Telegram message: "New High Priority Backend Task: Fix 500 error on user API
