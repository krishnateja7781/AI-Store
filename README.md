# AI-Store
This is an AI store you can order items which are available and get billing.


The AI Store Workflow is an N8N automation project that simulates an AI-powered store ordering system.
It allows users to order items and intelligently handles three scenarios:

✅ All Items Available → Confirms the order, provides delivery details, and calculates the total billing amount.

❌ No Items Available → Informs the user that the order cannot be taken.

⚖️ Partial Availability → If only some items are available, the system asks whether the user wants to proceed with the available items or cancel the order completely.

This project demonstrates intelligent decision-making with workflows and can be extended for e-commerce automation.

Features :

📦 Smart Order Handling – Manages different cases based on item availability.

🧾 Billing Calculation – Automatically calculates the order amount when items are confirmed.

🔄 Dynamic Responses – Adjusts workflow outcomes depending on availability.

🤖 AI-Powered Interaction – Uses an AI agent to interact with the user.

Workflow Logic :

User places an order → (via Telegram, Webhook, or other input).

AI Agent extracts items from user’s message.

Check item availability in Google Sheets / database.

Handle cases:

Case 1: All items available → Confirm order + calculate billing + delivery details.

Case 2: None available → Inform user order cannot be placed.

Case 3: Partially available → Ask user if they want available items or cancel.

Finalize response → Send message back to user.

![order items](https://github.com/user-attachments/assets/31332845-2b74-45c6-be62-08859cb597d8)
