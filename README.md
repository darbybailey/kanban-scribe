# KanbanScribe

**Google Sheets + AI-enhanced Kanban for families and teams, integrating journaling and calendar sync with secure Sentinel support**


## Overview
KanbanScribe is a shared productivity system designed for families or teams. It combines Google Sheets syncing, a drag-and-drop Kanban board, journaling with optional AI analysis, and full calendar export functionality—while also integrating with the Sentinel module from FamilyJewel for secure local data workflows.



## Features
- Sync with multiple Google Sheets across family/team members
- Drag-and-drop Kanban interface with XS–XL agile tags
- Daily journal entry via text or speech with AI summary
- Secure FamilyJewel Sentinel bridge for offline financial sync
- Export to Google Calendar
- Team task load and effort tracking



## Technologies
- Python 3.10+ (FastAPI, gspread, openai, pandas)
- React.js + TypeScript
- D3.js for visualization
- Google Apps Script (sync & validation)
- SQLite (optional local cache)



## Getting Started
1. Clone the repo
2. Setup `.env` with Google credentials and OpenAI/Gemini key
3. Run `docker-compose up`
4. Access the dashboard at `http://localhost:3000`
5. Configure the Google Sheet sync via provided Apps Script



## Sentinel Integration
KanbanScribe can optionally sync high-level summaries (e.g. budget, time estimates) into FamilyJewel's local Sentinel module for secure planning insights.
Set the `FAMILYJEWEL_SENTINEL_URL` in `.env` to enable.



## License
MIT License — see LICENSE file for details
