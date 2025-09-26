# N8N
workflow of getting crypto prices

Installation
Open your n8n editor.
Click Import → Paste JSON.
Paste the workflow JSON provided.
Click Import.
Configure credentials:
Go to Credentials → Telegram → Add new credential using your Bot Token.
Replace YOUR_CHAT_ID in the Telegram node with your chat ID.

Usage
Manual Execution
Open the workflow in n8n.
Click Execute Workflow.
You should receive a Telegram message with the current BTC price.
Automatic Execution (Optional)
Add a Cron node to run the workflow periodically (e.g., every hour).

Connect Cron → CoinGecko → Telegram.

Activate the workflow.
