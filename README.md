# AI Email Automation System (n8n + OpenAI)

## Overview

This project is an AI-powered email automation system built using **n8n, OpenAI, Gmail, and Google Sheets**.

The workflow automatically classifies incoming emails, sends an appropriate response, and logs the interaction.

---

## Workflow Architecture

Gmail Trigger  
↓  
Filter (check subject keywords)  
↓  
OpenAI AI Classification  
↓  
Switch (route email category)  
↓  
Send Automated Reply  
↓  
Log Email Data in Google Sheets

---

## Features

• AI-powered email classification  
• Automated email replies  
• Multi-category routing (order / inquiry / support)  
• Email interaction logging  
• Fully automated workflow

---

## Tech Stack

- n8n
- OpenAI API
- Gmail Integration
- Google Sheets
- Workflow Automation

---

## Example Categories

Order inquiries  
Customer inquiries  
Support requests

---

## Output Logging

All email activity is logged in Google Sheets including:

- Time
- Sender
- Subject
- Category
- Message

---

## Use Cases

Customer support automation  
Small business email handling  
Lead inquiry response system  
AI productivity tools
