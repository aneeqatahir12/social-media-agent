# Social Media Caption AI Agent

This repository contains the **Make.com (Integromat)** blueprint for an AI agent that automatically generates social media captions and product descriptions.

## 🧠 Overview
The agent connects **Google Sheets**, **Gemini API (via HTTP GET & POST)**, and **AI automation** to generate creative captions for each product automatically.

## ⚙️ Workflow Structure
1. **Google Sheets – Watch Rows:** Detects new or updated rows in the sheet.  
2. **HTTP GET Request:** Checks Gemini API models.  
3. **HTTP POST Request:** Sends product details (name, short description, tone) to Gemini AI for text generation.  
4. **Google Sheets – Update Row:** Writes the AI-generated text back into the “AI Description” column.

## 📁 File Included
- `social_media_agent_safe.json` — Make.com exported blueprint (API key removed for security).
- ## 🎬 Demo Video
Watch the 2-minute presentation of the Social Media Caption Agent:  
👉 [View Demo on Google Drive](https://drive.google.com/file/d/1Qh4ZSeRphPkp2znaoNpGgZa0MDsMIuxo/view?usp=sharing)

## 🧩 How to Use
1. Import the JSON file into your **Make.com** dashboard.  
2. Connect your Google account and Sheets.  
3. Replace `"YOUR_API_KEY_HERE"` with your own Gemini API key.  
4. Run the scenario — watch as AI-generated captions appear automatically in Google Sheets!

## 👩‍💻 Author
**Aneeqa Tahir**  
*Created as a beginner AI automation project using free tools (Google Sheets, Make.com, Gemini API).*
