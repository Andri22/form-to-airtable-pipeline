# Form to Airtable Pipeline — n8n Workflow

## What It Does
Captures client inquiry form submissions instantly, creates 
a structured entry in an Airtable base, and sends a 
real-time Telegram notification to the business owner.
Zero manual data entry required.

## Workflow
Tally Form → Webhook → n8n → Airtable Base + Telegram

## Tech Stack
- n8n
- Tally (form)
- Airtable Personal access tokens
- Telegram Bot API

## Features
- Real-time webhook trigger on form submission
- Dropdown field mapping (ID to label)
- Structured Airtable base entry with status tracking
- Instant Telegram notification with lead details

## Setup
1. Import the workflow JSON into your n8n instance
2. Connect your Airtable credential and share base with integration
3. Connect your Telegram Bot credential
4. Create your Tally form and paste webhook URL into Tally integrations
5. Activate the workflow

## Use Case
Small business owners who want to automatically capture 
and organize client inquiries without manual copy-pasting.

## Result
- Zero leads lost — every submission captured automatically
- Business owner notified within seconds of submission
- Clean Airtable database for tracking lead status
