# Adidas WhatsApp AI Support Agent

AI-powered WhatsApp customer support for Adidas using n8n, Groq AI API, and Airtable.

## 🚀 Features

- **24/7 WhatsApp Support** - Instant customer assistance
- **AI-Powered Conversations** - Natural responses with Groq GPT
- **Order Tracking** - Real-time status from Airtable
- **Product Info** - Inventory lookups
- **Ticket System** - Auto-create support tickets
- **Smart Routing** - Direct return policy answers

## ⚡ Quick Setup

### Prerequisites
- n8n Instance
- Twilio Account (WhatsApp API)
- Groq API Key
- Airtable Base with:
  - `Inventory` table
  - `Orders` table  
  - `Tickets` table

### Installation
1. **Import workflow JSON** into n8n
2. **Configure credentials**:
   - Twilio (WhatsApp numbers)
   - Groq API key
   - Airtable access token
3. **Set Airtable base IDs** in tool nodes
4. **Activate workflow** and test

## 🤖 AI Agent

**Role**: Adidas WhatsApp assistant named "Alex"

**Capabilities**:
- Order tracking via `order_tracking` tool
- Product info via `order_records` tool  
- Ticket creation via `create_tickets` tool
- Return policy: 6 days
- Default assignee: Waqar Iqbal

**Style**: Friendly, professional, concise responses

## 🔧 Core Tools

1. **Order Tracking** - Check order status
2. **Product Records** - Inventory lookup  
3. **Ticket Creation** - Support escalation

## 💬 Sample Queries

- "Where's my order #12345?"
- "Do you have Ultraboost in size 9?"
- "What's your return policy?"
- "I need help with a refund"

---

*Replace all placeholder IDs with your actual values*
