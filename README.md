# PM Team Desk

A virtual project-management office in a single page, built as a Claude artifact.

- **Version:** v53 (demo)
- **File:** `index.html`: the whole app (HTML, CSS and JS in one file).

## Demo data
All people, companies and clients in this demo are fictional: the manager Adam Fawzy, the CEO Tarek, the company Northwind Health and the client RMC (Riverside Medical Center).

## What's inside
- Animated office with AI assistants: Nour (secretary), Karim (CRs), Hana (finance), Youssef (support) and Malak "Sharshoba" (runner & morale).
- Meeting room with streaming voice replies, Stop/Continue, presenter pointer and phone + desktop sync.
- Files, reminders, tickets, finance views, Trash with restore, WhatsApp drafts and imported-chat search.

## How it runs
The page runs inside the claude.ai artifact runtime and uses its capabilities (`sample`, `tts`, `dictation`, `db`, `assets`, `downloads`, `user`). Opening `index.html` directly in a browser shows the layout, but the AI, voice and database features need the claude.ai runtime.

## Data & privacy
- No data is stored in this repo: tasks, files, meetings and chats live in the artifact's private database.
- Never commit patient names, MRNs, passwords, tokens, real customer names or exported chats here.
