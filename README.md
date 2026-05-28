# AI Email Triage Assistant

An AI-powered email triage workflow built using Make, OpenAI, Gmail, and Google Sheets to automatically categorize inbound emails, recommend next actions, generate draft responses, and structure outputs for operational efficiency.

## Overview

This MVP was designed to reduce manual email triage by automating the intake and categorization process.

The system reviews incoming emails, analyzes intent and urgency using AI, and organizes results into a structured Google Sheet for faster decision-making and response handling.

## What It Does

* Monitors inbound Gmail messages
* Uses AI to categorize email content
* Recommends next actions
* Generates draft responses
* Assigns confidence scoring
* Logs structured outputs into Google Sheets

### Example Output Fields

* Timestamp
* Sender Name
* Message Category
* AI Category
* Reasoning
* Recommended Action
* Draft Reply
* Confidence Score

## Workflow

Gmail → Make → OpenAI → Structured JSON Output → Google Sheets

## Why It Matters

Teams waste significant time manually sorting and responding to inbound communication. This workflow demonstrates how AI automation can improve response speed, consistency, and operational efficiency while maintaining human oversight.

## Tech Stack

* Make (Integromat)
* OpenAI API
* Gmail
* Google Sheets
* JSON Structuring

## Current Status

MVP Complete — continuing improvements to prompt reliability, categorization accuracy, and automation flow.

## Future Improvements

* CRM integration
* Priority escalation logic
* Sentiment detection
* Multi-department routing
* Automated follow-up suggestions

## Author

Leonard Klein
