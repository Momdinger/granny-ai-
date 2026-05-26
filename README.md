# Grandma Memory AI

This project is designed to help my grandma remember her life, her family, and her appointments using AI (Claude + NeMo/OpenClaw).

## Structure

- `data/`
  - `family.json` — family members and relationships
  - `life_events.json` — important events in her life
  - `appointments.json` — upcoming and past appointments
  - `daily_routine.json` — typical day structure and habits
  - `favorites.json` — favorite music, foods, places, hobbies

- `prompts/`
  - `system_prompt.txt` — core behavior and tone of the assistant
  - `memory_recall_prompt.txt` — how to help her recall memories
  - `appointment_reminder_prompt.txt` — how to remind her of appointments

## Usage

These files can be loaded into Claude or NeMo-based tools as:
- Context data (JSON)
- Prompt templates (TXT)

The goal is to provide a gentle, structured memory assistant experience for my grandma.
