# rule-based-expense-tracking-bot-make
A rule-based expense tracking automation built using Make (Integromat), Google Sheets, and Telegram Bot to automatically log expenses and income from chat messages.

## 🚀 Overview
This project automates expense tracking using Make (Integromat). 
The bot listens for Telegram messages, parses the text, categorizes entries as *Income* or *Expense*, 
and logs them into a Google Sheet automatically.

## ⚙️ Tools Used
- Make (Integromat)
- Telegram Bot API
- Google Sheets
- Text Parser & Routers
- Webhooks

## 🧠 Workflow Overview
1. Telegram Bot receives a message
2. Router classifies as Income or Expense
3. Text Parser extracts amount and category
4. Google Sheets stores the entry
5. Telegram sends confirmation message

## 🔗 Automation Flow Diagram

 Bot_visulas/Make_Workflow.png.png

## 📊 Example Message Format
Expense: Lunch ₹150
Income: Freelance ₹2000

markdown
Copy code

## 📁 Data Output
Each entry is logged in Google Sheets with:
| Date | Type | Category | Amount | Description |
|------|------|-----------|---------|--------------|

## 🧰 How to Recreate
1. Create a Telegram Bot using @BotFather  
2. Connect Telegram to Make via webhook  
3. Connect Google Sheets  
4. Use text parser and router modules to categorize data  
5. Test & deploy automation  

## ✨ Future Improvements
- Add chat model APIs to get duynamic responses
- Add auto-category detection via NLP
- Integrate with Notion or Airtable
- Build a dashboard in Power BI

## 🧑‍💻 Author
Niranjan N

💼 Early data professional

📧 Contact: niriyadav551@gmail.com
