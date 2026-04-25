# TikTok Affiliate Promo Generator (Taglish AI Automation)

Automated system that generates daily TikTok promo scripts, captions, and hashtags from affiliate product lists.

---

## Overview

This workflow automates bulk content generation for TikTok affiliates by pulling products from a database and generating ready-to-use promo content using AI.

Designed for scalability and daily content production.

---

## The Problem

Affiliate creators:
- Need multiple posts daily  
- Spend time writing scripts and captions  
- Struggle to scale content output  

---

## The Solution

Built a scheduled automation system that:

- Pulls product data from Google Sheets  
- Generates Taglish TikTok promo content using AI  
- Cleans and structures output  
- Stores results in a separate content database  
- Sends completion notifications via Telegram  

---

## How It Works

1. **Schedule Trigger**  
   Runs daily at 8:00 AM  

2. **Get Products**  
   Reads product list from Google Sheets  

3. **Limit (Test Mode)**  
   Limits to 3 products (for testing / rate control)  

4. **AI Generation (Groq)**  
   Generates:
   - 1 script  
   - 1 caption  
   - 5 hashtags  

5. **Data Cleaning**  
   Formats output into usable fields  

6. **Save Output**  
   Appends results into “Generated Promos” sheet  

7. **Notification**  
   Sends Telegram alert after completion  

---

## Tech Stack

- n8n (workflow automation)
- Groq API (fast/free AI generation)
- Google Sheets (data source + output)
- Telegram API (notifications)

---

## Key Features

- Fully automated daily content generation  
- Taglish output optimized for local audience  
- Structured output (clean, reusable content)  
- Scalable system (just add more products)  
- Low-cost operation (uses free AI via Groq)  

---

## Impact

- Automates bulk content creation  
- Enables daily posting without manual writing  
- Reduces content production time significantly  
- Creates a scalable affiliate content pipeline  

---

## Important Notes

- Currently limited to 3 products (testing mode)  
- Remove Limit node for full-scale automation  
- Easily scalable by adding more product rows  

---

## Proof

- Workflow screenshots in `/screenshots`  
- Sample generated outputs in Google Sheets  
- n8n workflow JSON included  

---

## Use Case

- High-volume TikTok affiliates  
- Content agencies managing multiple products  
- Automation systems for e-commerce marketing  

---

## Key Takeaway

This project shows how content production can be fully automated—from product input to ready-to-post TikTok promos—using AI and workflow automation.

---

## Built By

Marla Daniella  
AI Automation & Workflow Systems Builder  
