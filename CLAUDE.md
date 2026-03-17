# Claude Code Cheat Sheet — Project Instructions

## Purpose
Single-page printable HTML cheat sheet for Claude Code CLI.
Designed to print on A3 Landscape from Chrome → Print → Save as PDF.

## Update Process
Ask Claude: "há atualizações a fazer na cheat sheet?"
Claude will compare current content against known Claude Code features and suggest additions.

## Layout Philosophy
Sections ordered by frequency of use:
- **Row 1 (top):** Everyday — Keyboard Shortcuts, Slash Commands, CLI & Flags, Session Management
- **Row 2 (middle):** Regular — Skills & Agents, Memory & Files, Config & Env, MCP Servers
- **Row 3 (bottom):** Advanced — Hooks, Permission Rules, Vim Mode, Custom Keybindings

## Design Rules
- Dark theme (#0d1117 background)
- Each section has a unique accent color
- Font: monospace (Fira Code fallback stack)
- Content font-size: 9px (compact but readable)
- @media print targets A3 landscape
- No external dependencies — fully self-contained HTML

## File
- `index.html` — the cheat sheet (single file, self-contained)
