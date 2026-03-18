# Claude Code Desktop - Not Responding Fix

## Problem
The "Code" tab in the Claude Desktop app stops responding entirely. Messages are sent but no replies appear. The "Cowork" tab continues to work normally.

## Affected Session
- Session: "Migrate from creator platform to app.fastr.com"
- Working directory: `~/Desktop/Fastr Automations - MAIN`
- Model: Opus 4.6 (1M context)
- Plan: Max

## Root Cause Analysis
Possible causes identified:

1. **Frozen session** — The session processed earlier messages (table data, QA link) but became unresponsive mid-conversation
2. **Directory path with spaces** — `~/Desktop/Fastr Automations - MAIN` contains spaces which can cause issues with the underlying CLI process
3. **CLI process crash** — The Code tab relies on a local Claude Code CLI process that may have crashed silently

## Fix Steps

### Step 1: Start a fresh session
- Click **"New session"** in the sidebar
- Select the **"Code"** tab
- Do NOT reuse the frozen session

### Step 2: Rename the working directory (remove spaces)
```bash
mv ~/Desktop/"Fastr Automations - MAIN" ~/Desktop/Fastr-Automations-MAIN
```
Then set the new path as your working directory in the Code tab.

### Step 3: Verify Claude Code CLI is installed
Open Terminal and run:
```bash
claude --version
```
If not found, install:
```bash
npm install -g @anthropic-ai/claude-code
```

### Step 4: Restart the app
- Cmd+Q to fully quit (not just close window)
- Reopen Claude Desktop

### Step 5: If still broken
- Check logs: `cat ~/Library/Logs/Claude/main.log | tail -100`
- Reinstall the Claude Desktop app
- Use the **Chat** tab as a temporary workaround for non-coding tasks
